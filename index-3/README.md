# 하우투

## 변수: 생성, 초기화, 저장, 복구

텐서플로우 변수들은 텐서를 가지고 있는 메모리상의 버퍼입니다. 그것들을 이용해서 학습중에 어떻게 모델 파라미터들을 보관하고 업데이트 하는지를 설명합니다.

[튜토리얼 보기](index.md)

## 텐서플로우 구조 입문

텐서플로우 구조를 사용하여 어느정도 규모가 되는 모델을 학습하는 방법을 차근차근 상세하게 설명합니다. MNIST 필기 숫자 인식을 예제로 사용합니다.

[튜토리얼 보기](index-1.md)

## 텐서보드: 학습 시각화

텐서보드는 모델들의 학습 및 평가를 시각화 해주는 유용한 툴입니다. 이 튜토리얼을 통해 텐서보드를 어떻게 만들고 동작시키는지 알 수 있습니다. 그리고 Summary 연산자를 추가하여, 텐서보드가 시각화를 위해 사용하게 되는 이벤트 파일에 자동적으로 데이타를 출력하는 방법을 배웁니다.

[튜토리얼 보기](index-2.md)

## 텐서보드: 그래프 시각화

데이타 플로우를 그래프로 이해하고 수정을 가할 수 있도록, 텐서보드에서 그래프 시각화 툴을 사용하는 방법을 배웁니다.

[튜토리얼 보기](index-3.md)

## 데이터 로딩

텐서플로우 프로그램에 데이타를 로딩하는 세가지 방법을 설명합니다: Feeding, Reading, Preloading, 이렇게 세가지입니다.

[튜토리얼 보기](index-4.md)

## 분산처리

텐서플로우 서버 클러스터를 이용하여 텐서플로우 프로그램을 실행하는 방법을 설명합니다.

[튜토리얼 보기](index-6.md)

## 쓰레드와 큐

비동기 학습과 동시 학습을 구현하기 위한 다양한 텐서플로우 구조들을 설명합니다.

[튜토리얼 보기](index-5.md)

## 커스텀 연산자

텐서플로우는 이미 많은 수의 연산자들을 제공하고 있습니다. 스스로 커스텀 연산자를 만들 필요가 있는 경우, 이 튜토리얼을 참고하십시요.

[튜토리얼 보기](index-7.md)

## 텐서플로우 코드 작성 스타일

코드의 가독성을 높이고, 에러를 줄이며, 일관성을 장려하기 위해, 텐서플로우 개발자와 사용자들이 따라야 할 스타일 가이드입니다.

[스타일 가이드 보기](https://github.com/didim365-sysong/Didimnow/tree/7f72501e401f79ba8fc30ec387d7a50f8f80b0b5/g3doc/how_tos/style_guide.md)

## 문서화

텐서플로우의 도큐먼테이션들은 대부분 소스 코드들로부터 생성되었습니다. 이 튜토리얼을 통해, 문서의 포맷, 스타일 가이드, 그리고 소스로부터 업데이트된 도큐먼테이션을 생성하는 방법을 배울 수 있습니다.

[튜토리얼 보기](index-8.md)

## 커스텀 데이터 포맷

상당한 양의 커스텀 데이터를 가지고 있는 경우, 텐서플로우가 데이터 본래의 포맷으로 직접 읽어들이게 하는 방법입니다.

[튜토리얼 보기](index-9.md)

## GPU 사용하기

GPU상에서 모델을 구축하고 실행하는 방법을 설명하는 튜토리얼입니다.

[튜토리얼 보기](index-10.md)

## 변수 공유

큰 모델을 하나 이상의 GPU에서 돌리거나, 복잡한 LSTM 또는 RNN을 전개하는 경우에, 모델을 만드는 코드상의 여러 곳으로부터 동일한 변수 객체에 접근할 필요가 자주 생깁니다.

그것을 실현하기 위한 "변수 범위\(Variable Scope\)" 방식이라는 것이 있습니다.

[튜토리얼 보기](index-11.md)

## 모델 파일

텐서플로우 모델이 저장되는 포맷을 이해하는 것은, 모델을 읽어들이고, 분석하고, 수정하는 데에 도움을 줍니다. 이 튜토리얼을 통해서 모델이 저장되는 포맷에 대해 자세하게 알 수 있습니다.

[튜토리얼 보기](index-12.md)

## 트랜스퍼 학습을 이용한 부분 학습

Inception과 같은 완성된 형태의 인식 모델을 학습시키는 데에는, 많은 수의 이미지와 오랜 시간이 필요합니다. 학습이 끝난 모델의 최종 레이어만 다시 학습함으로써, 다른 카테고리의 대상을 인식할 수 있게 하는 트랜스퍼 학습 기법을 설명합니다. 모델을 처음부터 다시 학습하는 것보다 훨씬 빠르고 쉬운 방법입니다.

[튜토리얼 보기](index-13.md)

## 모델 Export 와 Import

모델을 사용하는 데에 필요한 일체를 Export하고, 나중에 Import하는 방법을 설명합니다.

[튜토리얼 보기](index-14.md)

## 텐서플로우로 뉴럴 네트워크를 정량화 하기

플로팅 포인트 모델을, 8비트 파라미터와 연산을 사용하도록 정량화\(양자화\)하는 방법을 배웁니다. 프로그램의 이면에서 정량화가 어떻게 동작하는지도 설명합니다.

[튜토리얼 보기](index-15.md)
