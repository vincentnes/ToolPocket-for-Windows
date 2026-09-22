# ToolPocket for Windows 工具口袋

輕量、免安裝的 Windows 小工具集。像手機資料夾一樣整理你的程式，外加桌面便利貼與待辦清單。
A lightweight, portable toolkit for Windows. Organize your programs like folders on a phone, plus desktop sticky notes and a to-do list.

> **[⬇ 下載最新版本 / Download the latest release](../../releases/latest)**
> Windows 10 / 11　·　免費 Free　·　不連網、不收集資料 / No internet, no data collection

<!-- 截圖 / Screenshot：把圖片拖進 GitHub 的編輯器上傳後，替換下面這行 -->
<!-- ![screenshot](docs/screenshot.png) -->

## 特色 / Features

### 📁 工具口袋（主程式） / ToolPocket (launcher)
- **像手機資料夾一樣分類**：新增資料夾就像在檔案總管按「新增資料夾」一樣簡單，直接輸入名稱。
  **Phone-style folders**: create a folder as easily as in File Explorer and type its name right away.
- **拖曳就能加入**：程式、捷徑、檔案、資料夾，甚至開始功能表裡的程式捷徑，拖進來就好；也能從清單挑選已安裝的程式。
  **Drag and drop**: programs, shortcuts, files, folders and Start menu shortcuts; or pick installed programs from a list.
- **放到桌面**：每個資料夾都能變成桌面上的一個圖示（會顯示裡面的程式縮圖），雙擊直接打開。
  **Put on desktop**: any folder can become a desktop icon (showing thumbnails of its contents); double-click to open it.
- **零常駐**：每個資料夾是獨立視窗，可同時開多個；關掉就完全結束，不佔記憶體、不佔 CPU。
  **Nothing runs in the background**: each folder is its own window; close it and it uses no memory or CPU.
- 開機自動開啟、以系統管理員執行、資料夾顏色、檔案總管式快速鍵（F2、Del、Alt+↑…）。
  Open at startup, run as administrator, folder colors, File Explorer-style shortcuts (F2, Del, Alt+↑…).

### 📝 便利貼 / Sticky Notes
- 多張便利貼、可設定標題、7 種顏色、永遠在最上層、透明度。
  Multiple notes with titles, 7 colors, always-on-top and adjustable opacity.
- 自動儲存並保留備份；網址可點擊；貼上時自動轉純文字。
  Auto-save with backup; clickable links; pasted text becomes plain text.
- 系統匣一鍵顯示／隱藏全部便利貼。
  Show or hide all notes with one click on the tray icon.

### ✅ 待辦事項 / To-Do
- 便利貼外觀的待辦清單：輸入後按 Enter 新增，貼上多行一次加入多項。
  A sticky-note style to-do list: type and press Enter; paste several lines to add several tasks.
- 勾選核取方塊劃掉（再按一次取消），自動寫入完成紀錄（CSV，可用 Excel 開啟）；小垃圾桶一鍵刪除，Ctrl+Z 可復原。
  Check a task to cross it out (click again to undo); every change goes to a completion log (CSV, opens in Excel). Delete with the trash icon, undo with Ctrl+Z.
- 已完成清單可搜尋，一鍵加回待辦清單。
  Search completed tasks and put them back on the list with one click.
- 拖曳即可上下排序；關閉視窗就結束，不常駐。
  Drag to reorder; closing the window exits the program.

### 🌐 介面語言 / Languages
繁體中文、简体中文、English，預設依 Windows 語言自動切換，也可在選單中手動選擇。
Traditional Chinese, Simplified Chinese and English. Follows your Windows language by default, or choose one from the menu.

## 安裝與使用 / Installation

1. 到 **[Releases](../../releases/latest)** 下載 `ToolPocket-vX.Y.Z.zip`。
   Download `ToolPocket-vX.Y.Z.zip` from **[Releases](../../releases/latest)**.
2. 解壓縮到任何資料夾（建議不要放在 Program Files）。
   Unzip it to any folder (preferably not Program Files).
3. 執行 `ToolPocket.exe`。
   Run `ToolPocket.exe`.

不需要安裝任何執行環境：程式使用 Windows 10/11 內建的 .NET Framework 4。
Nothing else to install: it uses the .NET Framework 4 built into Windows 10/11.

### 看到「Windows 已保護您的電腦」？ / Seeing "Windows protected your PC"?
這是因為本程式沒有購買程式碼簽章憑證。請按 **其他資訊 → 仍要執行**。
The program isn't code-signed yet. Click **More info → Run anyway**.

你可以用 Release 頁面提供的 SHA256 值核對下載的檔案是否完整：
You can check the download against the SHA256 value on the release page:

```
certutil -hashfile ToolPocket-vX.Y.Z.zip SHA256
```

## 常見問題 / FAQ

**資料存在哪裡？ / Where is my data stored?**
跟程式放在一起（`folders\`、`tools\data\`），整個資料夾搬走或備份即可。若放在沒有寫入權限的位置，會改存到 `%APPDATA%\ToolsForWindows`。
Next to the program (`folders\`, `tools\data\`), so you can move or back up the whole folder. If that location isn't writable, data goes to `%APPDATA%\ToolsForWindows`.

**怎麼更新？ / How do I update?**
結束所有工具後，用新版覆蓋舊的 exe，資料會保留。
Close all the tools, then overwrite the old exe files with the new ones. Your data is kept.

**為什麼開始功能表裡有些 App 拖不進來？ / Why can't I drag some Start menu apps in?**
Microsoft Store 的 App 沒有一般的捷徑檔。請改用「新增捷徑 → 從開始功能表加入…」，或拖曳它在桌面上的捷徑。
Microsoft Store apps don't have regular shortcut files. Use "Add shortcut → Add from Start menu…" instead, or drag their desktop shortcut.

## 意見回饋 / Feedback

歡迎到 [Issues](../../issues) 回報問題或提出建議。
Bug reports and suggestions are welcome in [Issues](../../issues).

## 授權 / License

免費軟體，可免費用於個人及商業用途，也可以分享官方原版壓縮檔；原始碼不公開。詳見 [LICENSE.txt](LICENSE.txt)。
Freeware: free for personal and commercial use, and you may share the official unmodified zip. The source code is not published. See [LICENSE.txt](LICENSE.txt).
