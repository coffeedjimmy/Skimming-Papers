# You May Not Need Attention

[Paper](https://arxiv.org/pdf/1810.13409.pdf)

### Abstract

- Neural Machine Translation에 있어서 최근 화두가 되었던 attention과 encoding/decoding을
분리하지 않고서 우리는 어디까지 나아갈 수 있는지에 대한 질문
- 이 논문에서는 attention과 encoding/decoding 부분 분리 없는 모델을 소개: `eager translation model`
- 장점: low-latency
  - target token을 첫 번재 source token을 읽자마자 쓰고, decoding을 하는 데에 있어 constant memory를 사용
- 이 모델은 기존 Bahdanau attention 모델과 성능이 비슷하고, 긴 문장에 있어서는 더 좋은 성능을 보였다고 주장


