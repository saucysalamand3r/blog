---
templateKey: blog-post
title: Privacy is a Fundamental Right. Protect it.
date: 2019-04-17T16:48:34.891Z
description: >-
  You have a fundamental right to privacy as a human being. Yet, the vast
  majority of society has given away this right for little bits of convenience,
  not realizing how profound these intrusions are, or simply not caring about
  them outright. Here, I will make the case that we ought to care about our
  privacy, identify the "bad guys", and offer solutions to the crisis.
tags:
  - privacy
  - security
  - software
  - open-source
  - Linux
  - encryption
---
# Why Should I Care?
Often, you'll hear people say things like

> "I don't care about my right to privacy, I've got nothing to hide."

However, as pointed out by Edward Snowden, [this is no different than saying you don't care about your freedom of speech because you have nothing to say](https://twitter.com/Snowden/status/661938964304166912). It's absurd, and very dangerous. It allows the worst members of society (tyrannical governments, greedy corporations, and evil people) to take advantage of your own laziness and use it to dominate you. You may think you're too boring to care about data collection being conducted against you, but the data that's being collected is often behavioral data, so that these companies can predict where you'll be, who you'll be with, when you'll be there, what you'll do or buy, and how they can use this data to manipulate you. As shown in Google's leaked internal video titled ["The Selfish Ledger"](https://youtu.be/QDVVo14A_fo), many massive corporations, in and out of the tech industry, are more than happy to exploit this behavioral data to manipulate your future behavior. This is beyond Orwellian, this is algorithmic brainwashing combined with systematic censorship of the opposition, and all happening behind the scenes. Perhaps if you express an unpopular political opinion online, Google will only provide you with search results to counter your belief, even if there's plenty of evidence for your view as well, or even more. Perhaps if you say or post something deemed hateful or dangerous to the status quo, these surveillance corporatists will use their ["unbiased"](https://www.nytimes.com/2018/09/21/technology/google-search-political-bias.html), proprietary search algorithms to prevent anyone from seeing what you say, effectively censoring you. This isn't a dystopian future, this is a dystopian present, and if we don't do anything now, it will only get worse.

# The Bad Guys

### Google

Google is a very easy target here. The amount of data they collect on users is almost unparalleled. If you think about it, it's easy to understand how. They're behind the [most popular search engine](https://www.netmarketshare.com/search-engine-market-share.aspx?options=%7B%22filter%22%3A%7B%7D%2C%22dateLabel%22%3A%22Trend%22%2C%22attributes%22%3A%22share%22%2C%22group%22%3A%22searchEngine%22%2C%22sort%22%3A%7B%22share%22%3A-1%7D%2C%22id%22%3A%22searchEnginesDesktop%22%2C%22dateInterval%22%3A%22Monthly%22%2C%22dateStart%22%3A%222018-04%22%2C%22dateEnd%22%3A%222019-03%22%2C%22segments%22%3A%22-1000%22%7D) (Google), [the most popular browser](https://www.netmarketshare.com/browser-market-share.aspx?options=%7B%22filter%22%3A%7B%7D%2C%22dateLabel%22%3A%22Trend%22%2C%22attributes%22%3A%22share%22%2C%22group%22%3A%22browser%22%2C%22sort%22%3A%7B%22share%22%3A-1%7D%2C%22id%22%3A%22browsersDesktop%22%2C%22dateInterval%22%3A%22Monthly%22%2C%22dateStart%22%3A%222018-04%22%2C%22dateEnd%22%3A%222019-03%22%2C%22segments%22%3A%22-1000%22%7D) (Chrome), [the most popular operating system](https://www.netmarketshare.com/operating-system-market-share.aspx?options=%7B%22filter%22%3A%7B%7D%2C%22dateLabel%22%3A%22Trend%22%2C%22attributes%22%3A%22share%22%2C%22group%22%3A%22platform%22%2C%22sort%22%3A%7B%22share%22%3A-1%7D%2C%22id%22%3A%22platformsDesktop%22%2C%22dateInterval%22%3A%22Monthly%22%2C%22dateStart%22%3A%222018-04%22%2C%22dateEnd%22%3A%222019-03%22%2C%22segments%22%3A%22-1000%22%7D) (Android), [the most popular video site](https://www.datanyze.com/market-share/online-video/) (Youtube), and most significantly, [the most profitable online advertisement business ever](https://www.statista.com/statistics/193530/market-share-of-net-us-online-ad-revenues-of-google-since-2009/). They have a stranglehold on the majority of the software used by everyday people, providing them with a strong advantage over their competition in advertising, because they can serve ads to users most likely to click those ads.

To avoid potential legal issues, Google supplies users with a [dashboard](https://myactivity.google.com) showing some of the uniquely-identifiable data they have stored on you as a user. No one with a shred of self-respect can look at that timeline of data and not hate Google for it.

Beyond this, Google has Google Analytics, a chunk of JavaScript that is loaded on [30-50 million websites](https://marketingland.com/as-google-analytics-turns-10-we-ask-how-many-websites-use-it-151892), meaning a massive portion of the web is jeopardized for anyone trying to escape the all-seeing gaze of Big Brother. Luckily, many script blockers block Google Analytics, including the one built into [Brave](https://brave.com), a browser built by the father of JavaScript himself.

Furthermore, Google runs Google Cloud, a cloud infrastructure available to third-party developers to run their applications on. This means that, while the company may not be owned by Google, its application runs on Google servers. Firebase, a tool Google created on Google Cloud, is behind push notification support for most applications, meaning Google is responsible for delivering those notifications. Apps which run on Google Cloud include Snapchat, iCloud,and [countless others](https://cloud.google.com/customers/#/).

### Facebook

I know, I'm beating a dead horse here. Everybody hates Facebook for [violations of privacy](https://www.nbcnews.com/news/us-news/cambridge-analytica-harvested-data-millions-unsuspecting-facebook-users-n857591) now, but many don't seem to realize how many other services are owned by Facebook. I've seen people posting #DeleteFacebook like crazy, then posting some more on Instagram. Instagram, Whatsapp, Oculus, and [others](https://en.wikipedia.org/wiki/List_of_mergers_and_acquisitions_by_Facebook) are owned by Facebook. 

Unlike with Google, all of Facebook's less-than-noble practices are publicly visible, and clearly disclosed. Every now and then, the media gets angry over the latest Facebook privacy scandal, but it's been happening all along. We're just too lazy to care. We are to blame.

### Microsoft

Microsoft has [always](https://www.heise.de/tp/features/How-NSA-access-was-built-into-Windows-3444341.html) been cooperative with governments in surveilling users. Nothing has changed there. In fact, it's only gotten worse with [Windows 10's telemetry settings](https://www.zdnet.com/article/windows-10-telemetry-secrets/). Microsoft is generally accepted to be in bed with the [NSA](https://www.nytimes.com/2013/09surveilling/06/us/nsa-foils-much-internet-encryption.html?pagewanted=all&_r=0), [FBI](https://mashable.com/2013/09/11/fbi-microsoft-bitlocker-backdoor/#xElHwPWGRiqQ), and any other three-letter agency that wants to violate the constitution. [Even ex-Microsoft employees don't trust Microsoft](https://www.csoonline.com/article/2225488/not-even-microsofties-trust-microsoft-s-approach-to-privacy.html). Enough said.

### Apple

If you believed Apple's ["What happens on your iPhone Stays on your iPhone"](https://www.cnbctv18.com/technology/what-happens-on-your-iphone-stays-on-your-iphone-2605861.htm) shtick, prepare for bad news. MacOS and iOS are proprietary, meaning there's no way for a third party to audit the code and ensure that Apple lives up to their claims on privacy. Between [recording users without their knowledge](https://venturebeat.com/2019/02/08/apples-latest-privacy-issues-show-we-need-now-recording-lights/), [the fact that iCloud is hosted on Google Cloud](https://www.cnbc.com/2018/02/26/apple-confirms-it-uses-google-cloud-for-icloud.html), and [iMessage's general unpopularity with security researchers](https://www.tomsguide.com/us/is-apple-imessage-secure,news-17741.html), Apple isn't much better than its competitors. On the upside, Apple is not a cloud-first company, and thus data collection isn't their business model. On the downside, they're reliant on such companies, and [don't catch third-party violations of their users' right to privacy in apps on their app store](https://www.engadget.com/2019/01/30/facebook-research-app-data-privacy-teenagers/).

### The State

#### US

- [The NSA conducts surveillance against citizens](https://www.eff.org/nsa-spying)
- [The FBI wanted Apple to jeopardize the security of iOS](https://www.cnbc.com/2016/03/29/apple-vs-fbi-all-you-need-to-know.html)
- [FISA warrants make surveillance far easier legally when a foreign power is potentially involved](https://www.ajc.com/news/national/what-fisa-warrant/WqP428Eg04nHe933u1GazO/)
- Do you really need any more?

#### China

[It's](https://www.theatlantic.com/international/archive/2018/02/china-surveillance/552203/) [well-established](https://www.washingtonpost.com/news/democracy-post/wp/2017/08/18/chinas-dystopian-push-to-revolutionize-surveillance/?noredirect=on&utm_term=.588de3c3ad16) [that](https://www.theguardian.com/world/2018/jan/18/china-testing-facial-recognition-surveillance-system-in-xinjiang-report) [China](https://www.wsj.com/video/life-inside-chinas-total-surveillance-state/CE86DA19-D55D-4F12-AC6A-3B2A573492CF.html) [is](http://fortune.com/2019/03/27/data-sheet-china-surveillance/) [the](https://www.huffpost.com/entry/china-surveillance-camera-big-brother_n_5a2ff4dfe4b01598ac484acc) [world's](https://thediplomat.com/2018/04/chinas-ever-expanding-surveillance-state/) [worst](https://www.bloomberg.com/news/articles/2019-02-21/the-companies-behind-china-s-high-tech-surveillance-state) [surveillance](https://thediplomat.com/2019/03/worried-about-huawei-take-a-closer-look-at-tencent/) [state.](https://www.theverge.com/2018/2/1/16721230/wechat-china-app-mini-programs-messaging-electronic-id-system)

#### Europe

The European Union has some of the most robust privacy regulations in the world, thanks to [GDPR](https://eugdpr.org/). However, this set the precedent that government is allowed to interfere with the Internet. Thus, we got [Article 13](https://www.cnet.com/news/article-13-europes-hotly-debated-eu-copyright-law-explained/) and [Article 15](https://www.businessinsider.com/explained-article-15-and-article-17-2019-3), which stifle freedom on the Internet severely, despite virtually no one wanting them to become law.

# The Solution

It may seem there's no way out. Our computers, phones, search engines, even our [TVs](https://www.nydailynews.com/news/national/wikileaks-documents-show-alleged-cia-program-hack-smart-tvs-article-1.2991141) are spying on us, on behalf of governments and corporations alike. However, there are options. The remainder of this article will be devoted to listing alternatives to the offending products and services, listed in order of difficulty from easiest to adjust to, all the way to the most secure options. 

## Things You Should Use

### A VPN

VPNs are a quick and easy way to prevent your Internet Service Provider (perhaps your cable or telephone company) from intercepting and tracking your internet traffic. Some VPNs are questionable, but some are reputable options with a clear no-logging policy, perfect for protecting user privacy. Among those, [Private Internet Access}(https://www.privateinternetaccess.com/) is my recommendation. They're incredibly friendly to the open source community and have a strong dedication to privacy. Other great options include [NordVPN](https://nordvpn.com/), and [ExpressVPN](https://expressvpn.com/).

### A Password Manager

Password managers allow you to generate and store passwords, ensuring they're secure and not duplicated across multiple sites and services. The simplest secure and open-source password manager at the moment is [BitWarden](https://bitwarden.com/), but other options include the veteran [KeePass](https://keepass.info/).

### Encryption

Encrypt everything! On Windows (Which you shouldn't use regardless), that means BitLocker. On Linux, use LVM and full-disk encryption. On Android, there's an option in settings. Wherever it may be for you, always enable encryption. Always. Stop reading this and do it now, then come back. 

## Alternatives You Should Switch To

### Google → DuckDuckGo

[DuckDuckGo](https://duckduckgo.com/) has a ridiculous name, but it's the go-to search engine that respects user privacy. Switching is easy, because all search engines basically work the same anyway. Additionally, DuckDuckGo allows "bang" commands, so you can search various other services by simply putting ! followed by a code of a few letters at the beginning of your search. Say you wanted to use Google instead because you weren't getting the results you wanted. Simply throw !g in front of your search, and it'll redirect your search to Google. 

### Chrome → Brave

I mentioned [Brave](https://brave.com) briefly earlier. It's a browser built to block invasive JavaScript and ads, from a company led by Brendan Eich, who was responsible for NetScape, Mozilla Firefox, and JavaScript itself. Once Brave starts filtering out ads and scripts, the web gets more secure and also faster. In incognito mode, Brave defaults to DuckDuckGo for search (although I'd suggest setting it as the default for any kind of tab), and there's an option to use the Tor Network, which is awesome because Tor is a technology that will be much further down this list, but Brave made it super easy to use, and it's built right in. 

### For Android Users: Google Play Store → F-Droid

[F-Droid](f-droid.org) is a repository of free and open source android apps. Think of it like an app store that only publishes apps which allow the public to see their code. Every app is available to be audited, and the community ensures apps don't survive if they don't play by the rules. 

### Gmail → Protonmail / Tutanota

Gmail and Outlook are the two significant mail services, and the smaller options (like Yahoo Mail) are almost never any better. Of the exceptions to this, [Protonmail](https://protonmail.com/). Protonmail encrypts emails to and from other Protonmail addresses, and hosts everything under Swiss jurisdiction. The general assumption is that this makes it more secure and privacy-respecting.

However, there are some [potential issues]() with Protonmail, and it isn't open source. Thus, a good alternative is [Tutanota](https://tutanota.com/), a service under German jurisdiction that handles encryption differently, and is entirely open-source. It also has an app on F-Droid, meaning it can operate on Google-free Android devices. 

### Messaging → Signal / Riot.im

Messaging is a rocky category right now. We're at the end of the life of SMS, so everybody's moving on to "smarter" chat apps. Unfortunately, none of the mainstream ones are secure by any means. [Signal Private Messenger](https://signal.org/) is end-to-end encrypted, super easy to use, and can handle SMS as well on Android. Signal has all the features people are looking for in other chat apps (video chat, calling over Wi-Fi, read receipts, etc), plus end-to-end, state-of-the-art encryption. 

However, Signal still runs on a centralized network, so while the data is all encrypted, it is still all going through servers owned and maintained by one organization. A good decentralized alternative is [Riot.im](https://riot.im/), a decentralized messenger that supports end-to-end encryption as well. 

### Facebook (Or other Social Media) → Mastodon

Ideally for privacy, one would leave social media altogether. However, many of us as social creatures struggle with that concept. My recommendation is [Mastodon](https://joinmastodon.org/), an open-source, decentralized social network that works a lot like Twitter (except without banning everyone). It takes the power out of the hands of one massive corporation and gives it to smaller owners of Mastodon instances: individual, distinct servers, which you can choose from to ensure your account lives in a good neighborhood. 

### Microsoft Office → LibreOffice

Microsoft Office is ubiquitous because of the education industry, but it's also a total ripoff. A Microsoft Office 365 subscription starts at $100 a year. That's insane. [LibreOffice](https://libreoffice.org) is free and open source. It edits documents too. I really can't wrap my head around why everybody still pays for something they could essentially get for free. Easiest sales pitch of all time. 

### Windows / MacOS → Linux

Windows, MacOS, and especially ChromeOS are insecure, or in the case of MacOS, at least potentially insecure. Linux, on the other hand, is open source, and there are a ton of distributions available. They're inherently secure, because if they're not, everyone will switch to one that is. For new users, I suggest giving [Elementary OS](https://elementary.io/) a shot. It's beautiful and easy to use. Better yet, if you're willing to jump right in, [PureOS](https://pureos.net/) is a distribution purpose-built for privacy, and the developers, a company called [Purism](https://puri.sm/) produce top-notch laptops with PureOS preinstalled, along with hardware kill switches. Hardware kill switches physically sever a sensor's connection to power, so you can be absolutely certain your laptop's camera, microphone, Bluetooth, or Wi-Fi are off.

### Android / iOS → LineageOS / Linux

Much to the disservice of consumers, the mobile operating system market is stuck in a duopoly between Google (Android) and Apple (iOS). There are no viable alternatives at the moment, and both should be considered unsafe. Many have tried and failed to infiltrate this market, including Blackberry, Palm, and most notably Microsoft. If the duopoly is inevitable, a de-googled Android system is the best option for privacy and security. There was once a project that did this called [CopperheadOS](https://www.copperheados.com/), but it's been abandoned. Thus, my suggestion for Google-free Android is [LineageOS](https://lineageos.org/) with no Google apps.

LineageOS is the successor to Cyanogenmod, and has a few features you won't find on a standard Android device, including Privacy Guard and Trust. Installation is relatively simple compared to other Android ROMs, but still difficult for those who don't know what they're doing. Luckily, [instructions are provided](https://wiki.lineageos.org/devices/).

Alternatively, there will be a new contender based on GNU / Linux rather than Android, coming from [Purism](https://puri.sm/). It's called the Librem 5, and it's going to be a smartphone shipping with PureOS. It'll have hardware kill switches and all the hardware will be open source for other vendors to modify or build software for. I think it could succeed, but beware, it could join the ranks of other attempted mobile operating systems. Worst case scenario, you could likely install LineageOS on the hardware. 

Honorary mentions include [postmarketOS](https://postmarketos.org/), [Ubuntu Touch](https://ubuntu-touch.io/), and [KDE Plasma Mobile](https://www.plasma-mobile.org/index.html), mobile Linux distributions. 

### Google Drive / OneDrive / Dropbox → Nextcloud
[Nextcloud](https://nextcloud.com/) allows you to self-host cloud storage for yourself. Just take an old, cheap, or unused computer, install Nextcloud, and you're ready to go. Nextcloud supports syncing contacts and calendars, encryption, and even document collaboration with [Collabora](https://www.collaboraoffice.com/). Nextcloud is shockingly easy to install and use, everyone should try it. 

## Advanced Options

### Tor Browser

Brave has Tor integration, but the [Tor Project](https://torproject.org/) builds a first-party browser with that integration baked in even more. Because it routes everything through Tor, it is noticeably slow, but it's a tradeoff sometimes worth making. 

### Qubes OS
[Qubes](https://qubes-os.org/) is [Edward Snowden's recommended operating system](https://twitter.com/Snowden/status/781493632293605376). It achieves security by sandboxing each application into its own virtual machine. If you don't know what that means, Qubes is likely not for you. If you do, give it a shot (after adding more RAM to your system).

### TAILS
[TAILS](https://tails.boum.org/) (The Amnesic Incognito Live System) is another operating system, but it's not meant to be installed. You boot it from a flash drive or other removable media. Upon shutdown, everything you did is erased. The entire time the system is active, it routes all internet traffic through Tor. [It's also recommended by Snowden](https://twitter.com/snowden/status/941018955405242369).

## A Note
This list of recommendations is by no means exhaustive. For more information on privacy-respecting software, as well as advice on privacy in general, check out [PrivacyTools.IO](https://privacytools.io), which goes more in-depth on all of this. 
