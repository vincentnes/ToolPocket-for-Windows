# ToolPocket for Windows 工具口袋

輕量、免安裝的 Windows 小工具集。像手機資料夾一樣整理你的程式，外加桌面便利貼與待辦清單。

> **[⬇ 下載最新版本](../../releases/latest)**　·　Windows 10 / 11　·　免費　·　不連網、不收集資料

<!-- 截圖：把圖片拖進 GitHub 的編輯器上傳後，替換下面這行 -->
<!-- ![screenshot](docs/screenshot.png) -->

## 特色

### 📁 工具口袋（主程式）
- **像手機資料夾一樣分類**：新增資料夾就像在檔案總管按「新增資料夾」一樣簡單，直接輸入名稱。
- **拖曳就能加入**：程式、捷徑、檔案、資料夾，甚至開始功能表裡的程式捷徑，拖進來就好；也能從清單挑選已安裝的程式。
- **放到桌面**：每個資料夾都能變成桌面上的一個圖示（會顯示裡面的程式縮圖），雙擊直接打開。
- **零常駐**：每個資料夾是獨立視窗，可同時開多個；關掉就完全結束，不佔記憶體、不佔 CPU。
- 開機自動開啟、以系統管理員執行、資料夾顏色、檔案總管式快速鍵（F2、Del、Alt+↑…）。

### 📝 便利貼
- 多張便利貼、可設定標題、7 種顏色、永遠在最上層、透明度。
- 自動儲存並保留備份；網址可點擊；貼上時自動轉純文字。
- 系統匣一鍵顯示／隱藏全部便利貼。

### ✅ 待辦事項
- 便利貼外觀的待辦清單：輸入後按 Enter 新增，貼上多行一次加入多項。
- 勾選核取方塊劃掉（再按一次取消），自動寫入完成紀錄（CSV，可用 Excel 開啟）；小垃圾桶一鍵刪除，Ctrl+Z 可復原。
- 已完成清單可搜尋，一鍵加回待辦清單。
- 拖曳即可上下排序；關閉視窗就結束，不常駐。

### 🌐 介面語言
繁體中文、简体中文、English，預設依 Windows 語言自動切換，也可在選單中手動選擇。

## English

**ToolPocket for Windows** is a small, portable toolkit for Windows 10/11 (no installation; it uses the built-in .NET Framework 4):
a phone-style **launcher** (group programs into folders, put folders on the desktop, no background processes),
**Sticky Notes**, and a sticky-note style **To-Do** list with a completion log. The interface is available in
English, Traditional Chinese and Simplified Chinese. Download the zip from **[Releases](../../releases/latest)**,
unzip it anywhere and run `ToolPocket.exe`.

## 安裝與使用

1. 到 **[Releases](../../releases/latest)** 下載 `ToolPocket-vX.Y.Z.zip`。
2. 解壓縮到任何資料夾（建議不要放在 Program Files）。
3. 執行 `ToolPocket.exe`。

不需要安裝任何執行環境：程式使用 Windows 10/11 內建的 .NET Framework 4。

### 看到「Windows 已保護您的電腦」？
這是因為本程式沒有購買程式碼簽章憑證。請按 **其他資訊 → 仍要執行**。
你可以用 Release 頁面提供的 SHA256 值核對下載的檔案是否完整：

```
certutil -hashfile ToolPocket-vX.Y.Z.zip SHA256
```

## 常見問題

**資料存在哪裡？**　跟程式放在一起（`folders\`、`tools\data\`），整個資料夾搬走或備份即可。若放在沒有寫入權限的位置，會改存到 `%APPDATA%\ToolsForWindows`。

**怎麼更新？**　結束所有工具後，用新版覆蓋舊的 exe，資料會保留。

**為什麼開始功能表裡有些 App 拖不進來？**　Microsoft Store 的 App 沒有一般的捷徑檔。請改用「新增捷徑 → 從開始功能表加入…」，或拖曳它在桌面上的捷徑。

## 意見回饋

歡迎到 [Issues](../../issues) 回報問題或提出建議。

## 授權

免費軟體，可免費用於個人及商業用途，也可以分享官方原版壓縮檔；原始碼不公開。詳見 [LICENSE.txt](LICENSE.txt)。
