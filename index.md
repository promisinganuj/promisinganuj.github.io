---
layout: home
title: Home
---

# Hi, I'm Anuj 👋

I’m a Principal Software Engineer working across **Data, AI, and Generative Systems**.

I write about:
- AI and its impact on our lives  
- Data engineering & architecture  
- Building systems that actually matter  

---

## ✨ Featured Post

### [A Selfish Perspective on Staying Human in the Age of AI](/2026/02/20/staying-human-ai.html)

AI is making us faster, more capable, and more productive.

But it’s also changing how we think, how we spend time, and how we live.

In this post, I explore:
- AI fatigue and cognitive overload  
- The hidden addiction loop of “vibe coding”  
- Why productivity gains don’t always translate to better lives  
- And how to consciously **stay human in the loop**  

👉 *Read the full post and reflect on what you want AI to optimize for.*

---

## 🧠 What I'm Exploring

- Multi-agent AI systems  
- LLMOps and real-world deployment patterns  
- The intersection of productivity and human well-being  

---

## 🤝 Let’s Connect

If this resonates with you, feel free to connect or reach out.

- LinkedIn: https://www.linkedin.com/in/promisinganuj/
- GitHub: https://github.com/promisinganuj  

---

## 📝 Latest Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> — <small>{{ post.date | date: "%b %d, %Y" }}</small>
    </li>
  {% endfor %}
</ul>