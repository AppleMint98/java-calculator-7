# java-calculator-precourse

## 기능 목표
입력한 문자열에서 숫자를 추출하여 더하는 계산기 구현
## 기능 목록

- 기본 구분자 ("," , ":") 를 지정하는 경우
    - 구분자를 기준으로 분리한 각 숫자의 합을 반환
        - ex) "" => 0, "1,2" => 3, "1,2,3" => 6, "1,2:3" => 6

- 커스텀 구분자 ("//", "\n" 사이 위치하는 문자) 를 지정하는 경우
    - 커스텀 구분자는 기본 구분자 외의 문자
    - 커스텀 구분자를 기준으로 분리한 각 숫자의 합을 반환
        - ex) "//;\n1;2;3" => 6

- 잘못된 값 입력 시 IllegalArgumentException 발생 후 애플리케이션 종료