# 로또

### 기능요구사항


* 로또 구입 금액을 입력하면 구입 금액에 해당하는 로또를 발급해야 한다.
* 로또 1장의 가격은 1000원이다.
  - 숫자만 입력가능
  - 1000원 이상이어야 1개 이상 구매 가능
* 로또 번호는 1~45까지 정수만 허용
* 지난 주 당첨 번호 입력 가능 - 6자리 숫자만 (중복 안됨)
* 당첨 통계 출력
  - 3개 일치 (5000원) 
  - 4개 일치 (50000원)
  - 5개 일치 (150000원)
  - 6개 일치 (2000000000원)
  - 수익률 계산 출력
  
### 프로그래밍 요구사항
* UI 로직을 InputView, ResultView 클래스로 분리한다.
* indent depth를 2를 넘지 않도록 한다. 1까지만 허용한다.
* 함수의 길이가 15라인을 넘어가지 않도록 구현한다.
* 모든 로직에 단위 테스트를 구현한다. 단 UI 로직은 제외.
* else, swith/case 사용하지 않는다.

![img.png](img.png)