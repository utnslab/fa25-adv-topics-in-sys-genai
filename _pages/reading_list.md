---
layout: page
permalink: /reading-list/
title: ""
---

## Part 1 - LLMs: Backbone of Modern AI
#### Introduction
<ul>
  {% include paper_item.html key="illtransformer" required=true %}
  <li>
    <b>(Required)</b> <a href="https://arxiv.org/pdf/2407.21783">The Llama 3 Herd of Models</a> (Sections 2, 3.3, and 4.1), <br/><em>Llama Team, AI @ Meta</em>
  </li>
  {% include paper_item.html key="megatron-sc21" required=true %}
</ul>


#### Scaling LLM Pre-Training
<ul>
  {% include paper_item.html key="wlbllm-osdi25" required="Context Parallelism" %}
  {% include paper_item.html key="hotspa-sosp24" %}
  {% include paper_item.html key="alpa-osdi22" required="Auto Parallelism" %}
  {% include paper_item.html key="partir-asplos25" %}
  {% include paper_item.html key="rdma-sigcomm24" required="Network" %}
  {% include paper_item.html key="cassini-nsdi24" %}
  {% include paper_item.html key="traincheck-osdi25" required="Silent Data Corruption" %}
  {% include paper_item.html key="superbench-atc24" %}
  {% include paper_item.html key="oobleck-sosp23" required="Fault-Tolerance" %}
  {% include paper_item.html key="tenplex-sosp24" %}
</ul>

#### LLM Post-Training for Alignment
<ul>
  {% include paper_item.html key="hybridflow-eurosys25" required="Resource Efficiency" %}
  {% include paper_item.html key="rlhfuse-nsdi25" %}
  {% include paper_item.html key="areal-arxiv25" required="Async RL" %}
  {% include paper_item.html key="asyncrlhf-iclr25" %}
</ul>

#### Efficient LLM Serving
<ul>
  {% include paper_item.html key="pagedattention-sosp23" required="KV Cache Management" %}
  {% include paper_item.html key="orca-osdi22" %}
  {% include paper_item.html key="nanoflow-osdi25" required="Optimal Throughput" %}
  {% include paper_item.html key="sarathiserve-osdi24" %}
  {% include paper_item.html key="distserve-osdi24" required="Prefill/Decode Disaggregation" %}
  {% include paper_item.html key="loongserve-sosp24" %}
  {% include paper_item.html key="waferllm-osdi25" required="New Hardware" %}
  {% include paper_item.html key="aqua-asplos25" %}
</ul>

#### Mixture-of-Experts
<ul>
  {% include paper_item.html key="switch-jmlr22" required="MoE Motivation and Architecture" %}
  {% include paper_item.html key="moe-iclr17" %}
  {% include paper_item.html key="fsmoe-asplos25" required="Training" %}
  {% include paper_item.html key="megablock-mlsys23" %}
  {% include paper_item.html key="moelight-asplos25" required="Serving" %}
  {% include paper_item.html key="pregatedmoe-isca24" %}
  {% include paper_item.html key="readme-neurips24" %}
</ul>

## Part 2 - GenAI: Beyond Simple Text Generation
#### Multi-Modal Generation
<ul>
  {% include paper_item.html key="illstablediff" required=true %}
  {% include paper_item.html key="approxcache-nsdi24" required="Diffusion Model Serving" %}
  {% include paper_item.html key="diffserve-mlsys24" %}
  {% include paper_item.html key="cogvideox-iclr25" required="Video Gen Model" %}
  {% include paper_item.html key="moviegen-arxiv24" %}
</ul>

#### Retrieval-Augmented Generation
<ul>
  {% include paper_item.html key="rago-isca25" required=true %}
  {% include paper_item.html key="patchwork-arxiv25" required=true %}  
  {% include paper_item.html key="metis-arxiv25" required=false %}
  {% include paper_item.html key="telerag-arxiv25" required=false %}
</ul>

#### LLM-Augmented Agentic Systems
<ul>
{% include paper_item.html key="parrot-osdi24" required=true %}
{% include paper_item.html key="autellix-arxiv25" required=true %}
{% include paper_item.html key="ayo-asplos25" required=false %}
</ul>

***
## Part 3 - GenAI for Systems
<ul>
{% include paper_item.html key="confucius-sigcomm25" required=true %}
{% include paper_item.html key="netllm-sigcomm24" required=true %}
{% include paper_item.html key="zoom2net-sigcomm24" required=false %}
{% include paper_item.html key="fmp-colm25" required=true %}
{% include paper_item.html key="textgrad-arxiv24" required=false %}
{% include paper_item.html key="alphaevolve-whitepaper25" required=true %}
</ul>
