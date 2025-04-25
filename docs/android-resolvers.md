## Android/iOS Secure DNS with Adblocking
Criteria: Must be have Ads, Tracker and Malware blocking capabilities

| Provider | Address | Apple Mobileconfig
| --- | --- | --- |
| ControlD DNS - Hagezi Pro | x-hagezi-pro.freedns.controld.com | [Apple](https://api.controld.com/mobileconfig/x-hagezi-proplus?type=free&exclude_common=1) |
| AdGuard DNS | dns.adguard-dns.com | [(Links)](https://adguard-dns.io/en/public-dns.html), Looks for option 2 and looks for iOS|
| Mullvad Base (Ads+Tracker+Malware) (potentially high latency and uptime issues) | base.dns.mullvad.net | [DNS-Over-HTTPS](https://github.com/mullvad/encrypted-dns-profiles/raw/refs/heads/main/base/mullvad-encrypted-dns-https-base.mobileconfig) [DNS-Over-TLS](https://github.com/mullvad/encrypted-dns-profiles/raw/refs/heads/main/base/mullvad-encrypted-dns-tls-base.mobileconfig)|

#### You may also looks for [RethinkDNS](https://github.com/arfshl/adblock-dns-config/blob/main/docs/rethinkdns.md) for more flexibility
