---
title: "Aether Features"
date: 2018-12-19T10:35:35-05:00
description: "Hugo combined with the Aether theme turns easy to write markdown into powerful web pages.  KaTeX, Highlight.js, and Hugo provides the ability to create mathmatical symobols, equations, highlighted code, tables, lists, and much more."
categories: ["Features"]
featuredImage: "/img/mdd-iphone.jpg"
dropCap: true
displayInMenu: false
displayInList: true
draft: false
---

Hugo combined with the Aether theme turns easy to write markdown into powerful web pages.  KaTeX, Highlight.js, and Hugo provides the ability to create mathmatical symobols, equations, highlighted code, tables, lists, and much more.

For each feature below, the first line is the markdown and the second line is the result after Hugo, KaTeX, and Highlight.js process the markdown.  You can find many more features in the Hugo documentation.

## LaTeX style math typsetting with KaTeX

```md
\\[\frac{n!}{k!(n-k)!} = \binom{n}{k}\\]
```

\\[\frac{n!}{k!(n-k)!} = \binom{n}{k}\\]

## Code (Supports many programming languages and formats)

````md
```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```
````

```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```

## Inline code

```md
Here is `var s = "Hello World"` inline code
```

Here is `var s = "Hello World"` inline code

## Tables 

```md
| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |
```

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

## Ordered List

```md
1. Number one
2. Number Two
    1. Indented Number 1
    2. Indented Number 2
```

1. Number one
2. Number Two
    1. Indented Number 1
    2. Indented Number 2

## Unordered List

```md
* Get groceries at Harris Teeter before the party
* Get a Spider Man cake
    * Chocolate or marble
    * Whipped cream frosting
* Don't forget to walk the dog before you leave
* Bring lots of plates and silverware so that we don't run out
    * Plastic Dixie brand is fine
```

* Get groceries at Harris Teeter before the party
* Get a Spider Man cake
    * Chocolate or marble
    * Whipped cream frosting
* Don't forget to walk the dog before you leave
* Bring lots of plates and silverware so that we don't run out
    * Plastic Dixie brand is fine

## Comments

```md
> This is some text that should show up as a comment. Someone may have made this comment but i'm not sure.
```

> This is some text that should show up as a comment. Someone may have made this comment but i'm not sure.

## Images

```md
![NYC Skyline](/img/nyc.jpg)
```

![NYC Skyline](/img/nyc.jpg)

## Links

```md
[Aether's Github page](https://github.com/josephhutch/aether)
```

[Aether's Github page](https://github.com/josephhutch/aether)