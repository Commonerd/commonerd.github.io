# Yummyos 

![Preview](https://user-images.githubusercontent.com/9112801/96329524-c8906600-101b-11eb-8fd8-4d45e7f0cd1b.jpg)

프로젝트 주제 및 목적 : 조회수와 좋아요 수를 기반으로 한 맛집 추천사이트
본인의 역할 : 메인페이지, 맛집 상세페이지, 위시리스트, 로그인/회원가입
프로젝트 선택이유와 중점기능: 지도와 이미지를 활용하여 맛집정보를 공유하는 것이 매력적이라 판단함. 랜덤메뉴추천, 위시리스트, 좋아요, 해시태그 기능에 중점.

### 개발환경

- OS : Window
- Database : Oracle
- Tools : Spring Boot
- Front End : Html5, Css3, Javascript
- Back End : Java
- API : 카카오맵 API


### 기술설명 및 핵심내용

- 회원가입 및 로그인 : 회원가입 시 중복검사, 메일 인증번호 발급, 세션과 인터셉터 적용
- 메인페이지: 앨범형으로 맛집 리스트 구현, TOP9(조회수 순) 식당 배너 클릭 시 해당 식당의 상세 페이지로 이동
- 오늘 뭐 먹지?: 랜덤 메뉴 선택, 해당 메뉴를 카카오 map API로 자동 검색
- 검색 페이지: 키워드(카테고리, 식당 이름, 글 제목) 필터링, 페이지네이션
- 최신맛집 리스트: 최신순으로 나열,  클릭시 상세 페이지로 이동, 페이지네이션
- 맛집상세페이지: 위도와 경도를 이용한 kakao map API 구현, 스마트에디터를 활용한 음식 사진 정보, 위시리스트 등록, 좋아요, 해시태그 기능
- 공지사항 : 글등록, 수정, 삭제
- 미디어픽 : 방송에 나온 맛집 소개, 앨범형 리스트 구현, 페이지네이션
- 푸드스토리 : 음식의 유래와 효능, 앨범형 리스트 구현, 페이지네이션


### About Me

소통을 통해 동반성장을 추구합니다.
일상의 문제를 기술적으로 해결하는 데 관심이 있습니다.
IT기술을 통해 보다 나은 세상을 꿈꿉니다.



All the possible classes are defined above and just referenced in the `className` attribute of each element. This comes with a couple benefits:

1. It keeps the overall component definition slightly cleaner (i.e. there isn't a huge class string)
2. You can reuse styles a little easier
3. This still qualifies as purgeable HTML (assuming the class is actually used)

This is however just a recommendation, the template allows you to write the components in any way you wish.

## License

Licensed under the [MIT License](https://github.com/RyanFitzgerald/devfolio/blob/master/LICENSE.md).
