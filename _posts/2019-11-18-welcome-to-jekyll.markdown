---
layout: post
title:  "Pre-compiling CSS"
date:   2019-11-18 01:40:24 -0600
categories: jekyll update
---
Why use CSS Pre-Processors?

I think that everyone who has used CSS has been annoyed at the fact that it is simply not very comfortable to use - it is the opposite of DRY, and it is honestly rather clumsy.

With CSS Pre-Processors, the experience of designing a web site can be made less clumsy, and more effortless. The hierarchy of the selectors is made visual with nesting. This makes it easier to read, as well as easier to understand it.

Another pro with CSS pre-processors is that it is more powerful so to say, in that you can use variables, and write other code directly in the pre-processor.

However, something sleek and effortless is usually more complex, and that is also the case with Pre-processors. It requires more tools, more setup, and with that requires more time - not only time to setup, but also to maintain, to load the page, etc.. It is also harder to debug.

Jekyll requires blog post files to be named according to the following format:

`YEAR-MONTH-DAY-title.MARKUP`

Where `YEAR` is a four-digit number, `MONTH` and `DAY` are both two-digit numbers, and `MARKUP` is the file extension representing the format used in the file. After that, include the necessary front matter. Take a look at the source for this post to get an idea about how it works.

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
