---
title: "Getting images to show in the posts, post!"
date:  2023-04-07 
categories:
  - blog
tags:
  - KNES-381
  - update
  - post-images
---
# time in T19:34:30-07:00
This time codes reads 7:34pm Mountain Standard time (GMT-7)
This is one of the first files I updated created new in this section

The front matter is the content between the triple dashes and has a specific format that jekyll is looking for.

I have placed the corrections to the posting image paths that I have made below

```ruby
# to get the images to disply here I had to add /webtheme to the path
# this top code displays the bio-photo shadow image
![caption](/webtheme/assets/images/bio-photo.jpg)
# this standard path code shows a broken image
![caption](/assets/images/bio-photo.jpg)
# so does this pathing even though autocomplete works with the pathing below!
![caption](../assets/images/bio-photo.jpg)
```
![image-center](/webtheme/assets/images/COLOURBOX16037408.jpg){: .align-center}
![working_path](/webtheme/assets/images/bio-photo.jpg)
![broken_path](/assets/images/bio-photo.jpg)
![broken_path](../assets/images/bio-photo.jpg)
![alt]({{ site.url }}{{ site.baseurl }}/assets/images/bio-photo.jpg)

I will enter some space betwee the two versions of the code posting suggested for by the theme manager...

<img src="{{ site.url }}{{ site.baseurl }}/assets/images/bio-photo.jpg" alt="">



Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/