---
title: "Install Arch Linux: the modern way"
excerpt_separator: "<!--more-->"
categories:
  - Blog
tags:
  - Installation
  - Arch Linux
  - Guide
---

# Motivation

The Linux Community introduces Bcachefs to main stream [Linux Kernel 6.7 (January 2024)](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=9e87705289667a6c5185c619ea32f3d39314eb1b). Bcachefs is the next generation linux file system format which aims on **encryption**, **compression** and **CoW**. Comparing to the legacy Btrfs which is also based on B-tree, Bcachefs ensures much better code quality. Comparing to the legacy Ext4 which is the generic standard, Bcachefs may greatly improve the longevity of the NVME driver.

I having been using Arch Linux on Ext4 file system for around 10 years. I think it's time to make a little bit forward--erase my Ext4 partition and setup Bcachefs on my NVME SSD.
