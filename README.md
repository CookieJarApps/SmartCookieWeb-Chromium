# SmartCookieWeb-Chromium

Chromium-based browser.

Repo structure borrowed from Kiwi Browser. The repo only stores files that differ from Chromium. The `chromium` branch holds the original copy of the modified file and the `main` branch the modified version. CHROMIUM_VERSION displays the version that the `chromium` branch is updated to. It is not recommended to build the browser on top of a Chromium codebase of another version to this. To build, download the `main` branch and clone the corresponding Chromium source version. Copy the files in this repo over the Chromium repo and build like you normally would Chromium.
