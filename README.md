# Pokemon Tracking App

個人 Pokemon 收集追蹤工具，用於管理 Pokemon GO 和 Pokemon HOME 之間的收集進度。

## 功能特色

- 📱 **跨裝置同步**: 透過 GitHub API 實現資料同步
- 📦 **歸檔系統**: 將已完成的 Pokemon 歸檔管理
- 🔍 **多重篩選**: 依照不同條件快速篩選 Pokemon
- 🎴 **雙視圖模式**: 列表檢視與網格檢視切換
- 🌐 **離線優先**: 支援本地資料，可選擇性使用 GitHub 同步

## 技術架構

- **前端**: 純 HTML/CSS/JavaScript（無框架）
- **資料儲存**: JSON 檔案
- **同步方式**: GitHub API + Personal Access Token
- **部署**: GitHub Pages
- **圖片資源**: PokeAPI sprites

## 檔案結構
```
deploy/
├── index.html            - 主頁面
├── pokemon_data.json     - Pokemon 資料
├── archived.html         - 已歸檔 Pokemon 頁面
├── pokemon_archived.json - 已歸檔 Pokemon 資料
└── sprites/
    └── pokemon/         - Pokemon sprite 圖示資源
        ├── 115.png
        ├── 208.png
        └── ...
```

## 使用方式

1. 開啟應用後，點擊 ⚙️ 設定 GitHub Token（可選）
2. 使用篩選按鈕查看不同類別的 Pokemon
3. 點擊 ✅ 按鈕標記捕捉狀態
4. 點擊 📦 按鈕將完成的 Pokemon 歸檔
5. 所有變更會自動同步到 GitHub（如有設定 Token）

---

**Live Demo**: https://leeboyd.github.io/blog/
