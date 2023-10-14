# A-Better-Way-Through-Internet
*Internet without harassment by ads company!*


This is the version 4 and probably final tutorial that will create a safe navigation with no ads, privacy focus and no annoying stuff like cookies warning, it will include some part of the older tuto but lighter in ram consumption and with some more filters.

> **0) Install your favorite Chromium browser (like, Brave, Ungoogled, Chrome, Vivaldi, etc.) or Firefox.**

(I recommend [Brave Beta](https://brave.com/download-beta/), if you do so under settings/protection set the fingerprint to strict, eventually if you are not getting access to some websites you can always disable a specific one by clicking the orange lion head on the right of the url search bar,
under settings/privacy you can also disable some annoyance feature like anonym stats)

Other than all the below steps will be a good point to block any 3rd party cookies from your browser (check your settings and search for Privacy and Security) and block any connection that not come with https.

Furthermore I can recommend you to use [https://presearch.com](https://presearch.com/)  as your default search engine Instead of Google (you don't need to sign up), 

here you can find the "url query": https://presearch.com/search?q=%s

Alternatively you can use a search engine based on SearXNG [https://etsi.me](https://etsi.me) and its "ulr query": https://etsi.me/search?q=%s

Lastly if you still want to use your Google account (chrome, yt, drive, etc.) make sure to check the following link and disable everything you are not comfortable with:
[https://myaccount.google.com/data-and-privacy](https://myaccount.google.com/data-and-privacy)

Same goes with Amazon services:
[https://www.amazon.com/alexa-privacy/apd/myad](https://www.amazon.com/alexa-privacy/apd/myad)

If you live in the EU make sure also to check those:
[https://www.youronlinechoices.com](https://www.youronlinechoices.com)


> **1) Install AdGuard:**

Chromium: [https://chrome.google.com/webstore/detail/adguard-adblocker/bgnkhhnnamicmpeenaelnjfhikgbkllg](https://chrome.google.com/webstore/detail/adguard-adblocker/bgnkhhnnamicmpeenaelnjfhikgbkllg)

Firefox: [https://addons.mozilla.org/en-US/firefox/addon/adguard-adblocker](https://addons.mozilla.org/en-US/firefox/addon/adguard-adblocker)

1.5) Once installed go to the option by clicking the green shield icon in your extension bar (make sure is visible) and click "Import settings" (General Settings) and add the attachment below (adg_ext...).

You can downloading it from here (remember to extract): [20230822_172413_adg_ext_settings_4.2.151.zip](https://github.com/Luke0094/A-Better-Way-Through-Internet/files/12906650/20230822_172413_adg_ext_settings_4.2.151.zip)



*This step will import custom settings and filters.*


> **2) Install Tampermoneky:**

Chromium: [https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)

Firefox: [https://addons.mozilla.org/en-US/firefox/addon/tampermonkey](https://addons.mozilla.org/en-US/firefox/addon/tampermonkey)

2.5) Same as before click the black/gray icon in your extension bar (make sure it is visible), click "Control panel" and go to "Utility", click "Import" and add the attachment below (tampermonkey-backup...).

You can downloading it from here (remember to extract): [tampermonkey-backup-chrome-2023-10-13T22-26-56-929Z.zip](https://github.com/Luke0094/A-Better-Way-Through-Internet/files/12906651/tampermonkey-backup-chrome-2023-10-13T22-26-56-929Z.zip)



*This step will import various user scripts such a "Pop up blocker" and few irrelevant but useful script (if you are not interested you can leave only the "AdGuard Popup Blocker")*

*What else is included:*

*EmuParadise Download Workaround - KAADIVVVV - vvvvid.it Anti-Adblock Killer - Remove Adblock Thing (for youtube, disabled due breaking layout, however working) - Simple YouTube Age Restriction Bypass*

> **3) Install Privacy Badger**

Chromium: [https://chrome.google.com/webstore/detail/privacy-badger/pkehgijcmpdhfbdbbnkijodmdjhbjlgp](https://chrome.google.com/webstore/detail/privacy-badger/pkehgijcmpdhfbdbbnkijodmdjhbjlgp)

Firefox: [https://addons.mozilla.org/en-US/firefox/addon/privacy-badger17/](https://addons.mozilla.org/en-US/firefox/addon/privacy-badger17/)

*This step will increase your rate of blocked trackers, is a bit redundant with AdGuard for most of the time but will be useful if for whatever reason you have to disable your adblocker*


> **4) Install FastForward:**

Chromium: [https://chrome.google.com/webstore/detail/fastforward/icallnadddjmdinamnolclfjanhfoafe](https://chrome.google.com/webstore/detail/fastforward/icallnadddjmdinamnolclfjanhfoafe)

*Warning: the version uploaded in the store come with less filters and there's still a lot of work to catch up so is best if you follow the instruction on their [Github](https://github.com/FastForwardTeam/FastForward/blob/main/docs/INSTALLING.md) and install it manually, you can download it directly from [here](https://nightly.link/FastForwardTeam/FastForward/workflows/main/main/FastForward_chromium.zip)*

To install this extension on chromium browser manually you have first unpack the .zip file with softwares like Winrar, 7-zip, enable the developer options in the extension page and simply drag and drop the zip file under the extension page.

Firefox: [https://addons.mozilla.org/en-US/firefox/addon/fastforwardteam](https://addons.mozilla.org/en-US/firefox/addon/fastforwardteam)

*Warning: the version uploaded in the store come with less filters and there's still a lot of work to catch up so is best if you follow the instruction on their [Github](https://github.com/FastForwardTeam/FastForward/blob/main/docs/INSTALLING.md) and install it manually, you can download it directly from [here](https://nightly.link/FastForwardTeam/FastForward/workflows/main/main/FastForward_firefox.zip)*

Important: some filters had to be removed by complains like from Linkvertise, you can re-add them by going to the extension setting (blue icon) and copy/paste to the "Custom bypass" the following script (extract and open the file .txt): [Linkvertise bypass.zip](https://github.com/Luke0094/A-Better-Way-Through-Internet/files/12906653/Linkvertise.bypass.zip)

Note: unpacked extension not have the ability to auto-update themself, once in a while check their [Github](https://github.com/qnoum/bypass-paywalls-chrome-clean-magnolia1234) for updates:

*This step will grand you the ability to skip various hosts limit like countdown on file hosts, skip paid shortcut, etc.*

> **5) Install Bypass Paywalls Clean:**

Chromium: [https://gitlab.com/magnolia1234/bypass-paywalls-chrome-clean/-/archive/master/bypass-paywalls-chrome-clean-master.zip](https://gitlab.com/magnolia1234/bypass-paywalls-chrome-clean/-/archive/master/bypass-paywalls-chrome-clean-master.zip)

To install this extension on chromium browser manually enable the developer options in the extension and simply drag and drop the zip file under the extension page.

Firefox: follow the instruction under their [Gitlab](https://gitlab.com/magnolia1234/bypass-paywalls-firefox-clean) page

Note: unpacked extension not have the ability to auto-update themself, once in a while check their [Github](https://github.com/qnoum/bypass-paywalls-chrome-clean-magnolia1234) for updates:

*This step will grand you the ability to skip certain paywalls based on daily views limit and/or similar issues*


All the steps below are totally optional but recommended for a better experience.
-


**Dark Mode**
> **6) Dark Reader:**

Chromium: [https://chrome.google.com/webstore/detail/dark-reader/eimadpbcbfnmbkopoojfekhnkhdbieeh](https://chrome.google.com/webstore/detail/dark-reader/eimadpbcbfnmbkopoojfekhnkhdbieeh)

Firefox: [https://addons.mozilla.org/en-US/firefox/addon/darkreader](https://addons.mozilla.org/en-US/firefox/addon/darkreader)

*This step will grand you the ability to set every website to a dark mode, please note that not all website will be showing correctly*

**CAPTCHA:**
> **7) Noptcha:**

Chromium: [https://chrome.google.com/webstore/detail/noptcha-recaptcha-hcaptch/dknlfmjaanfblgfdfebhijalfmhmjjjo](https://chrome.google.com/webstore/detail/noptcha-recaptcha-hcaptch/dknlfmjaanfblgfdfebhijalfmhmjjjo)

Firefox: [https://addons.mozilla.org/en-US/firefox/addon/noptcha](https://addons.mozilla.org/en-US/firefox/addon/noptcha)

*This step will grand you the ability to auto-complete the captcha around the net automatically, you can cutomize the behavior under the extension options*

**VPN:**
> **8) WorkingVPN:**

Chromium: [https://chrome.google.com/webstore/detail/workingvpn-a-free-vpn-tha/mhngpdlhojliikfknhfaglpnddniijfh](https://chrome.google.com/webstore/detail/workingvpn-a-free-vpn-tha/mhngpdlhojliikfknhfaglpnddniijfh)

Firefox: [https://addons.mozilla.org/en-US/firefox/addon/workingvpn-the-vpn-that-works/](https://addons.mozilla.org/en-US/firefox/addon/workingvpn-the-vpn-that-works/)

*This step will permit you to use a free vpn service without limit, take note that this is not the fastest nor the most secure but will work*

**YOUTUBE**
> **9) SponsorBlock for Youtube:**

Chromium: [https://chrome.google.com/webstore/detail/sponsorblock-for-youtube/mnjggcdmjocbbbhaepdhchncahnbgone](https://chrome.google.com/webstore/detail/sponsorblock-for-youtube/mnjggcdmjocbbbhaepdhchncahnbgone)

Firefox: [https://addons.mozilla.org/en-US/firefox/addon/sponsorblock](https://addons.mozilla.org/en-US/firefox/addon/sponsorblock)

*This step will flag portions of certain YT videos with sponsor materials and grand you the ability to skip them automatically*


> **10) Return YouTube Dislike:**

Chromium: [https://chrome.google.com/webstore/detail/return-youtube-dislike/gebbhagfogifgggkldgodflihgfeippi](https://chrome.google.com/webstore/detail/return-youtube-dislike/gebbhagfogifgggkldgodflihgfeippi)

Firefox: [https://addons.mozilla.org/en-US/firefox/addon/return-youtube-dislikes](https://addons.mozilla.org/en-US/firefox/addon/return-youtube-dislikes)

*This step will restore the count of dislike on YT videos*


> **11) Install Enhancer for YouTube:**

Chromium: [https://chrome.google.com/webstore/detail/enhancer-for-youtube/ponfpcnoihfmfllpaingbgckeeldkhle](https://chrome.google.com/webstore/detail/enhancer-for-youtube/ponfpcnoihfmfllpaingbgckeeldkhle)

Firefox: [https://addons.mozilla.org/en-US/firefox/addon/enhancer-for-youtube](https://addons.mozilla.org/en-US/firefox/addon/enhancer-for-youtube)

*This step will introduce to Youtube various extra option of customization*


> **12) Ambient light for YouTube:**

Chromium: [https://chrome.google.com/webstore/detail/ambient-light-for-youtube/paponcgjfojgemddooebbgniglhkajkj](https://chrome.google.com/webstore/detail/ambient-light-for-youtube/paponcgjfojgemddooebbgniglhkajkj)

Firefox: [https://addons.mozilla.org/en-US/firefox/addon/ambient-light-for-youtube](https://addons.mozilla.org/en-US/firefox/addon/ambient-light-for-youtube)

*This step will introduce to Youtube better theater mode and ambient light*

> **13) Better YouTube Shorts:**

Chromium: [https://chrome.google.com/webstore/detail/better-youtube-shorts/pehohlhkhbcfdneocgnfbnilppmfncdg](https://chrome.google.com/webstore/detail/better-youtube-shorts/pehohlhkhbcfdneocgnfbnilppmfncdg)

Firefox: [https://addons.mozilla.org/en-US/firefox/addon/better-youtube-shorts](https://addons.mozilla.org/en-US/firefox/addon/better-youtube-shorts)

*This step will introduce to Youtube better controls over YT short*

**TWITCH**
> **14) Previews (For TTV & YT):**

Chromium: [https://chrome.google.com/webstore/detail/previews-for-ttv-yt/hpmbiinljekjjcjgijnlbmgcmoonclah](https://chrome.google.com/webstore/detail/previews-for-ttv-yt/hpmbiinljekjjcjgijnlbmgcmoonclah)

Firefox: [https://addons.mozilla.org/en-US/firefox/addon/previews-for-ttv](https://addons.mozilla.org/en-US/firefox/addon/previews-for-ttv)

*This step will introduce to Twitch and partially Youtube better controls over lives*

> **15) TTV Tools (complementary - optional)**

Chromium: [https://chrome.google.com/webstore/detail/ttv-tools/fcfodihfdbiiogppbnhabkigcdhkhdjd](https://chrome.google.com/webstore/detail/ttv-tools/fcfodihfdbiiogppbnhabkigcdhkhdjd)

Firefox: NOT AVAILABLE, follow dev [Github](https://github.com/ephellon/twitch-tools)

*This step will introduce to Twitch better controls over Twitch lives*


**INSTAGRAM**
> **16) Controls for Instagram Videos:**

Chromium: [https://chrome.google.com/webstore/detail/controls-for-instagram-vi/eigfbedabacomcacemdnkelnlhgbiacn](https://chrome.google.com/webstore/detail/controls-for-instagram-vi/eigfbedabacomcacemdnkelnlhgbiacn)

Firefox: NOT AVAILABLE, follow dev [website](https://rehfeld.us/browser-extensions/controls-for-instagram/)

*This step will introduce to Instagram better controls over reels*


**STEAM**
> **17) Augmented Steam:**

Chromium: [https://chrome.google.com/webstore/detail/augmented-steam/dnhpnfgdlenaccegplpojghhmaamnnfp](https://chrome.google.com/webstore/detail/augmented-steam/dnhpnfgdlenaccegplpojghhmaamnnfp)

Firefox: [https://addons.mozilla.org/en-US/firefox/addon/augmented-steam](https://addons.mozilla.org/en-US/firefox/addon/augmented-steam)

*This step will introduce to Steam more features about bundles and currency over the world*


> **18) Steam Inventory Helper:**

Chromium: [https://chrome.google.com/webstore/detail/steam-inventory-helper/cmeakgjggjdlcpncigglobpjbkabhmjl](https://chrome.google.com/webstore/detail/steam-inventory-helper/cmeakgjggjdlcpncigglobpjbkabhmjl)

Firefox: NOT AVAILABLE, follow dev [website](https://steaminventoryhelper.com/)

*This step will introduce to Steam more features about trades and currency**


**CRUNCHYROLL**
> **19) Improve Crunchyroll:**

Chromium: [https://chrome.google.com/webstore/detail/improve-crunchyroll/elmhfjhlecffodalffipmgpploaihjgh](https://chrome.google.com/webstore/detail/improve-crunchyroll/elmhfjhlecffodalffipmgpploaihjgh)

Firefox: [https://addons.mozilla.org/en-US/firefox/addon/improve-crunchyroll](https://addons.mozilla.org/en-US/firefox/addon/improve-crunchyroll)

*This step will introduce to Crunchyroll various extra option of customization and unlock some of premium features like 1080p view*

**FLASH PLAYER**
> **20) Rufle:**

Chromium: [https://chrome.google.com/webstore/detail/ruffle/donbcfbmhbcapadipfkeojnmajbakjdc](https://chrome.google.com/webstore/detail/ruffle/donbcfbmhbcapadipfkeojnmajbakjdc)

Firefox: [https://addons.mozilla.org/en-US/firefox/addon/ruffle_rs](https://addons.mozilla.org/en-US/firefox/addon/ruffle_rs)

*This step will restore the possibility to play flash content on your browser*


***Enjoy the freedom of internet!***
