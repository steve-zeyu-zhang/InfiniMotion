<div align="center"><h1> InfiniMotion: Mamba Boosts Memory in Transformer for Arbitrary Long Motion Generation<br>
<!-- <sub><sup><a href="">Under Review</a></sup></sub> -->
</h1>

[Zeyu Zhang](https://steve-zeyu-zhang.github.io), [Akide Liu](https://www.linkedin.com/in/akideliu/), [Qi Chen](https://scholar.google.com/citations?hl=zh-CN&user=OgKU77kAAAAJ), [Feng Chen](https://github.com/Chenfeng1271), [Ian Reid](https://mbzuai.ac.ae/study/faculty/ian-reid/), [Richard Hartley](http://users.cecs.anu.edu.au/~hartley/), [Bohan Zhuang](https://bohanzhuang.github.io/), [Hao Tang](https://ha0tang.github.io/)<sup>✉</sup>

<sup>✉</sup>Corresponding author: bjdxtanghao@gmail.com

[![Website](https://img.shields.io/badge/Website-Demo-fedcba?style=flat-square)](https://steve-zeyu-zhang.github.io/InfiniMotion/) [![arXiv](https://img.shields.io/badge/arXiv-2403.07487-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2403.07487) 
<!--[![Papers With Code](https://img.shields.io/badge/Papers%20With%20Code-555555.svg?style=flat-square&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxuczp4bGluaz0iaHR0cDovL3d3dy53My5vcmcvMTk5OS94bGluayIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB2aWV3Qm94PSIwIDAgNTEyIDUxMiIgd2lkdGg9IjUxMiIgIGhlaWdodD0iNTEyIiA+PHBhdGggZD0iTTg4IDEyOGg0OHYyNTZIODh6bTE0NCAwaDQ4djI1NmgtNDh6bS03MiAxNmg0OHYyMjRoLTQ4em0xNDQgMGg0OHYyMjRoLTQ4em03Mi0xNmg0OHYyNTZoLTQ4eiIgc3Ryb2tlPSIjMjFDQkNFIiBmaWxsPSIjMjFDQkNFIj48L3BhdGg+PHBhdGggZD0iTTEwNCAxMDRWNTZIMTZ2NDAwaDg4di00OEg2NFYxMDR6bTMwNC00OHY0OGg0MHYzMDRoLTQwdjQ4aDg4VjU2eiIgc3Ryb2tlPSIjMjFDQkNFIiBmaWxsPSIjMjFDQkNFIj48L3BhdGg+PC9zdmc+)](https://paperswithcode.com/paper/motion-mamba-efficient-and-long-sequence)--> 
<!--[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-555555?style=flat-square)](https://huggingface.co/papers/2403.07487)-->
<!--[![BibTeX](https://img.shields.io/badge/BibTeX-Citation-eeeeee?style=flat-square)](https://steve-zeyu-zhang.github.io/MotionMamba/static/scholar.html)-->


</div>

_Text-to-motion generation holds potential for film, gaming, and robotics, yet current methods often prioritize short motion generation, making it challenging to produce long motion sequences effectively: (1) Current methods struggle to handle long motion sequences as a single input due to prohibitively high computational cost; (2) Breaking down the generation of long motion sequences into shorter segments can result in inconsistent transitions and requires interpolation or inpainting, which lacks entire sequence modeling. To solve these challenges, we propose **InfiniMotion**, a method that generates continuous motion sequences of arbitrary length within an autoregressive framework. We highlight its groundbreaking capability by generating a continuous **1-hour** human motion with around **80,000** frames. Specifically, we introduce the Motion Memory Transformer with Bidirectional Mamba Memory, enhancing the transformer's memory to process long motion sequences effectively without overwhelming computational resources. Notably our method achieves over **30%** improvement in FID and **6** times longer demonstration compared to previous state-of-the-art methods, showcasing significant advancements in long motion generation._

<div align="center">
<img src="static/images/main.svg" style="width: 100%;">
<img src="static/images/block.svg" style="width: 80%;">
</div>

## News

<!-- <b>(03/13/2024)</b> &#127881; Our paper has been highlighted by <a href="https://wx.zsxq.com/dweb2/index/topic_detail/1522541851241522"><b>CVer</b></a>! -->

## Citation


```
Coming soon.
```

