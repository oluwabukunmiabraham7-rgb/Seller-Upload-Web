# MARKET EXPRESS — Seller Upload Dashboard

Suggested GitHub repository: `market-express-seller-dashboard`

## Deploy
1. Create a separate GitHub repository named `market-express-seller-dashboard`.
2. Upload every file in this ZIP to the repository root.
3. In Settings → Pages, deploy from `main` and `/ (root)`.
4. Enable Email/Password Authentication and Firebase Storage.
5. Authorize this GitHub Pages domain in Firebase Authentication settings.
6. Publish carefully reviewed Firestore and Storage rules that allow only approved sellers to create/manage their own listings.

This site uses the shared Firebase project `enitan-collection-7e541`. Sellers must be approved first. Product submissions are saved in the shared `products` collection with `sellerId`, `status: pending`, and `active: false`. They should not appear on the storefront until approved by the admin.

Seller dashboard URL after deployment:
`https://YOUR-GITHUB-USERNAME.github.io/market-express-seller-dashboard/seller.html`

The root `index.html` redirects to the dashboard.

## Other MARKET EXPRESS websites
- Main storefront: https://oluwabukunmiabraham7-rgb.github.io/Market-expres/
- Seller applications: https://oluwabukunmiabraham7-rgb.github.io/market-express-seller-apply/seller-apply.html
- Seller upload dashboard: https://oluwabukunmiabraham7-rgb.github.io/market-express-seller-dashboard/seller.html
- Admin website: https://oluwabukunmiabraham7-rgb.github.io/market-express-admin/admin-sellers.html

These are suggested URLs. They become active only after you create the repositories with the exact names above and GitHub Pages finishes deploying. If your GitHub username differs, replace it in the links.
