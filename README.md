# DOMAIN-ONLY Filter Lists
**Last Updated:** 2021-08-28 16:15:22

- [Details](#details)
- [Usage](#usage)
  - [Using with Pi-Hole](#using-with-pi-hole)
  - [Using with other tools](#using-with-other-tools)
- [The Lists](#the-lists)
  - [EasyList](#easylist-domains-only) (Domains-only)
  - [EasyPrivacy](#easyprivacy-domains-only) (Domains-only)
  - [Fanboy's Social Blocking](#fanboys-social-blocking-domains-only) (Domains-only)
  - [CJX's EasyList Lite](#cjxs-easylist-lite-domains-only) (Domains-only)
  - [CJX's Annoyance List](#cjxs-annoyance-list-domains-only) (Domains-only)
  - [Fanboy's Annoyance List](#fanboys-annoyance-list-domains-only) (Domains-only)
  - [EasyList China](#easylist-china-domains-only) (Domains-only)
  - [AdGuard Simplified Domain Names Filter](#adguard-simplified-domain-names-filter-domains-only) (Domains-only)
  - [AdGuard Base Filter](#adguard-base-filter-domains-only) (Domains-only)
  - [AdGuard Tracking Protection filter](#adguard-tracking-protection-filter-domains-only) (Domains-only)
  - [AdGuard Social media filter](#adguard-social-media-filter-domains-only) (Domains-only)
  - [AdGuard Annoyances filter](#adguard-annoyances-filter-domains-only) (Domains-only)
  - [AdGuard Chinese filter](#adguard-chinese-filter-domains-only) (Domains-only)
  - [AdGuard Mobile ads filter](#adguard-mobile-ads-filter-domains-only) (Domains-only)
  - [NoCoin Filter List](#nocoin-filter-list-domains-only) (Domains-only)
  - [AdAway default blocklist](#adaway-default-blocklist-domains-only) (Domains-only)
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
| [EasyList](#easylist-domains-only) | [GPL3 / CC BY-SA 3.0](https://easylist.to/pages/licence.html) | 16030 | [**Download**](https://mili-tan.github.io/justdomains/lists/easylist.list) | 28 Aug 2021 16:07 UTC |
| [EasyPrivacy](#easyprivacy-domains-only) | [GPL3 / CC BY-SA 3.0](https://easylist.to/pages/licence.html) | 15637 | [**Download**](https://mili-tan.github.io/justdomains/lists/easyprivacy.list) | 28 Aug 2021 16:07 UTC |
| [Fanboy's Social Blocking](#fanboys-social-blocking-domains-only) | [CC BY 3.0](http://creativecommons.org/licenses/by/3.0/) | 101 | [**Download**](https://mili-tan.github.io/justdomains/lists/fanboy-social.list) | 28 Aug 2021 16:09 UTC |
| [CJX's EasyList Lite](#cjxs-easylist-lite-domains-only) | [LGPL-3.0 License](https://easylist-downloads.adblockplus.org/COPYING) | 20 | [**Download**](https://mili-tan.github.io/justdomains/lists/cjxlist.list) | 2020/12/08 08:56 +0800 |
| [CJX's Annoyance List](#cjxs-annoyance-list-domains-only) | [LGPL-3.0 License](https://github.com/cjx82630/cjxlist/blob/master/LICENSE) | 160 | [**Download**](https://mili-tan.github.io/justdomains/lists/cjx-annoyance.list) | 2021/08/28 13:54 +0800 |
| [Fanboy's Annoyance List](#fanboys-annoyance-list-domains-only) | [CC BY 3.0](http://creativecommons.org/licenses/by/3.0/) | 704 | [**Download**](https://mili-tan.github.io/justdomains/lists/fanboy-annoyance.list) | 28 Aug 2021 16:09 UTC |
| [EasyList China](#easylist-china-domains-only) | [GPL3 / CC BY-SA 3.0](https://easylist-downloads.adblockplus.org/COPYING) | 5682 | [**Download**](https://mili-tan.github.io/justdomains/lists/easylistchina.list) | 28 Aug 2021 16:03 UTC |
| [AdGuard Simplified Domain Names Filter](#adguard-simplified-domain-names-filter-domains-only) | [GPL3](https://github.com/AdguardTeam/AdguardSDNSFilter/blob/master/LICENSE) | 38451 | [**Download**](https://mili-tan.github.io/justdomains/lists/adguarddns.list) | 2021-08-28T12:06:33.224Z |
| [AdGuard Base Filter](#adguard-base-filter-domains-only) | [CC BY-SA 3.0](https://github.com/AdguardTeam/AdguardFilters/blob/master/LICENSE) | 1178 | [**Download**](https://mili-tan.github.io/justdomains/lists/adguard-base.list) |  |
| [AdGuard Tracking Protection filter](#adguard-tracking-protection-filter-domains-only) | [CC BY-SA 3.0](https://github.com/AdguardTeam/AdguardFilters/blob/master/LICENSE) | 18478 | [**Download**](https://mili-tan.github.io/justdomains/lists/adguard-tracking.list) |  |
| [AdGuard Social media filter](#adguard-social-media-filter-domains-only) | [CC BY-SA 3.0](https://github.com/AdguardTeam/AdguardFilters/blob/master/LICENSE) | 43 | [**Download**](https://mili-tan.github.io/justdomains/lists/adguard-social.list) |  |
| [AdGuard Annoyances filter](#adguard-annoyances-filter-domains-only) | [CC BY-SA 3.0](https://github.com/AdguardTeam/AdguardFilters/blob/master/LICENSE) | 662 | [**Download**](https://mili-tan.github.io/justdomains/lists/adguard-annoyances.list) |  |
| [AdGuard Chinese filter](#adguard-chinese-filter-domains-only) | [CC BY-SA 3.0](https://github.com/AdguardTeam/AdguardFilters/blob/master/LICENSE) | 5932 | [**Download**](https://mili-tan.github.io/justdomains/lists/adguard-chinese.list) |  |
| [AdGuard Mobile ads filter](#adguard-mobile-ads-filter-domains-only) | [CC BY-SA 3.0](https://github.com/AdguardTeam/AdguardFilters/blob/master/LICENSE) | 990 | [**Download**](https://mili-tan.github.io/justdomains/lists/adguard-mobile.list) |  |
| [NoCoin Filter List](#nocoin-filter-list-domains-only) | [MIT](https://github.com/hoshsadiq/adblock-nocoin-list/blob/master/LICENSE) | 689 | [**Download**](https://mili-tan.github.io/justdomains/lists/nocoin.list) | 20 Jan 2021 |
| [AdAway default blocklist](#adaway-default-blocklist-domains-only) | [CC Attribution 3.0](https://github.com/AdAway/AdAway/blob/master/LICENSE) | 8165 | [**Download**](https://mili-tan.github.io/justdomains/lists/adaway.list) |  |

&nbsp;

## EasyList (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [easylist.list](https://mili-tan.github.io/justdomains/lists/easylist.list) |
| Pi-Hole | [easylist.list](https://mili-tan.github.io/justdomains/lists/easylist.list) |

**Source:** [https://easylist.to/easylist/easylist.txt](https://easylist.to/easylist/easylist.txt)
- Title: EasyList
- Version: 202108281607
- Last Modified: 28 Aug 2021 16:07 UTC
- Homepage: [https://easylist.to/](https://easylist.to/)

**Conversion Details:**
```
Total Lines Processed: 54705
Comment Lines: 231
Empty Lines: 0
Non-Domain-only Rules Excluded: 36821
Domain-only Rules Excluded (unsupported options): 1575
Domain-only Rules Excluded (exception conflict): 48
Domain-only Rules Output: 16030
```

&nbsp;

## EasyPrivacy (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [easyprivacy.list](https://mili-tan.github.io/justdomains/lists/easyprivacy.list) |
| Pi-Hole | [easyprivacy.list](https://mili-tan.github.io/justdomains/lists/easyprivacy.list) |

**Source:** [https://easylist.to/easylist/easyprivacy.txt](https://easylist.to/easylist/easyprivacy.txt)
- Title: EasyPrivacy
- Version: 202108281607
- Last Modified: 28 Aug 2021 16:07 UTC
- Homepage: [https://easylist.to/](https://easylist.to/)

**Conversion Details:**
```
Total Lines Processed: 25339
Comment Lines: 465
Empty Lines: 0
Non-Domain-only Rules Excluded: 8894
Domain-only Rules Excluded (unsupported options): 203
Domain-only Rules Excluded (exception conflict): 140
Domain-only Rules Output: 15637
```

&nbsp;

## Fanboy's Social Blocking (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [fanboy-social.list](https://mili-tan.github.io/justdomains/lists/fanboy-social.list) |
| Pi-Hole | [fanboy-social.list](https://mili-tan.github.io/justdomains/lists/fanboy-social.list) |

**Source:** [https://easylist.to/easylist/fanboy-social.txt](https://easylist.to/easylist/fanboy-social.txt)
- Title: Fanboy's Social Blocking List
- Version: 202108281609
- Last Modified: 28 Aug 2021 16:09 UTC
- Homepage: [https://easylist.to/](https://easylist.to/)

**Conversion Details:**
```
Total Lines Processed: 20439
Comment Lines: 143
Empty Lines: 0
Non-Domain-only Rules Excluded: 20176
Domain-only Rules Excluded (unsupported options): 10
Domain-only Rules Excluded (exception conflict): 9
Domain-only Rules Output: 101
```

&nbsp;

## CJX's EasyList Lite (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [cjxlist.list](https://mili-tan.github.io/justdomains/lists/cjxlist.list) |
| Pi-Hole | [cjxlist.list](https://mili-tan.github.io/justdomains/lists/cjxlist.list) |

**Source:** [https://raw.githubusercontent.com/cjx82630/cjxlist/master/cjxlist.txt](https://raw.githubusercontent.com/cjx82630/cjxlist/master/cjxlist.txt)
- Title: CJX's EasyList Lite
- Version: 202012080856
- Last Modified: 2020/12/08 08:56 +0800
- Homepage: [https://github.com/cjx82630/cjxlist](https://github.com/cjx82630/cjxlist)

**Conversion Details:**
```
Total Lines Processed: 527
Comment Lines: 12
Empty Lines: 0
Non-Domain-only Rules Excluded: 494
Domain-only Rules Excluded (unsupported options): 1
Domain-only Rules Excluded (exception conflict): 0
Domain-only Rules Output: 20
```

&nbsp;

## CJX's Annoyance List (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [cjx-annoyance.list](https://mili-tan.github.io/justdomains/lists/cjx-annoyance.list) |
| Pi-Hole | [cjx-annoyance.list](https://mili-tan.github.io/justdomains/lists/cjx-annoyance.list) |

**Source:** [https://raw.githubusercontent.com/cjx82630/cjxlist/master/cjx-annoyance.txt](https://raw.githubusercontent.com/cjx82630/cjxlist/master/cjx-annoyance.txt)
- Title: CJX's Annoyance List
- Version: 202108281354
- Last Modified: 2021/08/28 13:54 +0800
- Homepage: [https://github.com/cjx82630/cjxlist](https://github.com/cjx82630/cjxlist)

**Conversion Details:**
```
Total Lines Processed: 1756
Comment Lines: 51
Empty Lines: 0
Non-Domain-only Rules Excluded: 1537
Domain-only Rules Excluded (unsupported options): 7
Domain-only Rules Excluded (exception conflict): 1
Domain-only Rules Output: 160
```

&nbsp;

## Fanboy's Annoyance List (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [fanboy-annoyance.list](https://mili-tan.github.io/justdomains/lists/fanboy-annoyance.list) |
| Pi-Hole | [fanboy-annoyance.list](https://mili-tan.github.io/justdomains/lists/fanboy-annoyance.list) |

**Source:** [https://easylist.to/easylist/fanboy-annoyance.txt](https://easylist.to/easylist/fanboy-annoyance.txt)
- Title: Fanboy's Annoyance List
- Version: 202108281609
- Last Modified: 28 Aug 2021 16:09 UTC
- Homepage: [https://easylist.to/](https://easylist.to/)

**Conversion Details:**
```
Total Lines Processed: 49366
Comment Lines: 580
Empty Lines: 0
Non-Domain-only Rules Excluded: 47996
Domain-only Rules Excluded (unsupported options): 50
Domain-only Rules Excluded (exception conflict): 36
Domain-only Rules Output: 704
```

&nbsp;

## EasyList China (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [easylistchina.list](https://mili-tan.github.io/justdomains/lists/easylistchina.list) |
| Pi-Hole | [easylistchina.list](https://mili-tan.github.io/justdomains/lists/easylistchina.list) |

**Source:** [https://easylist-downloads.adblockplus.org/easylistchina.txt](https://easylist-downloads.adblockplus.org/easylistchina.txt)
- Title: EasyList China
- Version: 202108281603
- Last Modified: 28 Aug 2021 16:03 UTC
- Homepage: [http://abpchina.org/forum/](http://abpchina.org/forum/)

**Conversion Details:**
```
Total Lines Processed: 19462
Comment Lines: 106
Empty Lines: 0
Non-Domain-only Rules Excluded: 13429
Domain-only Rules Excluded (unsupported options): 225
Domain-only Rules Excluded (exception conflict): 20
Domain-only Rules Output: 5682
```

&nbsp;

## AdGuard Simplified Domain Names Filter (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [adguarddns.list](https://mili-tan.github.io/justdomains/lists/adguarddns.list) |
| Pi-Hole | [adguarddns.list](https://mili-tan.github.io/justdomains/lists/adguarddns.list) |

**Source:** [https://filters.adtidy.org/extension/chromium/filters/15.txt](https://filters.adtidy.org/extension/chromium/filters/15.txt)
- Title: AdGuard DNS filter
- Version: 2.0.23.46
- Last Modified: 2021-08-28T12:06:33.224Z
- Homepage: [https://github.com/AdguardTeam/AdguardSDNSFilter](https://github.com/AdguardTeam/AdguardSDNSFilter)

**Conversion Details:**
```
Total Lines Processed: 39629
Comment Lines: 599
Empty Lines: 0
Non-Domain-only Rules Excluded: 539
Domain-only Rules Excluded (unsupported options): 5
Domain-only Rules Excluded (exception conflict): 35
Domain-only Rules Output: 38451
```

&nbsp;

## AdGuard Base Filter (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [adguard-base.list](https://mili-tan.github.io/justdomains/lists/adguard-base.list) |
| Pi-Hole | [adguard-base.list](https://mili-tan.github.io/justdomains/lists/adguard-base.list) |

**Source:** [https://filters.adtidy.org/extension/chromium/filters/2.txt](https://filters.adtidy.org/extension/chromium/filters/2.txt)
- Title: AdGuard Base filter
- Version: 2.1.92.61
- Homepage: [https://github.com/AdguardTeam/AdGuardFilters](https://github.com/AdguardTeam/AdGuardFilters)

**Conversion Details:**
```
Total Lines Processed: 99461
Comment Lines: 12024
Empty Lines: 0
Non-Domain-only Rules Excluded: 66132
Domain-only Rules Excluded (unsupported options): 2148
Domain-only Rules Excluded (exception conflict): 17979
Domain-only Rules Output: 1178
```

&nbsp;

## AdGuard Tracking Protection filter (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [adguard-tracking.list](https://mili-tan.github.io/justdomains/lists/adguard-tracking.list) |
| Pi-Hole | [adguard-tracking.list](https://mili-tan.github.io/justdomains/lists/adguard-tracking.list) |

**Source:** [https://filters.adtidy.org/extension/chromium/filters/3.txt](https://filters.adtidy.org/extension/chromium/filters/3.txt)
- Title: AdGuard Tracking Protection filter
- Version: 2.0.28.87
- Homepage: [https://github.com/AdguardTeam/AdGuardFilters](https://github.com/AdguardTeam/AdGuardFilters)

**Conversion Details:**
```
Total Lines Processed: 25517
Comment Lines: 1936
Empty Lines: 0
Non-Domain-only Rules Excluded: 4739
Domain-only Rules Excluded (unsupported options): 117
Domain-only Rules Excluded (exception conflict): 247
Domain-only Rules Output: 18478
```

&nbsp;

## AdGuard Social media filter (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [adguard-social.list](https://mili-tan.github.io/justdomains/lists/adguard-social.list) |
| Pi-Hole | [adguard-social.list](https://mili-tan.github.io/justdomains/lists/adguard-social.list) |

**Source:** [https://filters.adtidy.org/extension/chromium/filters/4.txt](https://filters.adtidy.org/extension/chromium/filters/4.txt)
- Title: AdGuard Social Media filter
- Version: 2.0.45.85
- Homepage: [https://github.com/AdguardTeam/AdGuardFilters](https://github.com/AdguardTeam/AdGuardFilters)

**Conversion Details:**
```
Total Lines Processed: 9867
Comment Lines: 554
Empty Lines: 0
Non-Domain-only Rules Excluded: 9262
Domain-only Rules Excluded (unsupported options): 4
Domain-only Rules Excluded (exception conflict): 4
Domain-only Rules Output: 43
```

&nbsp;

## AdGuard Annoyances filter (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [adguard-annoyances.list](https://mili-tan.github.io/justdomains/lists/adguard-annoyances.list) |
| Pi-Hole | [adguard-annoyances.list](https://mili-tan.github.io/justdomains/lists/adguard-annoyances.list) |

**Source:** [https://filters.adtidy.org/extension/chromium/filters/14.txt](https://filters.adtidy.org/extension/chromium/filters/14.txt)
- Title: AdGuard Annoyances filter
- Version: 2.0.92.45
- Homepage: [https://github.com/AdguardTeam/AdGuardFilters](https://github.com/AdguardTeam/AdGuardFilters)

**Conversion Details:**
```
Total Lines Processed: 29184
Comment Lines: 3957
Empty Lines: 0
Non-Domain-only Rules Excluded: 24437
Domain-only Rules Excluded (unsupported options): 95
Domain-only Rules Excluded (exception conflict): 33
Domain-only Rules Output: 662
```

&nbsp;

## AdGuard Chinese filter (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [adguard-chinese.list](https://mili-tan.github.io/justdomains/lists/adguard-chinese.list) |
| Pi-Hole | [adguard-chinese.list](https://mili-tan.github.io/justdomains/lists/adguard-chinese.list) |

**Source:** [https://filters.adtidy.org/extension/chromium/filters/224.txt](https://filters.adtidy.org/extension/chromium/filters/224.txt)
- Title: AdGuard Chinese filter
- Version: 2.0.32.47
- Homepage: [https://github.com/AdguardTeam/AdGuardFilters](https://github.com/AdguardTeam/AdGuardFilters)

**Conversion Details:**
```
Total Lines Processed: 21392
Comment Lines: 483
Empty Lines: 0
Non-Domain-only Rules Excluded: 14703
Domain-only Rules Excluded (unsupported options): 253
Domain-only Rules Excluded (exception conflict): 21
Domain-only Rules Output: 5932
```

&nbsp;

## AdGuard Mobile ads filter (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [adguard-mobile.list](https://mili-tan.github.io/justdomains/lists/adguard-mobile.list) |
| Pi-Hole | [adguard-mobile.list](https://mili-tan.github.io/justdomains/lists/adguard-mobile.list) |

**Source:** [https://filters.adtidy.org/extension/chromium/filters/11.txt](https://filters.adtidy.org/extension/chromium/filters/11.txt)
- Title: AdGuard Mobile Ads filter
- Version: 2.0.22.57
- Homepage: [https://github.com/AdguardTeam/AdGuardFilters](https://github.com/AdguardTeam/AdGuardFilters)

**Conversion Details:**
```
Total Lines Processed: 4930
Comment Lines: 974
Empty Lines: 0
Non-Domain-only Rules Excluded: 2929
Domain-only Rules Excluded (unsupported options): 24
Domain-only Rules Excluded (exception conflict): 13
Domain-only Rules Output: 990
```

&nbsp;

## NoCoin Filter List (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [nocoin.list](https://mili-tan.github.io/justdomains/lists/nocoin.list) |
| Pi-Hole | [nocoin.list](https://mili-tan.github.io/justdomains/lists/nocoin.list) |

**Source:** [https://raw.githubusercontent.com/hoshsadiq/adblock-nocoin-list/master/hosts.txt](https://raw.githubusercontent.com/hoshsadiq/adblock-nocoin-list/master/hosts.txt)
- Last Modified: 20 Jan 2021
- Homepage: [https://github.com/hoshsadiq/adblock-nocoin-list/](https://github.com/hoshsadiq/adblock-nocoin-list/)

**Conversion Details:**
```
Total Lines Processed: 706
Comment Lines: 10
Empty Lines: 1
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 0
Invalid Hosts (Ignored): 0
Duplicate Hosts (Ignored): 6
Hosts Output: 689
```

&nbsp;

## AdAway default blocklist (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [adaway.list](https://mili-tan.github.io/justdomains/lists/adaway.list) |
| Pi-Hole | [adaway.list](https://mili-tan.github.io/justdomains/lists/adaway.list) |

**Source:** [https://adaway.org/hosts.txt](https://adaway.org/hosts.txt)

**Conversion Details:**
```
Total Lines Processed: 12597
Comment Lines: 2224
Empty Lines: 2205
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 2
Invalid Hosts (Ignored): 0
Duplicate Hosts (Ignored): 1
Hosts Output: 8165
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
