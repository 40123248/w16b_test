# 建立分組協同報告

gitbook 與 github 倉儲的資料同步設定

* 先建立一個 github 上的 repository
* 在 gitbook 建立一本電子書專案
* 在 gitbook 中的 account setting 中設定與此電子書對應的 github 帳號
* 在電子書的設定中, 選擇 github, 並將 github 的倉儲 URL 填入設定位置
* 一旦同步設定完成生效後, 在 gitbook 中編輯存檔後, github 上的對應倉儲將同步更新
* 若選擇在 github 的電子書對應倉儲中更新資料, 內容是否會同步更新到 gitbook? 答案是: 會, 但是更新必須間隔一段時間後重新載入後才能同步
* 所以這裡的協同內容管理, 將可從 gitbook 的 collaborator 設定協同者 (只要發電子郵件給使用者即可), 或者從 github 中增加 collaborators

