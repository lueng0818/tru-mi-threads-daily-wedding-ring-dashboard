# Tru-Mi Threads 婚戒海巡儀表板

這個 repo 用來發布 Tru-Mi Threads 婚戒海巡儀表板。

GitHub Pages 網址：

https://lueng0818.github.io/tru-mi-threads-daily-wedding-ring-dashboard/

主要檔案：

- `index.html`：GitHub Pages 顯示用首頁
- `threads_wedding_ring_dashboard.html`：本機同步主檔

每日排程更新後，兩個 HTML 檔案會保持完全一致，並推送到 `main` 分支。推送完成後，GitHub Actions 會自動部署到 GitHub Pages。

每日 09:00 的 Codex 自動化會在更新儀表板後提交並推送到此 repo；若 GitHub 憑證失效，會保留本機提交並回報需重新登入。

若自動推送失敗，使用手動上傳頁覆蓋 `index.html`：

https://github.com/lueng0818/tru-mi-threads-daily-wedding-ring-dashboard/upload/main

## 第一次啟用 GitHub Pages

在 GitHub repo 進入 `Settings` → `Pages`，設定：

- Source：`Deploy from a branch`
- Branch：`main`
- Folder：`/root`

儲存後，網站會使用根目錄的 `index.html` 呈現。

## Global Colors

- Border Line：`#38761D`
- 主要：`#274E13`
- 次要：`#2F7652`
- 文字：`#443F3F`
- 摘要：`#E2B357`
- Background：`#F9F8F3`
- Surface White：`#FDFDFC`
- Hover Green：`#274E13`
