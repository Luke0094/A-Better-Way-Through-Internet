# A-Better-Way-Through-Internet
*Internet without harassment by ads company!*


This is the version **4.2** and probably final tutorial that will create a safe navigation with no ads, privacy focus and no annoying stuff like cookies warning, it will include some part of the older tuto but lighter in ram consumption and with some more filters.

> **0) Install your favorite Chromium browser (like Brave, Ungoogled, Chrome, Vivaldi, etc.) or Firefox.**

(I recommend [Brave Beta](https://brave.com/download-beta/), if you do so under settings/protection set the fingerprint to strict (this choice is no longer available), eventually if you are not getting access to some websites you can always disable a specific one by clicking the orange lion head on the right of the url search bar,
under settings/privacy you can also disable some annoyance feature like anonym stats.

If you wish to use Android you may want to use [Kiwi Browser](https://play.google.com/store/apps/details?id=com.kiwibrowser.browser), check for apk if is not available, for Android TV you most probably will need a usb mouse.)

Other than all the below steps will be a good point to block any 3rd party cookies from your browser (check your settings and search for Privacy and Security) and block any connection that not come with https.

Furthermore I can recommend you to use [https://presearch.com](https://presearch.com/)  as your default search engine Instead of Google due better uncensored searches (you don't need to sign up), 

here you can find the "url query": https://presearch.com/search?q=%s

Alternatively you can use a search engine based on SearXNG like [https://etsi.me](https://etsi.me) and here the "ulr query": https://etsi.me/search?q=%s

Lastly if you still want to use your Google account (chrome, yt, drive, etc.) make sure to check the following link and disable everything you are not comfortable with:
[https://myaccount.google.com/data-and-privacy](https://myaccount.google.com/data-and-privacy)

Same goes with Amazon services:
[https://www.amazon.com/alexa-privacy/apd/myad](https://www.amazon.com/alexa-privacy/apd/myad)

If you live in the EU make sure also to check those:
[https://www.youronlinechoices.com](https://www.youronlinechoices.com)


*Btw do you know that your ISP can prevent you from visiting certain websites by blacklisting? To avoid this block you need to change your DNS, this can be done manually or by using some softwares, here is one exemple with DNS Jumper [DnsJumper 2.2.zip](https://github.com/Luke0094/A-Better-Way-Through-Internet/files/13196421/DnsJumper.2.2.zip)*



> **1) Install AdGuard:**

Chromium: [https://chrome.google.com/webstore/detail/adguard-adblocker/bgnkhhnnamicmpeenaelnjfhikgbkllg](https://chrome.google.com/webstore/detail/adguard-adblocker/bgnkhhnnamicmpeenaelnjfhikgbkllg)

Firefox: [https://addons.mozilla.org/en-US/firefox/addon/adguard-adblocker](https://addons.mozilla.org/en-US/firefox/addon/adguard-adblocker)

*This step will add one of the best adblocker around to your searches.*

1.5) Once installed go to the option by clicking the green shield icon in your extension bar (make sure is visible) and click "Import settings" (General Settings) and add the attachment below (adg_ext...).

You can downloading it from here (remember to extract): [20240619_152432_adg_ext_settings_4.3.53.zip](https://github.com/user-attachments/files/15901576/20240619_152432_adg_ext_settings_4.3.53.zip)



*This step will import custom settings and filters.*


> **2) Install Tampermoneky:**

Chromium: [https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)

Firefox: [https://addons.mozilla.org/en-US/firefox/addon/tampermonkey](https://addons.mozilla.org/en-US/firefox/addon/tampermonkey)

*This step will will allow you to install custom scripts to your browser.*

2.5) Same as before click the black/gray icon in your extension bar (make sure it is visible), click "Control panel" and go to "Utility", click "Import" and add the attachment below (tampermonkey-backup...).

You can downloading it from here (remember to extract): [tampermonkey-backup-chrome-2024-06-19T13-41-26-906Z.zip](https://github.com/user-attachments/files/15901739/tampermonkey-backup-chrome-2024-06-19T13-41-26-906Z.zip)

*This step will import various user scripts such as "Ultra Popup Blocker" and few other useful ones.*

*What else is included:*

*ADGaurd Extra - Bypass All Shortlinks Debloated - KAADIVVVV - vvvvid.it Anti-Adblock Killer - Netflix Plus (disabled) - Netflix UHD (disabled) - Simple YouTube Age Restriction Bypass*

<details> 
  <summary>Known bugs: </summary>
   Some website that depend from pop ups (usually from Google) may not  work correctly with Ultra Popup Blocker enabled (the pop up warning is half hidden), here a list of what I've found out and how to fix:
  
  The easier solution is to click the tampermoneky icon when you are on the problematic page, click on Ultra Popup Blocker and select "exclude" a certain host, such as:
  
Google Drive: "exclude drive.google.com"

Google Classroom: "exclude classroom.google.com"

Google Remote Desktop "exclude remotedesktop.google.com"

Any coupon websites that will input pop ups before showing the code, the extension is actually working fine here but you might want to just refresh the page there, otherwise your cookies will be injected with ref codes
</details>

> **3) Install Privacy Badger**

Chromium: [https://chrome.google.com/webstore/detail/privacy-badger/pkehgijcmpdhfbdbbnkijodmdjhbjlgp](https://chrome.google.com/webstore/detail/privacy-badger/pkehgijcmpdhfbdbbnkijodmdjhbjlgp)

Firefox: [https://addons.mozilla.org/en-US/firefox/addon/privacy-badger17/](https://addons.mozilla.org/en-US/firefox/addon/privacy-badger17/)

**NOTE: login with social credentials (google, apple, etc.) are automatically blocked by this extension, if you wish to enable it, while in that specific page (like twitter), click on the extension icon (the skunk one) and allow the specific host (like "accounts.google.com").**

*This step will increase your rate of blocked trackers, is a bit redundant with AdGuard but other then blocking few more trackers it will be useful if for whatever reason you have to disable your adblocker.*


All the steps below are totally optional but recommended for a better experience.
-

**Paywalls**
> **4) Bypass Paywalls Clean:**

*(This step is marked as optional due filters already included inside the AdGuard config, it will however be useful in case you want to have the full list and/or add custom filters)*

Chromium: [https://github.com/bpc-clone/bpc_updates/releases/tag/latest](https://github.com/bpc-clone/bpc_updates/releases/tag/latest)

To install this extension on chromium browser manually you have first enable the developer options in the extension and then unpack the .zip file with softwares like winrar or 7zip and click on "load unpacked extension", alternatively you can create a .zip containing only the files (without main folder name) and drag and drop this one in the extension page

Note: unpacked extension not have the ability to auto-update themself, once in a while check their [Github](https://github.com/bpc-clone/bypass-paywalls-chrome-clean) for updates

Firefox: follow the instruction under their [Github](https://github.com/bpc-clone/bypass-paywalls-firefox-clean) page

*This step will grant you the ability to skip certain paywalls based on daily views limit and/or similar issues.*


**Dark Mode**
> **5) Dark Reader:**

Chromium: [https://chrome.google.com/webstore/detail/dark-reader/eimadpbcbfnmbkopoojfekhnkhdbieeh](https://chrome.google.com/webstore/detail/dark-reader/eimadpbcbfnmbkopoojfekhnkhdbieeh)

Firefox: [https://addons.mozilla.org/en-US/firefox/addon/darkreader](https://addons.mozilla.org/en-US/firefox/addon/darkreader)

*This step will grant you the ability to set every website to a dark mode, please note that not all website will be showing correctly.*


**CAPTCHA:**
> **6) Noptcha:**

*(Currently this extension is outdated due dev disappearance, this extension will still work but only partially)*
Chromium: [https://chrome.google.com/webstore/detail/noptcha-recaptcha-hcaptch/dknlfmjaanfblgfdfebhijalfmhmjjjo](https://chrome.google.com/webstore/detail/noptcha-recaptcha-hcaptch/dknlfmjaanfblgfdfebhijalfmhmjjjo)

Firefox: [https://addons.mozilla.org/en-US/firefox/addon/noptcha](https://addons.mozilla.org/en-US/firefox/addon/noptcha)

*This step will grant you the ability to auto-complete the captcha around the net automatically, you can cutomize the behavior under the extension options.*


**VPN:**
> **7) WorkingVPN:**

Chromium: [https://chrome.google.com/webstore/detail/workingvpn-a-free-vpn-tha/mhngpdlhojliikfknhfaglpnddniijfh](https://chrome.google.com/webstore/detail/workingvpn-a-free-vpn-tha/mhngpdlhojliikfknhfaglpnddniijfh)

Firefox: [https://addons.mozilla.org/en-US/firefox/addon/workingvpn-the-vpn-that-works/](https://addons.mozilla.org/en-US/firefox/addon/workingvpn-the-vpn-that-works/)

*This step will permit you to use a free vpn service without limit, take note that this is not the fastest nor the most secure but will work.*


**YOUTUBE**
> **8) SponsorBlock for Youtube:**

Chromium: [https://chrome.google.com/webstore/detail/sponsorblock-for-youtube/mnjggcdmjocbbbhaepdhchncahnbgone](https://chrome.google.com/webstore/detail/sponsorblock-for-youtube/mnjggcdmjocbbbhaepdhchncahnbgone)

Firefox: [https://addons.mozilla.org/en-US/firefox/addon/sponsorblock](https://addons.mozilla.org/en-US/firefox/addon/sponsorblock)

*This step will flag portions of certain YT videos with sponsor materials and grand you the ability to skip them automatically.*


> **9) Return YouTube Dislike:**

Chromium: [https://chrome.google.com/webstore/detail/return-youtube-dislike/gebbhagfogifgggkldgodflihgfeippi](https://chrome.google.com/webstore/detail/return-youtube-dislike/gebbhagfogifgggkldgodflihgfeippi)

Firefox: [https://addons.mozilla.org/en-US/firefox/addon/return-youtube-dislikes](https://addons.mozilla.org/en-US/firefox/addon/return-youtube-dislikes)

*This step will restore the count of dislike on YT videos.*


> **10) Install Enhancer for YouTube:**

Chromium: [https://chrome.google.com/webstore/detail/enhancer-for-youtube/ponfpcnoihfmfllpaingbgckeeldkhle](https://chrome.google.com/webstore/detail/enhancer-for-youtube/ponfpcnoihfmfllpaingbgckeeldkhle)

Firefox: [https://addons.mozilla.org/en-US/firefox/addon/enhancer-for-youtube](https://addons.mozilla.org/en-US/firefox/addon/enhancer-for-youtube)

*This step will introduce to Youtube various extra option of customization.*

*Here some custom settings that you can easily import (just copy and paste the string inside the .txt file and import it in the extension page)* [yt.enhancer.zip](https://github.com/user-attachments/files/16383966/yt.enhancer.zip)



> **11) Ambient light for YouTube:**

Chromium: [https://chrome.google.com/webstore/detail/ambient-light-for-youtube/paponcgjfojgemddooebbgniglhkajkj](https://chrome.google.com/webstore/detail/ambient-light-for-youtube/paponcgjfojgemddooebbgniglhkajkj)

Firefox: [https://addons.mozilla.org/en-US/firefox/addon/ambient-light-for-youtube](https://addons.mozilla.org/en-US/firefox/addon/ambient-light-for-youtube)

*This step will introduce to Youtube better theater mode and ambient light.*

*Here some custom settings that you can easily import (after excracting just click the extension icon and import the .json file)* [ambient-light-for-youtube-settings.zip](https://github.com/Luke0094/A-Better-Way-Through-Internet/files/13492685/ambient-light-for-youtube-settings.zip)


> **12) Better YouTube Shorts:**

*(Currently this extension is outdated due dev disappearance, all features are for now disabled)*

Chromium: [https://chrome.google.com/webstore/detail/better-youtube-shorts/pehohlhkhbcfdneocgnfbnilppmfncdg](https://chrome.google.com/webstore/detail/better-youtube-shorts/pehohlhkhbcfdneocgnfbnilppmfncdg)

Firefox: [https://addons.mozilla.org/en-US/firefox/addon/better-youtube-shorts](https://addons.mozilla.org/en-US/firefox/addon/better-youtube-shorts)

*This step will introduce to Youtube better controls over YT short.*


**TWITCH**
> **13) Previews (For TTV & YT):**

Chromium: [https://chrome.google.com/webstore/detail/previews-for-ttv-yt/hpmbiinljekjjcjgijnlbmgcmoonclah](https://chrome.google.com/webstore/detail/previews-for-ttv-yt/hpmbiinljekjjcjgijnlbmgcmoonclah)

Firefox: [https://addons.mozilla.org/en-US/firefox/addon/previews-for-ttv](https://addons.mozilla.org/en-US/firefox/addon/previews-for-ttv)

*This step will introduce to Twitch and partially Youtube better controls over lives.*


> **14) TTV Tools (complementary - optional)**

Chromium: [https://chrome.google.com/webstore/detail/ttv-tools/fcfodihfdbiiogppbnhabkigcdhkhdjd](https://chrome.google.com/webstore/detail/ttv-tools/fcfodihfdbiiogppbnhabkigcdhkhdjd)

Firefox: NOT AVAILABLE, follow dev [Github](https://github.com/ephellon/twitch-tools)

*This step will introduce to Twitch better controls over Twitch lives.*


> **15) TwitchNoSub:**

Chromium: [https://github.com/besuper/TwitchNoSub/releases](https://github.com/besuper/TwitchNoSub/releases)

To install this extension on chromium browser manually you have first enable the developer options in the extension and then unpack the .zip file with softwares like winrar or 7zip and click on "load unpacked extension", alternatively you can create a .zip containing only the files (without main folder name) and drag and drop this one in the extension page.

Firefox: follow the instruction under their [Github](https://github.com/besuper/TwitchNoSub/)

*This step will make you able to watch premium vod from twitch as free user.*

Note: unpacked extension not have the ability to auto-update themself, once in a while check their [Github](https://github.com/besuper/TwitchNoSub/) for updates.


**INSTAGRAM**
> **16) Controls for Instagram Videos:**

Chromium: [https://chrome.google.com/webstore/detail/controls-for-instagram-vi/eigfbedabacomcacemdnkelnlhgbiacn](https://chrome.google.com/webstore/detail/controls-for-instagram-vi/eigfbedabacomcacemdnkelnlhgbiacn)

Firefox: NOT AVAILABLE, follow dev [website](https://rehfeld.us/browser-extensions/controls-for-instagram/)

*This step will introduce to Instagram better controls over reels.*


**STEAM**
> **17) Augmented Steam:**

Chromium: [https://chrome.google.com/webstore/detail/augmented-steam/dnhpnfgdlenaccegplpojghhmaamnnfp](https://chrome.google.com/webstore/detail/augmented-steam/dnhpnfgdlenaccegplpojghhmaamnnfp)

Firefox: [https://addons.mozilla.org/en-US/firefox/addon/augmented-steam](https://addons.mozilla.org/en-US/firefox/addon/augmented-steam)

*This step will introduce to Steam more features about bundles and currency over the world.*


> **18) Steam Inventory Helper:**

**WARNING:** *The chrome extension is requiring way too much auth to work, probably has been breached*

Chromium: *removed due suspicious behavior*

Firefox: NOT AVAILABLE, follow dev [website](https://steaminventoryhelper.com/)

*This step will introduce to Steam more features about trades and currency.*


**CRUNCHYROLL**
> **19) Improve Crunchyroll:**

Chromium: [https://chrome.google.com/webstore/detail/improve-crunchyroll/elmhfjhlecffodalffipmgpploaihjgh](https://chrome.google.com/webstore/detail/improve-crunchyroll/elmhfjhlecffodalffipmgpploaihjgh)

Firefox: [https://addons.mozilla.org/en-US/firefox/addon/improve-crunchyroll](https://addons.mozilla.org/en-US/firefox/addon/improve-crunchyroll)

*This step will introduce to Crunchyroll various extra option of customization and unlock some of premium features like 1080p view.*


**FLASH PLAYER**
> **20) Rufle:**

Chromium: [https://chrome.google.com/webstore/detail/ruffle/donbcfbmhbcapadipfkeojnmajbakjdc](https://chrome.google.com/webstore/detail/ruffle/donbcfbmhbcapadipfkeojnmajbakjdc)

Firefox: [https://addons.mozilla.org/en-US/firefox/addon/ruffle_rs](https://addons.mozilla.org/en-US/firefox/addon/ruffle_rs)

*This step will restore the possibility to play flash content on your browser.*


***Enjoy the freedom of internet!***
