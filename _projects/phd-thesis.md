---
layout: default
title: Pd.D.
date: 2023-11-09 
description: A brief description of the project.
github_url: https://github.com/yourusername/my-project
demo_url: https://myproject.example.com  # Optional demo link
image: /assets/img/my-project-screenshot.png # Optional screenshot
tags: [python, django, web development]
---

# My Project

{{ page.description }}

## Features

*   Feature 1
*   Feature 2

## Technologies Used

*   Python
*   Django
*   PostgreSQL

## Source Code

[View on GitHub]({{ page.github_url }})

{% if page.demo_url %}
  ## Demo

  [Live Demo]({{ page.demo_url }})
{% endif %}

{% if page.image %}
  ![My Project Screenshot]({{ page.image }})
{% endif %}
