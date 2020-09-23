---
layout: home
title: Home
nav_order: 1
description: "A place to collect my projects and ideas so others can build on it"
permalink: /
---

## Fluffy Systems

<div align="justify" markdown="1">
>  This is a place where I can collect my projects and ideas so others can build on them and hopefully do something cool.
{: .fs-5 .fw-400}
</div>

----

Enough people have asked to hear more about my projects that it's time I put them together in one place.  Hopefully this site will be useful to aggregate all the information I've dug up in the course of my projects and be helpful to someone doing something similar.

----

## Get in Contact

<script defer src="https://use.fontawesome.com/releases/v5.8.0/js/all.js"
    integrity="sha384-ukiibbYjFS/1dhODSWD+PrZ6+CGCgf8VbyUH7bQQNUulL+2r59uGYToovytTf4Xm"
    crossorigin="anonymous"></script>

<style type="text/css">
    .footer-help-section {
    display: flex;
    justify-content: left;
    padding: 1rem 0;
    flex-wrap: wrap;
    }

    .footer-help-box {
    padding: 0 1rem;
    text-align: center;
    }

    .footer-help-box-image {
    min-height: 64px;
    align-items: center;
    justify-content: center;
    max-height: 64px;
    }

    .footer-help-box p {
    font-size: 14px;
    display: block;
    padding: 10px 0 0 0;
    font-weight: 300;
    text-transform: uppercase;
    letter-spacing: 0.1em;
    }
</style>

<div class="footer-help-section">
    {% for i in site.social %}
        {% assign social = i[1] %}
        <div class="footer-help-box">
            <div class="footer-help-box-image"><i class="{{ social.fa-icon-class }} fa-3x"></i></div>
            <a href=" {{ social.url }}" target="_blank" class="btn">{{ social.name }}</a>
        </div>
    {% endfor %}
</div>
