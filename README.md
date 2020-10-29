이번주는 CSS에 이어서 transition 속성과 transform 속성, animation속성에 대해서 배웠습니다.
trnasition 관련 속성은 delay, duration, property, timing-function이 있습니다. delay는 이벤트 발생 몇 초 후에 재생할지 지정하는 것이고,
duration은 몇 초동안 재생할지 지정하고, property는 어떤 속성을 변형할지 지정하고, timing-function은 수치 변형 함수를 지정합니다.

지난 주 과제에 적용한 부분은 각 섹션에 마우스를 올릴 때 글씨가 진하게 바뀌고 클릭을 하면 섹션의 배경의 색이 바뀌게 됩니다.
첫 번째 섹션은 header는 클릭을 하는 순간 바로 배경이 빨강으로 바뀌고, 두 번째 섹션은 aisde는 클릭하면 10초에 걸쳐서 서서히
배경의 색이 파랑으로 바뀌게 됩니다. 마지막 섹션인 section은 클릭을 계속했을 때 2초 동안은 변화가 없다고 2초 후에 변화가 나타납니다.

transform 속성은 객체를 회전 시키는 속성입니다. rotate 변환 함수를 사용하면 축자체도 이동하기 때문에 변환 함수를 사용하는 순서에 따라서 
결과가 바뀌게 될 수도 있습니다. 2D transform은 translate, sclae, skew, roate함수가 있습니다. 3D transform 함수는 2D transform함수와
내용은 비슷하지만 Z축이 추가됩니다. 

Animaion 속성은 화면을 변화시키는 속성입니다. delay, direction, duration, iteraion-count, name, play-state, timing-function이 있습니다.
Animaion 속성을 사용하기 위해서는 @keyframes을 정의해야 합니다. @keyframes은 form부터 to까지로 속성을 부여합니다. from은 시작점의 상태 점검을
설정하고, 중간 단계는 %로 값으로 설정하고, to는 마지막 시점에서의 상태를 설정합니다.


