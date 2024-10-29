---
title: Personalize Your SQL Query Language in EmEditor Text Editor
date: 2024-10-27T21:54:49.661Z
updated: 2024-10-29T00:14:50.269Z
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
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-the-ultimate-ipad-360-video-creation-for-facebook/"><u>[New] 2024 Approved The Ultimate iPad 360 Video Creation for Facebook</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-screen-times-best-and-worst-app-reviews/"><u>2024 Approved Screen Time's Best and Worst App Reviews</u></a></li>
<li><a href="https://win-data.techidaily.com/all-my-files-deleted-after-reboot-how-can-i-recover-them/"><u>All My Files Deleted After Reboot - How Can I Recover Them?</u></a></li>
<li><a href="https://win-data.techidaily.com/1728485287708-asus/"><u>ASUSトラブルシューター・バックアップ計画についての包括的なガイド</u></a></li>
<li><a href="https://win-data.techidaily.com/dwa-efektywne-techniki-przesuwac-stara-maszyne-do-najnowszej-podreczny-przewodnik/"><u>Dwa Efektywne Techniki Przesuwać Starą Maszynę Do Najnowszej: Podręczny Przewodnik</u></a></li>
<li><a href="https://techtrends.techidaily.com/easy-techniques-for-taking-precise-screenshots-on-any-computer-system/"><u>Easy Techniques for Taking Precise Screenshots on Any Computer System</u></a></li>
<li><a href="https://win-data.techidaily.com/einfache-schritte-zum-wechseln-von-daten-zwischen-verschiedenen-icloud-konten/"><u>Einfache Schritte Zum Wechseln Von Daten Zwischen Verschiedenen iCloud-Konten</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixed-how-to-bypass-preparing-to-configure-windows-dilemma/"><u>Fixed! How to Bypass 'Preparing to Configure Windows' Dilemma</u></a></li>
<li><a href="https://win-data.techidaily.com/gptmbr/"><u>GPTを使ったMBRディスクの簡単なクローニング手順 - 上から見るとこんな感じ</u></a></li>
<li><a href="https://win-data.techidaily.com/how-to-create-a-clone-of-windows-server-2012-r2-hdd/"><u>How to Create a Clone of Windows Server 2012 (R2) HDD</u></a></li>
<li><a href="https://win-data.techidaily.com/how-to-retrieve-accidentally-erased-photographs-on-a-seagate-usb-flash-drive/"><u>How To Retrieve Accidentally Erased Photographs on a Seagate USB Flash Drive</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-3-effective-methods-to-fake-gps-location-on-android-for-your-realme-11-pro-drfone-by-drfone-virtual/"><u>In 2024, 3 Effective Methods to Fake GPS location on Android For your Realme 11 Pro | Dr.fone</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-the-beginners-guide-to-designing-engaging-and-shareable-fb-slideshows/"><u>In 2024, The Beginner's Guide to Designing Engaging and Shareable FB SlideShows</u></a></li>
<li><a href="https://extra-tips.techidaily.com/mastering-audio-format-switches-srt-to-ssa-and-more/"><u>Mastering Audio Format Switches SRT to SSA & More</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/mastery-of-safaris-picture-in-picture-for-ios-and-macos/"><u>Mastery of Safari's Picture-in-Picture for iOS & macOS</u></a></li>
<li><a href="https://tech-revival.techidaily.com/transform-your-teaching-with-artificial-intelligence-8-inspiring-reasons-every-instructor-should-embrace-it/"><u>Transform Your Teaching with Artificial Intelligence: 8 Inspiring Reasons Every Instructor Should Embrace It</u></a></li>
<li><a href="https://win-data.techidaily.com/troubleshooting-failed-phone-calls-after-updating-to-ios-eby/"><u>Troubleshooting Failed Phone Calls After Updating to iOS Eby</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-in-2024-capturing-your-computers-sounds-a-guide-to-using-audacity/"><u>Updated In 2024, Capturing Your Computers Sounds A Guide to Using Audacity</u></a></li>
<li><a href="https://win-data.techidaily.com/1728475786157-windows-11/"><u>Windows 11の「古いシステム」ディレクトリをセキュリティ上正しく処分する手順</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2123512/26400" target="_top" id="2123512">
  <img src="//a.impactradius-go.com/display-ad/26400-2123512" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2123512/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

