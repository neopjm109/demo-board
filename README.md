# Demo Board Project
해당 프로젝트는 진행했던 프로젝트들의 경험을 토대로 각 프레임워크별 기본이 되며,<br/>
필요하다고 느낀 부분들을 간략하게 정리하여 만든 게시판 프로젝트입니다.

## 사용 프레임워크

### Backend
- **backend-java** : Spring Boot 3+ (Java)
- **backend-kt** : Spring Boot 3+ (Kotlin)
- **backend-nestjs** : NestJS
- **backend-laravel** : PHP 8+
- **backend-php8** : PHP 8+
- **bakcend-php5** : php 5.5+

> Backend는 모두 동일한 포트 8910을 사용한다.


### Frontend
- **frontend-nextjs** : NextJS 14.2
- **frontend-react** : React 18 + Vite
- **frontend-nuxt** : Nuxt 3

> Frontend는 모두 동일한 포트 3910을 사용한다.


### Admin
- **admin-nextjs** : NextJS 14.2

> Admin은 모두 동일한 포트 5910을 사용한다.

### Design Framework
- Frontend : **Tailwind**
- Admin : **Antd**


## 구현 기능

1. 게시글 리스트
- 반응형
    - Desktop (1280px 초과) : 3행
    - laptop (990px초과 1280px 이하) : 3행
    - Tablet (480px 초과 990px 이하) : 2행
    - Mobile (480px 이하) : 1행
- 고정 상단
    - 검색, 로그인, 글 작성 버튼

2. 게시글 상세
- 제목
- 내용
- 이미지 최대 5장
- 작성자 프로필 이미지 및 이름

3. 사용자 정보
- 이름
- 프로필 이미지
- 작성 게시글 수
- 작성 게시글 리스트

4. 로그인
- JWT 토큰 이용하는 로그인 기능