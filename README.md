# 공공(고고 ㅇㅇ)모임 - 프로토 타입

지방 이전 공공기관 직원 대상의 서비스로서 데이팅 목적을 지양하고, 다른 사람들과 취미 생활을 공유함으로써 인맥교류와 자기계발을 목적하는 모임 서비스

## 기술 스택
- 백엔드 : Nodejs, Express, MariaDB 10.4, redis
- 프론트엔드 : dart, flutter, sqlite
> [프론트엔드 repository 바로가기](https://github.com/jerry92k/gogooo-frontend)

## 주요 기능
- 회원가입
  - 이메인 인증(nodemailer)
- 로그인(bcrypt)
- 사용자인증(jwt, redis)
- 프로필 생성
- 모임 개설, 참여, 관리
- 채팅(socket.io와 push)
  - 기능 개선 필요 : [관련 이슈 보기](https://github.com/jerry92k/gogooo-backend/issues/4)

![그림1](https://user-images.githubusercontent.com/62507373/148953475-26efdc34-19b6-4e87-b945-2d14dfcc4189.png)

![그림2](https://user-images.githubusercontent.com/62507373/148953548-9dc1599b-8c87-477d-8aff-66f0e56df196.png)