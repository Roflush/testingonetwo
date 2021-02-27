# Guest posting for Para guide

Para welcomes all guest posting about topics the site is about. 

We allow many ways to guess post. Para Capone uses a site called "[Prose]" to add post to the site.

ParaGuide is a [static site] while that doesn't mean much for you (guest posting) it's just good to know about. A [Static site] is a site that all of it's webpages are prerended. This means that content on the site doesn't change, and is the same for everyone. While you can use stuff like JavaScript to add "Changes" that is outside of this overview. 

ParaGuide is built/uses a static site generator called [orchid] (Kotlin port), that generator uses [Markdown] in place of [HTML]. So you do need to know Markdown or look up a cheat sheet online. The generator also allows us to use addons to markdown for meta data and other things. Meta data is stuff like the date, title, author, and other stuff. I will be going over all of this in post.

[Static site]: https://en.wikipedia.org/wiki/Static_web_page
[Markdown]: https://www.markdownguide.org/
[orchid]: https://orchid.run/
[HTML]: https://en.wikipedia.org/wiki/HTML

## Getting started.

The first thing you want to is figure out if you want to use something like [Prose] or [Fork us on github] or send in by [email]. 

## How to do the github way.
The easest way to is [Fork] our repo on [github], Then added your post to [/src/orchid/resources/posts] (the sub folder it goes into i.e eve, games, random etc..). 

After you get it forked you are going to want to open the project in a "Markdown eidtor". We use [Prose], you can use whatever you want. For the tutoral we are going to be guessing that you are using [Prose]. 

Your working Dir or folder is _"/src/orchid/resources/posts/{category here}"_ (Like said before). 

[Fork]: https://guides.github.com/activities/forking/
[github]: https://github.com/Roflush/testingonetwo
[/src/orchid/resources/posts]: https://github.com/Roflush/testingonetwo/tree/master/src/orchid/resources/posts
[Prose]: https://prose.io/
[Fork us on github]: https://github.com/Roflush/testingonetwo
[email]: mailto:roflush@pm.me

## How to name your file.
This is very important to follow, or your post may not be seen on Paraguide. 

```
year-month-day-slug.md
```
You want to make sure your slug doesn't have numbers, or punctuation. It has a chance to throw off the complier. 

A slug is basically a url title? It's like a title but not. 

No space is allowed you have to use "-".


## Getting the right meta data.

Meta data is really easy it goes at the top of your .md file and looks like this

```
---
title: To the moon

author: "author fam"

featuredImage: assets/media/pic1.png

tags:

- tag1

---

```

That is a basic meta data layout if you would like to learn more. Checkout the docs [here].


# If you need more help

MarkDown has a guide on their site that can be found [here].

You can embed YouTube videos with [OrchidWritersBlock]

More info about meta data can be found [OrchidPosts]

[here]: https://www.markdownguide.org/getting-started/
[OrchidWritersBlock]: https://orchid.run/plugins/orchidwritersblocks
[OrchidPosts]: https://orchid.run/plugins/orchidposts
