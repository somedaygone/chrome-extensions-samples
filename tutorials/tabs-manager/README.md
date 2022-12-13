# Tabs Manager sample

For the tutorial, see [Tabs Manager Getting Started Guide](https://developer.chrome.com/docs/extensions/mv3/getstarted/tut-tabs-manager/).

It skips over some basics that are covered on the [Development basics](https://developer.chrome.com/docs/extensions/mv3/getstarted/development-basics/) page.

## Loading an unpacked extension

To load an unpacked extension in developer mode:

1. Go to the Extensions page by clicking on the Extensions menu puzzle button and select **Manage Extensions** at the bottom of the menu.
2. Enable Developer Mode by clicking the toggle switch next to **Developer mode**.
3. Click the **Load unpacked** button and select the extension directory.

<img src="https://wd.imgix.net/image/BhuKGJaIeLNPW9ehns59NfwqKxF2/BzVElZpUtNE4dueVPSp3.png" alt="Extensions page" width="400">

Pin your extension to the toolbar from the puzzle menu to quickly access your extension during development. 
When you click on the extension’s icon, you should see the popup html.

## Reloading the extension

1. After saving certain files, you also have to refresh the extension. Go to the Extensions page and click the refresh icon next to the **on/off** toggle:

<img src="https://wd.imgix.net/image/BhuKGJaIeLNPW9ehns59NfwqKxF2/4Ph3qL9aUyswxmhauRFB.png" alt="Reload an extension" width="400">

Not all components need to be reloaded to see changes made, as shown in the following table:

| Extension component        | Requires extension reload |
|----------------------------|:-------------------------:|
| The manifest               |            Yes            |
| Service worker             |            Yes            |
| Content Scripts            | Yes (plus the host page)  |
| The popup                  |            No             |
| Options page               |            No             |
| Other extension HTML pages |            No             |
