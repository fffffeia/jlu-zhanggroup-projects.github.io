---
title: Home
---

# jlu-zhanggroup-projects

该网站为吉林大学建设工程学院[张文老师](https://baike.baidu.com/item/%E5%BC%A0%E6%96%87/22934192)的国家优秀青年科学基金（项目号：42022053）专属网站! 
<br>

<b>项目简介: </b>
该项目xxxxxxx.


{% include section.html full=true %}

{% include banner.html image="images/banner.jpg" %}

{% include section.html %}

# Highlights

{% capture text %}
项目简介：.

{%
  include link.html
  link="项目简介"
  text="了解项目"
  icon="图标"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/publications.jpg"
  link="项目简介"
  title="项目简介"
  text=text
%}

{% capture text %}
项目成果：.

{%
  include link.html
  link="项目成果"
  text="看该项目取得的成果"
  icon="图标"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/research.jpg"
  link="项目成果"
  title="项目成果"
  flip=true
  text=text
%}

{% capture text %}
项目人员：  

{%
  include link.html
  link="项目人员"
  text="认识该项目涉及的人员"
  icon="图标"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/teams.jpg"
  link="项目人员"
  title="项目人员"
  text=text
%}"
