---
permalink: /
title: "About me"
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

I am a PhD candidate working under the supervision of Pr. <a href="https://dse.in.tum.de/bhatotia/">Pramod Bhatotia</a> at the Technical University of Munich (TUM).
My research explores the broad topic of OS design for performance-critical use-cases such as database systems or HPC applications. I am interested in specializing the OS to better interface with the application above and the hardware below.

{% comment %}
# 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.
{% endcomment %}

# 📝 Publications 

{% comment %}
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
{% endcomment %}

<div class='paper-box-text' markdown="1">
- [uCache: A Customizable Unikernel-based IO Cache](https://dse.in.tum.de/wp-content/uploads/2025/10/MorphOS-CoNEXT-2025.pdf). FAST'26
<br/>&nbsp;**Ilya Meignan**--**Masson**, Masanori Misono, Viktor Leis, Pramod Bhatotia

- [MorphOS: An Extensible Networked Operating System](https://dse.in.tum.de/wp-content/uploads/2025/10/MorphOS-CoNEXT-2025.pdf). CoNEXT'25
<br/>&nbsp;Peter Okelmann, **Ilya Meignan**--**Masson**, Masanori Misono, Pramod Bhatotia
<br/>&nbps; 🏆 Finalist — Best Paper Award

{% comment %}
[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
{% endcomment %}
</div>

{% comment %}
- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**
{% endcomment %}

{% comment %}
# 🎖Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
{% endcomment %}

# 📖 Education
- *2023.11 - now*, PhD of Computer Science, Technical University of Munich, Germany
- *2021.09 - 2023.06*, Master of Computer Science ([MoSIG](https://mosig.imag.fr/MainEn/HomePage)), Université Grenoble Alpes, France
- *2018.09 - 2021.06*, Bachelor of Computer Science (🇫🇷 *Licence d'informatique*), Université de Bourgogne, France

{% comment %}
# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
{% endcomment %}
