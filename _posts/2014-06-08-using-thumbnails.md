---
layout:     post
title:      Access by E-mail
date:       2002-08-22 2:02:54
summary:    Using thumbnails in your Carte Noire articles.
categories: jekyll
thumbnail: jekyll
tags:
 - Account login

---

Login with E-mail

## Images

```
jekyll: "https://imgur.com/a/TfUj0CZ"
```

You then add a `thumbnail` option to the article's frontmatter and provide the keyword
for that thumbnail.

```
thumbnail: jekyll
```

This allows you to re-use thumbnails across multiple articles without having to
specify the url each time.

## Font Awesome

If jekyll can't find a corresponding image in your `thumbnail.yml` file then it
will assume you want to use a Font Awesome icon instead. You can find the full
list of Font Awesome icons [here][4].

So for example if your article is about android and you want to use the [android icon][5]
from font awesome you can just specify the following in your frontmatter.

```
thumbnail: android
```

Then in the future if you decide you want to use your own android icon you can just
add it to `_data/thumbnails.yml` which will override it for all articles using
the android thumbnail.

[1]: http://jekyllrb.com/docs/frontmatter/
[2]: http://fortawesome.github.io/Font-Awesome/
[3]: http://imgur.com/
[4]: http://fortawesome.github.io/Font-Awesome/icons/
[5]: http://fortawesome.github.io/Font-Awesome/icon/android/
