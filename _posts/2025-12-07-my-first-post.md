---
layout: default
title: "Reducing False Positives in AF/AFL Detection – My Capstone Project"
date: 2025-12-07
---

For my Master of Predictive Analytics capstone at Curtin University, I built a **two-stage validator** for Atrial Fibrillation (AF) and Atrial Flutter (AFL).

- Stage 1: HuBERT-ECG embeddings + classifier  
- Stage 2: Clinical feature validator (RR/HRV metrics & flutter-band power)  

The goal is to reduce **false positives** so clinicians can focus on truly at-risk patients while cutting down time and cost.

I’ll use this blog to break down the dataset, modelling approach, and key results in more detail.
