# たたかうやつ(仮)開発用資料集
## ゲームの説明
VRChatで遊べる対戦アクションゲームです。

## このサイトの説明
ここは開発用資料が置かれています。
ゲームに関する大体の情報はここにあるはずです。

## 最終更新
{{ site.time }}

## 確定・実装済みの仕様
{% for page in site.fix %}
* [{{ page.title }}]({{ site.baseurl }}{{ page.url }})
{% endfor %}

## アップデート

## お知らせ

## 仕様メモ
{% for page in site.temp %}
* [{{ page.title }}]({{ site.baseurl }}{{ page.url }})
{% endfor %}
