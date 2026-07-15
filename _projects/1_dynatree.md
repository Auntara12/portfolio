---
layout: page
title: DynaTree
description: Adaptive tree speculative decoding for LLM inference acceleration
importance: 1
category: work
github: https://github.com/Auntara12/dynatree
---

**DynaTree** is a training-free speculative decoding method for accelerating LLM inference. Instead of a fixed draft tree, it dynamically adjusts tree breadth and depth per token based on the draft model's confidence, then verifies the whole tree losslessly in a single pass using tree attention.

**Results:**
- Outperformed EAGLE-2 by 7.4% on WikiText-2
- 9.4x speedup over standard autoregressive decoding
- No draft model training or architecture changes required — works with any existing draft/target model pair

**Stack:** Python, PyTorch

Code on [GitHub](https://github.com/Auntara12/dynatree).
