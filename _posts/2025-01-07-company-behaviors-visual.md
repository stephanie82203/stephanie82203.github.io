---
date: 2025-01-07 12:26:40
layout: post
title: HR Analytics
subtitle: Lorem ipsum dolor sit amet, consectetur adipisicing elit.
description: Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
image: https://res.cloudinary.com/dm7h7e8xj/image/upload/v1559825145/theme16_o0seet.jpg
optimized_image: https://res.cloudinary.com/dm7h7e8xj/image/upload/c_scale,w_380/v1559825145/theme16_o0seet.jpg
category: projects
tags:
  - R
  - visualization
  - projects
  - portfolio
author: mscheng
---

I started this project to complete an assignment, but by the time I finished it, I realized I actually enjoyed the workflow more than expected. The process helped me understand how to present HR insights clearly and choose visuals that highlight patterns without overcomplicating the analysis. 

This project helped me get more comfortable presenting findings visually and writing concise explanations. Even though it was an assignment, it gave me a better sense of how HR data connects to performance, fairness, and company decisions. It also showed me what a full analysis workflow feels like from start to finish, and it made me want to expand on this type of work.

# Objective
This project analyzes different aspects of an organization using R, mainly through visualizations created with `ggplot2` and `lattice`. The goal was to understand patterns related to performance, diversity, recruitment, termination, and salary structure. Each visualization focuses on a specific HR question and provides a straightforward interpretation of the results.

# Results & Recommendation
The analysis focuses on five questions...

## What is the relationship between employer evaluation and employee performance score?
<div style="display: flex; justify-content: center; gap: 20px;">
  <img src="/assets/img/HRProj/avg-EP-Scores.jpg" width="48%">
</div>

Employees working under Manager Eric Dougall have the highest average performance score (mean = 3.25 , n = 4), with 25% exceeding expectations and 75% fully meeting expectations.

In contrast, Manager Debra Houlihan has the lowest average performance score (mean = 2.67, n = 3), where 66.67% of employees fully meet expectations and 33.33% require improvement.

#### Recommendations
Given the **[3.25 − 2.67 = 0.58] point difference** in average performance scores and the substantially higher proportion of high-performing employees under Eric Dougall, future employee assignments could prioritize managers with stronger performance outcomes.

Rather than punitive measures, the lower performance outcomes observed under Debra Houlihan suggest a need for **targeted managerial training or performance coaching**, focusing on improving employee development and evaluation consistency.

# Future Enhancements
When I have more time, I’d like to extend this project into something more complete:
* Build an interactive dashboard (Plotly)
* Strengthen **predictive modeling** for employee attrition
* Expand the **salary equity analysis** using statistical tests
---
🔗 **GitHub Repository:** [Company-behaviors-Visualization](https://github.com/stephanie82203/Company-behaviors-Visualization)  

















