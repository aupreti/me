---
layout: post
title:  "Welcome to Jekyll!"
date:   2018-08-10 23:17:21 -0400
published: false
categories: jekyll update
---
You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/

LW x
SW y
when can we commute
- address different,
SW - same addre
SW - same
LW
LW
anytime -> when no data dependency.
first load not producing an address that is used in
2nd LW

FENCE instruction
memory fence
------
Serilizability of instruction
Not only  predecessor SW but also successor SW are getting ordered
A load has a set of candidate stores it can observe

Graph has Store has atomicity property and is serializable

Global memory order or view of other threads
RISCV
Conceptually, events from the same hart that are ordered by preserved program order must appear in that order from the perspective of other harts and/or observers.
