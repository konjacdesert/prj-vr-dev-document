# たたかうやつ(仮)資料集
## ゲームの説明
VRChatで遊べる対戦アクションゲームです。

## このサイトの説明
ここは開発用の資料が置かれています。
ゲームに関する情報は大体ここにあるはずです。

## 最終更新
{{ site.time }}

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
