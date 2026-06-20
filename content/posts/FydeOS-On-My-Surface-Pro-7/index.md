---
title: 'FydeOS on My Surface Pro 7'
draft: true
date: '2026-06-19T16:28:39Z'
tags: ["Linux","FydeOS","ChromeOS","de-google","Linux Surface Project"]
author: "ThatTransGal"
description: "My experiance of using FydeOS on my Microsoft Surface Pro 7"
showToc: true
TocOpen: false
hidemeta: false
comments: false
UseHugoToc: true
searchHidden: true
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
ShowWordCount: true
disableShare: false # set to true if you dont want people to be able to use the share button
disableHLJS: true
hideSummary: false
cover:
    image: "images/fydeos_banner.png" # path to image
    alt: "The FydeOS logo with a red backgroud"
    caption: "" # caption under image, leave empty for no caption
    relative: false
    hidden: false
editPost:
    URL: "https://github.com/thattransgal/thattransgal.github.io/content"
    Text: "Suggest Changes"
    appendFilePath: true

---
## A Brief Overview of FydeOS

### What FydeOS is

FydeOS is an operating system developed as a fork of the open-source ChromiumOS project. It uses the Linux kernel and integrates both a web browser platform and container technologies. The interface is similar to ChromeOS, and it is compatible with hardware platforms based on x86 and ARM architectures.  In practical terms, it gives you a Chromebook-like experience on virtually any PC or laptop — without the Google lock-in.

### A Brief History of FydeOS

FydeOS originally know as Flint OS was founded in 2015 by the UK/China-based startup Flint Innovations, with co-founder Carrie Gu leading the effort to build a secure, fast ChromiumOS-based platform optimized for cloud-centric computing and diverse hardware, including single-board computers.

FydeOS released its initial 0.1 version on October 28, 2016, which was compatible with the Raspberry Pi hardware platform, and it soon attracted the attention of Raspberry Pi enthusiasts.

The OS was built mainly for the Chinese market — where regular people are not familiar with the Google Play Store or Google Play Services at all. But because Android is still incredibly popular in China, Chinese users are very used to sideloading apps, so the lack of a single central app store is less of an issue there.

On March 6, 2018, FydeOS was acquired by Neverware, with the UK-based FydeOS company and overseas business becoming part of Neverware. The version with localization features for mainland China was renamed FydeOS. Then, following Flint Innovations' acquisition by Neverware in 2018, the Chinese development team spun off to form Fyde Innovations in China, continuing development of FydeOS with a focus on regional needs — ahead of Neverware's own acquisition by Google in 2020.

### How it Differs From ChromeOS

No Google account required. FydeOS can use a free Fyde account in place of a Google account. This was the original design intent for the Chinese market where Google services are inaccessible, and it continues to appeal to privacy-conscious users globally. 

Runs on any hardware. Fyde Innovations aims to provide a Chromebook-like experience on a wider range of hardware than Google's ChromeOS. ChromeOS is tightly controlled and officially only runs on certified Chromebook hardware (or via ChromeOS Flex on limited supported devices). 

Broader app compatibility. FydeOS supports Android apps, and Linux apps; making it more flexible than standard ChromeOS, which is mostly limited to what Google officially allows through the Play Store and its own Linux container (Crostini).

More interface customization. FydeOS offers more customization and feels a bit more flexible, allowing users to adjust it to suit their needs better. ChromeOS, by contrast, keeps a tightly curated, intentionally simple interface tied to Google's design decisions.

De-Googled by design. While ChromeOS is deeply integrated with Google's ecosystem — Drive, Docs, Search, account sync — FydeOS strips that dependency out. FydeOS can turn any PC or laptop into a Chromebook, complete with Android apps, all without signing into an account with the mothership.

### Where it Stands Today

FydeOS's latest release is version 22.0, released January 28, 2026, and it supports x86, x64, ARM, and ARM64 platforms. It's evolved from a niche Raspberry Pi project aimed at bypassing China's Google restrictions into a polished, globally available alternative to ChromeOS — one that's particularly appealing to homelab enthusiasts, privacy-focused users, and anyone wanting to breathe new life into older hardware without being tethered to Google's ecosystem.

##### Sources for the overview and history of FydeOS

- [FydeOS Wikapedia Page](https://en.wikipedia.org/wiki/FydeOS)
- [The Register](https://www.theregister.com/2025/08/21/fydeos_chromiumos_degoogled/)
- [DroidCrafts: FydeOS vs ChromeOS](https://droidcrafts.com/fydeos-vs-chrome-os/)
- [Dealroom.com](https://app.dealroom.co/companies/fydeos)
- [GmfReview](https://www.gfmreview.com/technology/fydeos-offers-chromeos-without-the-google-strings-attached)

## My Experience Using FydeOS as my Main OS on my Microsoft Surface Pro 7

FydeOS offers device-specific images for Microsoft Surface hardware and some other EOL devices (like the 2013 Chromebook Pixel) under their FydeOS for You category. FydeOS for You is a semi-paid version of FydeOS, which I wasn't thrilled about when I first set it up — especially since at the time it was only available as a $19.99/month subscription with no lifetime option.

They've since changed this. Pricing now includes a one-time 1-year purchase at $19.99, 2-year at $35.98, 3-year at $47.98, and a lifetime license for $199.99 (at the time of writing). The license model has also shifted to a device-based perpetual license with an included service period — per their pricing info page, this covers device-specific updates, troubleshooting, and technical support. You also get all of that free for the first 90 days after installing.

I decided to pay for the lifetime plan due to me liking FydeOS on my Surface Pro. While it is a large cost up-front, I think it is worth it if I'm going to continue to use FydeOS on my Surface Pro instead of Windows (I hate Windows tbh, It's too bloated and slow.)
