# 미션1 숫자야구
-1~9까지 중복되지 않는 랜덤한숫자 3개를 생성하고 유저가 이를 정확히 맞추게 하는 게임을 구현
## 기능 요구 목록

### 게임시작

- [x] 게임 시작시 게임시작 문구를 유저에게 출력하고 중복되지 않는 1~9 까지의 랜덤한 숫자 3개를 생성하고 유저 입력값을 초기화 해준다.

### 게임진행

- [x] 유저에게 숫자 3개를 입력받는다.
  - [x] 유저가 입력한 값이 예외상황(음수,숫자가아닌경우,중복되는경우,숫자가 3개가 아닐경우)에는 에러를 던져준다.

- [x] 유저에게 입력받은 값을 정답숫자와 비교하여 최종적으로 나온 스트라이크와 볼의 계수를 반환한다.
  - [x] 유저가 입력한 숫자가 정답에 포함되며 위치까지 똑같을경우 스트라이크를 +1한다.
  - [x] 유저가 입력한 숫자가 위치는 다르지만 정답에 포함될경우 볼을 +1한다.


### 게임종료

- [x] 게임진행 과정을 계속 반복 후 유저가 입력한 값과 정답값이 완전히 똑같을경우 게임종료 문구를 출력하며 게임을 재시작 할건지 의사를 묻는다.
  - [x] 유저가 1을 입력할경우 게임시작 단계로 돌아가 처음부터 다시 시작한다.
  - [x] 유저가 2를 입력할 경우 프로그램을 종료시킨다.
  - [x] 유저가 그 외 값을 입력할 경우 에러를 던져준다. 
