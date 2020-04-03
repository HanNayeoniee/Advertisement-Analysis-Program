# Advertisement Analysis Program (Neuro-Marketing)
# 광고 분석 프로그램 (뉴로 마케팅 이용)
![image](https://img.shields.io/badge/language-C%23-blue?style=plat&logo=Visual-Studio)  
[요약](#요약)  
[필요성](#필요성)  
[개발 기간](#개발-기간)  
[개발자](#개발자)  
[사용 하드웨어](#사용-하드웨어)  
[사용 프로그램](#사용-프로그램)  
[집중도 판단 방법](#집중도-판단-방법)
[결과](https://github.com/minji-o-j/Advertisement-Analysis-Program/wiki)

---
### 요약
- 뉴로 마케팅을 활용한 광고 분석 프로그램.

- 광고를 시청하는 동안의 사용자의 __집중도__ 와 __긍부정도__ 가 그래프로 나타남.  

- 실험에 기반한 계산을 통해 사용자의 집중도와 긍부정도를 고려한 구매 확률 제시

---
### 필요성
- 만든 광고에 대해서 소비자의 무의식적인 반응을 광고주가 알 수 없다.

- 광고주가 강조하고자 하는 이미지(긍정,부정)가 소비자에게도 잘 전달되는지 확인하고 싶다.  

--> __소비자의 뇌파에 대한 피드백을 받음으로써 광고의 효과를 극대화하고 단점을 보완할 수 있다.__

---
### 개발 기간

- 2019/01/18 ~ 2019/02/01
---
### 개발자

- [김나혜(nahye03)](https://github.com/nahye03), [정민지(minji-o-j)](https://github.com/minji-o-j), [한나연(HanNayeoniee)](https://github.com/HanNayeoniee)

---
### 사용 하드웨어
- [EMOTIV EPOC+ 14 Channel Mobile Brainwear®](https://www.emotiv.com/product/emotiv-epoc-14-channel-mobile-eeg/?gclid=CjwKCAjwvZv0BRA8EiwAD9T2VfQbwRLqpyAp6D0mM0hGsmNmKJnzB6Lr0rptqZTDyOw-YRXm3BlRXxoCc18QAvD_BwE)

![image](https://user-images.githubusercontent.com/45448731/78367153-962d9700-75fc-11ea-9b82-33d49da8e792.png)  

- 14 채널(AF3, F7, F3, FC5, T7, P7, O1, O2, P8, T8, FC6, F4, F8, AF4)의 뇌파 측정 가능

- 전도성 물질(식염수 등)이 필요
---
### 사용 프로그램
- __Visual Studio__: 프로그래밍, 뇌파 관련 데이터 처리  

- __Blend for Visual Studio__: GUI 제작  

- __SPSS Statistics__: 기준 채널 선정, 데이터 분석  

- __EMOTIVE application__: 실험 데이터 추출, 뇌파 감지 확인

---
### 집중도 판단 방법
![image](https://user-images.githubusercontent.com/45448731/78375633-0ee62080-7608-11ea-9486-ca595ff0f843.png)  
- ERP(사건관련전위) 중 late cognitive component(후기 인지적 정점)인 `P300`을 이용하여  집중도를 측정한다.

#### 1. p300 측정 방법
1. 1초에 128개의 뇌파 Data를 받는다.
2. 30초를 1초 단위로 쪼갠다. --> __1초 중에 250ms-500ms 구간중 최댓값을 P300으로 정한다.__

#### 2. 변화율에 대한 정의

---
### 긍/부정도 판단 방법
---
### 실험자 모드
---
###사용자 모드
---
### 결과

[결과 이미지 보기!!](https://github.com/minji-o-j/Advertisement-Analysis-Program/wiki)

