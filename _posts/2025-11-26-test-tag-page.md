---
title: "タグなどが出ない..."
categories: 
 - log
tags:
 - discussion
 - collaboration
---

ポストのタグなどが出ないので、Copilotに相談しながら試行錯誤中

---
_config.yml　に 
````markdown
category_archive:  
  type: liquid  
  path: /categories/  
tag_archive:   
  type: liquid   
  path: /tags/  
````  
  を記したら出るようになったかも

---

Copilot曰く

````copilot
## 🔹 まとめ
- 記事ページにタグやカテゴリを出す → `_config.yml` の `show_tags` / `show_categories`  
- タグ／カテゴリリンクを有効にする → `_config.yml` の `tag_archive` / `category_archive` ＋ `_pages/tags.md` / `_pages/categories.md`  
- 個別のタグ／カテゴリページを生成する → `jekyll-archives` プラグイン  

---

✨ 結論  
タグ名クリックで 404 になるのは「一覧ページがまだ存在しない」ためです。  
👉 `_pages/tags.md` と `_pages/categories.md` を作って permalink を `/tags/` `/categories/` に設定すれば、リンクが有効になります。  

````
完成