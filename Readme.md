API 목록
- 사용자 추가
- 사용자 목록
- 계좌 추가
- 계좌 목록
- 계좌내역 추가
- 계좌내역 목록


추가 REST API

** 예치금 : 입금액 - 출금액

사용자를 입력받아, 사용자의 계좌별 예치금을 출력하시오
IN : 사용자ID
OUT : List 형태[계좌번호, 잔고]
사용자 나이대 별로, 평균 예치금을 출력하시오
IN : 없음
OUT : List 형태[연령대(10, 20, 30 등등), 예치금]
년도를 입력받아, 해당년도의 예치금 총액을 출력하시오
IN : 년도
OUT : 예치금 총액
기간을 입력받아, 돈을 많이 예치한 사용자 순으로 정렬해서 출력하시오
** 사용자의 본의 계좌는 모두 합산합니다
** 기간에는 시작일과 종료일이 포함되며, 해당 기간내의 입금액/출금액만이 계산됩니다
IN : 시작일, 종료일
OUT : List 형태[사용자ID, 이름, 예치금]

swagger url : http://localhost:7071/swagger-ui/index.html
