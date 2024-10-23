---
title: Personalize Your SQL Query Language in EmEditor Text Editor
date: 2024-10-19T09:57:42.270Z
updated: 2024-10-22T16:21:23.677Z
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
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-open-world-wonders-beyond-gtas-empire/"><u>[New] 2024 Approved Open World Wonders Beyond GTA's Empire</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-from-scripted-to-spontaneous-elevating-reactions-for-youtube-success-3-steps/"><u>[Updated] 2024 Approved From Scripted to Spontaneous Elevating Reactions for YouTube Success (3 Steps)</u></a></li>
<li><a href="https://win-data.techidaily.com/1-bonus-simple-guide-restore-accidentally-deleted-data-on-your-flash-drive/"><u>1. [Bonus!] Simple Guide: Restore Accidentally Deleted Data on Your Flash Drive</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-unveiling-authentic-identity-in-fb-messages/"><u>2024 Approved Unveiling Authentic Identity in FB Messages</u></a></li>
<li><a href="https://win-data.techidaily.com/comment-executer-la-commande-slmgrrearm-sur-windows-guide-complet-et-conseils/"><u>Comment Exécuter La Commande SLMGR/RÉARM Sur Windows : Guide Complet Et Conseils</u></a></li>
<li><a href="https://tech-haven.techidaily.com/financial-wisdom-in-emojis-unveiling-trends-and-concerns/"><u>Financial Wisdom in Emojis: Unveiling Trends & Concerns</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/hacks-to-do-pokemon-go-trainer-battles-for-motorola-g24-power-drfone-by-drfone-virtual-android/"><u>Hacks to do pokemon go trainer battles For Motorola G24 Power | Dr.fone</u></a></li>
<li><a href="https://win-data.techidaily.com/how-to-transfer-messages-from-icloud-to-iphone-or-pc-using-fonebackup-comprehensive-guide/"><u>How to Transfer Messages From iCloud to iPhone or PC Using FoneBackup - Comprehensive Guide</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/24-exploring-mukbang-culture-in-live-video-formats/"><u>In 2024, Exploring Mukbang Culture in Live Video Formats</u></a></li>
<li><a href="https://win-data.techidaily.com/overcoming-connectivity-woes-effective-solutions-for-apple-devices-battery-charging-issues-following-the-latest-ios-update/"><u>Overcoming Connectivity Woes: Effective Solutions for Apple Devices' Battery Charging Issues Following the Latest iOS Update</u></a></li>
<li><a href="https://win-data.techidaily.com/solving-invalid-directory-name-error-in-windows-10-and-11-top-5-methods/"><u>Solving 'Invalid Directory Name' Error in Windows 10 and 11 - Top 5 Methods</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/upcoming-tech-anticipate-the-iphone-16-incorporating-key-feature-of-iphone-15-pro-revealed-by-zdnet/"><u>Upcoming Tech: Anticipate the iPhone 16 Incorporating Key Feature of iPhone 15 Pro, Revealed by ZDNet</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-in-2024-10-essential-fcpx-plugins-to-elevate-your-video-editing-game-free-and-paid/"><u>Updated In 2024, 10 Essential FCPX Plugins to Elevate Your Video Editing Game Free and Paid</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098703/14409" target="_top" id="2098703">
  <img src="//a.impactradius-go.com/display-ad/14409-2098703" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098703/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

