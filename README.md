# java-calculator-precourse

## 기능 목록
- [ ] 문자열 입력 받기
- [ ] 문자열 입력 없을 시 0 반환
- [ ] 사용자 문자열 입력 검증
  - [ ] 기본 구분자, 커스텀 구분자 구분하기
    - [ ] 기본 구분자 검증
      - 기본 구분자 [쉼표(,) 콜론(:)]만 사용 가능
      - 입력받은 숫자는 모두 양수이여야 함
    - [ ] 커스텀 구분자 검증
      - "//"와 "\n" 사이 커스텀 구분자 지정 가능(2개 이상의 문자로도 지정 가능)
      - 기본 구분자는 커스텀 구분자로 지정이 불가하다
      - 구분자로 나뉜 숫자는 모두 양수여야 함.
- [ ] 숫자들의 합을 출력
  - 구분자를 통해 문자열 분리하여 숫자들 합 계산
- [ ] 잘못된 입력 값이 들어오면 IllegalArgumentException을 발생시키고 프로그램을 종료