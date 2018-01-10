---
layout: post
title: "Designing an Operating System - I"
date: 2018-01-07
---

# Designing an Operating System - I

We (I along with two other super-talented blokes) designed an Operating System in three phases across the Fall of 2017. The three phases were:
* Threads and Scheduling
* Pseudo-virtual memory
* Simple File System

This writeup details out our second phase of implementation.

## Pseudo-virtual memory

We implemented a pseudo-virtual memory for our thread library.