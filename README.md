# FOMO 研究院 — 個人文章索引

> ⚠️ **個人使用，公開 archive 性質**
> 這個 repo 是 KP @ FOMO研究院電子報 (https://www.fomosoc.com/) 的文章索引，
> 用來給訂閱用戶在公司/手機上快速瀏覽 + 讀取已下載的 PDF。
>
> 內容版權仍歸 KP / FOMO研究院 所有，僅作個人 archive 用途。

## 結構

```
.
├── index.html   # 視覺索引頁（含所有文章 metadata + 篩選）
├── PDF/         # 147 篇文章的 PDF（66 免費 + 81 付費）
└── README.md
```

## 來源

- 索引資料：`archive.json`（每篇文章標題/日期/系列/封面圖）
- PDF：本地 `~/Desktop/排程運算/Substack/PDF/` 經 `html_to_pdf.py` 產出
- 抓取流程：見 [Substack/sync.command](https://github.com/kevin14752/Substack)

## 更新方式

本地跑 `~/Desktop/排程運算/Substack/sync.command`，新文章會自動同步到 `PDF/`，再 push 到這邊。

## License

個人使用。請勿重發或公開 redirect 到這 repo。
