# たたかうやつ(仮)開発用資料集
## ゲームの説明
VRChatで遊べる対戦アクションゲームです。

## このサイトの説明
ここは開発用資料が置かれています。
ゲームに関する大体の情報はここにあるはずです。

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
