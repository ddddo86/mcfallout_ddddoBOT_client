#Didcord Bot設定教學

[**初次設定(創建Discord Bot)**](#-Step1.)
[**邀請已建立的Bot進入伺服器**](#-Step5.)

## Step1.

進入網站 <https://discord.com/developers/applications> 並登入

## Step2.

點擊右上方`New Application`按鈕

輸入DC BOT的名字(自行創建)

設定頭貼並儲存

## Step3.

點選網頁左方的Bot頁籤

網頁滾動至下方，找到`Privileged Gateway Intents`標題

將第三個選項`(MESSAGE CONTENT INTENT)`開啟

![image](https://github.com/ddddo86/mcfallout_ddddoBOT_client/blob/main/docs/pic/discord_bot_step3.jpg)

回到該頁上方頭貼右方，點擊`Reset Token`

![image](https://github.com/ddddo86/mcfallout_ddddoBOT_client/blob/main/docs/pic/discord_bot_reset_token.jpg)

點擊Copy並將它貼在`setting.toml`的`token`中

**注意! 請勿將Token外流，否則他人將能夠隨意控制您的DC BOT**

## Step4. (開啟開發者模式)

開啟Discord開發者模式(使用者設定-應用程式設定-進階-開發者模式)

![image](https://github.com/ddddo86/mcfallout_ddddoBOT_client/blob/main/docs/pic/discord_bot_api.jpg)

## Step5.

回到網頁，點擊左方`OAuth2`並進入`URL Generator`頁籤

![image](https://github.com/ddddo86/mcfallout_ddddoBOT_client/blob/main/docs/pic/discord_bot_url.jpg) 

勾選`bot`選項，再勾選下方的`Administrator`選項

![image](https://github.com/ddddo86/mcfallout_ddddoBOT_client/blob/main/docs/pic/discord_bot_access.jpg)

網頁滾動至底部，複製下方網址並連線至網頁

將Bot加入抽獎城DC群中

![image](https://github.com/ddddo86/mcfallout_ddddoBOT_client/blob/main/docs/pic/discord_bot_add.jpg)
