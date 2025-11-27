# Add-Blocker-Hotstar

**Description**: This Chrome extension blocks ads on Hotstar so you can watch uninterrupted. It's distributed here as an unpacked extension you can load directly from this repository.

**Features**:
- **Ad Blocking:** Blocks common ad requests and elements on Hotstar pages.
- **Easy Install:** Load as an unpacked extension in Chrome or any Chromium-based browser.

**Installation (from this repo)**:
- **Clone the repo:**

	`git clone https://github.com/udaypratap1112/Add-Blocker-Hotstar.git`

- **Or download ZIP:** Click the green "Code" button on GitHub and choose "Download ZIP", then extract it.

- **Open Chrome extensions page:**

	`chrome://extensions/`

- **Enable Developer mode:** Toggle the switch in the top-right corner of the page.

- **Load the extension (unpacked):** Click `Load unpacked` and select the cloned or extracted repository folder (the folder that contains `manifest.json`, `background.js`, etc.).

**Usage**:
- After loading, the extension should appear in the toolbar. Navigate to `https://www.hotstar.com` (or your regional Hotstar URL) and verify that ads are blocked.



**Troubleshooting**:
- If ads still appear, try these steps:
	- Reload the extension on the `chrome://extensions/` page using the refresh button.
	- Clear the browser cache and reload the Hotstar page.
	- Open DevTools (F12) → Network and check for blocked requests or console errors from the extension.
- If the extension doesn't load, ensure your selected folder contains `manifest.json` at the top level.

**Development / Contribution**:
- Want to improve filtering or add rules? Fork the repo, make changes, and open a pull request.
- Keep tests small and focused. Add any rule files under `rules.json` or the `_metadata/generated_indexed_rulesets/` folder if applicable.

**License**:
- This repository does not include a license file. If you plan to reuse or redistribute, consider adding a license (e.g., MIT) so others know how they may use your code.

**Contact**:
- For questions or help, open an issue on the GitHub repository.

Enjoy ad-free Hotstar viewing!

