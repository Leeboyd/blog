# Pokemon Tracking - 部署說明

## 檔案結構
```
deploy/
├── index.html           - 主頁面
├── pokemon_data.json    - Pokemon 資料
└── sprites/
    └── pokemon/         - Pokemon sprite 圖片
        ├── 115.png
        ├── 208.png
        └── ...
```

## 部署方式

### 1. 靜態網站主機 (推薦)
- Netlify: 拖放 deploy 資料夾
- Vercel: 拖放 deploy 資料夾
- GitHub Pages: 推送到 gh-pages 分支
- Cloudflare Pages: 拖放 deploy 資料夾

### 2. 傳統 Web Server
將 deploy 資料夾中的所有檔案上傳到您的 web server 根目錄或子目錄

### 3. 本地測試
在 deploy 資料夾中執行:
```bash
python3 -m http.server 8000
```
然後開啟 http://localhost:8000

## 注意事項
- 所有檔案都是靜態的，不需要任何後端服務
- 不需要 Node.js 或其他執行環境
- 可以直接在任何支援靜態檔案的主機上運行
