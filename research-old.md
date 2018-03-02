---
layout: page
title: Research
permalink: /research-old/
---

This page is being updated and will be available soon! Thanks!

- Recommender Systems in Keras: [Link](https://nipunbatra.github.io/blog/2017/recommend-keras.html)
- PCA & t-SNE: [Visualization](https://medium.com/@luckylwk/visualising-high-dimensional-datasets-using-pca-and-t-sne-in-python-8ef87e7915b)
- Gitconfig file had a symbolic link to another .gitconfig file in a repo that was deleted. This prevented 'git config --global user.name "username"' from executing. It gave error it never found the .gitconfig file. The only solution was to remove said .gitconfig file from /Users/username/ and run the above command again.
- Idea: Donate items, public dropbox, classify items Keras->CoreML, Facebook/Twitter Oath2.0, nearby charities
- Sort a dictionary by it's key first, then by the 2nd value in its list:
{% highlight python %}
everything = OrderedDict(sorted(everything.items(), key=lambda t: t[0]))
	everything = [[k,v] for k, v in everything.items()]
	everything.sort(key=lambda pair: pair[1][1])
{% endhighlight %}
