---
title: "Misusing Tools in Large Language Models With Visual Adversarial Examples"
tags:
  - "LLM"
  - "Security"
date: Jun 2023 - Present
authors:
  - name: "advised by Earlence Fernado and Taylor Bert."
path: "research/llm_security"
excerpt: Large Language Models (LLMs) are being enhanced with the ability to use tools and to process multiple modalities. These new capabilities bring new benefits and also new security risks. In this work, we show that an attacker can use visual adversarial examples to cause attacker-desired tool usage. For example, the attacker could cause a victim LLM to delete calendar events, leak private conversations and book hotels. Different from prior work, our attacks can affect the confidentiality and integrity of user resources connected to the LLM while being stealthy and generalizable to multiple input prompts. We construct these attacks using gradient-based adversarial training and characterize performance along multiple dimensions. We find that our adversarial images can manipulate the LLM to invoke tools following real-world syntax almost always (~98%) while maintaining high similarity to clean images (~0.9 SSIM). Furthermore, using human scoring and automated metrics, we find that the attacks do not noticeably affect the conversation (and its semantics) between the user and the LLM.
selected: true
cover: "./llm-attack.png"
links:
  - name: "Paper(Arxiv)"
    url: "https://arxiv.org/abs/2310.03185"
priority: -20
---