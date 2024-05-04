---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

>"Swarm-LIO: Decentralized Swarm LiDAR-inertial Odometry", **Fangcheng Zhu**, Yunfan Ren, Fanze Kong, Huajie Wu, Siqi Liang, Nan Chen, Wei Xu, Fu Zhang, IEEE International Conference on Robotics and Automation (ICRA), 2023,  [paper](https://arxiv.org/abs/2209.06628), [video](https://youtu.be/MxeoKVXrmEs?si=kALhe8zFAKjvvuAJ)



>”Robust Real-time LiDAR-inertial Initialization”, **Fangcheng Zhu**, Yunfan Ren, Fu Zhang., IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), 2022, [paper](https://arxiv.org/abs/2202.11006), [video](https://youtu.be/WiHgcPpKwvU?si=QWxIVTfe0XeEjcuS)

























{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
