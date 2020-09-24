---
layout: inner
title: 关于我
permalink: /about/
---
## 个人信息

#### 姓名：李玉超

#### 性别：男

#### 出生年月：1998.11.08

#### 民族：汉

#### 电话：18203232573

#### 邮箱：1403053171@qq.com


# 自我评价
1. 本人认真负责、积极主动、能吃苦耐劳，能较好地完成自己的任务与工作。 

1. 本人开朗乐观、热心助人，有较强的交际能力。 

1. 本人为人诚恳、细心、稳重，有良好的团队精神。


This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

## Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### Header 3

{% highlight js %}
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
{% endhighlight %}

{% highlight ruby %}
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
{% endhighlight %}

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

---

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Wide image

![Branching](https://guides.github.com/activities/hello-world/branching.png)

### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

{% highlight txt %}
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
{% endhighlight %}

{% highlight txt %}
The final element.
{% endhighlight %}

---

## Syntax highlighting

Jekyll has [built in support](https://jekyllrb.com/docs/templates/#code-snippet-highlighting) for syntax highlighting of over 60 languages thanks to [Rouge](http://rouge.jneen.net/).

To render a code block with syntax highlighting, surround your code as follows:

{% highlight markdown %}
{% raw %}
{% highlight ruby %}
def foo
  puts 'foo'
end
{% endhighlight %}
{% endraw %}
{% endhighlight %}

[Pygments](http://pygments.org/) styles are present under section 6.0 of `css/style.scss` for customization.

### Examples

---

#### Bash

{% highlight bash %}
>_ ssh -i ~/.ssh/id_rsa account@host.com
account@host:~$
$ var="my-value"
$ echo $var
my-value
$ logout
{% endhighlight %}

#### HTML

{% highlight html %}
<!DOCTYPE html>
<html>
 <head>
   <meta charset="UTF-8">
   <title>title</title>
 </head>
 <body>

 </body>
</html>
{% endhighlight %}

#### CSS

{% highlight css %}
/*--------------------------------------------------------------
	1.0 Defaults
--------------------------------------------------------------*/

@media (min-width: 1200px) {
  .container {
    width: 1200px;
  }
}

body {
  background-color: #e9edf0;
  @extend %opensans;
  -webkit-font-smoothing: antialiased;
}
{% endhighlight %}

#### YAML

{% highlight yaml %}
### Phantom settings
paginate: 10
footer_text: '© 2018 Jami Gibbs'
admin_name: 'Jami Gibbs'
google_analytics: "UA-9999999-99" # Update with your own tracking ID

#### Phantom Navigation menu
enable_nav: true
nav_item:
  - { url: '/', text: 'Home' }
  - { url: '/about', text: 'About' }
{% endhighlight %}
