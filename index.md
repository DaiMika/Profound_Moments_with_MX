---
layout: default
title: "Profound Moments with MX"
---

<img src="/assets/images/logo.png" alt="Profound Moments with MX" style="width:120px;">

# Welcome to Profound Moments with MX

Hi, I’m **Maxyn Edogha** — author, storyteller, and creative thinker.  
This is where I share profound reflections, narratives, and personal insights from my journey as a writer.

---

## ✍️ Latest Reflections
{% for post in site.posts limit:2 %}
- [{{ post.title }}]({{ post.url }}) <small>({{ post.date | date: "%b %d, %Y" }})</small>
{% endfor %}

---

## 📰 Latest from Medium
{% for item in site.data.medium_feed.items %}
- <a href="{{ item.link }}" target="_blank">{{ item.title }}</a>  
  <small>Published {{ item.pubDate | date: "%b %d, %Y" }}</small>
{% endfor %}

---

## 🌐 Connect with Me

- 📘 [Facebook](https://bit.ly/ProfoundMomentswithMX)
- 📸 [Instagram](https://instagram.com/maxdie_tunnie)
- ✍️ [Medium](https://medium.com/@DaiMika)
- 📚 [Selar Store](https://selar.com/m/maxyn-edogha1)
- 📖 [Amazon Author Page](https://www.amazon.com/-/e/B0FN7H1RF2)
- 💬 WhatsApp: +234 915 953 0769

