# Discord Bot 設定教學

| Link | Description |
|---|---|
| [Step1.](Discord_Bot.md#step1-建立一個-discord-bot) | 建立一個 Discord bot |
| [Step2.](Discord_Bot.md#step2-邀請-discord-bot-至-discord-伺服器) | 邀請 Discord bot 至 Discord 伺服器 |
| [Step3.](Discord_Bot.md#step3-開啟-discord-開發者模式) | 開啟 Discord 開發者模式 |
| [Step4.](Discord_Bot.md#step4-取得伺服器id) | 取得伺服器id |

## Step1. 建立一個 Discord bot

### 登入至 Discord Developers Portal

點擊網址 <https://discord.com/developers/applications> 並登入

### 建立一個 Discord bot

點擊網頁右上方`New Application`按鈕

設定 DC Bot 的名字(自行創建，之後可修改)

設定頭像並按下網頁下方 `Save Changes` 儲存

### 設定 Discord bot

點選網頁左方的 `Bot` 頁籤

網頁滾動至下方，找到 `Privileged Gateway Intents` 標題

將第二 `SERVER MEMBERS INTENT` 及第三個選項 `MESSAGE CONTENT INTENT` 開啟

<img src="https://github.com/ddddo86/mcfallout_ddddoBOT_client/blob/main/docs/pic/discord_bot_step3.jpg"  width="60%" height="30%">

回到該頁上方頭貼右方，點擊 `Reset Token`

<img src="https://github.com/ddddo86/mcfallout_ddddoBOT_client/blob/main/docs/pic/discord_bot_reset_token.jpg"  width="60%" height="30%">

點擊 `Copy` 並將它暫時貼上於空白記事本中

**注意! 請勿將Token外流，否則他人將能夠隨意控制您的DC BOT**

## Step2. 邀請 Discord bot 至 Discord 伺服器

點選網頁左方的 `OAuth2` 頁籤

找到標題為 `OAuth2 URL Generator` 的區塊

勾選 `bot` 選項，再勾選下方的 `Administrator` 選項

<img src="https://github.com/ddddo86/mcfallout_ddddoBOT_client/blob/main/docs/pic/discord_bot_access.jpg"  width="60%" height="30%">

網頁滾動至底部，複製下方網址並連線至網頁

將Bot加入抽獎城DC群中

<img src="https://github.com/ddddo86/mcfallout_ddddoBOT_client/blob/main/docs/pic/discord_bot_add.jpg"  width="30%" height="15%">

## Step3. 開啟 Discord 開發者模式

回到 Discord ，依序點選 `使用者設定` - `進階` - `開發者模式`

<img src="https://github.com/ddddo86/mcfallout_ddddoBOT_client/blob/main/docs/pic/discord_bot_api.jpg"  width="60%" height="30%">

## Step4. 取得伺服器ID

開啟開發者模式後，右鍵抽獎城Discord伺服器，點選`複製伺服器ID`

將伺服器ID暫時貼上於剛剛建立的空白記事本中