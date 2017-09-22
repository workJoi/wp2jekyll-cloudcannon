---
layout: basic
_options:
  image_path:
    resize_style: "contain"
    mime_type: "image/jpeg"
    expandable: true
  content:
    resize_style: "contain"
    mime_type: "image/png"
    expandable: true
---
<link href="https://fonts.googleapis.com/css?family=Open+Sans+Condensed:300,700" rel="stylesheet">
<link rel="stylesheet" href="https://www.newtek.com/css/layouts/press-release.css">
<link rel="stylesheet" href="https://www.newtek.com/css/layouts/post.css">

<style>
    #post-banner {
        background-image: url({{page.featured-img}});
    }
</style>

<div id="post-banner">
    <a href="{{page.image.feature}}" class="venobox" title="{{page.title}}" data-gall="gallery"></a>
</div>
<div id="press-release">



    <h1 class="title">{{page.title}}</h1>

    <p style="font-size: 12px; font-style: italic; font-weight: 500; color: #212121;">{{ page.date | date: "%B %d, %Y" }} by {{ site.data.uk-blog.authors[page.author]['name'] }}</p>

    <div id="post-share">
        <p style="padding: 10px; border: 1px solid rgba(0,0,0,0.2);">Social Share Buttons Here</p>
    </div>
    <div id="blog" class="clearfix">
        {{content}}
    </div>
    <hr>
    <div id="post-footer">
        <p><i class="fa fa-folder" aria-hidden="true"></i> {% for cat in page.categories %} {{cat}},&#32; {% endfor %}
        </p>
        <p><i class="fa fa-tags" aria-hidden="true"></i> {% for tag in page.tags %} {{tag}},&#32; {% endfor %}
        </p>
    </div>
</div>

