# 設定教學
[**初次使用**]<#-Step1.>

[**Discord Bot設定**]<>

## Step1.
請先至[**連結**]<https://github.com/ddddo86/mcfallout_ddddoBOT_client/releases>下載最新版本執行檔及相應版本`user_setting.zip`

(不需下載Source Code)

![image](https://github.com/ddddo86/mcfallout_ddddoBOT_client/blob/main/docs/pic/Release_Download.jpg)

## Step2.
將兩個壓縮檔分別解壓縮，並創建一個資料夾後，分別將`.exe`及`user_setting`資料夾放入

![image](https://github.com/ddddo86/mcfallout_ddddoBOT_client/blob/main/docs/pic/folder.jpg)

## Step3.
開啟user_setting資料夾內的`user_setting.toml`

若電腦中無程式編譯軟體可使用記事本開啟

```toml
[config]
    username = 'username'
    ip = 'mcfallout.net'
[settings]
    whitelist = ["username"]
    publicity = false
    publicity_content = ["123",'test']
    interval = 605000
    log = true
[gamble]
    emerald_range = [0,1000]
    coin_range = [0,10]
    odds = 1.85
    protect_odds = 2
    redstone_position = [0,60,0]
    check_position = [0,59,3]
    itemId = [179,194]

[discord_setting]
    discord_bot = true
    token = "abc123456789123456789"
    guildID = '123456789123456789'
    bot_status = true
    bot_status_channel_name = '狀態'
    message_log = true
    only_claim = true
    message_log_channel_name = '訊息'
    betting_log = true
    betting_log_channel_name = '下注狀態'
    notice_log = true
    notice_log_channel_name = '通知'
```

