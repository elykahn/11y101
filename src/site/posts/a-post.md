---
title: A post page
date: 2018-03-21
---

https://www.reddit.com/r/ipad/comments/ff0ha7/educational_film_from_1967_predicts_the_tech_we/?utm_source=share&utm_medium=web2x

There's not much here in the sample post page. Better get to work.

The common front-matter data for all of the files in the posts section are abstracted into a `posts.json` file so that we don't need to repeat that on every file. Handy.

It looks like this:

```js
{
  "layout" : "layouts/post.md",
  "tags" : "post",
  "templateEngineOverride": "njk,md"
}
```


