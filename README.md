# SELF-DISCOVER Implementation

This repository contains an implementation of the SELF-DISCOVER framework as described in the paper "Self-Discover: Large Language Models Self-Compose Reasoning Structures" by Pei Zhou, Jay Pujara, Xiang Ren, Xinyun Chen, Heng-Tze Cheng, Quoc V. Le, Ed H. Chi, Denny Zhou, Swaroop Mishra, Huaixiu Steven Zheng.
SELF-DISCOVER enables Large Language Models (LLMs) to autonomously discover and compose reasoning structures to tackle complex reasoning tasks, significantly enhancing their performance on challenging benchmarks.

## Usage
set your together.ai API key as an enviroment variable `TOGETHER_API_KEY` or your groq API key as an enviroment variable `GROQ_API_KEY`.
Run the main pythons script `main.py`. Use -v to see the thinking process.

## Contributing

I welcome contributions to improve this implementation! Please feel free to submit issues or pull requests with enhancements, bug fixes, or suggestions.

## Citation

The idea is based on the paper "Self-Discover: Large Language Models Self-Compose Reasoning Structures" by Pei Zhou, Jay Pujara, Xiang Ren, Xinyun Chen, Heng-Tze Cheng, Quoc V. Le, Ed H. Chi, Denny Zhou, Swaroop Mishra, Huaixiu Steven Zheng.

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

The implementation is based on <https://github.com/catid/self-discover>
