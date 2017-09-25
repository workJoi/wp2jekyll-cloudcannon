---
layout: basic
permalink: /home/
---
<style>
#content {
    padding: 0;
}
#posts h2 {
 font-family: 'Helvetica Neue', 'Lato', Helvetica, Arial, sans-serif;
     font-weight: 500;
    margin: 20px;
    padding: 0;
}
#posts table {
    width: 100%;
    font-family: 'Helvetica Neue', 'Lato', Helvetica, Arial, sans-serif;
}
#posts th {
    font-weight: 500;
}
#posts th, #posts td {
    padding: 20px 10px;
    text-align: left;
}
#posts td {
    font-weight: 300;
    letter-spacing: 1px;
}
.editor-link {
  display: none;
}

.cms-editor-active .editor-link {
  display: block;
}

#posts tr:nth-of-type(odd){
    background: #f9f9f9;
}
</style>
<div id="posts">
<h2 class="clearfix">Recent Posts</h2>
<table cellspacing="0" cellpadding="0">
    <tr>
        <th>Title</th>
        <th>Author</th>
        <th>Date</th>
        <th>Status</th>
        <th></th>
    </tr>
    {% for post in site.posts %}
        {% if post.published %}{% assign status = "Published" %}{% else %}{% assign status = "Unpublished" %}{% endif %}
        <tr>
            <td><a href="{{post.url}}" target="_blank">{{post.title}}</a></td>
            <td>{{post.author}}</td>
            <td>{{post.date | date_to_string}}</td>
            <td>{{status}}</td>
            <td><a href="cloudcannon:collections/{{ post.path }}" class="editor-link">Edit</a></td>
        </tr>
    {% endfor %}
</table>


