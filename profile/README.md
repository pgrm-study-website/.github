# <img src="/profile/%EC%95%84%EC%9D%B4%EC%BD%984png.png" width="25" height="25"> [Plming](https://plming.netlify.app)

</br>

## 😁 서비스 소개

- Plming은 프로그래밍과 관련된 스터디, 공모전, 프로젝트 등의 팀원을 구할 수 있도록 도와주는 서비스입니다.

</br>

## 🧑‍💻 팀원 소개

- <img src="https://avatars.githubusercontent.com/u/66582313?v=4" align="center" width="25" height="25"> [slchoi](https://github.com/SulimChoi) : 게시글 관련 기능 구현 (게시글 작성 관련 API, 게시글 신청 API, 게시글 검색 API, 댓글 API, 알림 API )

- <img src="https://avatars.githubusercontent.com/u/80041449?v=4" align="center" width="25" height="25"> [JMsuper](https://github.com/JMsuper)

- <img src="https://avatars.githubusercontent.com/u/79067549?v=4" align="center" width="25" height="25"> [seuha](https://github.com/seuha516)

- <img src="https://avatars.githubusercontent.com/u/49177223?v=4" align="center" width="25" height="25"> [sumi](https://github.com/sumi-0011)

</br>

## 🖥 핵심 기능

### 1. 게시글 관련 핵심 기능

- 팀원 모집 **게시글 작성** 기능을 제공합니다.
  - 제목, 내용을 입력하고, 카테고리, 최대 모집 인원 수, 기간, 태그를 선택할 수 있습니다.
- 작성된 게시글을 **검색**할 수 있습니다.
  - 키워드 검색을 통해 게시글 제목 또는 내용 또는 제목 + 내용에 키워드가 포함되어 있는 게시글을 검색합니다.
  - 카테고리, 기간 혹은 태그를 통한 검색도 가능합니다.
- 게시글 **신청** 기능을 제공합니다.
  - 팀원 모집 게시글 내용과 게시글 작성자의 프로필을 확인하고, 참여를 희망하는 게시글에 참여를 신청할 수 있습니다.
  - 참여를 신청할 경우 게시글 작성자에게 알림이 가며, 게시글 작성자는 참여를 신청한 사용자를 팀원으로 받아들일지, 신청을 거절할지 선택할 수 있습니다.

|       메인 화면        |     게시글 목록      |
| :--------------------: | :------------------: |
| <img src="/images/메인%20화면.gif"/> | <img src="/images/게시글%20목록1.gif"/>|
|    **게시글 작성**     |   **게시글 수정**    |
|<img src="/images/게시글%20작성.gif"/>|<img src="/images/게시글%20수정.gif"/>|
| **게시글 키워드 검색** | **게시글 조건 검색** |
|<img src="/images/키워드%20검색.gif"/>|<img src="/images/조건%20검색.gif"/>|
|    **게시글 신청**     | **게시글 신청 취소** |
|<img src="/images/참여%20신청.gif"/>|<img src="/images/신청%20취소.gif"/>|
|  **게시글 신청 승인**  | **게시글 신청 거절** |
|<img src="/images/참여%20승인.gif"/>|<img src="/images/참여%20거절.gif"/>|
|     **댓글 달기**      |    **댓글 삭제**     |
|<img src="/images/댓글%20달기.gif"/>|<img src="/images/댓글%20삭제.gif"/>|
|    **대댓글 달기**     |   **대댓글 삭제**    |
|<img src="/images/대댓글%20달기.gif"/>|<img src="/images/대댓글%20삭제.gif"/>|



### 2. 사용자 관련 핵심 기능

- 이메일을 통한 회원가입 없이 **소셜 로그인**을 통해 로그인할 수 있는 기능을 제공합니다.
  - 구글, 카카오, 깃허브를 통한 소셜 로그인이 가능합니다.
- **쪽지** 기능을 제공합니다.
  - 쪽지를 통해 다른 사용자와 대화가 가능합니다.
- **알림** 기능을 제공합니다.
  - 본인이 작성한 게시글에 참여 신청이 들어오면 알림이 옵니다.
  - 본인이 작성한 게시글에 댓글이 달리거나, 본인이 작성한 댓글에 대댓글이 달릴 경우 알림이 옵니다.
  - 다른 사용자로부터 메시지를 받은 경우 알림옵니다.
- **마이페이지**를 통해 본인이 작성한 게시글과 신청한 게시글, 댓글 단 게시글을 확인할 수 있습니다.

|     회원 가입     |   이메일 로그인   |
| :---------------: | :---------------: |
|                   |<img src="/images/로그인.gif"/>|
|  **구글 로그인**  | **카카오 로그인** |
|                   |<img src="/images/카카오%20로그인.gif"/>|
| **깃허브 로그인** |  **마이페이지**   |
|                   |<img src="/images/마이페이지.gif"/>|
|   **쪽지 확인**   |  **쪽지 보내기**  |
|<img src="/images/메시지%20확인.gif"/>|<img src="/images/쪽지%20보내기.gif"/>|
|   **알림 확인**   |  **회원 탈퇴**   |
|                  |<img src="/images/회원탈퇴.gif"/>|

</br>

## 🏭 프로젝트 구조
![배포구조](/images/배포구조.PNG)

</br>

## 🕹 기술 스택
파트별 기술 스택은 아래 링크에서 확인할 수 있습니다.

- [백엔드 기술 스택](https://github.com/pgrm-study-website/Backend/blob/main/README.md)
- [프론트엔드 기술 스택](https://github.com/pgrm-study-website/Frontend/blob/main/README.md)

</br>

## 🗃 업데이트 내역
- 0.0.1

  > 초기 개발 기간: 2022년 3월 16일 ~ 2022년 4월 30일

  - 개발환경 구축
  - 게시글 관련 도메인 구
  - 사용자 관련 도메인 구현
  - API 문서화
  - 검색 기능 구현

</br>

## 📝 추가 정보
- [백엔드 깃허브 레포지토리](https://github.com/pgrm-study-website/Backend)
- [프론트엔드 깃허브 레포지토리](https://github.com/pgrm-study-website/Frontend)
