# ckalandk's Blog

Welcome to my new blog! I'm hosting this on GitHub Pages 🚀

This blog is where I'll share what I'm learning and building, especially around:

* ⚡ C++ and High-Performance Programming
* 🧠 Algorithms and Data Structures
* 🧵 Concurrency and Multithreading
* 🐍 Python for Automation and Tools
* 🔬 Numerical Methods and Applied Mathematics
* 🛠️ Systems Programming and Low-Level Concepts
* 🚀 My Personal Projects and Experiments

I'm excited to document my journey, share insights, and build things in public.

---

## My Blog Posts

{% for post in site.posts %}
* [{{ post.title }}]({{ site.baseurl }}{{ post.url }}) - *{{ post.date | date: "%B %d, %Y" }}*
{% endfor %}
