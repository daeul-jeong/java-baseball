# 숫자 야구 게임
## 진행 방법
* 숫자 야구 게임 요구사항을 파악한다.
* 요구사항에 대한 구현을 완료한 후 자신의 github 아이디에 해당하는 브랜치에 Pull Request(이하 PR)를 통해 과제를 제출한다.

## 과제 제출 과정
* [과제 제출 방법](https://github.com/next-step/nextstep-docs/tree/master/precourse)

## Commit Convention
> type(scope): comment 
- Type
    - feat : 기능 구현
    - fix : 버그 수정트
    - docs : 문서 작성 및 수정
    - style : 스타일 수정
    - refactor : 코드 리팩토링
    - test : 테스트 클래스 추가
    - chore : 기타
- scope 
    - 구체적 범위, 위치
- comment
    - 내용 적기

## 기능 요구사항
1. 컴퓨터는 1에서 9까지 서로 다른 임의의 다른 수 3개를 선택함.
2. 게임 플레이어도 컴퓨터가 선택했을 거 같은 1에서 9까지 서로 다른 임의의 다른 수 3개를 입력한다.
3. 
   - 같은 수가 같은 자리에 있는 경우 -> Strike
   - 같은 수가 다른 자리에 있는 경우 ->  Ball
   - 같은 수가 전혀 없는 경우 -> Nothing  
4. 계속 바나복하다가 3자리 모두 맞추면 게임 종료
5. 게임 종료 후 게임을 재시작하거나 완전히 종료할 수 있다.

## 기능 정의
1. 사용자로부터 1~9까지 서로 다른 임의의 수 3개를 입력 받는 기능
2. 1~9까지 서로 다른 임의의 수 3개를 선택하여 리턴하는 기능
2. Strike, Ball 체크하는 기능
3. 게임 재시작 또는 종료 기능