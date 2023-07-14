# Discord Bot設定教學

[**初次設定(創建Discord Bot)**](Tutorial_Discord_Bot.md#step1)

[**邀請已建立的Bot進入伺服器**](Tutorial_Discord_Bot.md#step5)

## Step1.

進入網站 <https://discord.com/developers/applications> 並登入

## Step2.

點擊右上方`New Application`按鈕

輸入DC BOT的名字(自行創建)

設定頭貼並儲存

## Step3.

點選網頁左方的Bot頁籤

網頁滾動至下方，找到`Privileged Gateway Intents`標題

將第二`SERVER MEMBERS INTENT`及第三個選項`MESSAGE CONTENT INTENT`開啟

<img src="https://github.com/ddddo86/mcfallout_ddddoBOT_client/blob/main/docs/pic/discord_bot_step3.jpg"  width="60%" height="30%">

回到該頁上方頭貼右方，點擊`Reset Token`

<img src="https://github.com/ddddo86/mcfallout_ddddoBOT_client/blob/main/docs/pic/discord_bot_reset_token.jpg"  width="60%" height="30%">

點擊Copy並將它貼在`setting.toml`的`token`中

**注意! 請勿將Token外流，否則他人將能夠隨意控制您的DC BOT**

## Step4.(開啟開發者模式)

開啟Discord開發者模式(使用者設定-應用程式設定-進階-開發者模式)

<img src="https://github.com/ddddo86/mcfallout_ddddoBOT_client/blob/main/docs/pic/discord_bot_api.jpg"  width="60%" height="30%">

## Step5.

回到網頁，點擊左方`OAuth2`並進入`URL Generator`頁籤

<img src="https://github.com/ddddo86/mcfallout_ddddoBOT_client/blob/main/docs/pic/discord_bot_url.jpg"  width="30%" height="15%">

勾選`bot`選項，再勾選下方的`Administrator`選項

<img src="https://github.com/ddddo86/mcfallout_ddddoBOT_client/blob/main/docs/pic/discord_bot_access.jpg"  width="60%" height="30%">

網頁滾動至底部，複製下方網址並連線至網頁

將Bot加入抽獎城DC群中

<img src="https://github.com/ddddo86/mcfallout_ddddoBOT_client/blob/main/docs/pic/discord_bot_add.jpg"  width="30%" height="15%">
