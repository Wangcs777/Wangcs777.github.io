---
layout: post
title:  "Welcome to Jekyll!"
date:   2016-06-04 13:50:39
categories: jekyll
---
Git是一个开源的分布式版本控制系统，可以对高效地处理项目版本管理。 使用git首先了解工作区，暂存区，版本库概念。 工作区:就是在电脑里能看到的目录。在工作区中进行对文件的修改（对文件的添加，删除，修改操作都属于对文件的修改，是相对于原来比较）。 暂存区:一般存放在".git目录下"下的index文件。对文件进行修改后将对文件改动的操作暂时存储的地方。 版本库:工作区有一个隐藏目录.git，这个就是本地的版本库，在本地修改好文件后存入版本库，再将版本库上传服务器。 git的使用流程如下: 从服务器上将仓库克隆到本地 ↓ 在本地对代码进行修改 a ↓ 对修改的代码进行整理 ↓ 将服务器上最新的代码更新下来，和本地的代码合并 ↓ 将本地仓库提交到服务器上
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

Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll’s dedicated Help repository][jekyll-help].

[jekyll]:      http://jekyllrb.com
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-help]: https://github.com/jekyll/jekyll-help
