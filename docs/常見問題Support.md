# 常見問題

請優先參考此頁面進行問題排解，若無效再聯繫DC: ddddo#0549

## 我的Bot沒辦法正常使用

無法正常使用的狀況分為3種

[小黑窗消失](#小黑窗消失)

[小黑窗還在，但顯示斷線或其他畫面](#顯示斷線或其他訊息)

[小黑窗都正常，但Bot沒反應](#Bot沒反應)

## 小黑窗消失

可能的錯誤

- Microsoft驗證問題，請嘗試重新開啟。若仍舊無法使用，請往下方原因繼續排錯

- 設定檔在錯誤的位置，請參考 [這裡](Tutorial_Setting.md#step2)

- 設定檔格式錯誤，請檢查該有的逗號、括號、引號 皆有補上

- 程式錯誤，請將問題回報至DC

以上問題可使用PowerShell執行來了解問題 [PowerShell使用方法](#如何使用powershell)

## 顯示斷線或其他訊息

請嘗試更換網路環境或更換ip

## Bot沒反應

可能的錯誤

- 座標設定錯誤

- 沒有給Bot建造(tt)權限

- 沒有簽屬頻道規章同意書

- 程式問題，請蒐集相關截圖回報至DC

- 其他

## 如何使用PowerShell

點擊電腦搜尋欄位，搜尋`PowerShell`

![image](https://github.com/ddddo86/mcfallout_ddddoBOT_client/blob/main/docs/pic/powershell_open.jpg)

開啟後，回到Bot資料夾，點擊上方路徑欄位並複製路徑

![image](https://github.com/ddddo86/mcfallout_ddddoBOT_client/blob/main/docs/pic/path.jpg)

回到PowerShell，輸入`cd`空白`你的路徑`，並按下`enter`
```fix
cd [path]
```
(\[path]請更換為自己複製的路徑)

舉例
```fix
cd C:\Users\User\Desktop\BOT\mcfallout_ddddoBOT
```

輸入完成後，將exe檔拖曳至PowerShell內，點擊PowerShell視窗後再按下`enter`即可在PowerShell中執行
