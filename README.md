# 裂縫注膠補強計算 PWA

裂縫環氧樹脂（Epoxy）注膠補強工程計算工具，支援 PWA 安裝與離線使用。

## 功能特色

- 裂縫注膠工程量計算
- 材料用量估算
- 圖表視覺化
- 匯出 PDF 計算書
- **PWA 支援**：可安裝至手機桌面，離線使用

## 部署至 GitHub Pages

1. 將此資料夾所有檔案推送至 GitHub Repository
2. 進入 Repository → Settings → Pages
3. Source 選擇 `main` branch，資料夾選 `/ (root)`
4. 儲存後即可透過 `https://<username>.github.io/<repo>/` 存取

## 安裝為 PWA

- **Android**：Chrome 瀏覽器開啟網址 → 選單 → 「新增至主畫面」
- **iOS**：Safari 開啟網址 → 分享按鈕 → 「加入主畫面」
- **桌面**：Chrome 網址列右側安裝圖示

## 檔案結構

```
├── index.html        # 主程式
├── manifest.json     # PWA 設定
├── sw.js             # Service Worker（離線快取）
├── icons/            # 各尺寸 App 圖示
│   ├── icon-72.png
│   ├── icon-96.png
│   ├── icon-128.png
│   ├── icon-144.png
│   ├── icon-152.png
│   ├── icon-192.png
│   ├── icon-384.png
│   └── icon-512.png
└── README.md
```

## 技術規範依據

ACI 224.1R / CNS 3090 / 交通部橋梁設計規範
