---
permalink: /
---

# たたかうやつ(仮)資料集
## ゲームの説明
VRChatで遊べる対戦アクションゲームです。
巨大人型メカに乗って敵をしばきましょう！

## このサイトの説明
ここは開発用の資料が置かれています。
ゲームに関する情報は大体ここにあるはずです。

仕様メモについては実際にゲームに実装されていない仮のものも含みます。

## 最終更新
{{ site.time }}

## 管理者
蒟蒻砂漠([Twitter](https://x.com/konjacdesert))

## アップデート
{% for post in site.categories.updates %}
* [{{ post.title }}]({{ site.baseurl }}{{ post.url }})
{% endfor %}

## お知らせ
{% for post in site.categories.notices %}
* [{{ post.title }}]({{ site.baseurl }}{{ post.url }})
{% endfor %}

## 仕様メモ
{% for page in site.specs %}
* [{{ page.title }}]({{ site.baseurl }}{{ page.url }})
{% endfor %}
