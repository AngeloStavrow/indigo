---
title: "Featured Typefaces"
date: 2018-10-01T08:30:00-04:00
draft: false
categories: ["meta"]
tags: ["typography"]
---

Indigo uses a combination of three beautiful typefaces to render your words.

<!--more-->

- [Fira Sans][fira-sans] for heading text
- [Charter][charter] for body text
- [Fira Code][fira-code] for monospaced text

Licenses are included in the theme’s `static/fonts` folder.

Have a look at a couple of paragraphs of placeholder text using the wonderfully readable Charter:

---
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer eleifend nulla ac elit venenatis posuere. Sed id aliquam arcu, et malesuada lectus. **Donec et dignissim massa. Pellentesque in laoreet nibh. Pellentesque sagittis, libero quis vestibulum aliquam, ante risus imperdiet magna, at ornare dolor libero quis nunc.** Donec quis tempus purus. Cras ornare magna ac facilisis tristique. Nulla aliquet purus quis massa rutrum interdum ac at magna. Cras fermentum magna id orci viverra facilisis. Ut vitae lobortis nisl.

Sed interdum tincidunt venenatis. Sed hendrerit dictum nisi, at dignissim orci consectetur quis. Aenean sed nisl et nisl placerat euismod. Proin hendrerit nulla at rhoncus molestie. Cras eu gravida erat, vestibulum ornare diam. _Praesent nunc arcu, ultrices et risus sed, dictum mattis dui. Maecenas vitae nisl at massa porta pellentesque_. Donec eget urna eget nisl imperdiet scelerisque eget a mauris. Nam fringilla sem id vehicula rhoncus. Curabitur tincidunt massa mauris, facilisis placerat odio eleifend sit amet. Etiam nec vehicula sapien, at dignissim risus. Sed elit erat, lacinia eu vulputate at, semper eu nulla. Quisque a urna sed nulla viverra egestas nec quis nunc. Curabitur iaculis elit in orci sollicitudin suscipit.

---

And code snippets look great with Fira Code:

```
<article>
    <header>
    {{ if .Title }}
    <h2 class="list-title"><a href="{{ .Permalink }}">{{ .Title }}</a></h2>
    {{ end }}
    <p class="list-post-date">
        <time datetime="{{ .Date.Format "2006-01-02T15:04:05Z07:00" | safeHTML }}">
        {{ .PublishDate.Format "2 January, 2006 at 15:04 MST" }}
        </time>
    </p>
    </header>
    <div>
    {{ .Summary | plainify | safeHTML }}
    </div>
    {{ if .Truncated }}
    <p><a class="read-more" href="{{ .Permalink }}">Read more &rarr;</a></p>
    {{ end }}
</article>
```

[fira-sans]: https://bboxtype.com/typefaces/FiraSans/#!layout=specimen
[charter]: https://practicaltypography.com/charter.html
[fira-code]: https://github.com/tonsky/FiraCode