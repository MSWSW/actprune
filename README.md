# ActPrune: Action-Grounded Visual Token Pruning for Efficient Vision-Language-Action Models

Sungwon Moon, Minji Kim, Hyemin Boo, Daeun Song<sup>†</sup>, Jiyoung Lee<sup>†</sup>

<sup>†</sup>Corresponding author

[![Paper](https://img.shields.io/badge/Paper-arXiv-b31b1b)](https://arxiv.org/abs/XXXX.XXXXX)

This repository contains the official implementation of **ActPrune**.

ActPrune is a training-free visual token pruning method that moves the pruning decision ahead of the vision encoder by grounding it in the robot's own action. It prunes in two stages: (1) **patch-level pruning** before encoding, which uses the previous action chunk to retain patches along the projected end-effector trajectory in the fixed third-person view and to merge motion-compensated redundant patches in the wrist view, and (2) **embedding-level pruning** after encoding, which ranks the remaining tokens by encoder attention.

![ActPrune overview](assets/method.png)

## Video

[▶ Watch the video](assets/demo.mp4)

## Code
Code will be released soon.

## Citation
```bibtex
@article{moon2026actprune,
  title   = {{ActPrune}: Action-Grounded Visual Token Pruning for Efficient Vision-Language-Action Models},
  author  = {Moon, Sungwon and Kim, Minji and Boo, Hyemin and Song, Daeun and Lee, Jiyoung},
  journal = {arXiv preprint arXiv:XXXX.XXXXX},
  year    = {2026}
}
```
