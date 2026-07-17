# piliwu-teach — AGENTS.md

## 專案入口

- 專案名稱：piliwu-teach
- 專案用途：國文教學工具與素材
- 主要工作目錄：`G:\我的雲端硬碟\piliwu-teach`
- GitHub repo：`https://github.com/piliwu01/piliwu-teach`
- 預設 branch：`main`
- 部署目標：GitHub Pages

## Obsidian 對應筆記

- Obsidian vault：`G:\我的雲端硬碟\secondbrain`
- 專案駕駛艙：`piliwu-teach/專案工作流程.md`
- 收工時優先更新：同上

> 專案駕駛艙是 Obsidian vault 裡的筆記，不是工作資料夾裡的進度檔。

## 工作桌 + 三個家

- 工作桌：`G:\我的雲端硬碟\piliwu-teach`
- GitHub：`https://github.com/piliwu01/piliwu-teach`
- Obsidian：`G:\我的雲端硬碟\secondbrain` + `piliwu-teach/專案工作流程.md`
- Firebase：使用；project ID 待建立或確認

## 同步規則

開工時：

- 使用 `startup-sync` 流程。
- 讀本檔與 Obsidian 駕駛艙。
- 檢查 Git 狀態。
- 不自動 pull、commit 或 push。

收工時：

- 使用 `shutdown-sync` 流程。
- 更新 Obsidian 駕駛艙。
- 只有規則、路徑或專案邊界改變時才更新本檔。
- 經確認後，只 commit 與 push 本次相關檔案。

新專案初始化時：

- 使用 `project-init-sync` 流程。

## 主要檔案

- 專案說明：`README.md`
- Agent 規則：`AGENTS.md`
- 忽略規則：`.gitignore`
- 網頁入口：待建立
- Firebase 設定：待建立；不得把 Admin 憑證加入 repo
- GitHub Pages：待啟用

## 不要做

- 不要把每日進度寫進 `AGENTS.md`。
- 不要自動納入無關的 Git 變更。
- 不要把 API key、token、密碼或 Firebase Admin 憑證寫進 repo。
- 不要儲存學生姓名；正式資料只使用座號與班級代號。
- Python 工具一律製作成 `tkinter GUI`，不要用命令列互動。
- 一律使用繁體中文；中文與英文／數字之間加半形空格。

