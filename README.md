# jwp-racingcar

## 1단계 구현 목록

### ✔️ 준비

- [x]  자동차 미션 코드 가져오기

### ✔️ 웹 요청/응답

- [x]  웹 요청 구현하기
    - [x]  이름 리스트
    - [x]  실행 횟수 받아오기
- [x]  웹 응답 구현하기
    - [x]  승자
    - [x]  움직인 결과(이름, 포지션) 리스트

### ✔️ DB 연결

- [x]  H2 DB 연동하기
- [x]  DB에 저장하기
    - [x]  실행 횟수
    - [x]  플레이어 별 최종 이동 거리 (이름, 최종 위치)
    - [x]  우승자
    - [x]  플레이한 날짜, 시간

---

## 2단계 구현 목록

### ✔️ 1단게 추가 수정사항

- [x]  DAO 빈(Bean) 적용
- [x]  데이터베이스 구조 변경
    - [x]  racing_game - winners column 삭제
    - [x]  racing_car - isWinner column 추가

### ✔️ 2단계 요구사항

- [ ]  게임 플레이 이력 API
    - [ ] 각 게임 별 이력 반환
        - [ ]  우승자
        - [ ]  각 자동차 이름과 최종 위치
- [ ]  기존 코드 출력 방식 변경
    - [ ]  게임 중간 과정 출력 삭제
- [ ]  중복 코드 제거
    - [ ]  자동차 게임 생성
    - [ ]  리팩토링
