# Sahil Hackz Website Firebase Hosting Setup

## Steps to Deploy

1. Install Firebase CLI:
   ```
   npm install -g firebase-tools
   ```

2. Login to Firebase:
   ```
   firebase login
   ```

3. Initialize project (only first time):
   ```
   firebase init
   ```
   - Select Hosting
   - Select existing project (sahil-hackz)
   - Set public directory as `public`
   - Choose No for SPA
   - Choose No for automatic builds

4. Deploy website:
   ```
   firebase deploy
   ```

5. Open website URL:
   ```
   https://sahil-hackz.web.app
   ```
6. Admin panel URL:
   ```
   https://sahil-hackz.web.app/admin
   ```

---

## Admin Login

- Email: mdshahil74828@gmail.com
- Password: sahil123 (Change this after deployment for security)