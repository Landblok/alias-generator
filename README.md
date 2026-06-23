# Alias Generator

A simple, lightweight AppleScript for macOS to generate, copy, and log unique email aliases for your catch-all domain.

## Features
- **Prompt-based:** Quickly enter the service name you are signing up for.
- **Configurable Suffix Length:** Easily switch between 5, 6, or any custom length of random characters for your email token.
- **True Random Alphanumeric Generation:** Generates a diverse mixture of lowercase letters and numbers dynamically.
- **Duplicate Checking:** Reads your local log file automatically to prevent duplicate tokens from ever being reused.
- **Auto-copy:** The complete generated email address is instantly copied to your clipboard for quick pasting.
- **Local Logging:** Securely logs all generated aliases alongside timestamps in a plain text file on your desktop.

## Setup
1. Open **Script Editor** on your Mac.
2. Create a new document and paste the script from `Alias Generator`.
3. Locate the configuration lines at the top of the script:
   - Update `set domainName to "REPLACE WITH YOUR DOMAIN"` to your actual catch-all domain (e.g., `"@yourdomain.com"`).
   - Adjust `set suffixLength to 6` to your desired random token length (e.g., `5` or `6`).
4. Save the file. You can run it directly from the editor, or save it as an **Application** to keep it in your Dock or Applications folder for quick access.

## License
Copyright (c) 2026 Landblok

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
