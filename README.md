# tynagity.github.io

日記ブログサイト - 主に日記、たまに数式

## 特徴

- Markdown (.md) で記事を管理
- タグ機能で記事を分類
- MathJax による数式表示のサポート
- GitHub Pages で自動デプロイ

## 記事の書き方

### 新しい記事を作成

`_posts/` ディレクトリに `YYYY-MM-DD-title.md` の形式でファイルを作成します。

```markdown
---
layout: post
title: "記事のタイトル"
date: 2026-01-08 12:00:00 +0900
tags: [タグ1, タグ2]
---

記事の内容をここに書きます。
```

### 数式の書き方

インライン数式: `$E = mc^2$` → $E = mc^2$

ディスプレイ数式:
```
$$
x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}
$$
```

## ローカルで確認

```bash
# 依存関係のインストール
bundle install

# ローカルサーバーの起動
bundle exec jekyll serve

# ブラウザで http://localhost:4000 にアクセス
```

## デプロイ

GitHub にプッシュすると自動的に GitHub Pages にデプロイされます。