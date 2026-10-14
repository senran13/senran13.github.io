# zongkunchang.com

張宗坤（Chang Zong-Kun）的個人學術網站原始碼。研究領域為冷戰時期台灣的勞動、基礎建設與技術史。

網站：<https://www.zongkunchang.com>

## 技術

- 以 [Hugo](https://gohugo.io/) v0.166.0 建置的靜態網站，經 GitHub Actions 部署至 GitHub Pages。
- 無 JavaScript 框架、無外部相依套件；字型為 Google Fonts 的 Lato。
- 自 Google Sites 遷移，網址結構與舊站相同（舊中文網址自動轉址）。
  - 內容遷移完成：2026-10-14
  - 網域切換上線：（待切換後填入）

## 目錄

| 路徑 | 內容 |
|---|---|
| `content/` | 各頁內容。多數為 Markdown；About Me 與 Blog 系列保留舊站排版，以 HTML 撰寫 |
| `layouts/` | 版型與 shortcode |
| `static/` | 樣式表、圖片、PDF、robots.txt |
| `hugo.toml` | 網站設定與導覽列 |

## 本機預覽

```bash
hugo server
```

## 授權

程式碼採 MIT 授權；文字與作者自有圖片、文件採 CC BY-NC 4.0；已刊行論文 PDF 與第三方圖片除外。詳見 [LICENSE](LICENSE)。
