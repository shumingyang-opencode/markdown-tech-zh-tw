# Markdown 繁體中文教學站

把 Markdown 從核心語法、GitHub Flavored Markdown，到整個生態系（GitHub、靜態網站、Obsidian、Mermaid）做成**中英對照**的分層教學。

- 目標讀者：初階工程師 / 學生
- 單元數：8 單元
- 授權：本站內容 CC-BY-4.0
- 網站：[https://shumingyang-opencode.github.io/markdown-tech-zh-tw/](https://shumingyang-opencode.github.io/markdown-tech-zh-tw/)

## 網站結構

```
markdown-tech-zh-tw/
├── index.html            # 課程總覽 + 入口卡片
├── map.html              # 概念地圖：Markdown 語法總覽圖
├── learning-path.html    # 學習路線：L0 → L4 分層
├── about.html            # 關於本站
├── docs/                 # 單元教學頁
│   ├── index.html        # 單元一覽
│   ├── unit-01-*.html    # …共 8 篇
├── assets/site.css       # 單一共享樣式
└── .nojekyll
```

## 單元列表

| # | 單元 | 內容 |
|---|------|------|
| 01 | Markdown 是什麼 | 與 HTML 的關係、應用場景、編輯器 |
| 02 | 基礎語法 | 標題、粗體斜體、段落、清單 |
| 03 | 連結與圖片 | 行內/參照式連結、圖片、相對路徑 |
| 04 | 程式碼 | 行內 code、程式碼區塊、語法高亮 |
| 05 | 表格與進階區塊 | 表格、引用、分隔線、內嵌 HTML |
| 06 | GitHub Flavored Markdown | Task list、刪除線、自動連結、footnote、emoji |
| 07 | Markdown 生態系 | README / Issues / PR、靜態網站、Mermaid、Obsidian |
| 08 | 實作與最佳實踐 | 完整 README 實作、常見錯誤、工具推薦 |

## 開發

本站為純靜態 HTML，無建置步驟。`docs/site.css` 為唯一樣式來源，所有頁面引用之。

```sh
# 本機預覽（擇一）
python3 -m http.server 8000
npx serve .
```

## 授權

本站教學內容（繁體中文解說）為本站原創，採 CC-BY-4.0；文中英文術語與語法示範引用自 Markdown 官方規格與 GitHub Flavored Markdown 規格。

## 相關連結

- 學習路徑建議服務：[learning-path-advisor](https://shuming-yang.github.io/learning-path-advisor/) — 依角色推薦教學網站學習路徑
