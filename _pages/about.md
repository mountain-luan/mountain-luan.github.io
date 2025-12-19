---
layout: about
permalink: /
title: About
description: >
  PhD student @ Wuhan University, Wuhan City, Hubei Province, China

# 1. 个人资料设置 (保持原模板样式)
profile:
  align: right          # 照片在右边 (如果不喜欢可以改为 left)
  image: bio_pic.png
  image_circular: false # 方形照片
  
  # 2. 这里是放 CV、Email、Scholar 图标的最佳位置
  more_info: >
    <div style="margin-top: 5px;">
      <a href="/assets/pdf/cv.pdf" target="_blank" style="color: var(--global-theme-color); font-weight: 800; font-size: 1.2rem; margin-right: 10px; text-decoration: none; font-family: 'Roboto', sans-serif;">CV</a>
      <a href="mailto:luanyy_1704@whu.edu.cn" style="color: var(--global-theme-color); margin-right: 10px;" title="Email"><i class="fa-solid fa-envelope fa-xl"></i></a>
      <a href="https://www.linkedin.com/in/yangyang-luan-a49177335/" style="color: var(--global-theme-color); margin-right: 10px;"><i class="fa-brands fa-linkedin fa-xl"></i></a>
      <a href="https://scholar.google.com/citations?hl=en&user=83fmELYAAAAJ&view_op=list_works&sortby=pubdate" style="color: var(--global-theme-color);"><i class="ai ai-google-scholar-square ai-xl"></i></a>
    </div>

# 3. 关键设置：关闭自动 News，我们在正文中手动加，以便控制字号
news: false  
selected_papers: false
social: true  # 开启页面底部的社交图标
---

<div class="clearfix" style="text-align: justify;">
  <p>
    I am currently a Ph.D. candidate at the School of Mathematics and Statistics, <strong>Wuhan University</strong>, advised by Prof. <a href="https://maths.szu.edu.cn/info/1016/2422.htm" target="_blank">Xiaoqun Wu</a>. 
    From Oct. 2024 to Sept. 2025, I was a Visiting Ph.D. student in the Division of Automatic Control at <strong>Linköping University</strong>, Sweden, hosted by Prof. <a href="https://liu.se/en/employee/claal66" target="_blank">Claudio Altafini</a>.
    Prior to my Ph.D. studies, I obtained my B.Sc. degree from the School of Mathematical Sciences at <strong>Anhui University</strong>, during which I was fortunate to work with Prof. <a href="https://scholar.google.com/citations?user=k3Kmv4QAAAAJ&hl=en" target="_blank">Haifeng Zhang</a>.
  </p> 

  <p>
    My research generally lies at the intersection of <strong>Control Theory</strong> and <strong>Network Science</strong>. 
    Currently, I primarily focus on <strong>Opinion Dynamics</strong>. This involves modeling how individuals update their beliefs over social networks using control-theoretic tools, as well as conducting data-driven analysis based on real-world user interactions on social media.
    Previously, I also worked on network synchronization, link prediction, and influential spreader identification.
  </p>
  
  <p>
    If you are interested in my research topics, you are more than welcome to contact me via email at <code>luanyy_1704@whu.edu.cn</code> (preferred) or <code>yyluan1999@gmail.com</code>. My office is located at the School of Mathematics and Statistics, Wuhan University.
  </p>
</div>

{% if site.announcements.enabled %}
  <h2 style="margin-top: 30px; border-bottom: 1px solid #e0e0e0; padding-bottom: 10px; font-size: 1.5rem; font-weight: bold; color: inherit;">
    <a href="{{ '/news/' | relative_url }}" style="color: inherit; text-decoration: none;">News</a>
  </h2>
  {% include news.liquid limit=true %}
{% endif %}
