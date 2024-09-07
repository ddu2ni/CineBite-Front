![003_1](https://github.com/user-attachments/assets/5465d012-e0dd-4f11-93d5-7649dc5a10ff)

![004](https://github.com/user-attachments/assets/7d534395-c36d-4168-a290-c9e5f788def0)

</br>

## 💡 프로젝트 소개

#### ㅣ 요즘 핫한 영화 다모여라~ 🎇

#### ㅣ 영화 관련된 커뮤니티엔 뭘 말하는지 궁금하다고❓

### </br></br>🍿 CineBite "시네바이트"에서 알려줄게 !

**"CineBite"**
는 **영화의 정보**(커뮤니티 포함)를 **통합적으로 제공하는 플랫폼**으로, 사용자들에게 작품 정보, 검색, 영화 추천 등을한곳에서 제공하는 것을 목표로 합니다.
</br></br></br>

## 💡주요 기능 소개

✅ **Ouath 구글·카카오·일반 로그인 / 회원가입**

🎞️ **메인) 핫한 영화 보여주기**

🎬 **찜하기 / 찜한 영화 기반 작품 추천**

🔎 **작품**(영화명/배우/장르) 및 **커뮤니티**(태그/게시글) **검색 · 조회**

💬 **커뮤니티 작성 및 인기 게시글/태그 기능**

</br></br>

## 💡 프로젝트 개요

<table>
    <tr>
        <th>프로젝트 명</th>
        <td>CineBite</td>
        <th>개발기간</th>
        <td>2024/06/03 ~ 2024/07/12</td>
    </tr>
    <tr>
        <th>프로젝트 개요</th>
        <td colspan="3"> 영화 커뮤니티 웹사이트</td>
    </tr>
    <tr>
        <th>개발인원</th>
        <td colspan="3">팀/ 5인 </td>
    </tr>
    <tr>
        <th>맡은기능</th>
        <td colspan="3"> 영화 및 커뮤니티 검색해서 조회 (최근검색어 · 연관검색어) / 메인 · 검색 및 리뷰 css </td>
    </tr>
    <tr>
        <th>운영체제</th>
        <td colspan="3">Windows 10</td>
    </tr>
    <tr>
        <th>개발언어</th>
        <td colspan="3"> java 11, JavaScript</td>
    </tr>
      <tr>
        <th>Backend</th>
        <td colspan="3"> Spring Boot (ver. 3.x / port : 4000)</td>
    </tr>
     <tr>
        <th>Frontend</th>
        <td colspan="3"> React (ver.18.3.1/port : 3000)</td>
    </tr>
    <tr>
        <th>개발도구</th>
        <td colspan="3">VSCode, Gradle</td>
    </tr>
    <tr>
        <th>DB</th>
        <td colspan="3">MySQL (8.3.0)</td>
    </tr>
     <tr>
        <th>형상관리</th>
        <td colspan="3">Git (개발/배포 브랜치 전략)</td>
    </tr>
</table>
</br>
- 추후 디벨롭 예정

---

</br></br>

💻 **참여인원**

| 이름   |  파트  | 역할                                                                              |
| ------ | :----: | --------------------------------------------------------------------------------- |
| 김지은 | BE, FE | 영화 tmdb api로 조회, 영화 상세정보, 랭킹, 오늘의 영화, 메인 css                  |
| 박진영 | BE, FE | EC2, RDS 배포, 영화 정보 및 상세 정보 tmdb api 조회, 영화 상세정보, 영화 추천, 영화 즐겨찾기,css                |
| 박 솔  | BE, FE | Oauth 로그인, 로그인 및 회원가입, 마이페이지 파일 업로드, 로그인 및 회원가입 css  |
| 윤수인 | BE, FE | 영화 및 커뮤니티 검색해서 조회 (최근검색어 · 연관검색어), 메인 · 검색 및 리뷰 css |
| 이혜민 | BE, FE | AWS S3 배포, 커뮤니티 게시글 및 태그 등록 및 삭제 , 핫한 영화 조회, 커뮤니티 css               |

---

</br></br>

📂 **파일구조 (front)**

```front
└─ src
   ├─ assets
   │  └─ images
   ├─ components
   │  ├─ Footer
   │  ├─ Header
   │  └─ Main
   │     ├─ Community
   │     ├─ Favorite
   │     ├─ Home
   │     ├─ MyPage
   │     ├─ NotFound
   │     ├─ Recommend
   │     ├─ Review
   │     ├─ Search
   │     └─ UserInfo
   ├─ hooks
   ├─ index.css
   ├─ index.js
   ├─ logo.svg
   ├─ reportWebVitals.js
   ├─ routes
   ├─ setupTests.js
   └─ utils
      ├─ userInfo
         ├─ api
         ├─ ResponseCode.js
         └─ ResponseMessage.js

```
