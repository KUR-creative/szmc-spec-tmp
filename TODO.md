# 생각해낸 기능들
나중에 스펙에 자세히 명확하게 구체적으로 적어드리겠음

### 익스플로러는 다음과 같이 탐색기처럼 구성
![구이](imgs/Slide3.PNG)
![탐색기](imgs/Slide4.PNG)
- 탐색기 안에 이미지와 마스크를 나열
- 열고 닫을 수 있음
- 깊이는 일단 1 단계만 가능해도 됨

### 툴의 경우 일단 v0 것들처럼 구현
![툴](imgs/Slide1.PNG)
- draw / erase 모드
- 펜 / 사각형 툴
- 펜 툴 크기 키우기 / 줄이기
- 마스크 보이기 / 안 보이기

### v0보다 나아진 개선사항
- 확대 / 축소
- undo / redo
- 마스크 알파 적용

### 몇몇 사항들
"현재 열고 있는 망가 프로젝트" 라는 상태는 없음

![하나선택](imgs/Slide8.PNG)
![두개선택](imgs/Slide9.PNG)
(마스크 생성 / 텍스트 제거)는 한번에 **여러 이미지**에 적용 가능한데 \
(탐색기처럼) 폴더를 선택하거나, 이미지 여럿을 선택하면 \
여러개의 이미지에 적용 가능

주의: 배치 명령 실행을 위한 선택과, 현제 에디터에 띄우기 위한 선택을 구분해야 함. \
일단 위 이미지에서 
- 초록색 사각형은 에디터에 표시되는 것
- 파란색 음영 선택은 배치 명령 실행을 위해 선택된 것