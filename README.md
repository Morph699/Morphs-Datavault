<img width="1696" height="2528" alt="Datavault" src="https://github.com/user-attachments/assets/079f5be9-5e21-4009-9b6a-f612a5ca76bf" />

🛡️ Morphs DataVault v1.94

100% Offline Air-Gapped Personal Safe & Digital Asset Vault

No Cloud. No Accounts. No Subscriptions. No Telemetry. Pure, client-side encryption running entirely on your local hardware.

🔒 Overview

Morphs DataVault is a privacy-first, zero-cloud personal vault designed to keep your most critical digital secrets—passwords, home Wi-Fi keys, developer API tokens, license keys, and recovery seed phrases—completely out of reach from cloud breaches, trackers, and network sniffers.

Unlike modern "cloud-synced" password managers that store your encrypted data on third-party servers, Morphs DataVault operates 100% air-gapped. It contains zero network dependencies, zero telemetry, and never makes an external connection. Your master key derives locally, encrypts your safe in-memory, and immediately purges from RAM upon locking.

Available as both a lightweight, install-free Android Web App / SPA and a high-performance Windows 10 / 11 Native Workstation, Morphs DataVault gives you full sovereignty over your private credentials.

⚡ Key Features & Cryptographic Architecture

  - Military-Grade Cryptographic Pipeline:
      - Android / Mobile SPA: Authenticated AES-256-GCM (12-byte random IV, 128-bit integrity tag) + PBKDF2-HMAC-SHA256 (310,000 rounds).
      - Windows Desktop: Authenticated AES-256-CBC with HMAC-SHA256 (Encrypt-then-MAC authentication) + PBKDF2 (310,000 iterations).
  - Dual Auto-Lock Sentry:
      - 20-Second Inactivity Timer: Automatically purges active memory and locks the vault if left unattended.
      - Instant Minimize Protection: Locks instantly the moment your screen turns off, the window minimizes, or you switch apps.
  - Air-Gapped Morphs Beam & .mvault Backups:
      - Transfer and backup your encrypted safe between devices without connecting to Wi-Fi or Bluetooth.
      - Export authenticated, self-contained .mvault container files or beam encrypted QR envelopes directly screen-to-screen.
  - Organized Category Grid:
      - 🔑 Account Logins & Passwords
      - 📶 Home & Office Wi-Fi Credentials
      - ⚡ Developer API Keys & Webhook Tokens
      - 📜 Morphs Ecosystem 12-Character License Keys
      - 📝 Secure Notes & Cold-Storage Seed Phrases
  - 10 High-Contrast Themes (WCAG AAA):
      - Includes Soft Slate (Light), Stealth Dark, Matrix Green, Cyber Yellow, Cyberpunk Pink, Dracula Purple, Blood Matrix, Nordic Frost, Solarized Ocean, and Sunset Amber.
  - 4-Tier Dynamic Font Scaling Engine:
      - Real-time scaling across Small, Medium, Large, and Extra Large typography with dedicated high-contrast accent contrast tokens (--accent-txt) for maximum digitizer legibility.

🛡️ Why Air-Gapped Matters

If a company stores your vault in the cloud, you are always one database breach, server misconfiguration, or subpoena away from exposure. With Morphs DataVault:

1.  Your master password never leaves your device because there is no server to send it to.
2.  If you don't unlock it, the data on your storage drive is mathematically indistinguishable from random digital noise.
3.  You own your backup files (.mvault) locally, permanently, and indefinitely.

💻 System Compatibility

  - Android: Compatible with Android 8.0+ via any modern browser, WebView wrapper, or PWA standalone launcher.
  - Windows Desktop: Native Windows 10 & Windows 11 executable (PowerShell 5.1+ / .NET WinForms runtime). Zero heavy dependencies or background services.
