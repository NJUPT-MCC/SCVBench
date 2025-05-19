# SCVBench

## Overview

Despite advancements in Large Vision-Language Models (LVLMs), their ability to understand long-term story-level video content remains limited. Challenges arise from oversimplified temporal information handling and action/event-centric training data biases.


## Introducing SCVBench

SCVBench is a novel benchmark for story-centric video understanding. It evaluates LVLMs through an event ordering task, broken into sub-questions leading to a final question, quantitatively measuring temporal reasoning. The dataset includes 1,253 final questions and 6,027 sub-question pairs from 925 videos, forming continuous multi-turn dialogues.

Experiments show that while closed-source GPT-4o performs best, most open-source LVLMs struggle with story-level understanding. See `SCVBench.jsonl` for detailed samples.


Details can be found in https://github.com/yuanrr/SCVBench
