---
layout: default
title: "Welcome to Roleplaying Adventures"
---

<div class="hero">
    <h1>Welcome to My ESO Blog</h1>
    <p>Join us on an exciting journey through the world of ESO Roleplaying Adventures.</p>
</div>

<div class="latest-posts">
    <h2>Latest Posts</h2>
    <ul>
        {% for post in site.posts %}
            <li>
                <a href="{{ YEAR-MONTH-DAY-title.md | relative_url }}">{{ YEAR-MONTH-DAY-title.md }}</a>
                <p>{{ post.excerpt }}</p>
            </li>
        {% endfor %}
    </ul>
</div>

<div class="about-section">
    <h2>About Us</h2>
    <p>Welcome to Roleplaying Adventures, where we share stories and tips about the amazing world of Elder Scrolls Online.</p>
</div>

<div class="contact-section">
    <h2>Contact Us</h2>
    <p>If you have any questions, feel free to reach out!</p>
    <a href="{{ '/contact/' | relative_url }}">Contact Page</a>
</div>
