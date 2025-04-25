# Adblock and DNS Services Configuration

## Table of Contents
- [AdGuard Home or AdGuard for Android DNS Filtering](https://github.com/arfshl/adblock-dns-config/tree/main#adguard-home-or-adguard-for-android-dns-filtering)
- [AdGuard Home Parental Control](https://github.com/arfshl/adblock-dns-config/tree/main#parental-control)
- [uBlock Origin | Brave Browser | AdGuard for Android Recommended Filter](https://github.com/arfshl/adblock-dns-config/tree/main#ublock-origin--brave-browser--adguard-for-android)
- [uBlock Origin Lite](https://github.com/arfshl/adblock-dns-config/tree/main#ublock-origin-lite)
- [Recommended Tampermonkey Userscirpt](https://github.com/arfshl/adblock-dns-config/tree/main#recommended-tampermonkey-userscripts)
- [Android/iOS Secure DNS](https://github.com/arfshl/adblock-dns-config/blob/main/docs/android-resolvers.md)
- [Parental Control DNS Services](https://github.com/arfshl/adblock-dns-config/blob/main/docs/parental-resolver.md)
- [NextDNS Configuration](https://github.com/arfshl/adblock-dns-config/blob/main/docs/nextdns.md)
- [AdGuard Private DNS](https://github.com/arfshl/adblock-dns-config/blob/main/docs/adguarddns.md)
- [RethinkDNS Configuration](https://github.com/arfshl/adblock-dns-config/blob/main/docs/rethinkdns.md)
- [dnswarden Configuration](https://github.com/arfshl/adblock-dns-config/blob/main/docs/dnswarden.md)
- [AhaDNS Configuration](https://github.com/arfshl/adblock-dns-config/blob/main/docs/ahadns.md)
- [AdGuard Home/AdGuard for Android DNS Upstream](https://github.com/arfshl/adblock-dns-config/blob/main/docs/dns-resolvers.md)

## AdGuard Home or AdGuard for Android DNS Filtering

- AdGuard DNS Filter (Enabled by default)

- [HaGeZi Pro Plus](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/pro.txt)

- [HaGeZi Threat Intelligence Feeds](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/tif.txt)

- [Abused TLDs - for local phishing](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/spam-tlds.txt)

- [WindowsSpyBlocker Update - For disabling windows update, but blocks access to microsoft store](https://github.com/crazy-max/WindowsSpyBlocker/raw/master/data/dnscrypt/update.txt)

- [Adobe Tracker Blocklist (if you use adobe products)](https://github.com/ignaciocastro/a-dove-is-dumb/raw/main/pihole.txt)

- [Supplements (blocks missed domain i came acrross, tor2web, IDN homographs (non-latin domains and TLDs), unblocking important domain)](https://github.com/arfshl/adblock-dns-config/edit/main/unified-filter/supplements.txt)

#### AdGuard Home Parental Control

- You Can Block/Unblock Services at Blocked Services menu, and set schedule for pause blocking

- [HaGeZi Gambling](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/gambling.txt)

- [ABPindo Adult](https://raw.githubusercontent.com/ABPindo/indonesianadblockrules/master/subscriptions/aghome_adult.txt)

- [adblock-dns-config anti-gambling (Experimental)](https://github.com/arfshl/adblock-dns-config/raw/main/my-filter/antijudol.txt)

- [HaGeZi NSFW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/nsfw.txt)

- [Safesearch Enforcing](https://github.com/AdguardTeam/HostlistsRegistry/raw/refs/heads/main/assets/engines_safe_search.txt)

- [YouTube Strict Mode](https://raw.githubusercontent.com/AdguardTeam/HostlistsRegistry/refs/heads/main/assets/youtube_safe_search.txt)

- [HaGeZi Safesearch Not Supported](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/nosafesearch.txt)

- [HaGeZi Piracy](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/anti.piracy.txt)

- [ShadowWhisperer's Dating List](https://raw.githubusercontent.com/ShadowWhisperer/BlockLists/master/Lists/Dating)

- [NextDNS Gaming](https://github.com/arfshl/nextdns-blocklists/raw/latest/subscriptions/gaming.txt)

- [NextDNS Social Networks](https://github.com/arfshl/nextdns-blocklists/raw/latest/subscriptions/social-networks.txt)

- [NextDNS Video Streaming](https://raw.githubusercontent.com/arfshl/nextdns-blocklists/latest/subscriptions/video-streaming.txt)

## uBlock Origin | Brave Browser | AdGuard for Android

- Enable Aggressive Mode for Brave browser 

- Keep Default List, Enable Easylist Social, Easylist Annoyances / Fanboy Annoyances, uBlock Annoyances (uBlock Origin only)

- Make sure ABPindo is enabled (For indonesian region)

- [HaGeZi Threat Intelligence Feeds (Unnecesary if you already use this on DNS-level)](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/tif.txt)

- [Abused TLDs - for local phishing (Unnecesary if you already use this on DNS-level)](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/spam-tlds-ublock.txt)

- [AdBlockID (for Indonesian region)](https://subscribe.adblockplus.org/?location=https://cdn.jsdelivr.net/gh/realodix/AdBlockID@master/dist/adblockid.adfl.txt&title=AdBlockID)

- [🚪 Browse websites without logging in](https://raw.githubusercontent.com/DandelionSprout/adfilt/refs/heads/master/BrowseWebsitesWithoutLoggingIn.txt)

- [Supplements (blocks missed domain/elements, tor2web, IDN homographs (non-latin domains and TLDs), unblocking important domain)](https://github.com/arfshl/adblock-dns-config/edit/main/unified-filter/supplements.txt)

## uBlock Origin Lite [(Chrome, Edge, Opera, Vivaldi, and other Chromium-based browsers)](https://chromewebstore.google.com/detail/ublock-origin-lite/ddkjiahejlhfcafbddmgiahcphecmpfh?hl=en)
#### Settings
- Default filtering mode: Complete
- Enable strict blocking: ON
#### Filter Lists
- Annoyances: Enable ALL
- Miscellaneous: Enable AdGuard URL Tracking Protection
- Regions, Languages: Depends on your region and language sites (ABPindo for Indonesian Languages)

## Recommended [Tampermonkey](https://www.tampermonkey.net/) Useerscript 
Removing more annoying elements from the websites

[DisableAMP](https://userscripts.adtidy.org/release/disable-amp/1.0/disable-amp.user.js) - This is a very simple userscript that disables AMP pages on the Google search results page. Open Google search results on a mobile phone, click on the link marked as AMP. This link should be opened without AMP.

[AutoAllPages (Indonesian Only)](https://raw.githubusercontent.com/reforget-id/AutoAllPage/main/script/autoallpage.user.js) - Otomatis menampilkan semua halaman artikel berita dalam 1 halaman.

#### I also shared my personal configuration files, notes that this only optimized for my own devices, only use this for references\

- [My Personal filter](https://raw.githubusercontent.com/arfshl/adblock-dns-config/refs/heads/main/internal-usage/b.txt)

- [AdGuard for Android](https://github.com/arfshl/adblock-dns-config/archive/refs/heads/adguard-for-android-config.zip)

- [Private AdGuard DNS](https://github.com/arfshl/adblock-dns-config/raw/main/res/adguarddnsconfig.txt)

- [uBlock Origin](https://github.com/arfshl/adblock-dns-config/raw/main/res/ublock0config.txt)

- [AdGuard Home for Windows](https://github.com/arfshl/adblock-dns-config/raw/main/res/aghome-win.yaml)

- [AdGuard Home for Linux](https://github.com/arfshl/adblock-dns-config/raw/main/res/aghome-linux.yaml)
