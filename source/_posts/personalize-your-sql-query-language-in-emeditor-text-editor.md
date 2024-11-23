---
title: Personalize Your SQL Query Language in EmEditor Text Editor
date: 2024-11-21T00:06:23.263Z
updated: 2024-11-22T16:50:24.350Z
tags:
  - product
categories:
  - emeditor
thumbnail: https://thmb.techidaily.com/90c2e01727fc918de7950373ab7790d2b6bd79b92f560dcc1472e9356e8fe972.png
---

## Personalize Your SQL Query Language in EmEditor Text Editor

Viewing 9 posts - 1 through 9 (of 9 total)

* Author  
Posts
* September 30, 2008 at 8:39 pm [#6273](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/ad4024b1aea4c5ba8e43f6b343318bad?s=80&d=identicon&r=g)Nufacik](https://www.emeditor.com/forums/users/Nufacik/ "View Nufacik's profile")  
Member  
Hi all.  
 Sorry for thit question, but I have ona problem.  
 I like to setup SQL syntax for writing keywords as uppercase. I mean, if I write select, after space EmEditor change word select -> SELECT.  
 I want this for every keywords…  
 Haw can I set up SQL syntax to working like this ???  
 Thank… (I am new in EmEditor (just 30 minutes), I like it)…  
 Nuf.  
October 1, 2008 at 12:59 am [#6279](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")  
Keymaster  
> Nufacik wrote:  
> Hi all.  
>  
> Sorry for thit question, but I have ona problem.  
> I like to setup SQL syntax for writing keywords as uppercase. I mean, if I write select, after space EmEditor change word select -> SELECT.  
> I want this for every keywords…  
> Haw can I set up SQL syntax to working like this ???  
> Thank… (I am new in EmEditor (just 30 minutes), I like it)…  
>  
> Nuf.  
 This is similar to my post here:  
[http://www.emeditor.com/modules/newbb/viewtopic.php?topic\_id=846&post\_id=2503&order=0&viewmode=flat&pid=2497&forum=12#forumpost2503](https://tools.techidaily.com/emeditor/products/)  
 Check your SQL configuration properties > Highlight (1) tab.  
October 1, 2008 at 7:51 pm [#6285](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/ad4024b1aea4c5ba8e43f6b343318bad?s=80&d=identicon&r=g)Nufacik](https://www.emeditor.com/forums/users/Nufacik/ "View Nufacik's profile")  
Member  
Hi Yutaka.  
 Of course, I have already setuped all keywords in Highlight (1) tab as uppercase. But, this working only if I write keyword, EmEditor show me autocomplete dialogbox with posibilitie words, I choose one and push enter. If I do this, keyword is changed tu uppercase. But this not working, if I write select, push space to continueing… dialog box will close, keyword select is still select and not SELECT. Is impossible confirming every word in autocomplete dialogbox… existing any others possibilities ??? May be this feature added in future. You can add this possibilitie into tab Highlight – where can user define keywords as underline, italic, bold – you can add UPPERCASE. EmEditor will change all keywords with this option tu uppercase.  
 What are you thinking about it?  
 Nuf  
October 2, 2008 at 8:50 pm [#6293](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")  
Keymaster  
> Nufacik wrote:  
> Hi Yutaka.  
>  
> Of course, I have already setuped all keywords in Highlight (1) tab as uppercase. But, this working only if I write keyword, EmEditor show me autocomplete dialogbox with posibilitie words, I choose one and push enter. If I do this, keyword is changed tu uppercase. But this not working, if I write select, push space to continueing… dialog box will close, keyword select is still select and not SELECT. Is impossible confirming every word in autocomplete dialogbox… existing any others possibilities ??? May be this feature added in future. You can add this possibilitie into tab Highlight – where can user define keywords as underline, italic, bold – you can add UPPERCASE. EmEditor will change all keywords with this option tu uppercase.  
> What are you thinking about it?  
>  
> Nuf  
 I am not exactly sure if I understand your questions, but do you want EmEditor to select “SELECT” when you type “select” and without pressing ENTER key? If you press ENTER after you type “select”, SELECT will be selected from the list.  
October 3, 2008 at 7:04 pm [#6302](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/ad4024b1aea4c5ba8e43f6b343318bad?s=80&d=identicon&r=g)Nufacik](https://www.emeditor.com/forums/users/Nufacik/ "View Nufacik's profile")  
Member  
Hi Yutaka.  
 Sorry if you dont understand me, may be it is becouse of my english… So, I try explain my question one more time and I will be more detailed. So, I want to use EmEditor for programming SQL codes (Oracle PLSQL). In this syntax people used to write keyword as uppercase. Like this example:  
 PROCEDURE showtime  
 IS  
 CURSOR curTab  
 IS  
 SELECT table\_name  
 FROM user\_table;  
 nCounter NUMBER(6);  
 BEGIN  
 FOR recTab IN curTab LOOP  
 DBMS\_OUTPUT.PUT\_LINE(TO\_CHAR(nCounter) || ‘ – table: ‘ || recTab.table\_name);  
 END LOOP;  
 END;  
 So, as can you see, keyword is putted as UPPERCASE words. And here is my question…  
 How can I setup EmEditor for this functionality… I can switch on WordCoplete. OK… if I write keyword “begin”, word complete show me little dialog vith this words, which is in dialog as “BEGIN”. My cursor is still on end of the worg “begin”, in dialog is highlited word “BEGIN”. A can do 2 things.  
 1\. I push enter. EmEditor aplicate word from dialog and transform word “begin” to “BEGIN”. This is nice, its OK. I can write next code… But, I must entered every keyword, if I want have keyword as uppercase.  
 2\. I push space. EmEditor close word complete dialog, space is addet next “begin” and I continueing in progrmming.  
 And I want to this:  
 I starting write “begin”… EmEditor show wordcomplete dialog to hinting pissibilities… If I dont choose noone, nothing happen. BUT, if I push space, EmEditr automaticaly transform “begin” to “BEGIN”. Because I have turn on checkbox To UpperCase in Highlight(1) option. Is is like after every keyword highlight this word and manualy change to uppercase function… What are you thinking about this functionality. It will be posiible add this to highlight option of SQL syntax???  
 I pray for this in EmEditor… :-D  
October 6, 2008 at 8:58 pm [#6335](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")  
Keymaster  
> Nufacik wrote:  
> Hi Yutaka.  
>  
> Sorry if you dont understand me, may be it is becouse of my english… So, I try explain my question one more time and I will be more detailed. So, I want to use EmEditor for programming SQL codes (Oracle PLSQL). In this syntax people used to write keyword as uppercase. Like this example:  
> PROCEDURE showtime  
> IS  
> CURSOR curTab  
> IS  
> SELECT table\_name  
> FROM user\_table;  
> nCounter NUMBER(6);  
> BEGIN  
> FOR recTab IN curTab LOOP  
> DBMS\_OUTPUT.PUT\_LINE(TO\_CHAR(nCounter) || ‘ – table: ‘ || recTab.table\_name);  
> END LOOP;  
> END;  
>  
> So, as can you see, keyword is putted as UPPERCASE words. And here is my question…  
> How can I setup EmEditor for this functionality… I can switch on WordCoplete. OK… if I write keyword “begin”, word complete show me little dialog vith this words, which is in dialog as “BEGIN”. My cursor is still on end of the worg “begin”, in dialog is highlited word “BEGIN”. A can do 2 things.  
> 1\. I push enter. EmEditor aplicate word from dialog and transform word “begin” to “BEGIN”. This is nice, its OK. I can write next code… But, I must entered every keyword, if I want have keyword as uppercase.  
> 2\. I push space. EmEditor close word complete dialog, space is addet next “begin” and I continueing in progrmming.  
>  
> And I want to this:  
> I starting write “begin”… EmEditor show wordcomplete dialog to hinting pissibilities… If I dont choose noone, nothing happen. BUT, if I push space, EmEditr automaticaly transform “begin” to “BEGIN”. Because I have turn on checkbox To UpperCase in Highlight(1) option. Is is like after every keyword highlight this word and manualy change to uppercase function… What are you thinking about this functionality. It will be posiible add this to highlight option of SQL syntax???  
>  
> I pray for this in EmEditor… :-D  
 I am sorry it took a long time before I can finally answer to your question. If you want the SPACE key to behave just like ENTER key, go to Word Complete Properties (Right-click on the Word Complete button on the Plug-ins toolbar), select SQL and double-click, click Keyboard tab, and select Complete in Commands drop-down list, and press SPACE in the Press New Shortcut Key. I hope this helps.  
October 7, 2008 at 1:10 pm [#6346](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/ad4024b1aea4c5ba8e43f6b343318bad?s=80&d=identicon&r=g)Nufacik](https://www.emeditor.com/forums/users/Nufacik/ "View Nufacik's profile")  
Member  
Hi Yutaka.  
 Your advice looks as the right solutions, but have 1 issue…  
 If I write keyword, I press SPACE to complete word and selection from dialog. Aftewr this, keyword will change tu uppercase. Its fine, but I’m still on edn of the word. So I have tu pust one mor time space to move cursor about one char next… So, If I do this, aj write word and must pust 2 times space to continueing writing… this is only one “bug”… otherwise its look fine…  
October 7, 2008 at 5:09 pm [#6354](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")  
Keymaster  
> Nufacik wrote:  
> Hi Yutaka.  
>  
> Your advice looks as the right solutions, but have 1 issue…  
> If I write keyword, I press SPACE to complete word and selection from dialog. Aftewr this, keyword will change tu uppercase. Its fine, but I’m still on edn of the word. So I have tu pust one mor time space to move cursor about one char next… So, If I do this, aj write word and must pust 2 times space to continueing writing… this is only one “bug”… otherwise its look fine…  
 You are right. But I don’t think there are ways to work arund this now. I might think about adding this feature in future versions. Thanks!  
October 7, 2008 at 7:00 pm [#6359](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/ad4024b1aea4c5ba8e43f6b343318bad?s=80&d=identicon&r=g)Nufacik](https://www.emeditor.com/forums/users/Nufacik/ "View Nufacik's profile")  
Member  
Great.  
 Thanks…  
 In what version? I have been vaiting with my free trial version :-)
* Author  
Posts

Viewing 9 posts - 1 through 9 (of 9 total)

* You must be logged in to reply to this topic.

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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-fbx-the-ultimate-gaming-video-guide/"><u>[New] FBX The Ultimate Gaming Video Guide</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/new-in-2024-enhancing-twitters-visual-capacity-to-fhd-level/"><u>[New] In 2024, Enhancing Twitter's Visual Capacity to FHD Level</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-power-play-the-ultimate-guide-to-selecting-lipos-for-uavs/"><u>[New] Power Play The Ultimate Guide to Selecting LiPos for UAVS</u></a></li>
<li><a href="https://win-data.techidaily.com/windows-11-pe-build/"><u>輕鬆使用Windows #11 PE Build器 - 完整指南創建引導性光碟介面</u></a></li>
<li><a href="https://win-data.techidaily.com/comment-resoudre-le-probleme-de-la-carte-micro-sd-introuvable-sur-windows-11/"><u>Comment Résoudre Le Problème De La Carte Micro-SD Introuvable Sur Windows 11 ?</u></a></li>
<li><a href="https://win-data.techidaily.com/comprehensive-solutions-for-fixing-windows-update-error-code-0x80070422/"><u>Comprehensive Solutions for Fixing Windows Update Error Code 0X80070422</u></a></li>
<li><a href="https://win-data.techidaily.com/comprehensive-walkthrough-easy-steps-to-obtain-and-install-remote-server-administration-tools-rsat-in-windows-11/"><u>Comprehensive Walkthrough: Easy Steps to Obtain & Install Remote Server Administration Tools (RSAT) in Windows 11</u></a></li>
<li><a href="https://tech-haven.techidaily.com/dealing-with-constant-100-cpu-use-fixes-unveiled/"><u>Dealing with Constant 100% CPU Use - Fixes Unveiled</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-reset-your-oppo-reno-11-5g-lock-screen-password-by-drfone-android/"><u>How to Reset your Oppo Reno 11 5G Lock Screen Password</u></a></li>
<li><a href="https://fox-that.techidaily.com/lost-iphone-notifications-revive-them-with-this-expert-guide-of-7-fixes/"><u>Lost iPhone Notifications? Revive Them With This Expert Guide of 7 Fixes</u></a></li>
<li><a href="https://common-error.techidaily.com/speaker-crackling-in-windows-117-solved/"><u>Speaker Crackling in Windows 11/7 [SOLVED]</u></a></li>
<li><a href="https://win-data.techidaily.com/step-by-step-guide-transforming-your-physical-pc-into-a-hyper-v-virtual-machine-p2v/"><u>Step-by-Step Guide: Transforming Your Physical PC Into a Hyper-V Virtual Machine (P2V)</u></a></li>
<li><a href="https://win-data.techidaily.com/toshiba-ssd-windows-111087/"><u>Toshiba SSD 在 Windows 11/10/8/7 上选择性能最高的压片软件概览</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qn1XkPJde9Y?si=i6ZJARXO8sJhy2FV&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

