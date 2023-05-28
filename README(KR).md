# 대화형 피카츄 그래프

다양한 그래프를 사용하여 물 위에 떠다니는 피카츄와 포켓볼의 대화형 그래프를 만들었습니다!
피카츄, 포켓볼, 그리고 물은 상호작용이 가능하도록 만들어져 더욱 멋지게 표현되었습니다!


![피카츄](https://github.com/juho-creator/Graphing-Pikachu/assets/72856990/df81b209-0bf5-4404-8255-aa2323151de5)


이곳에서 확인해보세요! [피카츄 그래프](https://www.desmos.com/calculator/v8mpye0wof)
<br />
<br />
<br />
<br />
# 생성 과정

## 피카츄
피카츄를 만드는 데는 각각의 부분을 추적하기 위해 다양한 방정식을 사용하여 많은 시간이 소요되었습니다.
<br />

**단계 1 :** Desmos에 피카츄의 PNG 이미지를 추가했습니다.
<br />
<br />


**단계 2 :** 그래프를 추적하기 위해 볼록성, X 및 Y 위치를 제어하는 변수 A, B 및 C를 가진 이차방정식을 생성했습니다. 다음 이차방정식이 사용되었습니다: $Y = A((X - B)^2) + C$
<br />
<br />


**단계 3 :** 그래프가 사진과 일치하는 경우, 영역과 범위를 사용하여 그래프의 불필요한 부분을 제거했습니다.<br />
![피카츄](https://github.com/juho-creator/Graphing-Pikachu/assets/72856990/88e56472-a879-4144-8cb2-e50f300d62f0)
<br />
<br />

**단계 4 :** 만약 특정 부분이 포물선 방정식으로 표현되지 않았다면, 다른 방정식들을 사용했습니다(원, 타원, 로그, 지수, 세제곱, 제곱근)<br />
![Pikachu_-_Chrome_2023-05-28_16-32-23_AdobeExpress](https://github.com/juho-creator/Graphing-Pikachu/assets/72856990/848dce22-e0b1-4037-8e9f-9bb35d6382d9)
<br />
<br />

**단계 5 :** 단계 1~4를 반복하여 피카츄를 만들었습니다.
<br />
<br />

**단계 6 :** 마지막으로, 피카츄의 모든 부분 방정식에는 가로와 세로 위치를 조절하기 위해 두 개의 슬라이더 변수가 포함되었습니다.<br />
![Pikachu_-_Chrome_2023-05-28_16-35-47_AdobeExpress](https://github.com/juho-creator/Graphing-Pikachu/assets/72856990/f740967f-7dd2-4423-91c6-f995e49a12b5)
<br />
<br />
<br />
<br />
## PokeBall
포켓볼을 만드는 것은 간단했습니다. 수평 접선과 두 개의 원만 필요했습니다.
<br />

**단계 1 :** 원을 위한 방정식 템플릿을 생성했습니다. $(X-A)^2+(Y-B)^2=C^2$
<br />
<br />

**단계 2 :** 두 원의 크기를 조정했습니다.<br />
![Pikachu_-_Chrome_2023-05-28_16-42-55_AdobeExpress](https://github.com/juho-creator/Graphing-Pikachu/assets/72856990/beb67fe5-adab-4f77-96ee-f9a7a85dfbb5)
<br />
<br />

**단계 3 :** 포켓볼 가운데 있는 두 줄을 위해 각각 다른 정의역을 가진 두 개의 수평 접선을 생성했습니다.<br />
![Pikachu_-_Chrome_2023-05-28_16-47-10_AdobeExpress](https://github.com/juho-creator/Graphing-Pikachu/assets/72856990/762c90a4-571c-4e8f-b0fa-2b941eb5b2a0)
<br />
<br />

**단계 4 :** 포켓볼의 가로와 세로 위치를 조절하기 위해 각 방정식에 두 개의 슬라이더 변수가 포함되었습니다.<br />
![Pikachu_-_Chrome_2023-05-28_16-52-29_AdobeExpress](https://github.com/juho-creator/Graphing-Pikachu/assets/72856990/cbe51756-feb1-4c6c-8cad-c2208d755d21)
<br />
<br />
<br />
<br />

## 물
물의 방정식은 사인 함수와 부등식을 사용하여 만들었으며, 간단한 작업이었습니다. 그러나 사인 파동 위에 다양한 상호작용 요소를 추가하는 것은 혼란스러웠습니다.

**단계 1:** 사인 함수와 부등식을 결합하여 물과 같이 파동 형태의 파란색으로 채워진 효과를 만들었습니다.
<br />
<br />

![피카츄](https://github.com/juho-creator/Graphing-Pikachu/assets/72856990/cc93cff3-219d-404b-b094-5d4abb404dfa)
<br />
<br />


**단계 2:** 물 파동을 제어하기 위해 4개의 슬라이더 변수가 추가되었습니다.<br />
![피카츄](https://github.com/juho-creator/Graphing-Pikachu/assets/72856990/b03b495f-4305-4717-ab9a-d8a5ae29f076)
<br />
<br />
<br />
<br />

# 그래프 구성 요소
각 구성 요소에 대한 그래프 함수는 다음 폴더에 있습니다:

### 1. 피카츄
피카츄는 다음과 같은 구성 요소로 이루어져 있습니다:
* 원 (9)
* 포물선 (9)
* 타원 (2)
* 로그 (2)
* 지수 함수 (1)
* 세차 함수 (1)
* 제곱근 (1)  
<br />
<br />

### 2. 포켓볼
포켓볼은 다음과 같은 구성 요소로 이루어져 있습니다:
* 원 (2)
* 수평 접선 (2)
<br />

### 3. 물
물은 사인 함수로 이루어져 있습니다.

총 30개의 방정식이 사용되었으며, 10가지 다른 유형의 함수가 사용되었습니다.

