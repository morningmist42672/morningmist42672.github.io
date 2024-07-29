---
title: STM32CubeMX 更新时无法勾选版本
date: 2024-07-29 15:36:15
tags:
  - STM32CubeMX
  - STM32
categories:
  - STM32CubeMX 配置
---

## 0. 系统说明及软硬件平台

操作系统：Windows 10 22H2

软件版本：

- 旧的 STM32CubeMX 版本：Version 6.3.0
- 目标 STM32CubeMX 版本：Version 6.12.0



## 1. 问题

同事的 STM32CubeMX 的版本比我的高，导致我无法打开他的工程，于是准备升级我的 STM32CubeMX。

打开 STM32CubeMX，进入更新页面。

![从 STM32CubeMX 进入更新页面](../assets/STM32CubeMX-更新时无法勾选版本/image-20240729161859470.png)

但发现这个复选框不能勾选：

![STM32CubeMX 更新页面复选框无法勾选](../assets/STM32CubeMX-更新时无法勾选版本/image-20240729160945975.png)

## 2. 解决方法

其实这里明确说了，下载更新包是需要 ***管理员权限*** 的，所以直接以管理员身份运行 STM32CubeMX，然后就会发现这个复选框可以勾选了。

![STM32CubeMX 更新需要管理员权限](../assets/STM32CubeMX-更新时无法勾选版本/image-20240729161430846.png)
