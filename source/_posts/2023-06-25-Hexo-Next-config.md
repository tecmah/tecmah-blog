---
title: Hexo-Next-config
date: 2023-06-25 11:34:51
tags:
---


# もちろんです。以下に、Hexoのテーマ「NexT」の設定ファイル`_config.yml`の説明をマークダウン形式で日本語に翻訳して記述します。

```markdown
# HexoテーマNexT設定

## 1. スキーム設定
NexTには様々なスキームが用意されています。お好みのものを選びましょう。
```yaml
scheme: Muse
```
Muse、Mist、Pisces、Geminiから選べます。

## 2. メニュー設定
サイトのメニューアイテムをカスタマイズできます。

```yaml
menu:
  home: / || fa fa-home
  about: /about/ || fa fa-user
  tags: /tags/ || fa fa-tags
  categories: /categories/ || fa fa-th
  archives: /archives/ || fa fa-archive
  schedule: /schedule/ || fa fa-calendar
  sitemap: /sitemap.xml || fa fa-sitemap
  commonweal: /404/ || fa fa-heartbeat
```
`menu`設定の下の各行はメニューアイテムを表しています。形式は`名前: URL || アイコン`です。

## 3. アバター設定
サイトにアバターを設定できます。
```yaml
avatar:
  url: #/images/avatar.gif
  rounded: true
  opacity: 0.9
```
`url`はアバター画像へのパスです。`rounded`はアバターを丸くするかどうかを決定します。`opacity`はアバターの不透明度を設定します。

## 4. ソーシャル設定
ソーシャルメディアのプロフィールへのリンクを追加できます。
```yaml
social:
  GitHub: https://github.com/yourusername || fa fa-github
  Twitter: https://twitter.com/yourusername || fa fa-twitter
  Weibo: https://weibo.com/yourusername || fa fa-weibo
```
`social`設定の下の各行はソーシャルメディアのリンクを表しています。形式は`プラットフォーム: URL || アイコン`です。

## 5. フッター設定
サイトのフッターをカスタマイズできます。
```yaml
footer:
  since: 2013
  post_meta: true
  busuanzi: true
```
`since`はサイトが作成された年です。`post_meta`はフッターに投稿のメタ情報を表示するかどうかを決定します。`busuanzi`はBusuanzi訪問者カウンターを有効にします。

以上がNexTの設定ファイルの一部の説明です。

全ての設定を理解するには、公式のドキュメン

