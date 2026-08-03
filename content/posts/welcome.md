---
title: "歡迎來到我的 Hugo 個人部落格！🎉"
date: 2026-08-03T10:30:00+08:00
draft: false
tags: ["Hugo", "部落格", "建站記錄"]
categories: ["技術筆記"]
summary: "這是我的第一篇部落格文章，紀錄使用 Hugo 與 PaperMod 搭建個人部落格的心得與體驗。"
ShowToc: true
TocOpen: true
---

## 為什麼選擇 Hugo？

在比較了多個靜態網站生成器（如 Hexo, Jekyll, Gatsby, Next.js）之後，我選擇了 **Hugo** 作為個人部落格的核心工具，主要原因如下：

1. **極速構建**：Hugo 由 Go 語言編寫，構建上百篇文章只需要幾毫秒。
2. **單一可執行檔**：無需複雜的 Node.js 或 Ruby 依賴環境，安裝維護極簡。
3. **豐富的主題生態**：擁有許多優質開源主題，例如本站使用的 **PaperMod**。

---

## 範例程式碼展示

Hugo 支援標準 Markdown 與語法高亮 (Syntax Highlighting)。以下是一個 Python 範例：

```python
def greet(name: str) -> str:
    """產生個人化招呼語"""
    return f"Hello, {name}! 歡迎來到 Hugo 個人部落格。"

if __name__ == "__main__":
    message = greet("讀者")
    print(message)
```

---

## 未來寫作計畫 🚀

- [x] 搭建 Hugo 站台與配置 PaperMod 主題
- [ ] 撰寫靜態網站自動化部署指南 (GitHub Actions)
- [ ] 整合 Giscus 留言板系統

感謝您的閱讀，歡迎隨時透過選單列的**搜尋**功能探索更多內容！
