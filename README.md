# 🍽️ SmartQR Menu: Digital Dining Solution

**SmartQR Menu** is a modern web application designed to help restaurants, cafes, and bars digitize their menus. By scanning a QR code, customers can instantly browse items, descriptions, and prices directly on their own devices without downloading any apps.

## 📋 Key Features
* **Touchless Experience:** Secure, hygienic, and fast access to the menu via QR scan.
* **Dynamic Management:** Update categories, items, and pricing instantly through the admin panel.
* **Responsive Design:** Optimized for all screen sizes, from small smartphones to tablets.
* **Lightweight & Fast:** Built for high performance even on slower mobile connections.

---

## 🛠️ Installation Guide (cPanel / Plesk)

This project is optimized for shared hosting environments. Since it connects to your existing database, no SQL import is necessary.

### Option 1: cPanel Setup
1. **Upload:** Use **File Manager** to upload the project files to your `public_html` or a specific directory.
2. **Extract:** Unzip the files in the target folder.
3. **PHP Version:** Ensure your hosting is running **PHP 7.4 or 8.x**.
4. **Config:** Update your database credentials in the `config.php` or `db_connect.php` file.

### Option 2: Plesk Setup
1. **Upload:** Navigate to the **Files** tab and upload your ZIP file to the `httpdocs` directory.
2. **Extract:** Use the built-in "Extract Files" tool in the Plesk file manager.
3. **PHP Settings:** Check the **PHP Settings** icon to ensure the version is compatible.
4. **Permissions:** If you see any 403 errors, use the "Fix Permissions" tool in the dashboard.

---

## ⚙️ Database Configuration
> [!NOTE]
> This repository does not include a `.sql` dump. It is designed to work with your existing database architecture. Please ensure your database host and user permissions are correctly set in the configuration files.

---

## 🛡️ Support
If you encounter issues with image uploads or menu loading, verify your folder permissions (CHMOD 755) and check your hosting error logs.
