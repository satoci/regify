# Regify — URL to Regex Checker

**Live tool → [Try Regify](https://satoshi.github.io/regify/)**

A lightweight, browser-based tool that converts any URL into a regex pattern ready to use in GA4, Google Tag Manager, and other analytics platforms — then lets you verify it against test cases instantly.

---

## Why I built this

As a UX Strategist and CRO Specialist, writing regex for GA4 filters and A/B testing tools is a recurring part of my workflow. For a while, I was handling it the way most analysts do: pasting URLs into a chat-based LLM and asking it to generate the pattern each time. It worked, but the back-and-forth added friction to tasks that should take seconds.

When I started working with Claude and realized I could build my own tools around it, the idea for Regify came immediately. Not just to save myself time, but because I knew this was a pain point shared by many marketers and analysts who deal with GA4 regex daily — people who are fluent in data but don't want to memorize regex syntax just to set up a filter.

Regify is the tool I wished existed: paste a URL, get a regex, confirm it matches what it should (and doesn't match what it shouldn't), done.

---

## Features

- **One-click regex generation** from any URL
- **Path-only or full-URL mode** — path mode is optimized for GA4 page filters
- **Auto-generated test cases** including query parameters (`?utm_source=google`) and anchors (`#section`)
- **`+?` / `#` buttons** to append params or anchors to any test URL in one click
- **Live match indicators** — each test case shows ✓ or ✗ in real time as you type
- **Inline regex breakdown** — explains what each part of the pattern does
- **Bilingual UI** — switch between Japanese and English
- **No install, no login** — runs entirely in the browser as a single HTML file

---

## Who it's for

- **Web analysts** configuring GA4 event filters, audience conditions, or channel groupings
- **Digital marketers** setting up goal filters or UTM-aware tracking rules
- **CRO practitioners** working with A/B testing tools that require regex-based URL targeting
- Anyone who needs to write a regex for a URL and wants to verify it before shipping

---

## Usage

1. Paste a URL into the input field (or press Enter)
2. Choose **Path only** (GA4 recommended) or **Full URL**
3. The regex is generated automatically — edit it directly if needed
4. Review the auto-generated test cases, or add your own
5. Use `+?` to test with query strings, `#` to test with anchors
6. Copy the regex and paste it into GA4, GTM, or your tool of choice

---

## Built by

**Satoshi** — UX Strategist / CRO Specialist  
Focused on GA4 analysis, conversion rate optimization, and UX redesign for digital products.

---

## License

MIT — free to use, modify, and share.

---
---

# Regify — URL → 正規表現チェッカー

**ツールを使う → [Regify を開く](https://satoshi.github.io/regify/)**

URLを貼り付けるだけで、GA4・GTM・各種A/Bテストツールに使える正規表現を即座に生成し、想定通りに動くかをその場で検証できるブラウザ完結型ツールです。

---

## なぜ作ったか

UXストラテジスト / CROスペシャリストとして、GA4のフィルタ設定やA/Bテストツールの設定で正規表現を書く場面は日常的にあります。しばらくの間は多くのアナリストと同じように、チャット形式のLLMにURLを貼り付けて正規表現を生成してもらうという方法で対応していました。機能はするのですが、毎回のやり取りが積み重なると、数秒で終わるはずのタスクに余計な手間がかかっていることに気づきます。

Claudeと出会い、自分でもツールが作れると気づいたとき、Regifyのアイデアはすぐに浮かびました。自分の効率を上げたいという動機もありましたが、それ以上に、GA4の正規表現を日常的に扱うマーケターやアナリストの多くが同じ課題を抱えているとわかっていたからです。データの扱いには慣れていても、フィルタを設定するためだけに正規表現の構文を覚えたくない、という人は少なくありません。

Regifyは、自分が欲しかったツールです。URLを貼り付けて、正規表現を得て、想定通りに動くか確認する。それだけです。

---

## 主な機能

- **URLから正規表現をワンクリック生成**
- **パスのみ / フルURL モード切替** — GA4ページフィルタにはパスモードが最適
- **テストケースを自動生成** — クエリパラメータ（`?utm_source=google`）・アンカー（`#section`）付きを含む
- **`+?` / `#` ボタン** — 既存のテストURLにパラメータ・アンカーをワンクリックで付与
- **リアルタイム判定** — 入力のたびに ✓ / ✗ を即時表示
- **正規表現の構造を解説** — 各パーツが何を意味するかをインラインで表示
- **日英バイリンガルUI** — ボタン一つで表示言語を切替
- **インストール不要・ログイン不要** — HTMLファイル単体でブラウザ上で完結

---

## こんな方に

- GA4のイベントフィルタ・オーディエンス条件・チャネルグループを設定している**Webアナリスト**
- 目標フィルタやUTMパラメータを考慮したトラッキング設定をしている**デジタルマーケター**
- A/BテストツールでURL条件を正規表現で指定する**CRO担当者**
- 正規表現を書いた後に「本当に合ってるか」確認したい**すべての人**

---

## 使い方

1. 入力欄にURLを貼り付ける（Enterキーでも生成可）
2. **パスのみ**（GA4推奨）か**フルURL**かを選ぶ
3. 正規表現が自動生成される — 必要に応じて直接編集も可
4. 自動生成されたテストケースを確認、または自分で追加
5. `+?` でクエリパラメータ付き、`#` でアンカー付きのテストURLを追加
6. 正規表現をコピーして GA4・GTM・各ツールに貼り付けて完了

---

## 作者

**Satoshi** — UX Strategist / CRO Specialist  
GA4分析・コンバージョン改善・UXリデザインを専門としています。

---

## ライセンス

MIT — 自由に使用・改変・共有できます。
