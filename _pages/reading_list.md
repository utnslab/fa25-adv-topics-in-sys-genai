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
  {% include paper_item.html key="wlbllm-osdi25" required=false %}
</ul>

#### Scaling LLM Pre-Training
<ul>
  {% include paper_item.html key="alpa-osdi22" required=true %}
  {% include paper_item.html key="partir-asplos25" required=false %}
  {% include paper_item.html key="rdma-sigcomm24" required=true %}
  {% include paper_item.html key="cassini-nsdi24" required=false %}
  {% include paper_item.html key="traincheck-osdi25" required=true %}
  {% include paper_item.html key="superbench-atc24" required=false %}
  {% include paper_item.html key="oobleck-sosp23" required=true %}
  {% include paper_item.html key="tenplex-sosp24" required=false %}
</ul>

#### LLM Post-Training for Alignment
<ul>
  {% include paper_item.html key="rlhfuse-nsdi25" required=true %}
  {% include paper_item.html key="hybridflow-eurosys25" required=false %}
  {% include paper_item.html key="areal-arxiv25" required=true %}
</ul>

#### Efficient LLM Serving
<ul>
  {% include paper_item.html key="pagedattention-sosp23" required=true %}
  {% include paper_item.html key="nanoflow-osdi25" required=true %}
  {% include paper_item.html key="sarathiserve-osdi24" required=false %}
  {% include paper_item.html key="distserve-osdi24" required=true %}
  {% include paper_item.html key="llumnix-osdi24" required=true %}
</ul>

#### Mixture-of-Experts
<ul>
  {% include paper_item.html key="switch-jmlr22" required=true %}
  {% include paper_item.html key="moe-iclr17" required=false %}
  {% include paper_item.html key="fsmoe-asplos25" required=true %}
  {% include paper_item.html key="tutel-mlsys23" required=false %}
  {% include paper_item.html key="moelight-asplos25" required=true %}
  {% include paper_item.html key="pregatedmoe-isca24" required=false %}
  {% include paper_item.html key="readme-neurips24" required=false %}
</ul>

## Part 2 - GenAI: Beyond Simple Text Generation
#### Multi-Modal Generation
<ul>
  {% include paper_item.html key="illstablediff" required=true %}
  {% include paper_item.html key="approxcache-nsdi24" required=true %}
  {% include paper_item.html key="diffserve-mlsys24" required=false %}
  {% include paper_item.html key="cogvideox-iclr25" required=true %}
  {% include paper_item.html key="moviegen-arxiv24" required=false %}
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
{% include paper_item.html key="fmp-arxiv25" required=true %}
{% include paper_item.html key="textgrad-arxiv24" required=false %}
{% include paper_item.html key="alphaevolve-whitepaper25" required=true %}
</ul>
