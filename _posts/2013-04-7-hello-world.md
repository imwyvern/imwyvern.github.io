---
layout: default
title: hello world
---
<header>
	<h2><em>{{ page.title }}</em></h2>
</header>
<section>
	<article>
		<p>我的第一篇文章<code>hello world</code></p>
		<time><i>{{ page.date | date_to_string }}</i></time>
	</article>
</section>