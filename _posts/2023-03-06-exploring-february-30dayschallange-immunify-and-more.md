---
layout: post
title: "Exploring February 2023: My journey through #30days challenge, immunify, and more"
tags: recap code4rena sherlock
---

Hey folks! It's time for my monthly roundup and I'm excited to share my journey from February.

## January audit results

First off, let me share my January contest results. All my findings have been released and I'm proud to say that I did 5 contests (4x code4rena, 1x Sherlock) and made $5436 with 62 hours of work. I found 5 high and 8 medium findings, all in all I would say it was a good month.

|Contest    |Ranking    |Payment    |Time   |QA    |Medium findings    |High findings|
|---|---|---|---|---|---|---|---|
|[2023-01-biconomy (c4)](https://code4rena.com/contests/2023-01-biconomy-smart-contract-wallet-contest) | **#8**  |   <span style="color:green; font-weight:bold">$1080.21</span> | 18:00h | <span style="color:green;">a-grade</span> | **3** | **1** |
|[2023-01-astaria (c4)](https://code4rena.com/contests/2023-01-astaria-contest) | **#35** |   <span style="color:green; font-weight:bold">$339.14</span> | 08:00h | <span style="color:green;">a-grade</span> | **1** | - |
|[2023-01-ondo-finance (c4)](https://code4rena.com/contests/2023-01-ondo-finance-contest) | **#5**  |   <span style="color:green; font-weight:bold">$2821.71</span> | 12:30h | <span style="color:green;">a-grade</span> | **-** | **1** |
|[2023-01-cooler (sherlock)](https://app.sherlock.xyz/audits/contests/36) | **#17**  |   <span style="color:green; font-weight:bold">$162.22</span> | 12:00h | - | **1** | **2** |
|[2023-01-rabbithole (c4)](https://code4rena.com/contests/2023-01-rabbithole-quest-protocol-contest) | **#8**  |   <span style="color:green; font-weight:bold">$1034.68</span> | 11:30h | <span style="color:green;">a-grade</span> | **3** | **1** |
|total   |  | **$5437,96** | **62:00h**  |   | **8**   | **5**   |

## #30days Challenge Experience

Now, let's talk about February. I didn't participate in any code4rena or Sherlock contests this month, but I participated in the #30days challenge from @Web3SecurityDAO and it pushed me to do at least one hour of research every day, and I discovered some awesome resources that I want to share with you.

- [Spearbit's](https://www.youtube.com/@Spearbit/videos) videos on YouTube are a must watch. So much alpha - highly recommended!
- [4naly3er](https://github.com/Picodes/4naly3er) from Picodes - it's an amazing tool and I try to contribute back by adding findings I don't want to include in my reports. Last month, I contributed the `Solmate's SafeTransferLib does not check for token contract's existence` finding and some configuration options.
- [Proxies research](https://proxies.yacademy.dev/) by yacademy is a must read. It's one of the best summaries I've come across.
- Chisel from Foundry is amazing and can help speed up some processes. I somtimes struggle to remember to use it for simple checks, but it's one of the best optimizations I've found.
- I also spent a lot of time reading old reports. I [open-sourced](https://github.com/zaskoh/audit-reports) this repo. With it I can get a Discord update and add it to my to-do list for reading the report. It scans for new code4rena and Sherlock audit reports that were released.
- [The QuillCTF](https://quillctf.super.site/challenges) was a fun weekly challenge. Some were challenging, some were easy, but it's a nice format. I think I'll continue to participate in it.
- Last but not least, I went down a rabbit hole on [Immunify](https://immunefi.com/explore/?filter=immunefi). Zobront open-sourced quickpoc and I adapted it so it's possible to use it on every chain. Check it out on [Github](https://github.com/zaskoh/quickpoc). It helps to easily spin up a project with all the inscope files. I went through about 3-4 projects in total, but didn't find anything that was in scope to report.

## Reflecting on February:

All in all, February was a research-heavy month for me. I missed some of my goals, but I still think it was a worthwhile experience. One of my main goals was to be more active on Twitter and connect with more security researchers. The #30days challenge helped me with posting on Twitter and I joined the Solidity Lab from https://guardianaudits.com/, where I joined the verified auditors and will try to be active on this community.

## My Goals for March

For March, I plan to participate in every new QuillCTF, focus more on code4rena and Sherlock audits, and be active on the Solidity Lab community. Simple, but effective. Let's go!
