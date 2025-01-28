---
layout: default
permalink: /specs/
---

# 仕様メモ

このページに乗っている情報は実際にゲームに実装されていない仮のものも含みます。

{% for pagespecs in site.specs %}
* [{{ pagespecs.title }}]({{ site.baseurl }}{{ pagespecs.url }})
{% endfor %}