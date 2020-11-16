# 숫자 야구 게임
## 기능 목록 
### 게임 룰
1. 1~9까지 서로 다른 3자리 숫자로 구성된 임의의 '문자열' 을 생성
2. 사용자가 입력한 문자열을 평가하고 결과를 집계
    * 같은 수가 동일한 자리(인덱스)에 있으면 '스트라이크' 힌트 
    * 같은 수가 존재하나 다른 자리(인덱스)에 있으면 '볼' 힌트
    * 같은 수가 하나도 없으면 '낫싱' 힌트
 
### 사용자 인터페이스
1. '3 스트라이크' 힌트에서 사용자 입력에 따른 '새로 시작'/'종료' 분기
2. 사용자가 '3 스트라이크' 힌트를 얻을 때까지 계속 Scanner 호출
3. 사용자가 입력한 3자리의 문자열이 유효한지 검증  
    * 아무것도 입력하지 않았을 시 재입력 유도
    * 숫자 이외의 문자가 포함되었을 시 재입력 유도
    * 중복된 숫자를 입력했을 시 재입력 유도
4. 유효하지 않은 사용자 입력에 대해 Exception 처리