![Image_1706017651672](https://github.com/South-Haruna-Institute-of-Technology/nightx_shit/assets/65479796/b2eccb0a-31a1-450f-882d-7c708a652a7e)

# What is this sh1t

This is a promotional pic of the latest scam project Nightx provided by our dear scammer Mr.Liu Enshuo A.K.A"澄1337" / "modica". 
![IMG_20240123_222524_674](https://github.com/South-Haruna-Institute-of-Technology/nightx_shit/assets/65479796/ccb139d3-9f2a-4f8e-b15d-5504dae1d4e2)

For this scam project, he made great efforts and tried to fabricate a non-existent "Russski team"

(yesli zdyes yest russkiy igrok na hvh, nadyeyus, vy yego nye poddyerzhitye)
![Image_1706019555379](https://github.com/South-Haruna-Institute-of-Technology/nightx_shit/assets/65479796/5f532da0-206e-4825-ac57-244cf69b12ce)

Who knows the truth? Maybe he just studied Photoshop

![IMG_20240123_231505_477](https://github.com/South-Haruna-Institute-of-Technology/nightx_shit/assets/65479796/1d19e975-cf2c-4bc2-b7b9-bba5f54f1654)
It seems that he is also going to conduct a GTA5 cheat software scam, but this time he did not even consider pasta, but chose to do .pptx directly.

# Who he is

Since his scam project requires an invitation, and we have learned from the past and are no longer willing to endorse his project, we decided to review his previous actions first, and let you who are reading now make the judgment.


Here is a ready-made >> [video](https://www.bilibili.com/video/BV1fR4y1B7ZX/) for you to watch

before making the big scam heverhit
he is already a scammer
![IMG_20240123_223317_372](https://github.com/South-Haruna-Institute-of-Technology/nightx_shit/assets/65479796/41060fa1-8c80-45e1-a097-32bcfc0e98cd)
and made his id leaked😉
![Screenshot_2024-01-23-22-35-36-155_org telegram messenger web-edit](https://github.com/South-Haruna-Institute-of-Technology/nightx_shit/assets/65479796/ad08fef1-abaa-4888-a4cf-a37eb9de1d0e)

## neverhit?
however,he continued his scam life
but using a neo-NAME "modica"
![Screenshot_2024-01-23-22-38-37-588_com android chrome-edit](https://github.com/South-Haruna-Institute-of-Technology/nightx_shit/assets/65479796/51af43ce-6a1f-4db7-bc21-a1383d19b842)
What shocks me is that as late as 2024, he was still browsing hvhbbs with the IP address 120.242.117.44
![Screenshot_2024-01-23-22-39-55-593_com android chrome-edit](https://github.com/South-Haruna-Institute-of-Technology/nightx_shit/assets/65479796/f3997957-d83a-4d21-997f-5af3468b70a5)
"Neverhit.club already has a very complete free DLL injector, providing convenient one-click injection service. Now we are about to launch our Legit and Rage cheats, hope you all support and like them. The prizes are as follows: Three forum invitation codes Monthly renewal for one Legit version Two full versions (Legit & Rage) monthly renewal A full version (Legit & Rage) quarterly (three months) renewal"

## 「pls crack me」
This software seems to be a bit real... 
![Screenshot_2024-01-24-01-03-06-400_com tencent mobileqq-edit](https://github.com/South-Haruna-Institute-of-Technology/nightx_shit/assets/65479796/b989a244-9113-4e33-bf44-cbab4b8c694e)

Our modica even pasted legendware to make a legit version of heverhit, but it was >>[ezcrked](https://twitter.com/M3351AN/status/1610679877526749186) in just one day

Interlude: When M3351AN gave the above video, Mr. Liu initially thought that Moxxie leaked the dll file to M3351AN, because M3351AN and Moxxie had known each other before.


## pasta
Our cracker @M3351AN discovered that this scam cheat even uses http to download dll files 😅 What’s even more hilarious is that we later discovered that [heverhit was using a C# loader](https://twitter.com/M3351AN/status/1610725657683824640) pasted from GitHub.

The following is the php interface of neverhit leaked
```cs

NeverHit_Api

文中的adress = https://neverhit.club/ 

//订阅检查
用到的网址 // https://neverhit.club/info.php/?username=Modica&isMemberOf  Modica替换成获取的用户名
如果没有订阅则返回nosub 反之则返回sub



//版本号检查
 如果获取的大于当前版本号 则会提示更新错误
用到的接口是https://neverhit.club/info.php?version 


//hwid接口也是最麻烦的一个接口 他拥有多重判定
你需要获取一个hwid上传至服务器获取到的hwid他应该是一个255的值
运用到的网站是https://neverhit.club/hwid.php/username=username&hwid=获取到的hwid
常见的hwid返回
0 = 错误的hwid
2 = 没有设置hwid 则会自动上传获取到的hwid
1 = 正确的hwid
3 = hwid set
4 = Else errors
//2  Hwid = 空   "0"; // Wrong //错误  "1"; // Correct//正确   "3"; // HWID Set 设置hwid    echo "4"; // Else errors 其他错误 


//账号密码检查
 如果他填写的账号密码是正确的则返回success否则是返回一个空白
 示例:
 正确的账号密码: https://neverhit.club/info.php?username=Modica&password=qzh123123   
 错误的账号密码: https://neverhit.club/info.php?username=username&password=password
用到的接口是:https://neverhit.club/info.php?username=username&password=password


//到期时间获取
name.nameValue建议加密 Name.nameValue = username
这边用到的接口是: https://neverhit.club/info.php/?username=name.nameValue&expire

//uid获取接口
需要的接口 &uid
这边用到的接口是: https://neverhit.club/info.php/?username=Modica&uid


//用户头像获取接口 
获取头像之前先要获取uid
前置获取 用户uid
直接获取头像这边用到的接口是: https://NeverHit.club/data/avatars/l/0/uid.jpg
获取头像连接的接口是: https://NeverHit.club/info.php/?username=Modica&avatar


//用户个人资料获取
需要前置 获取uid
这边用到的接口是: https://NeverHit.club/members/modica.1/


//info Get
这边用到的接口是: https://NeverHit.club/info.php/?info
用来获取更新内容以及修改日志 目前已知问题\n转行失效

//download.php 接口

在请求dll时需要发送key来获取dll

不需要这个！！！！！！！
```

Faced with this situation, he had to admit that he pasted this "legit" himself when russki did not respond for a long time, and this statement was also confirmed by @Moxxie, because he drew the interface for heverhit, which is also The only decent thing about heverhit is that it wasn't made by Modica or any "russki".
![IMG_20240124_001503_907](https://github.com/South-Haruna-Institute-of-Technology/nightx_shit/assets/65479796/63e21608-7652-463f-a1c9-5826dd31287c)


![IMG_20240123_230148_821](https://github.com/South-Haruna-Institute-of-Technology/nightx_shit/assets/65479796/81e69957-c35c-4bff-8671-3bd7824a1538)
is that russki really exists?idk

BUT it is said that he also implanted a virus in the loader😂
![Image_1706022597636](https://github.com/South-Haruna-Institute-of-Technology/nightx_shit/assets/65479796/d80b322f-6ef8-4ce3-81eb-f5e02ca0af25)
rESpeCt to la b1G hEcKeR🤡

## continue act the scam
So how does our Mr. Liu give an explanation to his customers? He made a fork like this in his GitHub organization
![Screenshot_2024-01-18-16-27-07-684_com android chrome](https://github.com/South-Haruna-Institute-of-Technology/nightx_shit/assets/65479796/9f2781cb-6bdf-498b-8cd2-bc790f75138f)
![Screenshot_2024-01-18-16-27-38-092_com android chrome](https://github.com/South-Haruna-Institute-of-Technology/nightx_shit/assets/65479796/70ca070b-932d-42c0-8bd3-80d8a522c347)
[Webpage snapshot](https://github.com/South-Haruna-Institute-of-Technology/nightx_shit/blob/main/Funt1337_Love-me)
pasta 10/10
but M3351AN will never luvs u

Just when he had barely made any changes to this legendware pasta, he announced the following
![IMG_20240123_234953_070](https://github.com/South-Haruna-Institute-of-Technology/nightx_shit/assets/65479796/c38c2414-ef8b-4d6a-ada1-7224cbf48910)
But at the same time, poor M3351AN, whose feelings were deceived by him.
![Screenshot_2024-01-24-01-03-58-210_com tencent mobileqq-edit](https://github.com/South-Haruna-Institute-of-Technology/nightx_shit/assets/65479796/9ff91499-a6c5-46a9-a495-697dcf4c1330)

At the same time, M3351AN, as a member of neverhit’s assisting developers at that time, endorsed neverhit, is falling into a crisis of publicity🥲
![IMG_20240123_235421_724](https://github.com/South-Haruna-Institute-of-Technology/nightx_shit/assets/65479796/0ae7d58b-3ed6-4f3b-925d-dca344c44d94)

## waifu?
![IMG_20240124_002922_546](https://github.com/South-Haruna-Institute-of-Technology/nightx_shit/assets/65479796/5639ab9f-c5fb-4391-a92b-6fca5fb47f69)
But when M3351AN, who was concerned about him, called 110, the policeman said that he had not found out that Mr. Liu had a wife, let alone any medical records.🤡

## mone¥?
As we all know, the invitation codes & subscription sold by this scam project brought Mr. Liu a considerable amount of income, but where did the money go in the end? we also want to know 

The administrator of hvhbbs conducted voluntary publicity for Mr. Liu's scam project Neverhit out of consideration for the forum's popularity and reputation, but what was the result? Mr. Liu’s scam has had a huge negative impact on the reputation of the forum. 

M3351AN was persuaded to join neverhit's team after cracking neverhit(at that time, M3351AN was not staff member of hvhbbs yet), but Mr. Liu did not give him any compensation, not even protection money. 

Moxxie made the interface for Neverhit almost for free, but the remuneration he deserved has not yet arrived. Mr. Liu said about this, "That russki asked for too much money, and I don't have the money to pay for the time being." 

But as mentioned before, as for who that Russki is and whether he only exists in Mr. Liu’s lies, it is still the biggest unsolved mystery of this century.
