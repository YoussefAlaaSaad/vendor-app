# Multi-Vendor E-Commerce — Vendor App

Flutter mobile app for vendors to manage their store, list products, process orders, and track earnings on the multi-vendor marketplace.

## Features

- **Store Profile** — manage store name, image, and description
- **Product Upload** — add new products with images, pricing, and details
- **Edit Products** — update existing product listings
- **Orders** — view incoming orders, update status (processing → delivered)
- **Earnings** — track total earnings and per-order revenue
- **Authentication** — vendor sign up, sign in, persistent sessions

## Tech Stack

- Flutter 3.4.3 (Dart)
- Riverpod — state management
- Cloudinary — product image hosting
- image_picker — image selection from device
- REST API via `http` package
- shared_preferences — local token storage
- google_fonts

## Related Repositories

| Repo | Role |
|------|------|
| [backend-api](https://github.com/YoussefAlaaSaad/backend-api) | Node.js/Express REST API + MongoDB |
| [customer-app](https://github.com/YoussefAlaaSaad/customer-app) | Flutter mobile app for shoppers |
| **vendor-app** | Flutter mobile app for vendors |
| [admin-panel](https://github.com/YoussefAlaaSaad/admin-panel) | Flutter web dashboard for admins |

## Getting Started

```bash
flutter pub get
flutter run
```

Update the API base URL in the providers/services layer to point to your backend before running.
