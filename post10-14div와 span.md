##div와 span 다루기<br>

- div<br>
div는 하나의 block 단위로 공간을 다루게 해준다. div 안에 width와 height를 정하면 div만의 고유 공간이 생기게 된다. 단 div를 다룰 경우 *을 통해 padding과 margin을 0으로 하고 

position 정리
fixed: 윈도우 내에서 위치를 결정함
absolute: 부모 태그에서 위치를 결정함
relative: 현재 태그에서 위치를 결정함
static: 결정된 위치 변경 불가
sticky: 스크롤을 내려도 결정된 위치에 존재

container와 item
container에 사용되는 태그
- display
- flex direction
- flex wrap
- flex flow
- justify-content
- align-item
- align-content

display: flex -> flex박스 정의
or grid: grid 방식으로 display 정의
flex-direction: 방향 설정 row, reverse  row
flex wrap: nowrap -> item들이 한 컨테이너에서 증가, wrap으로 할 경우 한 컨테이너가 채워지면 다음 라인으로 이동
flex flow: flex-direction과 flex wrap을 동시에 설정 가능
justify-content: flex-start(컨테이너 시작점 부터 아이템 정렬), flex-end(끝부분 부터 item 정렬), center(모든 아이템 가운데 정렬)
display: block

item
- order
- flex-grow
- flex-shrink
- flex
- align-self
