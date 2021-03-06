+++
date = "2017-01-08"
title = "Hugo Black & Light"
+++

I converted my blog from [Octopress to Hugo](/octopress-to-hugo/) and in as part of that process ported over the existing theme. Its available on the [Hugo Themes Site](http://themes.gohugo.io/black-and-light/).

Its called [Black and Light](https://github.com/davidhampgonsalves/hugo-black-and-light-theme) and is high contrast, text oriented, and Javascript-free.

## Features
* Loads in a single request (with web-fonts disabled)
* 100 / 100 on Google Page Speed test (100 / 100 on mobile with web-fonts disabled)
* Scriptless (unless you enable Google Analyitcs)
* Styles inlined in head
* High Contrast

## Style Demo
# h1 Heading
## h2 Heading
### h3 Heading
#### h4 Heading
##### h5 Heading
###### h6 Heading


---

**This is bold text**

__This is bold text__

*This is italic text*

_This is italic text_

~~Deleted text~~

> Block quotes are
> written like so.
>
> They can span multiple paragraphs,
> if you like.

Some text, and some `code` and then a nice plain [link with title](https://github.com/davidhampgonsalves/davidhampgonsalves.com-hugo "title text!").

and then

+ Create a list by starting a line with `+`, `-`, or `*`
+ Sub-lists are made by indenting 2 spaces:
  - Marker character change forces new list start:
    * Ac tristique libero volutpat at
+ Very easy!

vs.

1. Lorem ipsum dolor sit amet
2. Consectetur adipiscing elit
3. Integer molestie lorem at massa

## Code

Inline `code`

``` js
var foo = function (bar) {
  return bar++;
};

console.log(foo(5));
```
