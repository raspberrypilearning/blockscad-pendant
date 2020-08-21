## 고리 만들기

지금 만들게 될 디자인은 중앙에서 교차하는 6개의 고리를 바깥쪽에서 더 큰 고리로 감싸는 형태입니다. 펜던트의 너비는 4cm이고 매달기 위한 구멍이 있습니다. 2mm 두께이므로 3D 프린팅이 매우 빠릅니다.

먼저 안쪽 고리를 하나 만듭니다.

--- task ---

웹브라우저에서 BlocksCAD 편집기를 엽니다. [blockscad3d.com/editor/](https://www.blockscad3d.com/editor/){:target="_blank"}.

블록을 드래그 앤 드롭하여 3D 객체 제작을 위한 코드를 작성합니다.

--- /task --- --- task ---

반지름이 `12`이고 높이가 `2`인 `cylinder`(원기둥)를 만듭니다.

![스크린샷](images/pendant-cylinder.png)

`Cylinder`는 자동적으로 자신을 X축과 Y축에 대해 정렬합니다. `not centered` 를 선택하여 펜던트가 표면에 놓이도록 합니다. (즉, Z축 값이 0보다 큽니다.)

코드를 변경할 때마다 **Render** 버튼을 클릭하여 결과를 확인하세요.

--- /task --- --- task ---

이제 `difference`{:class="blockscadsetops"}를 사용하여 중앙의 작은 `cylinder` 와 겹치는 부분을 제거하세요. 이것은 후프를 만듭니다:

![스크린샷](images/pendant-hoop.png)

원하는 경우 색상 사각형을 클릭하여 뷰어에서 사용되는 색상을 변경할 수 있습니다. 펜던트 색상은 사용하는 필라멘트의 색상으로 결정되기에, 결과물에 영향을 주지는 않습니다.

--- /task ---
	
	
