# GOOD VIEW HUNTING

부제 : **Learning Photo Composition from Dense View Pairs**

[Paper](http://www.zijunwei.org/papers/cvpr18-photo-composition.pdf)

[Author's implementation](https://github.com/zijunwei/ViewProposalNet)

### Abstract

- 특정 이미지에 있어서 좋은 View(이미지의 특성이 잘 들어나는 View)를 찾는 것에 잇어 가장 어려운 점은 태깅이 된 큰 데이터셋이 부족하다는 점
- 이 논문 저자들은 큰 스케일의 Photo Composition dataset을 구성했고 크기는 백만개가 넘는다.
- 네트워크의 입장에서는 knowledge transfer framework를 제안하고 이를 **view proposal network**를 학습하는데에 사용해서 이 네트워크가 75+ FPS 이상을 다룰 수 있고 이미지 크로핑과 썸네일 생성 테스크에 있어 좋은 성능을 냈다고 주장.

