# java-racingcar-precourse

# 프로젝트 설명

이 프로젝트는 사용자가 입력한 자동차 이름으로 시물레이션을 돌리는 게임입니다.
자동차는 주어진 횟수만큼 전진 혹은 멈출 수 있으며 가장 멀리 간 우승자를 출력하면 됩니다.

# 기능 목록

[MODEL]

Car - 이름과 거리에 대한 변수가 있고 전진할 수 있는 기능
Race - 경주하는 차들을 받아 시도횟수 만큼 레이싱을 하는 기능

[VIEW]

InputView - 사용자에게 자동차 이름과 시도 횟수를 입력받는 기능
OutputView - 레이싱 진행 과정과 우승자를 출력하는 기능

[CONTROLLER]

RaceController - 사용자에게 입력받고 레이싱을 시작하고 우승자를 판별하고 출력하는 중간 매개체 기능

# 유의 사항

1. 자동차 이름이 5글자가 넘거나 빈 이름이면 예외 발생
2. 시도횟수가 음수이거나 숫자가 아니면 예외를 발생하고 0이면 참여자 모두 공동 우승자 처리
3. 자동차 이름에 공백이 들어가 있다면 앞뒤 공백 제거