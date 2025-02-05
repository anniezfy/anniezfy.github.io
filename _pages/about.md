---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

My research focuses on designing Fast Fourier Transform (FFT) processors on FPGA using Chisel and Verilog. The goal is to develop a flexible architecture adaptable to various parameters, such as parallelism, radix, and point size. Besides, I have published two patents and one conference paper related to FFT processor design.

I  am passionate about cutting-edge technology and highly self-motivated to push my limits when facing significant challenges. Moreover, I  enjoy sharing knowledge through open-source contributions and writing blogs on engineering techniques recording the solutions to complicated problems.😇

# 🔥 News
- *2024.09*: 🥳I released the [source code](https://github.com/anniezfy/FFT_MDC_Pipeline) related to the 512K-point FFT MDC pipeline architecture.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ISPA 2024</div><img src='images/top_level.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Adaptive Hybrid FFT: A Novel Pipeline and Memory-Based Architecture for Radix-$2^{k}$ FFT in Large Size Processing](https://arxiv.org/pdf/2501.01259)
**Fangyu Zhao**, Chunhua Xiao, Zhiguo Wang, Xiaohua Du,Bo Dong
</div>
</div>


# 🎖 Honors and Awards
- *2022,2023.09. Class A Scholarship, Chongqing University*
- *2022.10. Outstanding Graduate, Hefei University of Technology* 
- *2020.09. 2nd Prize, Physics Academic Competition of Anhui Province*

# 📖 Educations
- *2022.09 - 2025.06*, Chongqing Univerisity, Master of Science, Computer Science. 
- *2018.09 - 2022.06*, Hefei University of Technology, Bachelor of Engineer, Computer Science.


