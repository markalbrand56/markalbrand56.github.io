# Hello World!
## My projects
These are some projects I'm currently working on:

# FDS
A tool built on Python to assist students in some Statistic's topics.

# Automated Media Ingest
A personal tool to automate the ingest of media from an SD card to my computer.

# My Blog
<ul>
    {% for post in site.posts %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>

## Get in touch
<ul>
    <li><a href="https://twitter.com{{ site.twitter_username }}">Twitter</a> </li>
    <li><a href="https://twitter.com{{ site.github_username }}">GitHub</a> </li>
</ul>

