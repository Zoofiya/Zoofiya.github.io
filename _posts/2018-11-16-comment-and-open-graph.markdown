---
layout: post
title:  "Comments and Open graph"
date:   2018-11-16 07:48:17 -0600
categories: jekyll update
comments: true
---
## Comments and Open graph

#### How did you implement comments to blog posts?
I chose to use Disqus and to create comment boxes I needed to do as following(there):
+ First and foremost, I had to sign up for a Disqus account. It's within your account all of the comments are being sent and managed by me. I could switch from one site to another that I have registered in my account. I then followed the guide on their site and selected jekyll as my platform.  

+ The installing process to jekyll is the next step. The first step in this process was to add a key to my blog posts' front matters where I want comment sections. I had to add the key *"comments"* and set the value to *"true"* as following: 

{% highlight python %}
---
layout: default
comments: true
# other options
---
{% endhighlight %}

+ The last part of the installing process was to check that a [**Universal embed code**](https://help.disqus.com/installation/universal-embed-code) was already added to to my file disqus_comments.html between an if and an else statement.

+ Now, when It came to configuration I just needed to change a few things in my disqus_comments.html. I needed to substitute the EXAMPLE to my own shortname(Zoofiyas) that I defined on my account on Disqus when I linked my site. Then I had to define **this.page.url** and **this.page.identifier** as the URL for my site.

+ When I was done I just added some changes on Community & Comments Configuration my Disqus account.


<br><br/>
#### What is Open Graph and how do you make use of it?
Open graph adds riches to your link when you link you website on social medias for instance. Facebook originally founded invented It and now It is used mostly everywhere. Using open graph could for example show an image of the page when the site is being linked. This is good if you want to increase your click-through rate of a page. It gives the viewer a brief view of the page and makes usually It more attracting to click on It. In other words, It is a way to control how social media shares and shows your site and influences the social media traffic in a benificial way.

I added some meta tags in my head.html file. To know what to put as my url I first had to push up my site on Github pages in my new repository.
{% highlight python %}
  <meta property="og:title" content="Zoofiyas" />
  <meta property="og:image" content="https://zoofiya.github.io/" />
  <meta property="og:type" content="website" />
  <meta property="og:url" content="https://zoofiya.github.io/" />
{% endhighlight %}

[Previous post]({% post_url 2018-11-15-ssg %})
<a href="https://zoofiya.github.io/jekyll/update/2018/11/17/pre-compiling-css.html" class="next">Next post</a>
