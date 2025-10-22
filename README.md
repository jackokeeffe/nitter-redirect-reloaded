# ![nitter-redirect](images/icon32.png) Nitter Redirect Reloaded

[![Firefox Extension](images/badge-amo.png)](https://addons.mozilla.org/en-CA/firefox/addon/nitter-redirect-reloaded/)

A simple browser extension that redirects X (formerly Twitter) requests to [Nitter](https://github.com/zedeus/nitter), the privacy friendly alternative.

![Firefox Screenshot](images/Screenshot%20Firefox.png)

This is a **modified version** of Simon Brazell's [Nitter Redirect](https://github.com/SimonBrazell/nitter-redirect), which had not been updated to support x.com domains. 

This version also updates the [available Nitter instances](https://status.d420.de/), as the majority of the original instances had been taken down. The onion instances have also been removed — if you are aware of any active onion instances, please submit an issue or a pull request with the onion addresses.

No unnecessary permissions are required, only listens for and redirects requests made to `x.com`, `www.x.com`, `mobile.x.com`, and nothing else.

Allows for setting custom [Nitter instances](https://status.d420.de/) and toggling redirects on & off.

## Usage

The extension is currently being submitted to Firefox, and to submit to Chrome it must be updated to Manifest V3, which will take me some time. 

In the meantime, you can easily run the extension in Firefox by:
1. Downloading the ZIP of this extension.
1. Search about:debugging on Firefox.
2. Click on 'This Firefox' on the left-hand side.
3. Click 'Load Temporary Add-On'.
4. Select the manifest.json from the ZIP, open.
5. The extension will be active and redirect any requests made to x.com to an active Nitter instance.

## Contribute

If you wish to contribute to this extension, either submit a pull request or contact me @jackokeeffe:matrix.org

## License

Copyright (c) 2019 Simon Brazell.

Licensed under the [MIT license](LICENSE.txt).
