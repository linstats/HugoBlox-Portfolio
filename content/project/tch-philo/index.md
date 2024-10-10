---
title: My Philosophy of Teaching
summary: My approach to teaching and using statistics.
tags:
  - Teaching
date: 2024-09-15
---

One of my favorite professors, Cai Jingheng (蔡敬衡), once said: *“True discoveries or creations are not made by statisticians themselves, but by other scientists. Yet, almost all of them rely on an indispensable tool: statistics.”* I like this word and believe that the power of statistics lies not only in its mathematical rigor but in its ability to help us make sense of the world. I find immense joy in sharing statistical concepts with others—whether with friends, peers, roommates, or family—and I am committed to promoting the broad application of statistical methods across diverse fields.

To encourage the broad and accurate use of statistics, I believe visualization is a powerful tool for understanding complex statistical concepts. Through visual techniques, abstract ideas become more accessible and intuitive, helping people, regardless of their background, to grasp the core of statistical thinking. This is what I continuously pursue in my teaching and sharing. Below is an example of the suppport vector machines, where visualization aids understanding.

<table>
  <tr>
    <td style="width: 50%; vertical-align: top;">
      <strong>Definition</strong>:<br>
      A <strong>separating hyperplane</strong> $\mathcal{L}$ in $\mathbb{R}^p$ is a collection of points in the following form:<br><br>
      $$
      \mathcal{L} = \left\{ \mathbf{x} \in \mathbb{R}^p : \beta_0 + \boldsymbol{\beta}^{\top} \mathbf{x} = 0 \right\},
      $$  
      where $\beta_0 \in \mathbb{R}$ and $\boldsymbol{\beta} \in \mathbb{R}^p$.<br><br>
      In practical terms, this hyperplane is used to separate different classes in a dataset, making it a fundamental component of machine learning models like support vector machines.
    </td>
    <td style="width: 50%; vertical-align: top;">
      <img src="/images/teaching-fig1.jpg" alt="Teaching-SVM" style="width: 100%;">
    </td>
  </tr>
</table>