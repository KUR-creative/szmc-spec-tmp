# szmc-spec-tmp

## v1 spec

### 작업 과정

#### 사용자는 이미지 파일(png, jpg)을 열어서 만화 프로젝트를 생성할 수 있습니다.
##### 만화 프로젝트
- 만화 프로젝트: 만화 프로젝트는 만화 이미지들의 리스트와 각 이미지에 대응하는 [마스크](#마스크)들로 이루어집니다. 
- 순서유지: 만화 프로젝트는 순서가 유지되어야 합니다.
- 영속성: 만화 프로젝트는 사용자의 디스크에 영속적으로 저장되어야 합니다.
##### 마스크
- 마스크는 만화 이미지에서 지워야하는 영역을 표시합니다. 최초에는 투명한 빈 이미지입니다.
- 마스크는 투명한 빈 이미지 위에 지워야하는 영역을 빨간색(255,0,0)으로 표시합니다.

만화 프로젝트에서  
