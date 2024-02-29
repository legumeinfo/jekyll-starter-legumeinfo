---
layout: blog-post
title: Example Post
author: Alan Cleary
summary: This is the primary example of a blog post and should be used as a reference for creating your own.
---

This is a blog post.
As you may have noticed, the file extension in the source code is `.md` instead of `.html`.
That's because the post is written in [Markdown](https://www.markdownguide.org/) and compiled by Jekyll into HTML.
If there's something you need to do that's not supported by Markdown, don't fret, Jekyll allows you to use HTML in Markdown files.
Jekyll also supports the [Liquid](https://jekyllrb.com/docs/liquid/) templating language in Markdown files so you can use it in your blog posts to better integrate them with the rest of your site.

## Snow Pea

<i>Pisum sativum var. macrocarpum</i>, or _Snow Pea_, is the mascot of the Legume Information System.
An image of its flower is included here as an example of how to integrate Markdown, HTML, and Liquid in a blog post.
Click the image to view it in a lightbox!

<div uk-grid uk-lightbox>
    <a class="uk-inline" href="{{ site.logo }}" data-caption="The flower of <em>Snow Pea</em> in all its glory.">
        <img src="{{ site.logo }}" alt="">
    </a>
</div>
