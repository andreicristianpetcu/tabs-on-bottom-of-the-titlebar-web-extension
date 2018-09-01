# Tabs on bottom of the titlebar WebExtension

This extension puts the tabs at the bottom.

![screenshot]

How to install in Firefox v63+ Nightly or DevEdition:

1) Open `about:config?filter=extensions.legacy.enabled` and set it to true. This is a WebExtension but the API is still rough around the edges, it needs some legacy stuff.
2) Open about:debugging and load the manifest.json from disk.

Unfortunatelly this cannot be signed by Mozilla and published on AMO until [this issue](https://github.com/mozilla/addons-linter/issues/2166) gets fixed.

The CSS is based on [Timvde/UserChrome-Tweaks/tabs-on-bottom-titlebar.css](https://github.com/Timvde/UserChrome-Tweaks/blob/52f1eae0c3492d52c33adb9b97bc17a222ce4032/tabs/tabs-on-bottom-titlebar.css): 


More info about the new theme_experiment API on [the addons blog](https://blog.mozilla.org/addons/2018/08/31/extensions-in-firefox-63/).

[screenshot]: https://raw.githubusercontent.com/andreicristianpetcu/tabs-on-bottom-of-the-titlebar-web-extension/master/screenshot.png
