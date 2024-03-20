# Can ChatGPT Detect DeepFakes? A Study of Using Multimodal Large Language Models for Media Forensics

[![Github](https://img.shields.io/badge/Github%20webpage-222222.svg?style=for-the-badge&logo=github)]()
[![arXiv](https://img.shields.io/badge/-arXiv-B31B1B.svg?style=for-the-badge)]()

This is the official repository of the paper:
[Can ChatGPT Detect DeepFakes? A Study of Using Multimodal Large Language Models for Media Forensics]() 

[Shan Jia](https://shanface33.github.io/), Reilin Lyu, Kangran Zhao, Yize Chen, Zhiyuan Yan, Yan Ju, Chuanbo Hu, Xin Li, Baoyuan Wu, Siwei Lyu

## Summary
In this work, we investigate the capabilities of multimodal large language models (LLMs) in DeepFake detection. We conducted qualitative and quantitative experiments to demonstrate multimodal LLMs and show that they can expose AI-generated images through careful experimental design and prompt engineering. This is interesting, considering that LLMs are not inherently tailored for media forensic tasks, and the process does not require programming. We discuss the limitations of multimodal LLMs for these tasks and suggest possible improvements.

<p align="center">
 <img src="./figs/overview.png" alt="preview" width="500pt" />
</p>

Two multimodal LLMs have been evaluated: GPT4V and Gemini 1.0 Pro.

## Test-data
The dataset used in this study can be downloaded from the following [link](https://drive.google.com/file/d/1p2nxvQIQCSrACSpYCG_BJmBJ6gFZsywR/view?usp=sharing), which contains 1,000 StyleGAN2 generated face images, 1,000 Latent Diffusion generated images, and 1,000 real faces from FFHQ dataset, drived from [DF^3 dataset](https://arxiv.org/pdf/2211.08615.pdf). Both raw data and post-proccessed (pped) data have been provided.

The test data has the following structure:
```
Test_data
|--Real_512Size 
|--StyleGAN_raw_512size 
|--StyleGAN_pped_256size
|--LD_pped_256Size
|--LD_raw_512Size
```

## License and Citation
```
@article{jia2024can,
  title={Can ChatGPT Detect DeepFakes? A Study of Using Multimodal Large Language Models for Media Forensics},
  author={Jia, Shan and Lyu, Reilin and Zhao, Kangran and Chen, Yize and Yan, Zhiyuan and Ju, Yan and Hu, Chuanbo and Li, Xin and Wu, Baoyuan and Lyu, Siwei},
  journal={arXiv preprint},
  year={2024}
}
