---
layout: page
title: navyu_slam
# subtitle: 2D Navigation Packages
image: /assets/project/lidar_graph_slam.png
importance: 3
---

[Repository Link](https://github.com/RyuYamamoto/navyu_slam)

[Zennでの詳細説明記事](https://zenn.dev/ame_b/articles/e08cd40e7c5ec8#navyu_slam)

[robosemiでの発表スライド](https://docs.google.com/presentation/d/1Ug3iN_dS9tbv8h3ykxgRALGzIcdgnXafwgzDIzheE1s/edit?usp=sharing)

2D SLAMの実装です。現実装ではloop closeはなく、Scan Matching Odometryのみの実装になります。スキャンマッチング部分はNDT、ICPをフルスクラッチで実装しています。

<div style="display: flex; justify-content: center;">
<iframe width="560" height="315" src="https://www.youtube.com/embed/AqVtgPZ6WIc?si=zIPtEu0wTaJHwcp1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>
