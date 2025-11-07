---
title: "The Debugger: RAG Based Agentic Systems Debugger"
excerpt: "RAG, LLM, Vector Database, Agent, Tool Use, Systems Connection<br/><img src='/images/debugger_picture.png'>"
collection: portfolio
---
<!-- <video width="560" height="315" controls>
  <source src="/images/drone_vid.mp4" type="video/mp4">
</video> -->
<!-- <center>
  <video width="560" height="315" controls>
    <source src="/images/drone_vid.mp4" type="video/mp4">
  </video>
</center> -->
<img src="/images/debugger_picture.png" alt="" style="display: block; margin: 0 auto;">

* AI-driven troubleshooting agent that understands logs, analyzes system behavior, and even hypothesizes root causes like an engineer would.
* It can be connected to real robots via raspberry pi and mqtt protocol along with the protocol the robot is capable of communicating over.
* It uses RAG to use the documents to provide the context to the problem being asked to the debugger.
* A vector database is used to store the indexed document embeddings.
* It can also pull logs from the robot for a given query in real time and process the information to provide better resolution.
* It uses Agentic RAG along with LLM to route the query appropriately, use the tools as needed and provide a resolution response.