# 기능 요구 사항

## `1.` 자동차 생성
- [x] `1.1` 자동차 이름 입력 안내 문구를 출력한다.
- [x] `1.2` 구분자는 쉼표(`,`)로 입력 받는다.
- [x] `1.3` 잘못된 입력 시 예외를 발생시킨다.
  - [x] `1.3.1` 자동차의 이름은 최소 1글자, 최대 5글자로 제한한다.
  - [x] `1.3.2` 자동차의 이름은 중복될 수 없다. 
- [x] `1.4` 입력 받은 자동차들을 저장한다.

<br>

## `2.` 라운드 횟수
- [x] `2.1` 라운드(시도) 횟수 입력 안내 문구를 출력한다.
- [x] `2.2` 라운드 횟수를 입력 받는다.
- [x] `2.3` 잘못된 입력 시 예외를 발생시킨다.
  - [x] `2.3.1` 0이 아닌 양수만 가능하다.
  - [x] `2.3.2` `INT_MAX` 이하 값만 가능하다.
- [x] `2.4` 라운드 횟수를 저장한다.

<br>

## `3.` 전진 조건
- [x] `3.1` 각 자동차 별로 `0~9` 무작위 값을 생성한다.
- [x] `3.2` 각 라운드에 무작위 값이 4 이상인 자동차만 전진한다.
- [x] `3.3` 무작위 값이 3 이하인 경우 자동차는 전진할 수 없다.

<br>

## `4.` 라운드 출력
- [x] `4.1` 라운드 횟수만큼 경주 결과를 출력한다.
- [x] `4.2` 각 라운드마다 자동차의 위치를 출력한다.

<br>

## `5.` 우승자 출력
- [x] `5.1` 최종 우승자를 출력한다.
  - [x] `5.1.1` 단독 우승자를 출력한다.
  - [x] `5.1.2` 공동 우승자인 경우 쉼표(`,`)로 구분하여 출력한다.

<br>
