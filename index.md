---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: Portfolio
---

## 自己紹介

#### Ryu Yamamoto(山本 龍)

自動運転や自律移動ロボットの開発。自己位置推定とかSLAMとか。  
個人で自律移動ソフトウェアパッケージ開発やつくばチャレンジ、RoboCupなどやったりしています。

## 経歴

- 2020/2 〜
  - [TIER IV inc](https://tier4.jp/).
  - 自動運転システムの開発。主にLocalization / Mappingを担当
  - 自動運転バスのインテグレーションやOSS開発
- 2018/4 〜 2020/1
  - [SoftBank inc](https://www.softbank.jp/).
  - コミュニケーションロボット「Pepper」のBtoB向けアプリ開発や自律移動機能開発を担当
  - 屋外自律移動ロボット開発に参加しソフトウェアを担当。つくばチャレンジ2019に参加
- 2016/3 〜 2018/3
  - 千葉工業大学大学院 工学研究科 未来ロボティクス専攻
  - ヒューマノイドロボットの歩行パターン生成に関する研究
- 2012/4 〜 2016/3
  - 千葉工業大学 工学部 未来ロボティクス学科
  - RoboCupチーム「[CIT Brains](https://citbrains.studio.site/)」に所属。2015年世界大会にてKid Sizeリーグ優勝

***

## Development

{% assign sorted_developments = site.developments | sort: "importance" %}
{% for development in sorted_developments %}
- [{{ development.title }}]({{ development.url | relative_url }}) {% if development.icon %}{{ development.icon }}{% endif %}
{% endfor %}

## Project

{% assign sorted_projects = site.projects | sort: "importance" %}
{% for project in sorted_projects %}
- [{{ project.title }}]({{ project.url | relative_url }}) {% if project.icon %}{{ project.icon }}{% endif %}
{% endfor %}
