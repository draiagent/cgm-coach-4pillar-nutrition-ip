# GitHub 上傳說明

## 儲存庫資訊

名稱：`cgm-coach-4pillar-nutrition-ip`

About 描述：酵蛋纖菌™｜CGM Coach 每日營養四柱：Enzyme、Protein、Fiber、Probiotics。整合 A → A+ → S 的品牌框架、概念視覺與商標準備資料。

Topics：`cgm-coach`、`nutrition-framework`、`brand-assets`、`health-education`、`traditional-chinese`

## 網頁上傳

1. 解壓縮本檔案。
2. 在自己的 GitHub 帳號或組織建立上述名稱的空白 repository。
3. 選擇所需公開範圍；建立時不必額外產生 README 或授權檔。
4. 使用「uploading an existing file」或 Add file → Upload files。
5. 上傳解壓後專案資料夾**內的內容**，讓 README.md 位於 repository 根目錄；不是只上傳 ZIP。
6. 提交訊息可填 `docs: publish four-pillar nutrition IP v1.0.0`。
7. 確認 README 三張圖可顯示，文件連結與 Word 下載正常。

本包單一檔案均小於網頁上傳的25 MiB限制。若檔案選擇器未顯示 .gitignore，可用 GitHub Desktop 或命令列上傳全部內容。

## 命令列（空白遠端儲存庫）

先把 YOUR-OWNER 替換為自己的帳號或組織名稱，並完成 GitHub 登入：

```bash
cd cgm-coach-4pillar-nutrition-ip
git init
git add .
git commit -m "docs: publish four-pillar nutrition IP v1.0.0"
git branch -M main
git remote add origin https://github.com/YOUR-OWNER/cgm-coach-4pillar-nutrition-ip.git
git push -u origin main
```

若遠端已有內容，先 clone，再把本包檔案複製進去提交；不要強制覆寫遠端。

## 發布狀態

本交付是可上傳專案包，尚未代為建立或推送任何 GitHub 遠端儲存庫。授權採保留權利方式，不應在建立 repository 時自行套用 MIT 等開源授權。

官方說明：https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository
