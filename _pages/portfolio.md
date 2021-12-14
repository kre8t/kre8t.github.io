---
layout: page
title: Portfolio
subheading: The works of IJH
permalink: /portfolio
---
<div class="uk-child-width-1-2@s uk-child-width-1-4@m uk-child-width-1-6@l uk-grid>
{% for portfolio_item in site.portfolio_items %}
	 <div>
	    <a href="{{site.baseurl}}/portfolio/{{portfolio_item.slug}}/"><img src="{{page.image}}"></a>
	 </div>
{% endfor %}
</div>

<div class="uk-width-1-2@m">
Binkity Bonk. Let's make some fun designs!
</div>
<div class="uk-width-1-2@m">

</div>
