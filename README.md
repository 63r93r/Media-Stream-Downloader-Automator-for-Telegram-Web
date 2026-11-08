# Privacy Policy

**Last Updated:** November 7, 2026

This privacy policy governs your use of the **Media Stream Downloader & Automator for Telegram Web** browser extension (the "Extension"). The Extension is designed as a localized developer and productivity automation utility to assist users in reassembling browser-accessible media streams on the Telegram Web interface (`https://telegram.org*`).

---

### 1. Data Collection and Usage
We firmly believe in absolute data minimization:
* **No Core Personal Data Collected:** The Extension does not collect, log, or monitor any personal information, usernames, accounts, phone numbers, chat logs, or communication histories.
* **No Media Retention:** The process of capturing and reassembling video stream fragments occurs strictly within your browser's active execution memory space. Once the download process concludes or the Extension window is closed, all temporary files and stream chunks are permanently cleared from volatile memory.

### 2. Zero-Storage Architecture
The Extension operates entirely statelessly and does not request or utilize browser storage APIs (such as `chrome.storage.local` or `chrome.storage.sync`):
* No user preferences, download history logs, configurations, or operational states are saved to your physical device. 
* All detected media items and current download progress indicators are held strictly in temporary, short-lived system memory (RAM) and are completely erased upon terminating the browser tab or popup.

### 3. Permissions Justification
The Extension requests specific browser capabilities solely to execute its single programmatic purpose:
* **`host_permissions` (`https://telegram.org*`):** Required exclusively to inspect DOM elements, hooks, and local network buffer contexts natively running on the active Telegram Web client. This allows the Extension to automate the manual retrieval of stream chunks as if executed via the user's browser developer console.

### 4. Third-Party Advertising and Analytics
To keep this Extension entirely free to use, we include advertisement banners at the bottom of the extension's popup user interface:
* These banners are served by privacy-respecting third-party ad network partners (such as ExtAds or similar contextual providers).
* **Data Insulation:** Our ad providers only receive basic, non-identifying telemetry or context data (such as the fact that the request originated from an extension layout) required to serve the visual banner. No private user contents, messaging traffic, or video information from `web.telegram.org` are ever scraped, processed, or transferred to these third-party providers.

### 5. Data Security and Transmission
* **100% Client-Side Processing:** All automated assembly features happen locally on your own machine. 
* **No Remote Servers:** We do not own, rent, or maintain any external databases or remote storage servers. No video files, session tokens, or browser data are ever transmitted over the network to us or any unauthorized third party.

### 6. Changes to This Privacy Policy
We may update this Privacy Policy from time to time to maintain compliance with changing Chrome Web Store requirements. Any modifications will be posted directly within this document and reflected in the "Last Updated" date above.

### 7. Contact Us
If you have any questions, security concerns, or inquiries regarding your data privacy while using this Extension, please feel free to reach out to us at:

**Email:** 63r93r@gmail.com
