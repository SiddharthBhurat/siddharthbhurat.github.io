---
title: 'Debugging Agents That Think Like Engineers'
date: 2025-08-14
permalink: /posts/2013/08/blog-post-2/
tags:
  - agents
  - RAG
  - llm
  - sensor data
---

In most factories, debugging a failure involves staring at logs, cross-checking sensor data, and guessing where things went wrong. My multi-stage debugging agent emulates this process. It first locates the “error tick” in the logs, analyzes correlated sensor data, builds hypotheses, and refines them with context from prior errors. It doesn’t just answer “what went wrong,” but also why — by connecting data, context, and code knowledge.


Model Base Debugging: Can LLMs Read Robot Code?
------

Phase two of The Debugger tackles a fascinating problem: code understanding. The system reads the entire codebase of a robot, summarizes its logic, error conditions, and dependencies into structured markdown, and builds a searchable knowledge graph. When an error occurs, it cross-references code and logs to find probable causes. This is a step toward robots that understand their own codebase — a foundation for self-debugging systems. This is all with the assumption that the model of the system could be infered with the code it is running