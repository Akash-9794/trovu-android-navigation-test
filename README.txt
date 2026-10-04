Trovu #329 Android navigation feasibility test

This is a diagnostic PWA, not a proposed fix. It contains no account or payment functionality.

Deployment: upload this folder's contents to an HTTPS static host. Keep its files together and serve it from a stable path. Open index.html on Android 12 using Chrome, install the app, and launch from the home-screen icon. Verify the page says Installed standalone mode detected. If the install menu is missing, check that HTTPS, manifest, PNG icons, and service worker all load correctly.

Run tests 1 through 5 with Google, then repeat tests 3 and 4 with YouTube and Google Maps. Record Android and Chrome versions and your default browser. Each time record: full browser with address bar AND tab switcher, an in-app view with X, a matching app, chooser, or blocked.

Chrome-specific test 4 cannot be treated as the final solution: the bounty also requires respecting the system default browser and associated native apps. Test 5 approximates asynchronous timing; it is not the actual Trovu query pipeline.

Desktop testing and running this from a downloaded file do not prove the installed Android PWA behavior. Do not submit a bounty claim on the basis of this lab alone. A final fix must be tested in Trovu with query g and recorded on Android.

Sources:
https://github.com/trovu/trovu/issues/329
https://developer.chrome.com/docs/android/intents
