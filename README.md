# 『撞球教學網頁』
操作步驟：
process:

0.請幫我建立D槽的資料夾名為Agile01
1.輸入:
  原始需求（給 AI）：
「請教我產生一個『撞球教學網頁』的提示詞，要有擊球、進球的角度示範。」

2.複製提示詞
提供按鈕：「重置球位」、「隨機球位」。

教學輔助線（這是最重要的）：

假想球（Ghost Ball）：當瞄準線對準子球時，顯示子球進袋前，母球應該撞擊的理想位置（用半透明虛線圓圈表示）。

進球路線：顯示子球被撞擊後的預測路徑。

分離角（Tangent Line）：顯示撞擊後，母球會往哪個方向彈開（90度分離角原理）。

物理模擬：

實現基礎的 2D 碰撞物理（動量守恆）。

模擬摩擦力，讓球會慢慢停下來。

邊緣反彈。

技術限制：使用 Tailwind CSS 進行 UI 排版，所有程式碼（HTML, CSS, JS）整合在一個檔案中。

3.輸入：優化擊球UX交互體驗
4.輸入：出現這畫面，按滑鼠左鍵就可以擊球

5.完成後,輸入:幫我同步到github
 回答:
我已經幫你 安裝了 Git，並且在你的 Agile01 資料夾中 初始化了本地的 Git 儲存庫（Repository）！

因為這是你第一次在這個環境使用 Git 同步到 GitHub，我們還需要幾個步驟來完成設定。請告訴我以下資訊：

GitHub 儲存庫網址：你是否已經在 GitHub 上建立了一個新的（且空白的）儲存庫？

如果有，請將網址貼給我（例如：https://github.com/你的帳號/你的專案.git）。
如果還沒，請先到 GitHub 建立一個新的儲存庫，然後再將網址給我。
設定 Git 帳號：因為 Git 是剛剛安裝的，我們需要填寫你的名字與 Email（這會顯示在 commit 紀錄上）。請告訴我你想設定的：

使用者名稱（Username）
Email

6.輸入：
1.https://github.com/breezeChen267/Agile01.git
2.Email: lovelysmc06@gmail.com; username:breezechen267

回答:
太棒了！你的程式碼已經成功同步到 GitHub 上了 🎉。

我已經幫你完成了以下步驟：

設定了 Git 帳號（使用者：breezechen267，信箱：lovelysmc06@gmail.com）。
追蹤了所有檔案 並進行了首次提交（Commit）。
將主要分支設定為 main。
將本地程式碼成功推播（Push） 到了你提供的 GitHub 儲存庫 https://github.com/breezeChen267/Agile01.git。
你可以現在到你的 GitHub 儲存庫頁面 重新整理，應該就能看到你的程式碼（包含 billiards.html 等檔案）已經上傳囉！如果後續還有修改，只要再重複 Commit 和 Push 的動作就可以更新上去。

請確認一下 GitHub 上是否有看到檔案，如果有任何問題隨時跟我說！

