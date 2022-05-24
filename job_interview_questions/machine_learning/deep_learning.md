<div align='center'>
  <h1>🧠 Deep Learning 🧠</h1>
</div>

- last updated: 2022.05.24.

#### Questions ❓

- [CNN과 Vision Transformer의 차이는 무엇인가요?](#no1)
- [ReLU 함수가 sigmoid 또는 softmax에 비해 최근 activation function으로 선호되는 이유는 무엇인가요?](#no2)
- [Backpropagation을 미분 관점에서 설명해보세요.](#no3)
- [딥러닝에서 nonlinearity가 왜 중요한 역할을 하나요?](#no4)
- [딥러닝은 학습 시의 local minima의 위험성에도 불구하고 왜 효과적인가요?](#no5)
- [Batch Normalization과 Dropout은 각각 무엇이며, 왜 효과적인가요?](#no6)

---
#### No.1

**CNN과 Vision Transformer의 차이는 무엇인가요?**

- [자이냅스](../../company_infos/speech/Xinapse.md) 기술면접 질문

Convolution은 데이터로부터 특정 패턴을 찾아내는 커널을 학습시키는 연산이다. 때문에 CNN은 모델을 학습시킬 때 사용한 데이터의 도메인에 큰 영향을 받게 된다. 어떤 태스크를 위해서 도메인이 다른 데이터셋으로 학습시킨 CNN 모델을 사용하는 것은 부적합하다.

Transformer는 (어떤 데이터가 들어오든 간에) 데이터를 잘 표현하는 임베딩을 학습하는 것을 목표로 한다. Transformer는 주로 많은 양의 데이터로 학습 시킨 다음 특정 태스크를 위해 fine-tuning 하는 방식으로 사용된다. 

한편, ICLR2022 Spotlight으로 "How Do Vision Transformers Work?" 라는 논문이 발표되었다. [저자가 밝힌 주요 3가지 포인트](https://www.facebook.com/groups/TensorFlowKR/permalink/1687154681625583) 중 하나에 의하면, Convolution이 high-pass filter인 것과 달리 MSA는 low-pass filter이며, 이 것은 conv는 texture-biased 되어 있고, MSA는 shape-biased 되어 있다는 것을 암시한다. 따라서, 이 둘은 상호보완적이라고 한다.

---

#### No.2

**ReLU 함수가 sigmoid 또는 softmax에 비해 최근 activation function으로 선호되는 이유는 무엇인가요?**

- [포자랩스](../../company_infos/music/PozaLabs.md) 기술면접 질문



---

#### No.3

**Backpropagation을 미분 관점에서 설명해보세요.**

- [포자랩스](../../company_infos/music/PozaLabs.md) 기술면접 질문



---

#### No.4

**딥러닝에서 nonlinearity가 왜 중요한 역할을 하나요?**

- [포자랩스](../../company_infos/music/PozaLabs.md) 기술면접 질문



---

#### No.5

**딥러닝은 학습 시의 local minima의 위험성에도 불구하고 왜 효과적인가요?**

- [포자랩스](../../company_infos/music/PozaLabs.md) 기술면접 질문



---

#### No.6

**Batch Normalization과 Dropout은 각각 무엇이며, 왜 효과적인가요?**

- [포자랩스](../../company_infos/music/PozaLabs.md) 기술면접 질문



