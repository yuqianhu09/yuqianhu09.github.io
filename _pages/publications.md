---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Journal Articles
======
* Guozhen Zhu, **Yuqian Hu**, Beibei Wang, Chenshu Wu, Xiaolu Zeng, K. J. Ray Liu, "WI-MOID: Human and Non-Human Motion Discrimination Using WiFi With Edge Computing," in IEEE Internet of Things Journal, Dec., 2023.
* **Yuqian Hu**, Muhammed Zahid Ozturk, Beibei Wang, Chenshu Wu, Feng Zhang, K. J. Ray Liu, "Robust Passive Proximity Detection Using Wi-Fi," in IEEE Internet of Things Journal, vol. 10, no. 7, pp. 6221-6234, 1 April, 2023, doi: 10.1109/JIOT.2022.3224701.
* Sai Deepika Regani, Beibei Wang, **Yuqian Hu**, K. J. Ray Liu, "GWrite: Enabling Through-the-Wall Gesture Writing Recognition Using WiFi," in IEEE Internet of Things Journal, vol. 10, no. 7, pp. 5977-5991, 1 April1, 2023, doi: 10.1109/JIOT.2022.3224313.
* **Yuqian Hu**, Beibei Wang, C. Wu and K. J. R. Liu, "mmKey: Universal Virtual Keyboard Using A Single Millimeter-Wave Radio," in IEEE Internet of Things Journal, vol. 9, no. 1, pp. 510-524, 1 Jan., 2022, doi: 10.1109/JIOT.2021.3084560. 
* **Yuqian Hu**, Feng Zhang, Chenshu Wu, Beibei Wang and K. J. Ray Liu, "DeFall: Environment-Independent Passive Fall Detection Using WiFi," in IEEE Internet of Things Journal, vol. 9, no. 11, pp. 8515-8530, 1 June, 2022, doi: 10.1109/JIOT.2021.3116136. [[IEEE Explore]](https://ieeexplore.ieee.org/document/9552243)
* Chenshu Wu, Feng Zhang, **Yuqian Hu** and K. J. Ray Liu, "GaitWay: Monitoring and Recognizing Gait Speed Through the Walls," in IEEE Transactions on Mobile Computing, vol. 20, no. 6, pp. 2186-2199, 1 June 2021, doi: 10.1109/TMC.2020.2975158. [[IEEE Explore]](https://ieeexplore.ieee.org/document/9003416)


Conference Papers
======


Selected Patent Applications
======

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
