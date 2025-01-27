---
title: How To Broadcast Live on Dex 3 and Icecast for Perfect Audio Streaming with PCDJ
date: 2025-01-22T08:23:10.073Z
updated: 2025-01-27T05:29:32.304Z
tags:
  - product
categories:
  - pcdj
thumbnail: https://thmb.techidaily.com/053654aac9195ea45d1f77852c408a3b2770cc6c802ff6728e9e3d8c452deddb.jpg
---

## How To Broadcast Live on Dex 3 and Icecast for Perfect Audio Streaming with PCDJ

[![](https://i1.wp.com/pcdj.com/wp-content/uploads/2015/06/broadcastmix-coverimage.jpg?resize=530%2C298&ssl=1)](https://i1.wp.com/pcdj.com/wp-content/uploads/2015/06/broadcastmix-coverimage.jpg?fit=530%2C298&ssl=1 "broadcastmix-coverimage")

The [DEX 3.4 DJ and VJ software](https://tools.techidaily.com/pcdj/products/) pre-release hit the streets a few days ago and introduced a few new features including internet radio broadcasting support with [Icecast](http://icecast.org/).

![](https://i0.wp.com/pcdj.com/wp-content/uploads/2015/06/radiostation-image-blog.png?fit=255%2C300&ssl=1 "radiostation-image-blog")

##### _What is Icecast?_ From the company website:

> _Icecast is a streaming media server which currently supports Ogg (Vorbis and Theora), Opus, WebM and MP3 audio streams. It can be used to create an Internet radio station or a privately running jukebox and many things in between. It is very versatile in that new formats can be added relatively easily and supports open standards for communication and interaction._

Direct Icecast integration in DEX 3 means creating an internet radio station and broadcasting your mixes is a cinch.

There are quite a few internet radio platforms you can use to broadcast a radio mix show from including [Radionomy](https://www.radionomy.com/) (_free, and you can make money by gaining listeners and running ads — we’ll touch more on this in a later blog post_), [Mixify](http://www.mixify.com/) (_free and paid_) and [Shoutcheap](https://www.shoutcheap.com/) (_paid_).

[![](https://i2.wp.com/pcdj.com/wp-content/uploads/2015/06/DEX3broadcasttab.jpg?fit=300%2C231&ssl=1 "DEX3broadcasttab")](https://i2.wp.com/pcdj.com/wp-content/uploads/2015/06/DEX3broadcasttab.jpg?fit=692%2C532&ssl=1)

Just yesterday I created a radio show and time slot at Mixify.com so I could test the new broadcasting capabilities in the [DEX 3.4 pre-release](https://tools.techidaily.com/pcdj/products/) and was surprised by how easy it is to get setup and start broadcasting live. I think for DEX 3 mixing software users [Mixify.com](http://www.mixify.com/) would be a great first step into the internet radio world as setup was the easiest I’ve tried so far.

Once you’ve created your show you are provided all the credentials to populate the new “broadcast” tab in DEX 3.4’s options menu, and with a click of a button you can go live. We’ll be sure to create an in-depth article soon about broadcasting your mix with DEX 3 via Mixify specifically, and will likely touch on the other available platforms, too.

For now, if you want to test streaming locally with DEX 3.4 here’s our quick start guide including links to all the components you’ll need to get started. When broadcasting on sites like Mixify you won’t use the VLC player for listening, and you’ll use the custom server setup credentials provided by Mixify under the broadcast tab in DEX 3’s options.

#### Icecast Quick Start Guide for DEX 3 on Windows

1. ##### Requirements (for Windows)

| **Requirement**      | **Reason/s**                                                                                | **Download Link**                                                                |
| -------------------- | ------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- |
| PCDJ DEX 3           | _Allows you:_ · To record your mix · Create a radio station · Broadcast your radio station. | <https://www.pcdj.com/dj-software/dex-3/>                                        |
| Icecast Server 2.4.1 | Hosts your radio station for your fans to connect to.                                       | <http://downloads.xiph.org/releases/icecast/icecast%5Fwin32%5F2.4.1.exe>         |
| VLC Media Player     | (For Local Streaming – Test)                                                                | <http://download.cnet.com/VLC-Media-Player/3001-13632%5F4-10267151.html?hlndr=1> |

1. ##### Installing Icecast Server

| To install IceCast Server, select the link above for IceCast Server, and you will be taken to a page where you will need to select the type of installation you need.In this case, ‘Icecast for Windows.’ You will be asked to run or save the following file: ‘icecast\_win32\_2.4.1.exe’ Choose Run | [![](https://i2.wp.com/pcdj.com/wp-content/uploads/2015/06/1.png?fit=300%2C80&ssl=1 "1")](https://i2.wp.com/pcdj.com/wp-content/uploads/2015/06/1.png?fit=1030%2C273&ssl=1) |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |

| You may see the following message:Choose ‘Yes’ to begin the installation. | [![](https://i2.wp.com/pcdj.com/wp-content/uploads/2015/06/2.png?fit=300%2C153&ssl=1 "2")](https://i2.wp.com/pcdj.com/wp-content/uploads/2015/06/2.png?fit=568%2C290&ssl=1) |
| ------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |

| Accept the License Agreement by clicking ‘I Agree’ to continue with the installation. | [![](https://i1.wp.com/pcdj.com/wp-content/uploads/2015/06/3.png?fit=300%2C243&ssl=1 "3")](https://i1.wp.com/pcdj.com/wp-content/uploads/2015/06/3.png?fit=582%2C471&ssl=1) |
| ------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |

| Choose ‘Next’ to install the default components | [![](https://i0.wp.com/pcdj.com/wp-content/uploads/2015/06/4.png?fit=300%2C242&ssl=1 "4")](https://i0.wp.com/pcdj.com/wp-content/uploads/2015/06/4.png?fit=586%2C472&ssl=1) |
| ----------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |

| Choose the installation Path (we recommend the default path), and select Next. | [![](https://i1.wp.com/pcdj.com/wp-content/uploads/2015/06/5.png?fit=300%2C242&ssl=1 "5")](https://i1.wp.com/pcdj.com/wp-content/uploads/2015/06/5.png?fit=584%2C472&ssl=1) |
| ------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |

| Select Install to complete the installation. | [![](https://i2.wp.com/pcdj.com/wp-content/uploads/2015/06/6.png?fit=300%2C242&ssl=1 "6")](https://i2.wp.com/pcdj.com/wp-content/uploads/2015/06/6.png?fit=587%2C473&ssl=1) |
| -------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |

| Once the installation has finished, choose close. | [![](https://i1.wp.com/pcdj.com/wp-content/uploads/2015/06/7.png?fit=300%2C244&ssl=1 "7")](https://i1.wp.com/pcdj.com/wp-content/uploads/2015/06/7.png?fit=584%2C475&ssl=1) |
| ------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |

1. ##### Installing VLC Player

| To install the IceCast Server for Windows, select the link above for VLC Player, and you will be taken to a webpage, where you will be asked to run or save ‘vlc-2.2.1-win32.exe’Choose RunYou may see the following message Choose ‘Yes’ to begin the installation. | [![](https://i2.wp.com/pcdj.com/wp-content/uploads/2015/06/8.png?fit=300%2C151&ssl=1 "8")](https://i2.wp.com/pcdj.com/wp-content/uploads/2015/06/8.png?fit=566%2C284&ssl=1) |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |

| Choose the language that you’d like to use to complete the installation process, and choose ‘OK.’ | [![](https://i1.wp.com/pcdj.com/wp-content/uploads/2015/06/9.png?fit=300%2C164&ssl=1 "9")](https://i1.wp.com/pcdj.com/wp-content/uploads/2015/06/9.png?fit=340%2C186&ssl=1) |
| ------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |

| Accept the user license agreement by choosing ‘Next’ | [![](https://i1.wp.com/pcdj.com/wp-content/uploads/2015/06/10.png?fit=300%2C244&ssl=1 "10")](https://i1.wp.com/pcdj.com/wp-content/uploads/2015/06/10.png?fit=577%2C470&ssl=1) |
| ---------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |

| Accept the user license agreement by choosing ‘Next’ | [![](https://i0.wp.com/pcdj.com/wp-content/uploads/2015/06/11.png?fit=300%2C246&ssl=1 "11")](https://i0.wp.com/pcdj.com/wp-content/uploads/2015/06/11.png?fit=582%2C477&ssl=1) |
| ---------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |

| Choose Next to install VLC default components: | [![](https://i0.wp.com/pcdj.com/wp-content/uploads/2015/06/12.png?fit=300%2C244&ssl=1 "12")](https://i0.wp.com/pcdj.com/wp-content/uploads/2015/06/12.png?fit=585%2C476&ssl=1) |
| ---------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |

| Choose the installation path (we recommend the default path), and then select Install. | [![](https://i0.wp.com/pcdj.com/wp-content/uploads/2015/06/13.png?fit=300%2C245&ssl=1 "13")](https://i0.wp.com/pcdj.com/wp-content/uploads/2015/06/13.png?fit=581%2C474&ssl=1) |
| -------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |

| Once the installation is complete, select Finish to complete the installation, and run VLC player. | [![](https://i1.wp.com/pcdj.com/wp-content/uploads/2015/06/14.png?fit=300%2C244&ssl=1 "14")](https://i1.wp.com/pcdj.com/wp-content/uploads/2015/06/14.png?fit=581%2C472&ssl=1) |
| -------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |

1. ##### Running Icecast Server on your local machine

| From your Windows Start Menu, type in ‘icecast,’ and select ‘Run Icecast (console). | [![](https://i2.wp.com/pcdj.com/wp-content/uploads/2015/06/15.png?fit=300%2C205&ssl=1 "15")](https://i2.wp.com/pcdj.com/wp-content/uploads/2015/06/15.png?fit=507%2C346&ssl=1) |
| ----------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |

| You will see a command prompt. At this point the Icecast server is running. | [![](https://i0.wp.com/pcdj.com/wp-content/uploads/2015/06/16.png?fit=300%2C194&ssl=1 "16")](https://i0.wp.com/pcdj.com/wp-content/uploads/2015/06/16.png?fit=830%2C536&ssl=1) |
| --------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |

1. ##### Broadcasting your audio mix to your Icecast Server

| Open PCDJ DEX 3.4, select, ‘Record,’ and click ‘Broadcast audio mix’ | [![](https://i1.wp.com/pcdj.com/wp-content/uploads/2015/06/17.png?fit=300%2C97&ssl=1 "17")](https://i1.wp.com/pcdj.com/wp-content/uploads/2015/06/17.png?fit=727%2C235&ssl=1) |
| -------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |

1. ##### Using VLC to connect to your Icecast Radio Station

| Open VLC player, by clicking on your start menu, typing in ‘vlc,’ and selecting ‘VLC Media Player’ | [![](https://i2.wp.com/pcdj.com/wp-content/uploads/2015/06/18.png?fit=300%2C183&ssl=1 "18")](https://i2.wp.com/pcdj.com/wp-content/uploads/2015/06/18.png?fit=507%2C309&ssl=1) |
| -------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |

| Select Media, and choose ‘Open Network Stream’ | [![](https://i0.wp.com/pcdj.com/wp-content/uploads/2015/06/19.png?fit=300%2C221&ssl=1 "19")](https://i0.wp.com/pcdj.com/wp-content/uploads/2015/06/19.png?fit=608%2C448&ssl=1) |
| ---------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |

| For the network URL, type in the following: http://127.0.0.1:8000/stream1and then select ‘Play.’At this point, you will be connected to your radio station. | [![](https://i2.wp.com/pcdj.com/wp-content/uploads/2015/06/20.png?fit=300%2C257&ssl=1 "20")](https://i2.wp.com/pcdj.com/wp-content/uploads/2015/06/20.png?fit=535%2C459&ssl=1) |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HtM7d4dpN1I?si=2vN_xgVGD4eYGORu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### _Related_

https://i1.wp.com/pcdj.com/wp-content/uploads/2015/06/broadcastmix-coverimage.jpg?fit=530%2C298&ssl=1 298 530 Ryan Sherr https://www.pcdj.com/wp-content/uploads/2021/07/pcdj-main-logo-2.png Ryan Sherr2015-06-16 10:23:172018-12-03 12:01:08Broadcast Your Mix With DEX 3 And Icecast}

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-videos.techidaily.com/new-stealthy-view-tips-for-invisible-instagram-stories-consumption-via-pcandroidiphone-for-2024/"><u>[New] Stealthy View Tips for Invisible Instagram Stories Consumption via PC/Android/iPhone for 2024</u></a></li>
<li><a href="https://youtube-data.techidaily.com/approved-the-real-deal-behind-asmr-videos/"><u>2024 Approved The Real Deal Behind ASMR Videos</u></a></li>
<li><a href="https://tech-haven.techidaily.com/boosting-your-elder-scrolls-online-game-solutions-to-increase-frames-per-second-fps/"><u>Boosting Your Elder Scrolls Online Game: Solutions to Increase Frames Per Second (FPS)</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/t-friendly-strategies-to-infuse-text-and-video-for-2024/"><u>Budget-Friendly Strategies to Infuse Text & Video for 2024</u></a></li>
<li><a href="https://win-data.techidaily.com/comprehensive-insights-on-identified-risks-in-windows-defender-your-guide-yl-computing/"><u>Comprehensive Insights on Identified Risks in Windows Defender: Your Guide - YL Computing</u></a></li>
<li><a href="https://win-data.techidaily.com/enhance-computer-efficiency-with-a-memory-upgrade-tips-and-tricks-by-yl-technology-experts/"><u>Enhance Computer Efficiency with a Memory Upgrade: Tips and Tricks by YL Technology Experts</u></a></li>
<li><a href="https://win-data.techidaily.com/expand-access-a-detailed-walkthrough-for-creating-new-accounts-in-yl-softwares-admin-panel/"><u>Expand Access: A Detailed Walkthrough for Creating New Accounts in YL Software's Admin Panel</u></a></li>
<li><a href="https://win-data.techidaily.com/exploring-extra-capabilities-more-than-just-virus-scanning-in-windows-defender-insights-by-yl-computing/"><u>Exploring Extra Capabilities: More Than Just Virus Scanning in Windows Defender - Insights by YL Computing</u></a></li>
<li><a href="https://win-able.techidaily.com/fixing-crash-errors-in-dragon-quest-xi-a-comprehensive-guide/"><u>Fixing Crash Errors in Dragon Quest XI - A Comprehensive Guide</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-apps-from-nokia-105-classic-to-another-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Apps from Nokia 105 Classic to Another | Dr.fone</u></a></li>
<li><a href="https://win-data.techidaily.com/master-tailor-your-taskbar-with-microsofts-windows-control-panel-simple-instructions-for-a-custom-user-experience/"><u>Master Tailor Your Taskbar with Microsoft's Windows Control Panel: Simple Instructions for a Custom User Experience</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/seamless-multitasking-via-firefoxs-pip-mode-for-2024/"><u>Seamless Multitasking via Firefox's PIP Mode for 2024</u></a></li>
</ul></div>

