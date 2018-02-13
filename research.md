---
layout: page
title: Research
permalink: /research/
---

This page is being updated and will be available soon! Thanks!

- Recommender Systems in Keras: https://nipunbatra.github.io/blog/2017/recommend-keras.html
- PCA & t-SNE: https://medium.com/@luckylwk/visualising-high-dimensional-datasets-using-pca-and-t-sne-in-python-8ef87e7915b
- Gitconfig file had a symbolic link to another .gitconfig file in a repo that was deleted. This prevented 'git config --global user.name "username"' from executing. It gave error it never found the .gitconfig file. The only solution was to remove said .gitconfig file from /Users/username/ and run the above command again.
- Idea: Donate items, public dropbox, classify items Keras->CoreML, Facebook/Twitter Oath2.0, nearby charities
- Sort a dictionary by it's key first, then by the 2nd value in its list:

{% highlight python %}
everything = OrderedDict(sorted(everything.items(), key=lambda t: t[0]))
	everything = [[k,v] for k, v in everything.items()]
	everything.sort(key=lambda pair: pair[1][1])
{% endhighlight %}

Nullam libero nunc, rutrum vitae tellus ut, pretium sollicitudin sapien. In auctor ipsum sed orci aliquam, eget malesuada velit auctor. Nulla vel maximus ligula, vel molestie odio. Vivamus ac lorem quis libero dictum blandit. Fusce tincidunt justo quis lorem sollicitudin, sed rhoncus nibh facilisis. Morbi vitae congue nunc. Praesent a enim rhoncus, malesuada urna ac, accumsan ex. Fusce ornare porta ipsum id iaculis. Phasellus consectetur nisl vitae est pretium, at ultrices mauris placerat. Duis pellentesque mauris sapien, sed tristique ante auctor vel. Vivamus at sodales metus, eget malesuada eros.

Nunc quis venenatis nunc. Nunc nec libero non quam suscipit placerat. Pellentesque lobortis sagittis arcu at euismod. Phasellus odio nisl, mattis sed sagittis semper, aliquet id sem. Quisque iaculis nisl urna, ac accumsan elit commodo vel. Proin sagittis eleifend sollicitudin. Sed libero lorem, tempus eget turpis id, aliquet commodo augue. Proin diam dolor, rutrum et magna at, semper rutrum sapien.
