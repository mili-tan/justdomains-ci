# DOMAIN-ONLY Filter Lists
**Last Updated:** 2025-02-10 16:15:46

- [Details](#details)
- [Usage](#usage)
  - [Using with Pi-Hole](#using-with-pi-hole)
  - [Using with other tools](#using-with-other-tools)
- [The Lists](#the-lists)
  - [AdAway Blocklist](#adaway-blocklist-domains-only) (Domains-only)
  - [StevenBlack's Hosts](#stevenblacks-hosts-domains-only) (Domains-only)
  - [Yoyos Hosts](#yoyos-hosts-domains-only) (Domains-only)
  - [AdRules DNS List](#adrules-dns-list-domains-only) (Domains-only)
  - [AdGuard DNS Filter](#adguard-dns-filter-domains-only) (Domains-only)
  - [EasyList](#easylist-domains-only) (Domains-only)
  - [EasyPrivacy](#easyprivacy-domains-only) (Domains-only)
  - [CJX's Annoyance List](#cjxs-annoyance-list-domains-only) (Domains-only)
  - [Fanboy's Annoyance List](#fanboys-annoyance-list-domains-only) (Domains-only)
  - [EasyList China](#easylist-china-domains-only) (Domains-only)
  - [AdGuard Tracking Filter](#adguard-tracking-filter-domains-only) (Domains-only)
  - [AWAvenue Adblock Rule](#awavenue-adblock-rule-domains-only) (Domains-only)
  - [OISD Small](#oisd-small-domains-only) (Domains-only)
  - [OISD Big](#oisd-big-domains-only) (Domains-only)
  - [Hagezi Blocklists Light](#hagezi-blocklists-light-domains-only) (Domains-only)
  - [Hagezi Blocklists Normal](#hagezi-blocklists-normal-domains-only) (Domains-only)
  - [Blackmatrix7's Advertising Rules](#blackmatrix7s-advertising-rules-domains-only) (Domains-only)
  - [Blackmatrix7's Advertising Rules Lite](#blackmatrix7s-advertising-rules-lite-domains-only) (Domains-only)
  - [d3Host List by d3ward](#d3host-list-by-d3ward-domains-only) (Domains-only)
  - [NoCoin Filter](#nocoin-filter-domains-only) (Domains-only)
  - [CERT.PL's Warning List](#certpls-warning-list-domains-only) (Domains-only)
  - [Hagezi Anti Bypass](#hagezi-anti-bypass-domains-only) (Domains-only)
  - [DDNS Filter](#ddns-filter-domains-only) (Domains-only)
  - [IPFS Filter](#ipfs-filter-domains-only) (Domains-only)
  - [Anti SafeSearch Bypass](#anti-safesearch-bypass-domains-only) (Domains-only)
  - [NextDNS Native Tracking Filter](#nextdns-native-tracking-filter-domains-only) (Domains-only)
  - [Blackmatrix7's MiTV Rules](#blackmatrix7s-mitv-rules-domains-only) (Domains-only)
  - [Anti HTTPDNS Bypass](#anti-httpdns-bypass-domains-only) (Domains-only)
  - [HideMyTel](#hidemytel-domains-only) (Domains-only)
  - [Anti-AD Encrypted DNS](#anti-ad-encrypted-dns-domains-only) (Domains-only)
  - [Anti-AD Auto Number Verification](#anti-ad-auto-number-verification-domains-only) (Domains-only)
  - [Anti-AD PCDN](#anti-ad-pcdn-domains-only) (Domains-only)
- [License](#license)
- [Reporting Conversion Issues](#reporting-conversion-issues)

&nbsp;

# Details:
These are "DOMAIN-ONLY" **converted** versions of various popular original filter / blocking lists.
They have been modified from their original versions by scripts at: https://github.com/justdomains/ci

The scripts output **only** the full-domain-blocking entries from the original lists, while attempting to filter any domains that conflict with an exception rule on the original list.

**Because these are automated, converted _subsets_ of the original lists, please do not report omissions from these converted files to the list originator.**

&nbsp;

# Usage:
These converted files can be used with various DNS and domain-blocking tools:

## Using with [Pi-Hole](https://pi-hole.net/):
1. Copy the link to the Pi-Hole format for the desired list (from the appropriate table below).
2. [Add the URL to your Pi-Hole's block lists (**Settings** > **Pi-Hole's Block Lists**).](https://github.com/pi-hole/pi-hole/wiki/Customising-Sources-for-Ad-Lists)

## Using with other tools:
The converted lists are provided in a "Raw Domain List" format that contains only domains, one per line. Many other tools / scripts can ingest this format to add them to your blocklist.

&nbsp;

# The Lists:

| Converted List | License | Domains | Domain List | Last Updated |
:- | - | - | :-: | - |
| [AdAway Blocklist](#adaway-blocklist-domains-only) | [CC BY 3.0](https://github.com/AdAway/AdAway/blob/master/LICENSE) | 6540 | [**Download**](https://mili-tan.github.io/justdomains/lists/adaway.list) |  |
| [StevenBlack's Hosts](#stevenblacks-hosts-domains-only) | MIT | 121376 | [**Download**](https://mili-tan.github.io/justdomains/lists/stevenblack.list) | 05 February 2025 02:17:13 (UTC) |
| [Yoyos Hosts](#yoyos-hosts-domains-only) | MCRAE GENERAL PUBLIC LICENSE | 3538 | [**Download**](https://mili-tan.github.io/justdomains/lists/yoyo.list) |   Sat, 08 Feb 2025 02:26:10 GMT |
| [AdRules DNS List](#adrules-dns-list-domains-only) | WTFPL | 113529 | [**Download**](https://mili-tan.github.io/justdomains/lists/adrules.list) |  |
| [AdGuard DNS Filter](#adguard-dns-filter-domains-only) | [GPL3](https://github.com/AdguardTeam/AdguardSDNSFilter/blob/master/LICENSE) | 57171 | [**Download**](https://mili-tan.github.io/justdomains/lists/adguarddns.list) | 2025-02-10T12:01:30.849Z |
| [EasyList](#easylist-domains-only) | [GPL3 / CC BY-SA 3.0](https://easylist.to/pages/licence.html) | 32245 | [**Download**](https://mili-tan.github.io/justdomains/lists/easylist.list) | 10 Feb 2025 15:47 UTC |
| [EasyPrivacy](#easyprivacy-domains-only) | [GPL3 / CC BY-SA 3.0](https://easylist.to/pages/licence.html) | 44990 | [**Download**](https://mili-tan.github.io/justdomains/lists/easyprivacy.list) | 10 Feb 2025 15:47 UTC |
| [CJX's Annoyance List](#cjxs-annoyance-list-domains-only) | [LGPL-3.0](https://github.com/cjx82630/cjxlist/blob/master/LICENSE) | 149 | [**Download**](https://mili-tan.github.io/justdomains/lists/cjx-annoyance.list) | 2024/12/21 19:27 +0800 |
| [Fanboy's Annoyance List](#fanboys-annoyance-list-domains-only) | [CC BY 3.0](https://easylist.to/pages/licence.html) | 794 | [**Download**](https://mili-tan.github.io/justdomains/lists/fanboy-annoyance.list) | 10 Feb 2025 15:47 UTC |
| [EasyList China](#easylist-china-domains-only) | [GPL3 / CC BY-SA 3.0](https://easylist.to/pages/licence.html) | 4757 | [**Download**](https://mili-tan.github.io/justdomains/lists/easylistchina.list) | 10 Feb 2025 16:01 UTC |
| [AdGuard Tracking Filter](#adguard-tracking-filter-domains-only) | [CC BY-SA 3.0](https://github.com/AdguardTeam/AdguardFilters/blob/master/LICENSE) | 51330 | [**Download**](https://mili-tan.github.io/justdomains/lists/adguard-tracking.list) |  |
| [AWAvenue Adblock Rule](#awavenue-adblock-rule-domains-only) | CC BY-NC-SA 4.0 | 739 | [**Download**](https://mili-tan.github.io/justdomains/lists/awavenue.list) |  |
| [OISD Small](#oisd-small-domains-only) | [CC BY-SA 3.0](https://github.com/sjhgvr/oisd/blob/main/LICENSE) | 44167 | [**Download**](https://mili-tan.github.io/justdomains/lists/oisdsmall.list) | 2025-02-10T16:11:07+0000 |
| [OISD Big](#oisd-big-domains-only) | [CC BY-SA 3.0](https://github.com/sjhgvr/oisd/blob/main/LICENSE) | 217772 | [**Download**](https://mili-tan.github.io/justdomains/lists/oisdbig.list) | 2025-02-10T16:10:50+0000 |
| [Hagezi Blocklists Light](#hagezi-blocklists-light-domains-only) | [CC BY-NC-SA 3.0](https://github.com/hagezi/dns-blocklists/blob/main/LICENSE) | 70539 | [**Download**](https://mili-tan.github.io/justdomains/lists/hagezi.list) | 10 Feb 2025 13:42 UTC |
| [Hagezi Blocklists Normal](#hagezi-blocklists-normal-domains-only) | [CC BY-NC-SA 3.0](https://github.com/hagezi/dns-blocklists/blob/main/LICENSE) | 164288 | [**Download**](https://mili-tan.github.io/justdomains/lists/hagezi-normal.list) | 10 Feb 2025 13:49 UTC |
| [Blackmatrix7's Advertising Rules](#blackmatrix7s-advertising-rules-domains-only) | GPL2 | 157314 | [**Download**](https://mili-tan.github.io/justdomains/lists/bm7.list) |  |
| [Blackmatrix7's Advertising Rules Lite](#blackmatrix7s-advertising-rules-lite-domains-only) | GPL2 | 37655 | [**Download**](https://mili-tan.github.io/justdomains/lists/bm7l.list) |  |
| [d3Host List by d3ward](#d3host-list-by-d3ward-domains-only) | CC BY-NC-SA | 131 | [**Download**](https://mili-tan.github.io/justdomains/lists/d3.list) |  |
| [NoCoin Filter](#nocoin-filter-domains-only) | [MIT](https://mit-license.org/) | 409 | [**Download**](https://mili-tan.github.io/justdomains/lists/nocoin.list) | 12 April 2023 |
| [CERT.PL's Warning List](#certpls-warning-list-domains-only) | AGPL3 | 0 | [**Download**](https://mili-tan.github.io/justdomains/lists/certpl.list) |  |
| [Hagezi Anti Bypass](#hagezi-anti-bypass-domains-only) | [CC BY-NC-SA 3.0](https://github.com/hagezi/dns-blocklists/blob/main/LICENSE) | 3737 | [**Download**](https://mili-tan.github.io/justdomains/lists/hagezi-bypass.list) | 10 Feb 2025 15:31 UTC |
| [DDNS Filter](#ddns-filter-domains-only) | Unlicense | 32414 | [**Download**](https://mili-tan.github.io/justdomains/lists/ddns.list) |  |
| [IPFS Filter](#ipfs-filter-domains-only) | MIT | 77 | [**Download**](https://mili-tan.github.io/justdomains/lists/ipfs.list) |  |
| [Anti SafeSearch Bypass](#anti-safesearch-bypass-domains-only) | MIT | 175 | [**Download**](https://mili-tan.github.io/justdomains/lists/nosafesearch.list) |  |
| [NextDNS Native Tracking Filter](#nextdns-native-tracking-filter-domains-only) | MIT | 98 | [**Download**](https://mili-tan.github.io/justdomains/lists/nativetracking.list) |  |
| [Blackmatrix7's MiTV Rules](#blackmatrix7s-mitv-rules-domains-only) | GPL2 | 165 | [**Download**](https://mili-tan.github.io/justdomains/lists/bm7mitv.list) |  |
| [Anti HTTPDNS Bypass](#anti-httpdns-bypass-domains-only) | GPL3 | 22 | [**Download**](https://mili-tan.github.io/justdomains/lists/httpdns.list) |  |
| [HideMyTel](#hidemytel-domains-only) | MIT | 23 | [**Download**](https://mili-tan.github.io/justdomains/lists/cellular-identity.list) |  |
| [Anti-AD Encrypted DNS](#anti-ad-encrypted-dns-domains-only) | MIT | 64 | [**Download**](https://mili-tan.github.io/justdomains/lists/anti-ad-dns.list) |  |
| [Anti-AD Auto Number Verification](#anti-ad-auto-number-verification-domains-only) | MIT | 13 | [**Download**](https://mili-tan.github.io/justdomains/lists/anti-ad-anv.list) |  |
| [Anti-AD PCDN](#anti-ad-pcdn-domains-only) | MIT | 28 | [**Download**](https://mili-tan.github.io/justdomains/lists/anti-ad-pcdn.list) |  |

&nbsp;

## AdAway Blocklist (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [adaway.list](https://mili-tan.github.io/justdomains/lists/adaway.list) |
| Pi-Hole | [adaway.list](https://mili-tan.github.io/justdomains/lists/adaway.list) |

**Source:** [https://adaway.org/hosts.txt](https://adaway.org/hosts.txt)

**Conversion Details:**
```
Total Lines Processed: 10607
Comment Lines: 2042
Empty Lines: 2023
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 2
Invalid Hosts (Ignored): 0
Duplicate Hosts (Ignored): 0
Hosts Output: 6540
```

&nbsp;

## StevenBlack's Hosts (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [stevenblack.list](https://mili-tan.github.io/justdomains/lists/stevenblack.list) |
| Pi-Hole | [stevenblack.list](https://mili-tan.github.io/justdomains/lists/stevenblack.list) |

**Source:** [https://raw.githubusercontent.com/StevenBlack/hosts/master/hosts](https://raw.githubusercontent.com/StevenBlack/hosts/master/hosts)
- Title: StevenBlack/hosts
- Last Modified: 05 February 2025 02:17:13 (UTC)

**Conversion Details:**
```
Total Lines Processed: 128087
Comment Lines: 4216
Empty Lines: 2483
Invalid Lines: 0
Non-Loopback Lines (Ignored): 7
Local Hosts (Ignored): 4
Invalid Hosts (Ignored): 1
Duplicate Hosts (Ignored): 0
Hosts Output: 121376
```

&nbsp;

## Yoyos Hosts (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [yoyo.list](https://mili-tan.github.io/justdomains/lists/yoyo.list) |
| Pi-Hole | [yoyo.list](https://mili-tan.github.io/justdomains/lists/yoyo.list) |

**Source:** [https://pgl.yoyo.org/adservers/serverlist.php?hostformat=hosts&showintro=0&mimetype=plaintext](https://pgl.yoyo.org/adservers/serverlist.php?hostformat=hosts&showintro=0&mimetype=plaintext)
- Last Modified:   Sat, 08 Feb 2025 02:26:10 GMT

**Conversion Details:**
```
Total Lines Processed: 3552
Comment Lines: 14
Empty Lines: 0
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 0
Invalid Hosts (Ignored): 0
Duplicate Hosts (Ignored): 0
Hosts Output: 3538
```

&nbsp;

## AdRules DNS List (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [adrules.list](https://mili-tan.github.io/justdomains/lists/adrules.list) |
| Pi-Hole | [adrules.list](https://mili-tan.github.io/justdomains/lists/adrules.list) |

**Source:** [https://raw.githubusercontent.com/Cats-Team/AdRules/main/dns.txt](https://raw.githubusercontent.com/Cats-Team/AdRules/main/dns.txt)
- Title: AdRules DNS List
- Homepage: [https://github.com/Cats-Team/AdRules](https://github.com/Cats-Team/AdRules)

**Conversion Details:**
```
Total Lines Processed: 113870
Comment Lines: 7
Empty Lines: 0
Non-Domain-only Rules Excluded: 334
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 113529
```

&nbsp;

## AdGuard DNS Filter (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [adguarddns.list](https://mili-tan.github.io/justdomains/lists/adguarddns.list) |
| Pi-Hole | [adguarddns.list](https://mili-tan.github.io/justdomains/lists/adguarddns.list) |

**Source:** [https://filters.adtidy.org/extension/chromium/filters/15.txt](https://filters.adtidy.org/extension/chromium/filters/15.txt)
- Title: AdGuard DNS filter
- Version: 2.0.76.42
- Last Modified: 2025-02-10T12:01:30.849Z
- Homepage: [https://github.com/AdguardTeam/AdguardSDNSFilter](https://github.com/AdguardTeam/AdguardSDNSFilter)

**Conversion Details:**
```
Total Lines Processed: 59309
Comment Lines: 1334
Empty Lines: 0
Non-Domain-only Rules Excluded: 740
Domain-only Rules Excluded (unsupported options): 5
Domain-only Rules Excluded (exception conflict): 59
Domain-only Rules Output: 57171
```

&nbsp;

## EasyList (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [easylist.list](https://mili-tan.github.io/justdomains/lists/easylist.list) |
| Pi-Hole | [easylist.list](https://mili-tan.github.io/justdomains/lists/easylist.list) |

**Source:** [https://easylist.to/easylist/easylist.txt](https://easylist.to/easylist/easylist.txt)
- Title: EasyList
- Version: 202502101547
- Last Modified: 10 Feb 2025 15:47 UTC
- Homepage: [https://easylist.to/](https://easylist.to/)

**Conversion Details:**
```
Total Lines Processed: 64926
Comment Lines: 283
Empty Lines: 0
Non-Domain-only Rules Excluded: 27187
Domain-only Rules Excluded (unsupported options): 5145
Domain-only Rules Excluded (exception conflict): 66
Domain-only Rules Output: 32245
```

&nbsp;

## EasyPrivacy (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [easyprivacy.list](https://mili-tan.github.io/justdomains/lists/easyprivacy.list) |
| Pi-Hole | [easyprivacy.list](https://mili-tan.github.io/justdomains/lists/easyprivacy.list) |

**Source:** [https://easylist.to/easylist/easyprivacy.txt](https://easylist.to/easylist/easyprivacy.txt)
- Title: EasyPrivacy
- Version: 202502101547
- Last Modified: 10 Feb 2025 15:47 UTC
- Homepage: [https://easylist.to/](https://easylist.to/)

**Conversion Details:**
```
Total Lines Processed: 53755
Comment Lines: 697
Empty Lines: 1
Non-Domain-only Rules Excluded: 7684
Domain-only Rules Excluded (unsupported options): 203
Domain-only Rules Excluded (exception conflict): 181
Domain-only Rules Output: 44990
```

&nbsp;

## CJX's Annoyance List (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [cjx-annoyance.list](https://mili-tan.github.io/justdomains/lists/cjx-annoyance.list) |
| Pi-Hole | [cjx-annoyance.list](https://mili-tan.github.io/justdomains/lists/cjx-annoyance.list) |

**Source:** [https://raw.githubusercontent.com/cjx82630/cjxlist/master/cjx-annoyance.txt](https://raw.githubusercontent.com/cjx82630/cjxlist/master/cjx-annoyance.txt)
- Title: CJX's Annoyance List
- Version: 202412211927
- Last Modified: 2024/12/21 19:27 +0800
- Homepage: [https://github.com/cjx82630/cjxlist](https://github.com/cjx82630/cjxlist)

**Conversion Details:**
```
Total Lines Processed: 1838
Comment Lines: 20
Empty Lines: 0
Non-Domain-only Rules Excluded: 1660
Domain-only Rules Excluded (unsupported options): 8
Domain-only Rules Excluded (exception conflict): 1
Domain-only Rules Output: 149
```

&nbsp;

## Fanboy's Annoyance List (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [fanboy-annoyance.list](https://mili-tan.github.io/justdomains/lists/fanboy-annoyance.list) |
| Pi-Hole | [fanboy-annoyance.list](https://mili-tan.github.io/justdomains/lists/fanboy-annoyance.list) |

**Source:** [https://easylist.to/easylist/fanboy-annoyance.txt](https://easylist.to/easylist/fanboy-annoyance.txt)
- Title: Fanboy's Annoyance List
- Version: 202502101547
- Last Modified: 10 Feb 2025 15:47 UTC
- Homepage: [https://easylist.to/](https://easylist.to/)

**Conversion Details:**
```
Total Lines Processed: 47607
Comment Lines: 1296
Empty Lines: 0
Non-Domain-only Rules Excluded: 45406
Domain-only Rules Excluded (unsupported options): 71
Domain-only Rules Excluded (exception conflict): 40
Domain-only Rules Output: 794
```

&nbsp;

## EasyList China (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [easylistchina.list](https://mili-tan.github.io/justdomains/lists/easylistchina.list) |
| Pi-Hole | [easylistchina.list](https://mili-tan.github.io/justdomains/lists/easylistchina.list) |

**Source:** [https://easylist-downloads.adblockplus.org/easylistchina.txt](https://easylist-downloads.adblockplus.org/easylistchina.txt)
- Title: EasyList China
- Version: 202502101601
- Last Modified: 10 Feb 2025 16:01 UTC
- Homepage: [https://github.com/easylist/easylistchina/](https://github.com/easylist/easylistchina/)

**Conversion Details:**
```
Total Lines Processed: 18087
Comment Lines: 105
Empty Lines: 0
Non-Domain-only Rules Excluded: 13059
Domain-only Rules Excluded (unsupported options): 155
Domain-only Rules Excluded (exception conflict): 11
Domain-only Rules Output: 4757
```

&nbsp;

## AdGuard Tracking Filter (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [adguard-tracking.list](https://mili-tan.github.io/justdomains/lists/adguard-tracking.list) |
| Pi-Hole | [adguard-tracking.list](https://mili-tan.github.io/justdomains/lists/adguard-tracking.list) |

**Source:** [https://filters.adtidy.org/extension/chromium/filters/3.txt](https://filters.adtidy.org/extension/chromium/filters/3.txt)
- Title: AdGuard Tracking Protection filter
- Version: 2.0.80.21
- Homepage: [https://github.com/AdguardTeam/AdGuardFilters](https://github.com/AdguardTeam/AdGuardFilters)

**Conversion Details:**
```
Total Lines Processed: 146814
Comment Lines: 3208
Empty Lines: 0
Non-Domain-only Rules Excluded: 91544
Domain-only Rules Excluded (unsupported options): 443
Domain-only Rules Excluded (exception conflict): 289
Domain-only Rules Output: 51330
```

&nbsp;

## AWAvenue Adblock Rule (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [awavenue.list](https://mili-tan.github.io/justdomains/lists/awavenue.list) |
| Pi-Hole | [awavenue.list](https://mili-tan.github.io/justdomains/lists/awavenue.list) |

**Source:** [https://raw.githubusercontent.com/TG-Twilight/AWAvenue-Ads-Rule/main/AWAvenue-Ads-Rule.txt](https://raw.githubusercontent.com/TG-Twilight/AWAvenue-Ads-Rule/main/AWAvenue-Ads-Rule.txt)
- Title: AWAvenue Ads Rule
- Version: 1.5.6-release

**Conversion Details:**
```
Total Lines Processed: 760
Comment Lines: 6
Empty Lines: 3
Non-Domain-only Rules Excluded: 15
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 739
```

&nbsp;

## OISD Small (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [oisdsmall.list](https://mili-tan.github.io/justdomains/lists/oisdsmall.list) |
| Pi-Hole | [oisdsmall.list](https://mili-tan.github.io/justdomains/lists/oisdsmall.list) |

**Source:** [https://small.oisd.nl](https://small.oisd.nl)
- Title: oisd small
- Version: 202502101611
- Last Modified: 2025-02-10T16:11:07+0000
- Homepage: [https://oisd.nl](https://oisd.nl)

**Conversion Details:**
```
Total Lines Processed: 44180
Comment Lines: 11
Empty Lines: 1
Non-Domain-only Rules Excluded: 2
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 44167
```

&nbsp;

## OISD Big (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [oisdbig.list](https://mili-tan.github.io/justdomains/lists/oisdbig.list) |
| Pi-Hole | [oisdbig.list](https://mili-tan.github.io/justdomains/lists/oisdbig.list) |

**Source:** [https://big.oisd.nl](https://big.oisd.nl)
- Title: oisd big
- Version: 202502101610
- Last Modified: 2025-02-10T16:10:50+0000
- Homepage: [https://oisd.nl](https://oisd.nl)

**Conversion Details:**
```
Total Lines Processed: 217785
Comment Lines: 11
Empty Lines: 1
Non-Domain-only Rules Excluded: 2
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 217772
```

&nbsp;

## Hagezi Blocklists Light (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [hagezi.list](https://mili-tan.github.io/justdomains/lists/hagezi.list) |
| Pi-Hole | [hagezi.list](https://mili-tan.github.io/justdomains/lists/hagezi.list) |

**Source:** [https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/light.txt](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/light.txt)
- Title: HaGeZi's Light DNS Blocklist
- Version: 2025.0210.1342.20
- Last Modified: 10 Feb 2025 13:42 UTC
- Homepage: [https://github.com/hagezi/dns-blocklists](https://github.com/hagezi/dns-blocklists)

**Conversion Details:**
```
Total Lines Processed: 70551
Comment Lines: 11
Empty Lines: 0
Non-Domain-only Rules Excluded: 1
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 70539
```

&nbsp;

## Hagezi Blocklists Normal (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [hagezi-normal.list](https://mili-tan.github.io/justdomains/lists/hagezi-normal.list) |
| Pi-Hole | [hagezi-normal.list](https://mili-tan.github.io/justdomains/lists/hagezi-normal.list) |

**Source:** [https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/multi.txt](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/multi.txt)
- Title: HaGeZi's Normal DNS Blocklist
- Version: 2025.0210.1349.17
- Last Modified: 10 Feb 2025 13:49 UTC
- Homepage: [https://github.com/hagezi/dns-blocklists](https://github.com/hagezi/dns-blocklists)

**Conversion Details:**
```
Total Lines Processed: 164300
Comment Lines: 11
Empty Lines: 0
Non-Domain-only Rules Excluded: 1
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 164288
```

&nbsp;

## Blackmatrix7's Advertising Rules (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [bm7.list](https://mili-tan.github.io/justdomains/lists/bm7.list) |
| Pi-Hole | [bm7.list](https://mili-tan.github.io/justdomains/lists/bm7.list) |

**Source:** [https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/AdGuard/Advertising/Advertising.txt](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/AdGuard/Advertising/Advertising.txt)

**Conversion Details:**
```
Total Lines Processed: 157528
Comment Lines: 5
Empty Lines: 2
Non-Domain-only Rules Excluded: 209
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 157314
```

&nbsp;

## Blackmatrix7's Advertising Rules Lite (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [bm7l.list](https://mili-tan.github.io/justdomains/lists/bm7l.list) |
| Pi-Hole | [bm7l.list](https://mili-tan.github.io/justdomains/lists/bm7l.list) |

**Source:** [https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/AdGuard/AdvertisingLite/AdvertisingLite.txt](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/AdGuard/AdvertisingLite/AdvertisingLite.txt)

**Conversion Details:**
```
Total Lines Processed: 37662
Comment Lines: 5
Empty Lines: 2
Non-Domain-only Rules Excluded: 2
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 37655
```

&nbsp;

## d3Host List by d3ward (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [d3.list](https://mili-tan.github.io/justdomains/lists/d3.list) |
| Pi-Hole | [d3.list](https://mili-tan.github.io/justdomains/lists/d3.list) |

**Source:** [https://raw.githubusercontent.com/d3ward/toolz/master/src/d3host.adblock](https://raw.githubusercontent.com/d3ward/toolz/master/src/d3host.adblock)
- Title: d3Host List by d3ward
- Homepage: [https://github.com/d3ward/toolz](https://github.com/d3ward/toolz)

**Conversion Details:**
```
Total Lines Processed: 225
Comment Lines: 47
Empty Lines: 43
Non-Domain-only Rules Excluded: 47
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 131
```

&nbsp;

## NoCoin Filter (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [nocoin.list](https://mili-tan.github.io/justdomains/lists/nocoin.list) |
| Pi-Hole | [nocoin.list](https://mili-tan.github.io/justdomains/lists/nocoin.list) |

**Source:** [https://raw.githubusercontent.com/hoshsadiq/adblock-nocoin-list/master/hosts.txt](https://raw.githubusercontent.com/hoshsadiq/adblock-nocoin-list/master/hosts.txt)
- Last Modified: 12 April 2023
- Homepage: [https://github.com/hoshsadiq/adblock-nocoin-list/](https://github.com/hoshsadiq/adblock-nocoin-list/)

**Conversion Details:**
```
Total Lines Processed: 420
Comment Lines: 10
Empty Lines: 1
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 0
Invalid Hosts (Ignored): 0
Duplicate Hosts (Ignored): 0
Hosts Output: 409
```

&nbsp;

## CERT.PL's Warning List (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [certpl.list](https://mili-tan.github.io/justdomains/lists/certpl.list) |
| Pi-Hole | [certpl.list](https://mili-tan.github.io/justdomains/lists/certpl.list) |

**Source:** [https://hole.cert.pl/domains/domains_adblock.txt](https://hole.cert.pl/domains/domains_adblock.txt)
- Title: CERT.PL's Warning List
- Version: 202502101613
- Homepage: [https://cert.pl/news/single/ostrzezenia_phishing/](https://cert.pl/news/single/ostrzezenia_phishing/)

**Conversion Details:**
```
Total Lines Processed: 266095
Comment Lines: 4
Empty Lines: 0
Non-Domain-only Rules Excluded: 1
Domain-only Rules Excluded (unsupported options): 266090
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 0
```

&nbsp;

## Hagezi Anti Bypass (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [hagezi-bypass.list](https://mili-tan.github.io/justdomains/lists/hagezi-bypass.list) |
| Pi-Hole | [hagezi-bypass.list](https://mili-tan.github.io/justdomains/lists/hagezi-bypass.list) |

**Source:** [https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/doh-vpn-proxy-bypass.txt](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/doh-vpn-proxy-bypass.txt)
- Title: HaGeZi's Encrypted DNS/VPN/TOR/Proxy Bypass DNS Blocklist
- Version: 2025.0210.1531.52
- Last Modified: 10 Feb 2025 15:31 UTC
- Homepage: [https://github.com/hagezi/dns-blocklists](https://github.com/hagezi/dns-blocklists)

**Conversion Details:**
```
Total Lines Processed: 3750
Comment Lines: 12
Empty Lines: 0
Non-Domain-only Rules Excluded: 1
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 3737
```

&nbsp;

## DDNS Filter (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [ddns.list](https://mili-tan.github.io/justdomains/lists/ddns.list) |
| Pi-Hole | [ddns.list](https://mili-tan.github.io/justdomains/lists/ddns.list) |

**Source:** [https://dns-mili-tan.koyeb.app/tohosts/raw.githubusercontent.com/alexandrosmagos/dyn-dns-list/refs/heads/master/links.txt](https://dns-mili-tan.koyeb.app/tohosts/raw.githubusercontent.com/alexandrosmagos/dyn-dns-list/refs/heads/master/links.txt)

**Conversion Details:**
```
Total Lines Processed: 32416
Comment Lines: 0
Empty Lines: 0
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 0
Invalid Hosts (Ignored): 2
Duplicate Hosts (Ignored): 0
Hosts Output: 32414
```

&nbsp;

## IPFS Filter (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [ipfs.list](https://mili-tan.github.io/justdomains/lists/ipfs.list) |
| Pi-Hole | [ipfs.list](https://mili-tan.github.io/justdomains/lists/ipfs.list) |

**Source:** [https://mili.one/lists/ipfs.txt](https://mili.one/lists/ipfs.txt)

**Conversion Details:**
```
Total Lines Processed: 78
Comment Lines: 0
Empty Lines: 0
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 0
Invalid Hosts (Ignored): 1
Duplicate Hosts (Ignored): 0
Hosts Output: 77
```

&nbsp;

## Anti SafeSearch Bypass (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [nosafesearch.list](https://mili-tan.github.io/justdomains/lists/nosafesearch.list) |
| Pi-Hole | [nosafesearch.list](https://mili-tan.github.io/justdomains/lists/nosafesearch.list) |

**Source:** [https://dns-mili-tan.koyeb.app/tohosts/raw.githubusercontent.com/nextdns/no-safesearch/refs/heads/main/domains](https://dns-mili-tan.koyeb.app/tohosts/raw.githubusercontent.com/nextdns/no-safesearch/refs/heads/main/domains)

**Conversion Details:**
```
Total Lines Processed: 175
Comment Lines: 0
Empty Lines: 0
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 0
Invalid Hosts (Ignored): 0
Duplicate Hosts (Ignored): 0
Hosts Output: 175
```

&nbsp;

## NextDNS Native Tracking Filter (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [nativetracking.list](https://mili-tan.github.io/justdomains/lists/nativetracking.list) |
| Pi-Hole | [nativetracking.list](https://mili-tan.github.io/justdomains/lists/nativetracking.list) |

**Source:** [https://dns-mili-tan.koyeb.app/filestohosts/alexa,apple,huawei,roku,samsung,sonos,windows,xiaomi/raw.githubusercontent.com/nextdns/native-tracking-domains/refs/heads/main/domains](https://dns-mili-tan.koyeb.app/filestohosts/alexa,apple,huawei,roku,samsung,sonos,windows,xiaomi/raw.githubusercontent.com/nextdns/native-tracking-domains/refs/heads/main/domains)

**Conversion Details:**
```
Total Lines Processed: 99
Comment Lines: 0
Empty Lines: 0
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 0
Invalid Hosts (Ignored): 0
Duplicate Hosts (Ignored): 1
Hosts Output: 98
```

&nbsp;

## Blackmatrix7's MiTV Rules (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [bm7mitv.list](https://mili-tan.github.io/justdomains/lists/bm7mitv.list) |
| Pi-Hole | [bm7mitv.list](https://mili-tan.github.io/justdomains/lists/bm7mitv.list) |

**Source:** [https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/AdGuard/AdvertisingMiTV/AdvertisingMiTV.txt](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/AdGuard/AdvertisingMiTV/AdvertisingMiTV.txt)

**Conversion Details:**
```
Total Lines Processed: 172
Comment Lines: 5
Empty Lines: 2
Non-Domain-only Rules Excluded: 2
Domain-only Rules Excluded (unsupported options): 0
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 165
```

&nbsp;

## Anti HTTPDNS Bypass (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [httpdns.list](https://mili-tan.github.io/justdomains/lists/httpdns.list) |
| Pi-Hole | [httpdns.list](https://mili-tan.github.io/justdomains/lists/httpdns.list) |

**Source:** [https://dns-mili-tan.koyeb.app/tohosts/raw.githubusercontent.com/VirgilClyne/GetSomeFries/main/ruleset/HTTPDNS.Block.list](https://dns-mili-tan.koyeb.app/tohosts/raw.githubusercontent.com/VirgilClyne/GetSomeFries/main/ruleset/HTTPDNS.Block.list)

**Conversion Details:**
```
Total Lines Processed: 22
Comment Lines: 0
Empty Lines: 0
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 0
Invalid Hosts (Ignored): 0
Duplicate Hosts (Ignored): 0
Hosts Output: 22
```

&nbsp;

## HideMyTel (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [cellular-identity.list](https://mili-tan.github.io/justdomains/lists/cellular-identity.list) |
| Pi-Hole | [cellular-identity.list](https://mili-tan.github.io/justdomains/lists/cellular-identity.list) |

**Source:** [https://raw.githubusercontent.com/notSachiho/HideMyTel/refs/heads/main/hosts](https://raw.githubusercontent.com/notSachiho/HideMyTel/refs/heads/main/hosts)

**Conversion Details:**
```
Total Lines Processed: 25
Comment Lines: 1
Empty Lines: 1
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 0
Invalid Hosts (Ignored): 0
Duplicate Hosts (Ignored): 0
Hosts Output: 23
```

&nbsp;

## Anti-AD Encrypted DNS (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [anti-ad-dns.list](https://mili-tan.github.io/justdomains/lists/anti-ad-dns.list) |
| Pi-Hole | [anti-ad-dns.list](https://mili-tan.github.io/justdomains/lists/anti-ad-dns.list) |

**Source:** [https://dns-mili-tan.koyeb.app/tohosts/raw.githubusercontent.com/privacy-protection-tools/anti-AD/refs/heads/master/discretion/dns.txt](https://dns-mili-tan.koyeb.app/tohosts/raw.githubusercontent.com/privacy-protection-tools/anti-AD/refs/heads/master/discretion/dns.txt)

**Conversion Details:**
```
Total Lines Processed: 64
Comment Lines: 0
Empty Lines: 0
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 0
Invalid Hosts (Ignored): 0
Duplicate Hosts (Ignored): 0
Hosts Output: 64
```

&nbsp;

## Anti-AD Auto Number Verification (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [anti-ad-anv.list](https://mili-tan.github.io/justdomains/lists/anti-ad-anv.list) |
| Pi-Hole | [anti-ad-anv.list](https://mili-tan.github.io/justdomains/lists/anti-ad-anv.list) |

**Source:** [https://dns-mili-tan.koyeb.app/tohosts/raw.githubusercontent.com/privacy-protection-tools/anti-AD/refs/heads/master/discretion/anv.txt](https://dns-mili-tan.koyeb.app/tohosts/raw.githubusercontent.com/privacy-protection-tools/anti-AD/refs/heads/master/discretion/anv.txt)

**Conversion Details:**
```
Total Lines Processed: 13
Comment Lines: 0
Empty Lines: 0
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 0
Invalid Hosts (Ignored): 0
Duplicate Hosts (Ignored): 0
Hosts Output: 13
```

&nbsp;

## Anti-AD PCDN (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [anti-ad-pcdn.list](https://mili-tan.github.io/justdomains/lists/anti-ad-pcdn.list) |
| Pi-Hole | [anti-ad-pcdn.list](https://mili-tan.github.io/justdomains/lists/anti-ad-pcdn.list) |

**Source:** [https://dns-mili-tan.koyeb.app/tohosts/raw.githubusercontent.com/privacy-protection-tools/anti-AD/refs/heads/master/discretion/pcdn.txt](https://dns-mili-tan.koyeb.app/tohosts/raw.githubusercontent.com/privacy-protection-tools/anti-AD/refs/heads/master/discretion/pcdn.txt)

**Conversion Details:**
```
Total Lines Processed: 28
Comment Lines: 0
Empty Lines: 0
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 0
Invalid Hosts (Ignored): 0
Duplicate Hosts (Ignored): 0
Hosts Output: 28
```

&nbsp;

# License:
Each converted / modified list file is licensed under the same license as the original list.

For more details, see the [LICENSES](LICENSES) file.

&nbsp;

# Reporting Conversion Issues:
If you find an issue in the output of the conversion process (i.e. comparing to the original upstream list), please report it over on: https://github.com/justdomains/ci/issues

**NOTE: We do not manage the upstream lists themselves, and will not be able to add any new blocks to the lists.**

&nbsp;

<sup>These files are provided "AS IS", without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose and noninfringement. In no event shall the authors or copyright holders be liable for any claim, damages or other liability, arising from, out of or in connection with the files or the use of the files.</sup>

<sub>Any and all trademarks are the property of their respective owners.</sub>
