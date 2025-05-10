Microsoft Activation Scripts (MAS)
MAS is an open-source project for activating Windows and Office using multiple reliable methods: HWID, Ohook, TSforge, KMS38, and Online KMS. It also includes advanced troubleshooting features.

🔑 Supported Activation Methods
HWID – Digital license activation (Windows)

Ohook – Local KMS emulator (Office)

TSforge

KMS38 – Activation valid until the year 2038 (Windows)

Online KMS – Remote KMS server-based activation

🚀 How to Activate Windows / Office
Method 1 – PowerShell (Windows 8 and later) ❤️
Open PowerShell (press Windows + X, then select Windows PowerShell or Terminal)

Copy and paste the following command, then press Enter:

irm https://get.activated.win | iex

When prompted:

Press 1 for Windows activation using HWID

Press 2 for Office activation using Ohook

✅ That’s it! You’re activated.

Method 2 – Traditional (Windows Vista and later)
If the PowerShell method doesn't work, you can use the traditional script by downloading it manually. Refer to the official documentation or trusted sources to get the script package.

💻 Office for macOS
This project does not support Office activation on macOS. Please refer to official Microsoft documentation for Mac licensing.

⚙️ Unattended Mode
To run MAS scripts in unattended/silent mode (no user interaction), check the relevant documentation for command-line usage and parameters.

❓ Troubleshooting
Can’t launch MAS using PowerShell? ➡️ Try the traditional method.

Seeing errors in the script? ➡️ Follow the blue-colored instructions displayed in the console.

Still need help? ➡️ Reach out via the official issue tracker or community channels.

📜 License
This project is released under the MIT License. See the LICENSE file for details.
