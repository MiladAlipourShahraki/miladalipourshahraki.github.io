---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
redirect_from:
  - /resume
---

My research develops controllers for nonlinear systems that are both near-optimal and provably safe. The central problem is that optimizing performance and enforcing safety pull in different directions: an optimal policy will happily drive the state into an unsafe region if the cost rewards it. My dissertation addresses this with a two-stage framework that computes an approximate value function offline (via sum-of-squares and policy iteration on the Hamilton-Jacobi-Bellman equation) and then enforces safety online through a control-barrier-function quadratic program. This decouples performance from constraint enforcement: the safe set can be modified online without recomputing the value function. I have also designed real-time CLF/CBF-QP controllers for spacecraft attitude control under reaction-wheel torque and momentum limits, treating state and input bounds as hard constraints. These methods matter wherever a system must act efficiently while respecting hard safety limits, such as aerospace and autonomous systems.

<!---
{% raw %}
<iframe src="https://miladalipourshahraki.github.io/side_by_side_spacecraft_attitude_control_animation.html" width="1000" height="300"></iframe>
{% endraw %}


{% raw %}
<div style="width: 600px; height: 400px; overflow: hidden; border: 1px solid black;">
  <iframe src="https://miladalipourshahraki.github.io/side_by_side_spacecraft_attitude_control_animation.html" width="100%" height="100%" style="border: none;"></iframe>
</div>
{% endraw %}
-->

{% raw %}
<div style="width: 950px; height: 500px; overflow: hidden; border: 1px solid black; position: relative;">
  <iframe src="https://miladalipourshahraki.github.io/side_by_side_spacecraft_attitude_control_animation.html" style="
    width: 1700px;  /* Scale width */
    height: 900px;  /* Scale height */
    transform: scale(0.6); /* Adjust scale (1 = original size, 0.5 = half size) */
    transform-origin: top left;
    border: none;
    position: absolute;
    top: 0;
    left: 0;
  "></iframe>
</div>
{% endraw %}

{% raw %}
To view the animation in a new tab click <b><a href="https://miladalipourshahraki.github.io/side_by_side_spacecraft_attitude_control_animation.html" target="_blank" style="text-decoration:none; color:#2F4F4F">here</a>.
{% endraw %}

{% include base_path %}

