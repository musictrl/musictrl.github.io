---
layout: post
read_time: true
show_date: true
title:  S2系列超高性价比飞行控制与导航系统
date:   2021-03-12 13:32:20 -0600
description: Some neural network optimization algorithms mostly to implement momentum when doing back propagation.
img: posts/20210312/nnet_optimization.jpg
tags: [coding, machine learning, optimization, deep Neural networks]
author: Armando Maynez
github: amaynez/TicTacToe/blob/7bf83b3d5c10adccbeb11bf244fe0af8d9d7b036/entities/Neural_Network.py#L199
mathjax: yes # leave empty or erase to prevent the mathjax javascript from loading
toc: yes # leave empty or erase for no TOC
---
飞行控制与导航系统是 ＵＡＶ 飞行系统设计的关键，它通过飞行控制、管理与导航等功能实现ＵＡＶ 飞行姿态控制与导航，直接关系到 ＵＡＶ 获取遥感信息的效果。目前，多数飞行控制系统主要利用经典的单回路频域或根轨迹等线性控制方法来 设 计 飞 行 控 制 与 导 航 系 统，这 种 方 式 在ＵＡＶ 工 业 领 域 得 到 了 成 功 应 用。


但 是，随 着ＵＡＶＲＳ对 ＵＡＶ 飞行性能要求的复杂化，常规的线性控制和单独的导航方法已很难满足 ＵＡＶＲＳ任务 的 实 际 需 求。近 年 来，非 线 性 动 态 控制、神经网络智能控制和组合导航等方法已有很多研究。这些新型飞行控制与导航方法能很好地从不同角度提高 ＵＡＶ 飞行性能。如神经网络自适应控制方法能提供飞行器在整个飞行模式下连续的操纵品质，较大程度上提高了 ＵＡＶ 飞行控制的稳定 性。


ＧｕｉｌｌａｕｍｅＪ．Ｊ．Ｄｕｃａｒｄ 提 出 的 基于 Ｋａｌｍａｎ滤波的完全非线性故障检测与隔离飞行控制系统，能在外部干扰和模型不确定时，保持控制与导航系统的鲁棒性，有效监测 ＵＡＶ 的健康状态，并根据系统故障与机体损伤进行重构，实现容错性飞行控制与导航，为 ＵＡＶＲＳ作业提供更高的安全性［２０］。因此，时效性、模块化和高效计算的非线性模型和多组合导航方法将是未来ＵＡＶ 飞行 控 制 与 导 航 系 统 的 主 要 发 展 方 向 之一



