# 2FA (Two-Factor Authentication)

A simple, privacy-focused Two-Factor Authentication (2FA) code manager built for the web.

## Features

* 🔐 Generate TOTP (Time-based One-Time Password) codes
* 💾 All data is stored locally using IndexedDB
* 🚫 No server-side database
* 🌐 No user data is transmitted to the server
* ⚡ Fast and lightweight
* 📱 Works directly in modern web browsers

## Privacy First

Unlike many online 2FA managers, **2Step** does not store your secrets on a remote server.

All account information, secret keys, and generated codes are stored locally in your browser using IndexedDB. This means:

* Your 2FA secrets never leave your device
* No account registration is required
* No cloud synchronization
* No server-side storage

Your data remains under your control.

## How It Works

1. Add your TOTP secret key manually or by scanning a QR code.
2. The application stores the secret locally in IndexedDB.
3. TOTP codes are generated directly in your browser.
4. No sensitive information is sent to any server.

## Security Notice

While this application does not store data on a server, the security of your 2FA secrets still depends on the security of your device and browser.

For maximum security:

* Keep your operating system updated
* Use a trusted browser
* Protect your device with a password or biometric authentication
* Avoid using the application on shared or public computers

## Live Demo

https://2step.zone.id

## Technology

* HTML5
* JavaScript
* IndexedDB
* Web Crypto API

## Disclaimer

This project is provided "as is" without warranty of any kind. Users are responsible for maintaining backups of their 2FA secrets and recovery codes.

Loss of browser data, clearing site storage, or device failure may result in the loss of stored secrets.

## License

MIT License
