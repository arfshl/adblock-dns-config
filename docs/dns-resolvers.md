## Encrypted DNS Clients (System Wide)

- Android
  1. Built-in Private DNS or [RethinkDNS App](https://play.google.com/store/apps/details?id=com.celzero.bravedns)
- Windows
  1. Built-in Windows 11 or [YogaDNS](https://www.yogadns.com/) and [dnscrypt-proxy](https://github.com/DNSCrypt/dnscrypt-proxy)
- macOS and iOS
  1. Built-in
- Linux
  1. [systemd-resolved](https://wiki.archlinux.org/title/Systemd-resolved) or [dnscrypt-proxy](https://github.com/DNSCrypt/dnscrypt-proxy)

## Recommended Encrypted DNS Upstream
| Provider | DoH | DoT | Alternative UDP Port (fallback/bootstrap) | Apple |
| --- | --- | --- | --- | --- |
| AdGuard DNS | https://dns.adguard-dns.com/dns-query | dns.adguard-dns.com | - | https://adguard-dns.io/en/blog/encrypted-dns-ios-14.html |
| AdGuard DNS Unfiltered | https://unfiltered.adguard-dns.com/dns-query | unfiltered.adguard-dns.com | 94.140.14.140:5353, 94.140.14.141:5353 | - |
| Cloudflare DNS | https://cloudflare-dns.com/dns-query | cloudflare-dns.com | - | - |
| Cloudflare DNS - Security | https://security.cloudflare-dns.com/dns-query | security.cloudflare-dns.com | - | - |
| ControlD Ads&Tracking | https://freedns.controld.com/p2 | p2.freedns.controld.com | - | - |
| ControlD - Hagezi Pro | https://freedns.controld.com/x-hagezi-pro | x-hagezi-pro.freedns.controld.com | - | https://api.controld.com/mobileconfig/x-hagezi-proplus?type=free&exclude_common=1 |
| ControlD Malware | https://freedns.controld.com/p1 | p1.freedns.controld.com | - | - |
| ControlD Uncensored | https://freedns.controld.com/uncensored | uncensored.freedns.controld.com | - | - |
| ControlD Unfiltered | https://freedns.controld.com/p0 | p0.freedns.controld.com | - | https://docs.controld.com/docs/ios-platform, https://docs.controld.com/docs/macos-platform#manual-setup-profile |
| NextDNS Public DNS | https://dns.nextdns.io/dns-query | dns.nextdns.io | 45.90.28.0:5353, 45.90.30.0:5353 | - |
| Quad9 (Anti-malware) | https://dns.quad9.net/dns-query | dns.quad9.net | 9.9.9.9:9953, 149.112.112.112:9953 | https://docs.quad9.net/Setup_Guides/iOS/iOS_14_and_later_(Encrypted), https://docs.quad9.net/Setup_Guides/MacOS/Big_Sur_and_later_(Encrypted) |

## Encrypted with Parental Control
| Provider | DNS-Over-HTTPS/HTTP3 | DNS-Over-TLS/QUIC | IPv4 | Apple |
| --- | --- | --- | --- | --- |
| AdGuard DNS Family (Supports Ad-Blocking) | https://family.adguard-dns.com/dns-query | family.adguard-dns.com | 94.140.14.15, 94.140.15.16 | https://adguard-dns.io/en/public-dns.html |
| CleanBrowsing Adult (MIxed Contents like reddit and bypass methods like VPNs or Proxies allowed) | https://doh.cleanbrowsing.org/doh/adult-filter/ | adult-filter-dns.cleanbrowsing.org | 185.228.168.10, 185.228.169.11 | http://my.cleanbrowsing.org/download-mobile-config.php?filter=adult |
| CleanBrowsing Family (No MIxed Contents like reddit, blocks bypass methods like VPNs or Proxies) | https://doh.cleanbrowsing.org/doh/family-filter/ | family-filter-dns.cleanbrowsing.org | 185.228.168.168, 185.228.169.168 | http://my.cleanbrowsing.org/download-mobile-config.php?filter=family |
| Cloudflare DNS Family | https://family.cloudflare-dns.com/dns-query | family.cloudflare-dns.com | 1.1.1.3, 1.0.0.3 | |
| ControlD Family Friendly (Malware + Ads & Tracking + Adult Content + Drugs) | https://freedns.controld.com/family | family.freedns.controld.com | 76.76.2.4, 76.76.10.4 | https://api.controld.com/mobileconfig/family?type=free&exclude_common=1 |
| ControlD Social (Malware + Ads & Tracking + Social Networks) | https://freedns.controld.com/p3 | p3.freedns.controld.com | 76.76.2.3, 76.76.10.3 | https://api.controld.com/mobileconfig/p3?type=free&exclude_common=1 |

