---
layout: about
title: About
permalink: /
subtitle: PhD student @ Wuhan University, Wuhan City, Hubei Province, China

profile:
  align: left
  image: bio_pic.png
  image_circular: false
  more_info: >
    <div style="display: flex; align-items: center; justify-content: flex-start; margin-top: 10px;">
      <a href="/assets/pdf/cv.pdf" style="color: var(--global-theme-color); font-weight: 800; font-size: 1.4rem; text-decoration: none; margin-right: 12px; font-family: 'Roboto', sans-serif; line-height: 1;">CV</a>
      <a href="mailto:luanyy_1704@whu.edu.cn" style="color: var(--global-theme-color); margin-right: 12px;" title="Email Me"><i class="fa-solid fa-envelope fa-2x"></i></a>
      <a href="https://www.linkedin.com/in/yangyang-luan-a49177335/" style="color: var(--global-theme-color); margin-right: 12px;"><i class="fa-brands fa-linkedin fa-2x"></i></a>
      <a href="https://scholar.google.com/citations?hl=en&user=83fmELYAAAAJ&view_op=list_works&sortby=pubdate" style="color: var(--global-theme-color);"><i class="ai ai-google-scholar-square ai-2x"></i></a>
    </div>
   
news: false # includes a list of news items
selected_papers: false # includes a list of papers marked as "selected={true}"
awards: false
social: false # includes social icons at the bottom of the page

---

<div class="clearfix" style="text-align: justify;">
  <p>
    I am currently a Ph.D. candidate at the School of Mathematics and Statistics, Wuhan University, advised by Prof. <a href="https://maths.szu.edu.cn/info/1016/2422.htm" target="_blank">Xiaoqun Wu</a>. 
    From Oct. 2024 to Sep. 2025, I was a Visiting Ph.D. student in the Division of Automatic Control at Linköping University, Sweden, hosted by Prof. <a href="https://liu.se/en/employee/claal66" target="_blank">Claudio Altafini</a>.
    Prior to my Ph.D. studies, I obtained my B.Sc. degree from the School of Mathematical Sciences at Anhui University, during which I worked with Prof. <a href="https://scholar.google.com/citations?user=VHrlqpgAAAAJ&hl=en" target="_blank">Haifeng Zhang</a>.
  </p> 

  <p>
    My research generally lies at the intersection of Control Theory and Network Science. 
    Currently, I primarily focus on **Opinion Dynamics**. This involves modeling how individuals update their beliefs over social networks using *control-theoretic tools*, as well as conducting *data-driven analysis* based on real-world user interactions on social media.
    Previously, I also worked on network synchronization, link prediction, and influential spreader identification.
  </p>
  
  <p>
    If you are interested in my research topics, you are more than welcome to contact me via email at luanyy_1704@whu.edu.cn (preferred) or yyluan1999@gmail.com.
  </p>
</div>

{% if site.announcements.enabled %}
  <h2 style="margin-top: 30px; border-bottom: 1px solid #e0e0e0; padding-bottom: 10px; font-size: 1.5rem; font-weight: bold; color: inherit;">
    <a href="{{ '/news/' | relative_url }}" style="color: inherit; text-decoration: none;">News</a>
  </h2>
  {% include news.liquid limit=true %}
{% endif %}
