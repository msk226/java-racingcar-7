# java-racingcar-precourse

## 1. 입력 처리
- **문구 출력**
    - [x] `"경주할 자동차 이름을 입력하세요.(이름은 쉼표(,) 기준으로 구분)"` 문구 출력
    - [x] `"시도할 횟수는 몇 회인가요?"` 문구 출력

- **입력 받기**
    - [ ] 자동차 이름을 쉼표(,) 기준으로 구분하여 입력 받기
    - [ ] 시도할 횟수를 입력 받기

## 2. 입력 검증
- **자동차 이름 검증**
    - [x] 입력 값이 비어 있지 않은지 확인 
    - [x] 각 이름이 5자 이하인지 확인
    - [x] 동일한 이름이 여러 번 입력되지 않았는지 확인

- **시도할 횟수 입력 검증**
    - [x] 입력 값이 비어 있지 않고 정수인지 확인
    - [x] 입력된 시도 횟수가 1 이상인지 확인

## 3. 자동차 경주
- **자동차 정보 초기화**
    - [x] 입력된 이름을 사용해 각 자동차 객체 생성
    - [x] 모든 자동차는 초기 위치를 0으로 설정

- **경주 진행**
    - [ ] 각 시도마다 모든 자동차에 대해 0에서 9 사이의 무작위 값 생성
    - [x] 무작위 값이 4 이상인 경우 자동차가 한 칸 전진
    - [x] 각 시도 결과를 기록하고 누적 결과를 저장

## 4. 출력
- **자동차 경주 결과 출력**
    - [ ] 각 이동마다 모든 자동차의 이름과 위치 출력 (`자동차 이름 : 위치 표시`)
    - [ ] 예시: `pobi : --`, `woni : ---`

- **최종 우승자 출력**
    - [ ] 전체 시도 종료 후 가장 많이 전진한 자동차(들)를 우승자로 선정
    - [ ] 우승자가 여러 명일 경우 쉼표(,)로 구분하여 출력
    - [ ] 예시: `최종 우승자 : pobi, jun`

## 5. 종료 조건
- **예외 발생 시**
    - [ ] 예외 발생 시 오류 메시지를 출력하고 애플리케이션 종료
