# 設定教學

[**Discord Bot設定**](Tutorial_Discord_Bot.md)

## Step1.
請先至[**連結**](https://github.com/ddddo86/mcfallout_ddddoBOT_client/releases)下載最新版本執行檔及相應版本`user_setting.zip`

(不需下載Source Code)

![image](https://github.com/ddddo86/mcfallout_ddddoBOT_client/blob/main/docs/pic/Release_Download.jpg)

## Step2.
將兩個壓縮檔分別解壓縮，並創建一個資料夾後，分別將`.exe`及`user_setting`資料夾放入

![image](https://github.com/ddddo86/mcfallout_ddddoBOT_client/blob/main/docs/pic/folder.jpg)

## Step3.
設定Discord Bot

[點擊連結前往教學頁面](Tutorial_Discord_Bot.md)

## Step4.
開啟user_setting資料夾內的`user_setting.toml`

若電腦中無程式編譯軟體可使用記事本開啟

填入說明如下

```toml
[config]
    username = 'username'                     #填入bot的id或是隨意代號
    ip = 'mcfallout.net'
[settings]
    whitelist = ["username1","username2"]     #填入白名單id，若多人需用逗號分隔
    publicity = false                         #是否開啟宣傳
    publicity_content = ["%123","$test"]      #宣傳內容
    interval = 605000                         #每次宣傳的間隔時間，單位為毫秒
    log = true                                #是否將交易內容存至本地( 位置: bot資料夾/logs/日期.txt )
[gamble]
    emerald_range = [0,1000]                  #綠寶石下注範圍 [下限,上限]
    coin_range = [0,10]                       #村民錠下注範圍 [下限,上限]
    odds = 1.85                               #賠率
    protect_odds = 2                          #破產保護倍數 ( 若 下注金額*破產保護倍數 > 餘額 => 退款 )
    redstone_position = [0,60,0]              #紅石粉座標
    check_position = [0,59,3]                 #漏斗上方空氣座標
    itemId = [179,194]                        #輸贏物品id [ 中獎,未中獎 ] (預設為黑白羊毛)

[discord_setting]
    discord_bot = true                        #是否開啟Discord Bot (使用額外功能務必開啟)
    token = "abc123456789123456789"           #DC Bot的token，詳情請參考#Discord bot Setting   注意! 請勿將此token透漏給不信任的人，否則你的discord bot將有被盜用的風險
    guildID = '123456789123456789'            #DC伺服器的ID，開啟開發者模式後對DC頭像按右鍵即可取得伺服器ID
    bot_status = true                         #狀態頁是否開啟
    bot_status_channel_name = '狀態'          #狀態頁頻道名稱 (可自訂但需與DC群內頻道相符)
    message_log = true                        #訊息頁是否開啟
    only_claim = true                         #僅顯示[系統] [領地] [附近] 訊息
    message_log_channel_name = '訊息'         #訊息頁頻道名稱 (可自訂但需與DC群內頻道相符)
    betting_log = true                        #金流頁是否開啟，內容包括下注輸贏、簽到、領錢
    betting_log_channel_name = '下注狀態'     #金流頁頻道名稱 (可自訂但需與DC群內頻道相符)
    notice_log = true                         #通知頁是否開啟，內容包括轉帳錯誤訊息及DC綁定訊息
    notice_log_channel_name = '通知'          #通知頁頻道名稱 (可自訂但需與DC群內頻道相符)
```

[如何開啟開發者模式](Tutorial_Discord_Bot.md#step4-開啟開發者模式)

## Step5. (無額外功能者可直接[跳過](#Step6))

開啟user_setting資料夾內的`extra_setting.toml`

若電腦中無程式編譯軟體可使用記事本開啟

填入說明如下

```toml
[dc_role_id]
    LINKED = '123456789123456789'                       #目前不可用
[role]
    daily_role = [       
        ['最高身分組','&d最高身分組','300000'],          #須按照身分組地位高低，由高到低排列
        ['次高身分組','&a次高身分組','200000'],          #格式為 [ dc身分組名稱 , minecraft顯示名字(可自行更換色碼) , 每日簽到金額 ]  (dc身分組名稱需完全相符，包含表情符號)
        ['第三身分組','&b第三身分組','100000']           #每新增一個身分組記得要加一個逗號
    ]
[setting]
    default_close = false                               #簽到功能是否預設為關閉 ( false = 24小時開啟 ，true則是需要輸入指令開啟 )
```

## Step6.

確認設定檔格式無誤即可雙擊exe檔執行

若仍無法正確執行請參考[常見問題](常見問題Support.md)