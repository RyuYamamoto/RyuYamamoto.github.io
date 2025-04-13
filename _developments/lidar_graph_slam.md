---
layout: page
title: lidar_graph_slam
# subtitle: 2D Navigation Packages
image: /assets/project/lidar_graph_slam.png
importance: 2
---

[Repository Link](https://github.com/RyuYamamoto/lidar_graph_slam)

[Zennでの詳細説明記事](https://zenn.dev/ame_b/articles/e08cd40e7c5ec8#lidar_graph_slam)

3D LiDARを用いたSLAMパッケージです。本パッケージはフロントエンド処理としてLiDARを用いたスキャンマッチングによるlidar odometry推定及び最適化候補となるキーフレームポーズ生成、バックエンド処理としてglobal map構築とループ検出及びポーズグラフ最適化による全体軌跡の修正を行っています。大まかなシステムとしては以下になります。

![navyu](/assets/project/lidar_graph_slam.png)

<div style="display: flex; justify-content: center;">
<iframe width="560" height="315" src="https://www.youtube.com/embed/hhWxuyCu7Us?si=DILO9p9_bAIIm9-9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>
