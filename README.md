# MVP

ERD : https://www.erdcloud.com/p/JYqD8jKydarZYmrxE
-----------------------------------------------------------
### Music Value Platform

### 개요
* 인디 음악가들이 자신의 음악을 판매하고, 구매자가 해당 음악을 다양한 창작물에 법적으로 활용할 수 있도록 지원하는 온라인 마켓플레이스입니다.
* 다양한 창작물에 인디 음악가들의 음악이 사용되어 대중들에게 노출되어 인디 음악가의 인지도 상승 및 부가적인 수익 창출이 가능합니다.
-----------------------------------------
### 기술스택
- 백엔드: Django, Python, PostgreSQL
- 프론트엔드: JavaScript, CSS, HTML
-----------------------------------------
### 주요 기능
* 로그인/회원가입 -> 구글,네이버 소셜 로그인 및 가입 지원.
* 맘에 드는 음악 찜하기/취소하기
   - NavBar 찜한음악
     + 자신이 찜한 음악의 썸네일, 타이틀, 아티스트명, 가사보기 버튼, mp3 플레이어, 구매버튼이 표시됨. 찜 취소시 목록에서 삭제됩니다.
     + 
     + 최근들은 음악: 최근 들은 음악 10개가 표시됨. 가장 최근 음악이 맨 위로 올라오고 들은지 가장 오래된 음악이 삭제됩니다.
* 마이페이지(홈/구매내역/판매내역/팔로우)
  - 홈
    + 프로필 이미지 및 닉네임을 변경 가능.
    + 구매자의 경우 [찜한음악, 판매자 신청하러 가기] 두개의 바로가기가 표시됩니다.
    + 구매자의 경우 자신이 최근에 구매한 9개의 음악 썸네일이 입체적으로 표시됩니다.
  - 구매내역
    + 구매한 음악의 구매날짜, 제목, 제작자, 가격이 최신순으로 표시됩니다.
    + 구매날짜 클릭 시, 결제 정보를 더 상세하게 확인 가능합니다.
  - 판매내역
    + 자신이 판매한 음악의 등록날짜, 제목, 총 구매자의 수, 총 수익이 표시됩니다.
  - 팔로우
    + 자신이 팔로우 중인 아티스트들이 표시됩니다.
    + 팔로우한 아티스트들의 최근 활동 내역이 표시됩니다.
    + 팔로우 취소버튼을 누르면 팔로우 목록에서 삭제됩니다.
----------------------------------------------------------------------------
* 음악 업로드(판매자 전용)















