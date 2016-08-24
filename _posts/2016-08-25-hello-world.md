---
layout: post
title: "Blogging Like a hacker"
date:   2016-08-25 02:23:52 +0900
categories: jekyll update
---
## Jekyll

![jekyll](http://hbn-blog-assets.s3.amazonaws.com/saltfactory/images/84755ce7-0464-4833-9cc5-2b4a922bf8e9)

[Jekyll](http://jekyllrb.com/)은 static websites 생성 프레임워크이다. `Ruby`로 만들어진 이 것은 **Markdown** 파일을 `_posts` 디렉토리에 생성하는 것 만으로 멋진 static website를 만들어준다. Markdown을 사용하는 개발자에게 반가운 이야기일 것이다. 우리도 Markdown을 표준 document format으로 정하고 난 뒤에 Jekyll을 사용해서 Pages를 만들고 기존의 블로그를 이전하고 있다.ndex.html 파일을 git push 하는 것 만으로도 만들 수 있고, 다른 static website generator framework를 사용해도 된다. GitHub에서는 공식적인 Database를 지원하고 있지 않기 때문에 static website(HTML 파일)을 사용해야 한다.


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

[jekyll-docs]: http://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
