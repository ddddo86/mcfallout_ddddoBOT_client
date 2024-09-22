# 設定 config.toml

## Step1.

開啟 `config-example.toml`

若電腦中無程式編譯軟體可使用記事本開啟 (推薦的編譯軟體 [Visual Studio Code](https://code.visualstudio.com/))

填入說明如下

```toml
[Discord]
    BOT_TOKEN = 'abc123456789'  #Discord bot token，請勿將此token外流以免遭到帳號盜用
    GuildID = '0123456789876'  #DC群頭像右鍵-複製伺服器ID (需先開啟開發者模式)
[Setting]
    username = ['ddo_2j4@對賭','4d_2j4@賭花']  #botID@對賭/賭花/比大小(須完全一致)，若只有一隻請填 ['botID@對賭'] 即可
    ip = 'jp.mcfallout.net'  #輸入你喜歡的節點
    debug = true  #目前無作用

#設定完成後請將檔名改為 config.toml
```

[如何取得BOT_TOKEN](Discord_Bot.md#設定-discord-bot)

[如何取得GuildID](Discord_Bot.md#step4-取得伺服器id)

## Step2.

編輯完成後，將檔案儲存並關閉，並將檔名重新命名為`config.toml`

## Step3.

現在你已經完成所有本地設定了，確認無誤後即可開啟`index.exe`來執行檔案

(初次執行需要連線至Microsoft來進行驗證)
