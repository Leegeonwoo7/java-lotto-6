# 우테코 3주차 - lotto

* Person class - 로또번호를 구매하는 객체 클래스
  * 멤버변수
    1. int pay - 로또 구매금액
    2. List<List<Integer>> lottoTicket - 6개의 번호로 이루어진 줄들을 담고있는 리스트
  * 메서드
    1. buyLotto - 6개의 번호(1줄)을 금액만큼 구매
    2. displayTicket - 구매하여 보유중인 로또들의 번호를 출력

* LottoMachine class - 로또를 발급해주는 객체 클래스
  * 멤버변수
    1. List<Integer> lottoNumbers - 6자리의 로또번호를 저장하는 변수
  * 메서드
    1. generateLottoTicket - 랜덤 6개의 번호를 발급하는 메서드
