CSS

- Float : 본래는이미지 좌, 우측 주변으로 텍스트를 둘러싸는 레이아웃을 위해 도입, 더 나아가 이미지가 아닌 다른 요소들에도 적용해 웹 사이트의 전체 레이아웃을 만드는데까지 발전
  - flexbox 및 그리드 레이아웃과 같은 기술이 나오기 이전에 Float은 열 레이아웃을 만드는데 사용됨
  - flexbox와 grid의 출현과 함께 결국 원래 텍스트 블록 내에서 float 이미지를 위한 역할로 돌아감
  - none, left, right
  - Float clear
    - 선택한 요소의 맨 마지막 자식으로 가상 요소를 하나 생성
    - 보통 content 속성과 함께 짝지어, 요소에 장식용 콘텐츠를 추가할 때 사용
    - 기본값은 inline
    - 선행 floating 요소 다음일 수 있는지 또는 그 아래로 내려가야 하는지를 지정
    - clear 속성은 부동 및 비부동 요소 모두에 적용됨
- Flexbox : 요소 간 공간 배분과 정렬 기능을 위한 1차원(단방향) 레이아웃
  - 요소 : Flex Container(부모 요소), Flex item(자식 요소)
  - 축 : main axis(메인축), cross axis(교차축)
  - Flex Container : flexbox 레이아웃을 형성하는 가장 기본적인 모델, Flex Item들이 놓여있는 영역, display 속성을 flex 혹은 inline-flex로 지정
  - Flex Item : 컨테이너의 컨텐츠
  - flex-direction / justify-content / align-items, align-self, align-content / flex-wrap, flex-flow, flex-grow, order

