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

## 未確定の仕様
{% for page in site.temp %}
* [{{ page.title }}]({{ site.baseurl }}{{ page.url }})
{% endfor %}

## すべて
{% for page in site.pages %}
* [{{ page.title }},{{page.categories}},{{page.collection}}]({{ site.baseurl }}{{ page.url }})
{% endfor %}
