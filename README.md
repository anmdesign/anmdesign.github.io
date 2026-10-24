# anmdesign.github.io

Holds `.well-known/assetlinks.json`, which lets the YouTube Finder Android app
(io.github.arunknm.malayalam_youtube) open https://anmdesign.github.io/malayalam-youtube/
full-screen, without a browser bar. The fingerprint is the app's signing key
(twa/android.keystore in anmdesign/malayalam-youtube). `.nojekyll` makes GitHub
Pages serve the `.well-known` folder.
