---
title: "Markdown Extra Components"
layout: post
date: 2019-12-3 22:48
image: /assets/images/markdown.jpg
headerImage: false
tag:
- markdown
- components
- extra
category: blog
author: jamesfoster
description: Markdown summary with different options
---

## Summary:

You can pick as item to see how to apply in markdown.

#### Especial Elements
- [Evidence](#evidence)
- [Side-by-Side](#side-by-side)
- [Star](#star)
- [Especial Breaker](#especial-breaker)
- [Spoiler](#spoiler)

#### External Elements
- [Gist](#gist)
- [Codepen](#codepen)
- [Slideshare](#slideshare)
- [Videos](#videos)

---

## Evidence

You can try the evidence!

<span class="evidence">Paragraphs can be written like so. A paragraph is the basic block of Markdown. A paragraph is what text will turn into when there is no reason it should become anything else.</span>

{% highlight html %}
<span class="evidence">Paragraphs can be written like so. A paragraph is the basic block of Markdown. A paragraph is what text will turn into when there is no reason it should become anything else.</span>
{% endhighlight %}

---

## Side-by-side

Like the [Medium](https://medium.com/) component.

**Image** on the left and **Text** on the right:

{% highlight html %}
<div class="side-by-side">
    <div class="toleft">
        <img class="image" src="tarek 1.jpg" alt="Alt Text">
        <img class="image" src="tarek 2 .jpg" alt="Alt Text">
        <img class="image" src="tarek 3 .jpg" alt="Alt Text">
        <figcaption class="caption">Photo by John Doe</figcaption>
    </div>

    <div class="toright">
        <p>biostatistics blog

K-Nearest Neighbour Classification


k-nearest neighbour classification for test set from training set.
 For each row of the test set, the k nearest (in Euclidean distance) training set vectors are found, and the classification is decided by majority vote, with ties broken at random.
  If there are ties for the kth nearest vector, all candidates are included in the vote.
</p>
    </div>
</div>
{% endhighlight %}

<div class="side-by-side">
    <div class="toleft">
        <img class="image" src="/bassam.jpg" alt="Alt Text">
        <img class="image" src="bassam2.jpg" alt="Alt Text">
        <img class="image" src="bassam3.png" alt="Alt Text">
        <figcaption class="caption">Photo by John Doe</figcaption>
    </div>

    <div class="toright">
        <p> we used also  a classification with decision tree breaking down a dataset into smaller and smaller subsets while at the same time an associated decision tree is incrementally developed.
   The final result is a tree with decision nodes and leaf nodes.
</p>
    </div>
</div>

**Text** on the left and **Image** on the right:

{% highlight html %}
<div class="side-by-side">
    <div class="toleft">
        <p> we used a Bayes Theorem for Naive Bayes Algorithm :with an assumption of independence among predictors.
    In simple terms, a Naive Bayes classifier assumes that the presence of a particular feature in a class is unrelated to the presence of any other feature.</p>
    </div>
</div>
    <div class="side-by-side">
    <div class="toleft">
        <img class="image" src="poline1.png " alt="Alt Text">
        <img class="image" src="poline2.png" alt="Alt Text">
        <img class="image" src="poline3.png" alt="Alt Text">
        <figcaption class="caption">Photo by John Doe</figcaption>
    </div>
</div>
{% endhighlight %}



---

## Star

You can give evidence to a post. Just add the tag to the markdown file.

{% highlight raw %}
star: true
{% endhighlight %}

---

## Especial Breaker

You can add a especial *hr* to your text.

{% highlight html %}
<div class="breaker"></div>
{% endhighlight %}

<div class="breaker"></div>

---

## Spoiler

You can add an especial hidden content that appears on hover.

{% highlight html %}
<div class="spoiler"><p>your content</p></div>
{% endhighlight %}

<div class="spoiler"><p>.</p></div>

---

## Gist

You can add Gists from github.

{% highlight raw %}
{ % gist sergiokopplin/91ff4220480727b47224245ee2e9c291 % }
{% endhighlight %}

{% gist sergiokopplin/91ff4220480727b47224245ee2e9c291 %}

---

## Codepen

You can add Pens from Codepen.

{% highlight html %}
<p data-height="268" data-theme-id="0" data-slug-hash="gfdDu" data-default-tab="result" data-user="chriscoyier" class='codepen'>
    See the Pen <a href='http://codepen.io/chriscoyier/pen/gfdDu/'>Crappy Recreation of the Book Cover of *The Flame Alphabet*</a> by Chris Coyier (<a href='http://codepen.io/chriscoyier'>@chriscoyier</a>) on <a href='http://codepen.io'>CodePen</a>.
</p>
<script async src="//assets.codepen.io/assets/embed/ei.js"></script>
{% endhighlight %}

<p data-height="268" data-theme-id="0" data-slug-hash="gfdDu" data-default-tab="result" data-user="chriscoyier" class='codepen'>See the Pen <a href='http://codepen.io/chriscoyier/pen/gfdDu/'>Crappy Recreation of the Book Cover of *The Flame Alphabet*</a> by Chris Coyier (<a href='http://codepen.io/chriscoyier'>@chriscoyier</a>) on <a href='http://codepen.io'>CodePen</a>.</p>
<script async src="//assets.codepen.io/assets/embed/ei.js"></script>

---

## Slideshare

Add your presentations here!

{% highlight html %}
<iframe src="//www.slideshare.net/slideshow/embed_code/key/hqDhSJoWkrHe7l" width="560" height="310" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen> </iframe>
{% endhighlight %}

<iframe src="//www.slideshare.net/slideshow/embed_code/key/hqDhSJoWkrHe7l" width="560" height="310" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen> </iframe>

---

## Videos

Do you want some videos? Youtube, Vimeo or Vevo? Copy the embed code and paste on your post!

**Example**

{% highlight html %}
<iframe width="560" height="310" src="https://www.youtube.com/embed/r7XhWUDj-Ts" frameborder="0" allowfullscreen></iframe>
{% endhighlight %}

<iframe width="560" height="310" src="https://www.youtube.com/embed/r7XhWUDj-Ts" frameborder="0" allowfullscreen></iframe>

[1]: http://daringfireball.net/projects/markdown/
[2]: http://www.fileformat.info/info/unicode/char/2163/index.htm
[3]: http://www.markitdown.net/
[4]: http://daringfireball.net/projects/markdown/basics
[5]: http://daringfireball.net/projects/markdown/syntax
[6]: http://kune.fr/wp-content/uploads/2013/10/ghost-blog.jpg
