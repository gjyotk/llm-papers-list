# llm-papers

## Overview

Every week, I set out to read, reflect on, and document my learnings from one LLM-based research paper. This repository is a personal effort to stay connected with the latest developments, deepen my understanding of Machine Learning, and share my insights with others who share this passion. 

## Papers List

Below is the list of most relevant foundational papers on LLMs (according to me) that I've curated from Latent Space's 2025 Papers [list](https://www.latent.space/p/2025-papers#%C2%A7section-frontier-llms) and suggested reading materials from the course "Generative AI with Large Language Models" by Deeplearning.ai on Coursera:


1. **[Improving Language Understanding by Generative Pre-Training](https://cdn.openai.com/research-covers/language-unsupervised/language_understanding_paper.pdf)** by *Alec Radford et al., 2018*
   - [Paper Notes](https://www.dropbox.com/scl/fi/d6p85rjw5ccs1521a0sat/language_understanding_paper.pdf?rlkey=plnwzmzmrqijzcjt1je9im0zw&st=7cuzqrp7&dl=0)
   - **Summary:** This paper introduces a semi-supervised approach using generative pre-training on a large, unlabeled text corpus, followed by discriminative fine-tuning on specific tasks. This method enhances performance across various NLP tasks by leveraging unsupervised learning to capture broad linguistic patterns before task-specific training.
   - **Key Contributions:** The paper implements a combined approach of generative pre-training on unlabelled data (for getting the model to learn general patterns) followed by discriminative fine-tuning on labelled data (for better performance on specific tasks). The task-agnostic model outpreforms task-specific model on multiple benchmarks
   - **Challenges the Paper Solves:** The paper addresses the scarcity of labelled data required for training language models. Using unlabelled data for model pre-training that also helps with regularisation. Implements task-specific input transformations that use traversal-style approach to convert structured inputs into ordered outputs. This reduces the extensive reconfiguration that was previously required for pretrained model to adapt to specific task.

3. **[Attention is All You Need](https://arxiv.org/abs/1706.03762)** by *Ashish Vaswani et al., 2017*
   - [Paper Notes]()
   - [My Professor's Notes](https://www.dropbox.com/scl/fi/ejmmafmrfn21qmm24n51z/Attention-is-all-You-Need-explained.pdf?rlkey=bova7kjufm1gzdowwzmrkcrx1&st=icrhibk5&dl=0) (for detailed reference)
   - **Summary:**
   - **Key Contributions:**
   - **Challenges the paper solves:**


## How to Use This Repository

You can follow my progress by checking the updates in this README or visiting [this](gjyotk.github.io/llm-papers-list/#/) URL . Feel free to share your thoughts, suggest additional papers, or discuss the content via GitHub issues or pull requests.

Stay tuned for weekly updates!


