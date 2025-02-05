# Updrive - WordPress File Management Engine

<img width="800" src="/assets/banner.png">

A robust file management solution for WordPress that combines simple operation with professional-grade features.

[![WordPress Plugin Active Installs](https://img.shields.io/wordpress/plugin/installs/updrive?style=flat-square)](https://wordpress.org/plugins/updrive/)
[![GitHub release](https://img.shields.io/github/release/yourusername/updrive.svg?style=flat-square)](https://github.com/yourusername/updrive/releases)

## 🚀 Features
- **Drag & Drop Uploads** - Browser-based file uploads with progress indicator
- **Smart File Organization** - Automatic directory structure generation
- **Public Sharing URLs** - Generate direct download links with expiration controls
- **File Versioning** - Keep historical versions of updated files
- **Security Suite** - Malware scanning, download limits, and hotlink protection
- **Cloud Ready** - Optional integration with S3/Wasabi/Backblaze storage
- **Usage Analytics** - Track downloads and user engagement

## 📦 Installation
1. Download the latest release ZIP
2. In WordPress admin: Plugins → Add New → Upload Plugin
3. Activate "Updrive" through the Plugins menu
4. Configure settings under → Updrive → Settings

**Requirements:**  
- WordPress 5.6+  
- PHP 7.4+  
- 100MB+ upload limit recommended

## 🛠️ Usage

### Basic File Management
```plaintext
1. Navigate to Updrive → Dashboard
2. Upload files via drag & drop or traditional uploader
3. Manage files through the intuitive grid interface
4. Copy public URLs using the "Share" button
```

### Advanced Features
- Set expiration dates for temporary shares
- Create password-protected file links
- Generate usage reports (CSV/PDF)
- Configure automatic cloud backups

## ⚙️ Configuration

### Core Settings
- Storage Path: /wp-content/updrive/  
- Max File Size: 2GB  
- Allowed Types: zip,pdf,docx,xlsx,pptx  
- Download Limits: 100/day

### Security Settings
[✔] Enable virus scanning  
[✔] Prevent direct directory access  
[✔] Require login for uploads  

## 🔒 Security Features
- Military-grade AES-256 encryption for sensitive files
- Real-time ClamAV integration for upload scanning
- Automatic .htaccess hardening for storage directories
- Nonce verification for all admin operations
- Session-based download authentication

## 🤝 Contributing
We welcome contributions! Please follow our guidelines:
1. Fork the repository
2. Create a feature branch (git checkout -b feature/amazing-feature)
3. Commit changes (git commit -m 'Add amazing feature')
4. Push to branch (git push origin feature/amazing-feature)
5. Open a Pull Request

## 📄 License
GPLv3 © [fled.dev]. See LICENSE for full details.
