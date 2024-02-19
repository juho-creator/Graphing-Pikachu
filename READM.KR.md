[![English](https://img.shields.io/badge/lang-English-blue.svg)](https://github.com/juho-creator/Interactive-Pikachu-Pokeball-Graph/blob/main/README.md)

# 움직이는 피카츄 그래프
- 다양한 그래프를 사용하여 물 위에 떠다니는 피카츄와 포켓볼을 그래프로 만들었습니다. </br>
- 피카츄, 포켓볼,물 모두 상호작용이 가능합니다.

![피카츄](https://github.com/juho-creator/Graphing-Pikachu/assets/72856990/df81b209-0bf5-4404-8255-aa2323151de5)


여기서 확인할 수 있습니다 : [피카츄 그래프](https://www.desmos.com/calculator/v8mpye0wof)
<br />
<br />
<br />
<br />
# 생성 과정

## 피카츄
피카츄를 구성하는 모든 부분을 적합한 그래프로 따라 그리는데 상당히 많은 시간이 소요되었습니다.
<br />

**단계 1 :** Desmos에 피카츄의 이미지를 추가했습니다.
<br />
<br />


**단계 2 :** 피카츄의 일부를 따라 그리기 위해 그래프의 오목성과 X,Y 위치를 제어하는 변수 A,B,C를 가진 이차방정식을 생성했습니다. 다음 이차방정식이 사용되었습니다: $Y = A((X - B)^2) + C$
<br />
<br />


**단계 3 :** 그래프의 모양이 사진의 일부와 일치하는 경우, 그래프의 영역과 범위를 조절하여 불필요한 부분을 제거했습니다.<br />
![피카츄](https://github.com/juho-creator/Graphing-Pikachu/assets/72856990/88e56472-a879-4144-8cb2-e50f300d62f0)
<br />
<br />

**단계 4 :** 특정 부분이 이차방정식으로 표현되지 않았을땐 다른 방정식들을 사용했습니다 (원, 타원, 로그, 지수, 세제곱, 제곱근)<br />
![Pikachu_-_Chrome_2023-05-28_16-32-23_AdobeExpress](https://github.com/juho-creator/Graphing-Pikachu/assets/72856990/848dce22-e0b1-4037-8e9f-9bb35d6382d9)
<br />
<br />

**단계 5 :** 단계 1~4를 반복하여 피카츄를 만들었습니다.
<br />
<br />

**단계 6 :** 마지막으로 피카츄를 구성하는 모든 방정식의 X,Y위치를 조절하기 위해 모든 방정식에 2개의 슬라이더 변수가 포함되었습니다.<br />
![Pikachu_-_Chrome_2023-05-28_16-35-47_AdobeExpress](https://github.com/juho-creator/Graphing-Pikachu/assets/72856990/f740967f-7dd2-4423-91c6-f995e49a12b5)
<br />
<br />
<br />
<br />

## PokeBall
포켓볼을 만드는 것은 수평선과 원 2개만 사용하여 다른 그림에 비해 간단했습니다.
<br />

**단계 1 :** 적절한 크기를 갖는 원을 만들기 위한 방정식을 생성했습니다. $(X-A)^2+(Y-B)^2=C^2$
<br />
<br />

**단계 2 :** 두 원의 크기를 조정했습니다.<br />
![Pikachu_-_Chrome_2023-05-28_16-42-55_AdobeExpress](https://github.com/juho-creator/Graphing-Pikachu/assets/72856990/beb67fe5-adab-4f77-96ee-f9a7a85dfbb5)
<br />
<br />

**단계 3 :** 다른 정의역을 갖는 두 개의 수평 접선을 추가하여 포켓볼 가운데 있는 두 줄을 그었습니다 .<br />
![Pikachu_-_Chrome_2023-05-28_16-47-10_AdobeExpress](https://github.com/juho-creator/Graphing-Pikachu/assets/72856990/762c90a4-571c-4e8f-b0fa-2b941eb5b2a0)
<br />
<br />

**단계 4 :** 포켓볼의 가로와 세로 위치를 조절하기 위해 모든 방정식에 2개의 슬라이더 변수를 추가했습니다.<br />
![Pikachu_-_Chrome_2023-05-28_16-52-29_AdobeExpress](https://github.com/juho-creator/Graphing-Pikachu/assets/72856990/cbe51756-feb1-4c6c-8cad-c2208d755d21)
<br />
<br />
<br />
<br />

## 물
물은 사인 함수와 부등호를 사용하여 만들었으며 비교적 만들기 쉬웠습니다. 하지만 사인 파동에 기능을 추가하는 것은 어려웠습니다.

**단계 1:** 사인 함수와 부등호를 결합하여 물과 비슷한 파동 형태를 파란색으로 채울 수 있었습니다.
<br />
<br />

![피카츄](https://github.com/juho-creator/Graphing-Pikachu/assets/72856990/cc93cff3-219d-404b-b094-5d4abb404dfa)
<br />
<br />


**단계 2:** 물을 제어하기 위한 4개의 슬라이더 변수가 모든 방정식에 추가되었습니다.<br />
![피카츄](https://github.com/juho-creator/Graphing-Pikachu/assets/72856990/b03b495f-4305-4717-ab9a-d8a5ae29f076)
<br />
<br />
<br />
<br />

# 그래프 구성 요소
각 구성 요소에 대한 그래프 함수는 다음 폴더에 있습니다:

### 1. Pikachu
피카츄는 다음과 같은 구성 요소로 이루어져 있습니다:
* 원 (9)
* 타원 (2)
* 로그 함수(2)
* 지수 함수 (1)
* 삼차 함수 (1)
* 제곱근 (1)  
<br />
<br />

### 2. Pokeball
포켓볼은 다음과 같은 구성 요소로 이루어져 있습니다:
* 원 (2)
* 수평선 (2)
<br />

### 3. Water
물은 사인 함수로 이루어져 있습니다.

총 30개의 방정식이 사용되었으며, 10가지 다른 유형의 함수가 사용되었습니다.

