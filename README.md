# 베이비 복스

#### 테스트 링크:  [클릭](https://kchanyou.github.io/BabyBoks_PlayTest/) <br>
#### 조작법 <br>
&nbsp;&nbsp;  1. 로비 <br>
&nbsp;&nbsp;  &nbsp;&nbsp;  Q,&nbsp; A 스테이지 좌우 이동 <br> 
&nbsp;&nbsp;  &nbsp;&nbsp;  O 선택 <br><br>
&nbsp;&nbsp;  2. 스테이지 <br>
&nbsp;&nbsp;  &nbsp;&nbsp;  Q,&nbsp; O 좌우 이동 <br>
&nbsp;&nbsp;  &nbsp;&nbsp;  L 생명력 강제 감소(6번 누르면 게임오버) <br> 
&nbsp;&nbsp;  -> 좌우 이동 조작 통일 시키는게 좋을듯 <br> 

### Unity 버전 / Target Platform
- **Unity 2022.3.35f1**
- **PC(Windows)**


## 메인 폰트  
- **프리텐다드**  
- **자이언츠체 Inline**


## 씬 구조  
1. **시작 씬**  
2. **스테이지 선택 씬 / 복어 커스터마이징 씬**  
3. **스테이지 씬** (총 9개)


## 스테이지 선택  
- **캐릭터 꾸미기**: 원하는 스타일로 복어 커스터마이징  
- **스테이지 선택**: 플레이할 스테이지를 선택  


## 스테이지 구성  

### 캐릭터  
- **복어 이동**:  
  - 제자리에서 좌우 이동 및 점프 가능  
- **먹이(노트)**:  
  - 먹이를 먹으면 콤보 수 증가 및 스코어 상승  
  - 먹이를 놓치면 생명력 감소 (초기 생명력: 6개)  
- **아이템(별)**:  
  - 복어가 일시적으로 커져 2~3개의 레인을 동시에 먹을 수 있음  

### 점수 시스템  
- **스테이지 해금 조건**:  
  - 각 스테이지의 최고 점수를 누적 점수로 달성 시 다음 스테이지 해금  

### 쉬엄모드 / 열일모드 (논의 중)


## 게임 상태  

- **게임오버**  
  - 정산 UI 표시: 점수, 다시하기, 나가기  
- **클리어**  
  - 정산 UI 표시: 점수, 다시하기, 나가기  
- **중도 이탈**  
  - 키보드나 마우스 조작을 통해 이탈  


💡 **Note:**  
