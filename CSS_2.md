CSS

- 결합자
  - 자손 결합자 : selectorA 하위의 모든 selectorB 요소
  - 자식 결합자 : selectorA 바로 아래의 selectorB 요소
  - 일반 형제 결합자 : selectorA의 형제 요소 중 뒤에 위치하는 selectorB 요소를 모두 선택
  - 인접 형제 결합자 : selectorA의 형제 요소 중 바로 뒤에 위치하는 selectorB 요소를 선택
- Box model
  - 모든 HTML 요소는 box 형태로 되어있다.
  - content, padding, border, margin
  - margin : 테두리 바깥의 외부 여백, 배경색을 지정할 수 없다.
  - border : 테두리 영역
  - content : 글이나 이미지 등 요소의 실제 내용
  - padding : 테두리 안쪽의 내부 여백 요소에 적용된 배경색, 이미지는 padding까지 적용
  - box-sizing : 기본적으로 모든 요소의 box-sizing은 content-box, padding을 제외한 순수 contents 영역만을 box로 지정, => 해결 : box-sizing을 border-box로 설정
  - 마진 상쇄 : block A의 top 과 block B의 bottom에 적용된 각각의 margin이 둘 중에서 큰 마진 값으로 결합되는 현상
