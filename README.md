
## **주요 내용**

Coffee + Order의 합성어로 어느 카페에서나 자리를 확인 할 수 있고,  음료를 예약 주문 할 수 있는 어플리케이션 입니다.

![스크린샷 2024-07-11 122456](https://github.com/KIPUMP/coffee_order_APP/assets/86760876/e685c24d-f11f-461b-af17-5f42bc3ca25b)
![스크린샷 2024-07-11 122441](https://github.com/KIPUMP/coffee_order_APP/assets/86760876/6d26945d-4acd-4886-8de7-adce0e0f6d86)


## **담당 업무**

아키텍처 설계 | usecase 다이어그램 및 시나리오 작성 | ERD 작성 및 DB 모델링 | API 설계 및 문서화 작업 | unit test 작성

### usecase diagram

![스크린샷 2024-07-11 122629](https://github.com/KIPUMP/coffee_order_APP/assets/86760876/a8b825a5-0cca-4432-b438-524b486325f1)

### Database modeling
![스크린샷 2024-07-11 122720](https://github.com/KIPUMP/coffee_order_APP/assets/86760876/1def2cf1-6c0e-4c23-afc9-330f07a793ec)

![스크린샷 2024-07-11 122725](https://github.com/KIPUMP/coffee_order_APP/assets/86760876/a42e2901-7f74-41fb-be01-25db49c019d5)


## **사용 기술**

 Android studio | Firebase | Github | Jira

## 개선 사항

### 로그인 / 로그아웃 기능

RDBMS(MySQL, Oracle) 에서 로그인을 구현 할 때 아이디와 패스워드가 같으면 앱에 접속 할 수 있는 방식에서 NoSQL 기반의 Firebase를 사용하여 보안처리와 속도적인 측면에서 개선 할 수 있었습니다.

### 카페 자리 예약 API

기존의 스타벅스의 사이렌오더를 착안해서 이를 개인 카페에서도 사용할 수 있도록 만듦과 동시에 기존의 서비스에서 기능적으로 개선할 점이 있는지 알아보던 중 개인 카페 가는 이유는 보통 사람들이 커피를 먹으러 간다기보단 카페에서 시간을 보내기 위해(ex. 분위기) 간다는 것을 알게 되었고 카페의 남은 자리 확인 기능을 기획하였고 이를 구현하였습니다.

## **결과 / 성과**

- Firebase에 등록된 카페 정보를 보여주는 API
- 카페 상세 페이지에서 음료를 주문할 수 있는 API
- 음료를 주문한 뒤 카페 안의 자리를 예약 할 수 있는 API
- 카페 내부의 좌석 현황을 알 수 있는 API
- 로그인/로그아웃 API
