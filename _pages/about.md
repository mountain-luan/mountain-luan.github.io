---
layout: about
title: About
permalink: /
subtitle: PhD student @ Wuhan University, Wuhan City, Hubei Province, China

profile:
  align: left
  image: bio_pic.jpg
  image_circular: false
  
  more_info: >
    <div style="display: flex; flex-wrap: wrap; align-items: center; justify-content: flex-start; margin-top: 10px; gap: 10px;">
      <a href="/assets/pdf/cv.pdf" target="_blank" style="color: var(--global-theme-color); font-weight: 800; font-size: 1.4rem; text-decoration: none; font-family: 'Roboto', sans-serif; line-height: 1;">CV</a>
      <a href="mailto:luanyy_1704@whu.edu.cn" style="color: var(--global-theme-color);" title="Email Me"><i class="fa-solid fa-envelope fa-2x"></i></a>
      <a href="https://www.linkedin.com/in/yangyang-luan-a49177335/" style="color: var(--global-theme-color);"><i class="fa-brands fa-linkedin fa-2x"></i></a>
      <a href="https://scholar.google.com/citations?hl=en&user=83fmELYAAAAJ&view_op=list_works&sortby=pubdate" style="color: var(--global-theme-color);"><i class="ai ai-google-scholar-square ai-2x"></i></a>
    </div>
    
news: true # 保持原模板设置
selected_papers: false
awards: false
social: false 

---

I am currently a Ph.D. candidate at the School of Mathematics and Statistics, Wuhan University, advised by Prof. [Xiaoqun Wu](https://maths.szu.edu.cn/info/1016/2422.htm). From Oct. 2024 to Sept. 2025, I was a Visiting Ph.D. student in the Division of Automatic Control at Linköping University, Sweden, hosted by Prof. [Claudio Altafini](https://liu.se/en/employee/claal20). Prior to my Ph.D. studies, I obtained my B.Sc. degree from the School of Mathematical Sciences at Anhui University, during which I worked with Prof. [Haifeng Zhang](https://scholar.google.com/citations?user=VHrlqpgAAAAJ&hl=en).

My research interests lie at the intersection of **Network Science** and **Control Theory**, with a particular focus on **Multi-agent Systems**. Currently, I primarily focus on **Opinion Dynamics**, which investigates the evolution of complex opinions and the emergence of collective behaviors (e.g., consensus and polarization) over social networks. My work integrates **theoretical modeling** using control-theoretic tools to uncover the mathematical mechanisms behind these social phenomena with **data-driven applications** that validate sociological hypotheses against real-world user interactions on social media. Previously, I also worked on network synchronization, link prediction, and influential spreader identification.

If you are interested in my research topics, you are more than welcome to contact me via email at [luanyy_1704@whu.edu.cn](mailto:luanyy_1704@whu.edu.cn) (preferred) or [yyluan1999@gmail.com](mailto:yyluan1999@gmail.com).

<style>
  /* 电脑端：保持原样，限制图片宽度，左浮动 */
  .profile {
    width: 20% !important;
    max-width: 250px;
    margin-right: 30px;
  }

  /* === 移动端 (屏幕小于768px) === */
  @media (max-width: 768px) {
    /* 1. 容器设置：占满全宽，给图标足够的空间不换行 */
    .profile {
      width: 100% !important; 
      max-width: 100% !important;
      float: none !important; 
      display: block !important; 
      margin-bottom: 20px !important;
    }

    /* 2. 图片单独设置：缩小并居中 */
    /* 注意：这里精准控制图片标签 img，使其不跟随容器变宽 */
    .profile img {
      width: 40% !important;  /* 图片只占屏幕宽度的 40% */
      max-width: 160px !important; /* 限制最大宽度 */
      display: block;
      margin: 0 auto !important; /* 图片水平居中 */
    }
    
    /* 3. 图标区域：居中显示 */
    .profile .more-info div {
       justify-content: center !important;
       flex-wrap: nowrap !important; /* 强制不换行 */
    }
  }
</style>
