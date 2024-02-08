# SELF-DISCOVER Implementation

This repository contains an implementation of the SELF-DISCOVER framework as described in the paper "Self-Discover: Large Language Models Self-Compose Reasoning Structures" by Pei Zhou, Jay Pujara, Xiang Ren, Xinyun Chen, Heng-Tze Cheng, Quoc V. Le, Ed H. Chi, Denny Zhou, Swaroop Mishra, Huaixiu Steven Zheng. 
SELF-DISCOVER enables Large Language Models (LLMs) to autonomously discover and compose reasoning structures to tackle complex reasoning tasks, significantly enhancing their performance on challenging benchmarks.

## Features

- **Self-Discovery Mechanism**: Implements the self-discovery process for identifying and composing atomic reasoning modules.
- **Enhanced Reasoning Capability**: Demonstrates improved performance on reasoning benchmarks like BigBench-Hard, grounded agent reasoning, and MATH.
- **Efficiency**: Offers substantial computational efficiency compared to Chain of Thought (CoT) and CoT-Self-Consistency methods.
- **Cross-Model Applicability**: Validates the universal applicability of discovered reasoning structures across various model families including PaLM 2-L, GPT-4, and Llama2.



## Contributing

I welcome contributions to improve this implementation! Please feel free to submit issues or pull requests with enhancements, bug fixes, or suggestions.

## Citation

```
@article{zhou2024selfdiscover,
  title={Self-Discover: Large Language Models Self-Compose Reasoning Structures},
  author={Zhou, Pei and Pujara, Jay and Ren, Xiang and Chen, Xinyun and Cheng, Heng-Tze and Le, Quoc V. and Chi, Ed H. and Zhou, Denny and Mishra, Swaroop and Zheng, Huaixiu Steven},
  journal={ArXiv},
  volume={abs/2402.03620},
  year={2024},
  url={https://arxiv.org/abs/2402.03620}
}
```
