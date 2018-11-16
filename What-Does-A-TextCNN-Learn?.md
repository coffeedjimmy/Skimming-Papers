# What Does a textcnn learn?

[Paper](https://arxiv.org/pdf/1801.06287.pdf)

### Introduction

- TextCNN은 기존에 비전에서 사용되던 CNN을 텍스트에 사용한 것으로 감성분석이나 문제 분류 등과 같은 분야에서 좋은 성능을 냄.
- Neural net은  해석하기가 어려워서 black-box 모델로 간주되어 옴.
- Deep visualisation과 같은 시도로 연구자들이 CNN의 동작과정을 이해하려는 시도를 해오고 있지만, TexCNN에 대해선 여전히 부족하다고 저자들은 주장.
- 이 논문에서는 2가지 NLP 테스크를 통해 TextCNN이 무엇을 배우는지 이해하는 것을 목표로 함.
  - 서로 다른 Convolutional kernel들을 이용해서 kernel들 사이에 어떤 상관관계가 있는지에 집중함.

