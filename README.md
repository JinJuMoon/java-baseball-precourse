# 숫자 야구 게임

## 구현할 기능 목록
1. 컴퓨터가 1부터 9까지 서로 다른 수로 이루어진 3자리의 수를 생성한다.

2. 사용자가 3자리의 숫자를 입력한다.  
    - 사용자의 입력값이 예외인 경우  
        1) 숫자로만 이루어져 있지 않은 경우  
        2) 3자리 숫자가 아닌 경우  
        3) 0이 들어있는 경우  

3. 컴퓨터가 생성한 숫자와 사용자라 입력한 숫자를 비교한다.

4. 비교 결과를 출력한다.  
    4-1. 정답이 아닐 경우, 힌트를 출력하고 2번으로 돌아간다.  
    4-2. 정답일 경우, 게임 종료 사실을 출력하고 5번으로 넘어간다.  

5. 게임 종료 후, 사용자가 게임을 다시 시작할지 완전히 종료할 지 입력한다.  
    5-1. '1'을 입력하면 게임을 새로 시작한다.(1번으로 돌아간다.)  
    5-2. '2'를 입력하면 게임을 완전히 종료한다.  