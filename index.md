---
---

## 説明
ここは開発用資料が置かれています。
ゲームに関する大体の情報はここにあるはずです。
資料の更新:{{ site.time }}

## 仕様
{% for page in site.fix %}
* [{{ page.title }}]({{ site.baseurl }}{{ page.url }})
{% endfor %}

## 考え中
{% for page in site.temp %}
* [{{ page.title }}]({{ site.baseurl }}{{ page.url }})
{% endfor %}
