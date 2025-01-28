---
layout: home
permalink: /
---

# たたかうやつ(仮)資料集
## ゲームの説明
VRChatで遊べる対戦アクションゲームです。
巨大人型メカに乗って敵をしばきましょう！

[詳しい遊び方](./_pages/howtoplay.md)

## このサイトの説明
ここは開発用の資料が置かれています。
ゲームに関する情報は大体ここにあるはずです。

## 最終更新
{{ site.time }}

## 管理者
蒟蒻砂漠([Twitter](https://x.com/konjacdesert))

## アップデート
{% for pageupdate in site.categories.updates %}
* [{{ pageupdate.title }}]({{ site.baseurl }}{{ pageupdate.url }})
{% endfor %}

## お知らせ
{% for pagenotices in site.categories.notices %}
* [{{ pagenotices.title }}]({{ site.baseurl }}{{ pagenotices.url }})
{% endfor %}

## TIPS
{% for pagetips in site.tips %}
* [{{ pagetips.title }}]({{ site.baseurl }}{{ pagetips.url }})
{% endfor %}

***

[?](./_pages/specs.md)