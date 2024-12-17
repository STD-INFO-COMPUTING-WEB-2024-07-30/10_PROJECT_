# 농산물 거래 중계 플랫폼

<img src="https://img.shields.io/badge/IntelliJ-000000?style=for-the-badge&logo=intellijidea&logoColor=white"> <img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">

# Project Intrudution
### 온라인 농산물 거래를 돕는 중계 플랫폼
* 농산물이 소량인 경우에도 이용 가능
* 지도를 통해 가까운 거리의 경우 직거래 가능

 ---------------
 
**판매자**         
* 농산물 판매 가게 생성          
* 직거래를 위한 농지 위치 기입               
* 농지 사진 기입              
* 판매 품목 작성          
  * 판매 품목의 큰 종과 세부 속을 작성 (당근 - 하루 당근)           
  * 농산물 사진, 가격, 수량 작성           

**구매자**
* 키워드, 자신의 위치를 기준으로 검색 가능          
* 구매 폼목의 후기 작성 가능

**관리자**
* 관리자 계정으로 로그인
* 판매자의 가게가 생성되면 관리자에게 알림 수신
 * 판매자 가게에 문제가 되는 부분 발견 시 삭제 가능
 * 구매자 후기에 문제가 되는 부분 발견 시 삭제 가능

<br>

# History
### Members
|조원|역할|작업 경로|
|-|-|-|
|우상원|역할|Git link|
|김기현|역할|Git link|
|지윤서|역할|Git link|

--------------------

### Plan
|작업 파트|작업 기간|작업 설명|사용 기술|
|-|-|-|-|
|FN|12/06~12/8|프론트엔드|React <img src="https://img.shields.io/badge/JS-F7DF1E?style=for-the-badge&logo=javascript&logoColor=white">|
|BN|12/9~12/10|상품 주문|OAuth2, JWT|
|BN|12/9~12/13|상품 CRUD|OAuth2, JWT|
|BN|12/9~12/13|장바구니 CRUD|OAuth2, JWT|


|BN|12/14~12/16|판매자 - 가게 생성, 품목 작성 구현||
|BN|12/16~12/18|구매자 - 내정보, 구매, 후기 구현||
|BN|12/18~1219|관리자, 지도 구현||

<br>

# 작업 로직
## ERD

## EndPoint Documents
|URI|Request Method|Description|
|-|-|-|
|/user/login|GET/POST|계정 로그인|
|/user/join|POST|계정 회원 가입 - 판매자, 구매자, 관리자|
|/seller/add|GET/POST|판매자 가게 물품 추가|
|/seller/update|GET/POST|판매자 가게 물품 수정 - 판매|
|/seller/delete|DELETE|판매자 가게 물품 - 매진|
|/seller/select|GET/POST|판매자 가게 물품 조회 - 키워드 검색|
|/comment/add||농산품 후기 추가 - 작성|
|/comment/update||농산품 후기 수정|
|/comment/delete||농산품 후기 삭제|
|/comment/select||농산품 후기 조회 - 구매자 별 후기|

## Tree 

## Dependencies Lists
