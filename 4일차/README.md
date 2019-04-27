# 4회차

<br>

## 그리드시스템 (Grid system) 설계
![](https://i.imgur.com/vR7TIDW.png)
> 그리드시스템 설계는 텍스트 및 레이아웃의 배치를 규칙적으로 정렬하여 웹을 사용하는 사용자에게 정보 전달력을 높이기 위해 편집 디자인의 기술인 그리드시스템을 웹에 반영하여 정보 전달력을 높이기 위해 규칙과 패던을 정의합니다.

<br>

### 그리드시스템
 - 그리드시스템은 컬럼 (Columns), 거터 (Gutter), 마진 (Margin)으로 이루어져 있습니다.
 - 컬럼 구하는 공식 : 컬럼 폭 = ( 디바이스 중단점 너비 - ( 거터 폭 * ( 컬럼 수 - 1 )) / 컬럼 수
<br>

![](https://i.imgur.com/7eTAIUG.png)
<br>
[마크업](https://codepen.io/heeseung83/pen/yrEvzz)

<br>

#### 유니클로 그리드 셀계
- max width: 1200px
- Gutter width: 20px
- columns: 12cols
- margin width:28px
- column width:77px
<br>
 [마크업](https://codepen.io/heeseung83/pen/vMbVNG)


### 레이아웃 중단점 설정 (Breakpoint)
- Dasktop, Tablet, Mobile 등 중단점 기준 설정


<br>

![](https://i.imgur.com/D43c5UQ.png)

<br>

####유니클로 레이아웃 중단점 설정

- Dasktop min-width 1200px
- Tablet max-width 960px
<br>

### 참고
- [그리드 계산 사이트](http://gridcalculator.dk/)
- [Device Metrics](https://material.io/tools/devices/)
- [8-Point Grid System](https://builttoadapt.io/intro-to-the-8-point-grid-system-d2573cde8632)
- [반응형 프로젝트 진행 시 참고](https://i.imgur.com/UQWlHW3.png)