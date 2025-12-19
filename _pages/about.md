---
layout: default
title: About
---
<div class="post">
  <header class="post-header">
    <h1 class="post-title">
      <span class="font-weight-bold">{{ site.first_name }}</span> {{ site.middle_name }} {{ site.last_name }}
    </h1>
    <p class="desc">{{ page.subtitle }}</p>
  </header>

  <article>
    {% if page.profile %}
      <div class="profile float-{% if page.profile.align == 'left' %}left{% else %}right{% endif %}" style="width: 30%; min-width: 150px; margin: 20px;">
        {% if page.profile.image %}
          {% assign profile_image_path = page.profile.image | prepend: 'assets/img/' %}
          {% assign profile_image_class = 'img-fluid z-depth-1 rounded' %}
          {% capture sizes %}(min-width: {{ site.max_width }}) {{ site.max_width | minus: 30 | times: 0.3}}px, (min-width: 576px) 30vw, 95vw{% endcapture %}
          {% include figure.liquid loading="eager" path=profile_image_path class=profile_image_class sizes=sizes alt=page.profile.image cache_bust=true %}
        {% endif %}
        
        <div class="more-info" style="margin-top: 15px;">
           <div style="display: flex; align-items: center; justify-content: center;">
              <a href="/assets/pdf/cv.pdf" target="_blank" style="color: var(--global-theme-color); font-weight: 800; font-size: 1.4rem; text-decoration: none; margin-right: 15px; font-family: 'Roboto', sans-serif; line-height: 1;">CV</a>
              <a href="mailto:luanyy_1704@whu.edu.cn" style="color: var(--global-theme-color); margin-right: 15px;" title="Email"><i class="fa-solid fa-envelope fa-2x"></i></a>
              <a href="https://www.linkedin.com/in/yangyang-luan-a49177335/" style="color: var(--global-theme-color); margin-right: 15px;"><i class="fa-brands fa-linkedin fa-2x"></i></a>
              <a href="https://scholar.google.com/citations?hl=en&user=83fmELYAAAAJ&view_op=list_works&sortby=pubdate" style="color: var(--global-theme-color);"><i class="ai ai-google-scholar-square ai-2x"></i></a>
           </div>
        </div>
      </div>
    {% endif %}

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
      <h2 style="margin-top: 40px; border-bottom: 1px solid #eee; padding-bottom: 10px; font-size: 1.5rem; font-weight: bold;">
        <a href="{{ '/news/' | relative_url }}" style="color: inherit">News</a>
      </h2>
      {% include news.liquid limit=true %}
    {% endif %}

    {% if page.social %}
      <div class="social">
        <div class="contact-icons">{% include social.liquid %}</div>
        <div class="contact-note">{{ site.contact_note }}</div>
      </div>
    {% endif %}
  </article>
</div>
