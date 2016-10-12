---
layout: post
title: the Information Interview
---

Jeykll supports the use of [Markdown](http://daringfireball.net/projects/markdown/syntax) with 

My first reaction to having to do an information interview was visceral. Having to go ask someone I don't know to take precious time out of their busy day to talk to me about what they do sounded like a very bad idea.
It stayed that way for a while.
The breakthrough cam when, at a meetup, mentioning my anxiety, a fellow coder exclaimed: "I love information interviews!" Needless to say, I was puzzled. She quickly continued with this brief explanation: "I've found that people love talking about themselves." She said more but that was the part that made the light go on for me. In an Information Interview, I would not be the one the attention would be on. It would be a window into someone else's reality. . . and they would enjoy the chance to share.
Needless to say that armed with that gracious attitude this young coder gave me, I proceeded to jump at the opportunity to ask anyone I could about their life as a programmer. 


Tables have also been extended from Markdown:

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

Here's an example of an image, which is included using Markdown:

![Geometric pattern with fading gradient](/img/sample_feature_img_2.png)

Highlighting for code in Jekyll is done using Pygments or Rouge. This theme makes use of Pygments by default.

{% highlight js %}
// count to ten
for (var i = 1; i <= 10; i++) {
    console.log(i);
}

// count to twenty
var j = 0;
while (j < 20) {
    j++;
    console.log(j);
}
{% endhighlight %}

Type Theme uses KaTeX to display maths. Equations such as $$S_n = a \times \frac{1-r^n}{1-r}$$ can be displayed inline.

Alternatively, they can be shown on a new line:

$$ f(x) = \int \frac{2x^2+4x+6}{x-2} $$
