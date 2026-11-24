# 🍱 런치캐치

> 점심시간에 주변 가게의 선착순 할인 쿠폰을 광고로 띄우고
> 점주는 노출된 만큼 포인트를 내는 위치 기반 광고 플랫폼

<p align="center">
  <img src="https://raw.githubusercontent.com/lunch-catch/lc-frontend/main/docs/images/user-swipe.webp" alt="사용자 앱 오늘 점심 피드" width="148" />
  <img src="https://raw.githubusercontent.com/lunch-catch/lc-frontend/main/docs/images/owner-home.webp" alt="점주 앱 홈의 진행 중인 캠페인" width="148" />
  <img src="https://raw.githubusercontent.com/lunch-catch/lc-frontend/main/docs/images/admin-template-chat.webp" alt="관리자 앱 쿠폰 전단지 템플릿 편집기" width="512" />
  <br />
  <sub>왼쪽부터 사용자 앱 · 점주 앱 · 관리자 앱 UI 이미지</sub>
</p>

<br>

| | 주소 |
|---|---|
| 사용자 | [lunchcatch.com](https://lunchcatch.com) |
| 점주 | [owner.lunchcatch.com](https://owner.lunchcatch.com) |
| 관리자 | [admin.lunchcatch.com](https://admin.lunchcatch.com) |
| API 문서 | [Swagger UI](https://api.dev.lunchcatch.com/swagger-ui.html) |

<br>

## 서비스 소개

| 구분 | 하는 일 |
|---|---|
| 회원 | 지금 위치 주변의 쿠폰 광고를 피드로 받고, 가게를 찜하고, 선착순 쿠폰을 받아 가게에서 QR 로 쓴다 |
| 점주 | 가게를 등록하고 쿠폰 캠페인을 만들고, 포인트를 충전해 광고를 집행하고, 노출과 발급 실적을 본다 |
| 관리자 | 점주의 입점과 사업자 정보를 검수하고, 쿠폰 전단지 템플릿을 만들고, 포인트 정책과 환불을 다룬다 |

<br>

## 저장소

| | 무엇 | 스택 |
|---|---|---|
| [**lc-backend**](https://github.com/lunch-catch/lc-backend) | 광고 서빙, 쿠폰 발급, 포인트 정산 | Java 21 · Spring Boot 4 · MySQL · Valkey |
| [**lc-frontend**](https://github.com/lunch-catch/lc-frontend) | 사용자 · 점주 · 관리자 앱 셋 | TypeScript |
| [**lc-infra**](https://github.com/lunch-catch/lc-infra) | AWS 구성과 배포 | Terraform |

도메인 9개 · 테이블 74개 · HTTP API 127개 · 테스트 3,957개

<br>

## 팀

### Frontend

| 이규태 | 고유정 | 서지현 |
| :---: | :---: | :---: |
| <img src="https://github.com/Ourumo.png" width="110" /> | <img src="https://github.com/daenggg.png" width="110" /> | <img src="https://github.com/jhwest-dev.png" width="110" /> |
| [@Ourumo](https://github.com/Ourumo) | [@daenggg](https://github.com/daenggg) | [@jhwest-dev](https://github.com/jhwest-dev) |
| FE 파트장 · 점주 앱 | 관리자 앱 | 사용자 앱 |

### Backend

| 박준서 | 김현우 | 정규동 | 최민혁 | 최재웅 |
| :---: | :---: | :---: | :---: | :---: |
| <img src="https://github.com/devjohnpark.png" width="110" /> | <img src="https://github.com/muzimzz.png" width="110" /> | <img src="https://github.com/gyudongjeong.png" width="110" /> | <img src="https://github.com/MinhyeokChoi99.png" width="110" /> | <img src="https://github.com/yongmaru789.png" width="110" /> |
| [@devjohnpark](https://github.com/devjohnpark) | [@muzimzz](https://github.com/muzimzz) | [@gyudongjeong](https://github.com/gyudongjeong) | [@MinhyeokChoi99](https://github.com/MinhyeokChoi99) | [@yongmaru789](https://github.com/yongmaru789) |
| 팀장 · 광고 서빙 · 인프라 | 회원 · 정산 · 분석 | 계정 · 입점 · 알림 | 쿠폰 · 가게 탐색 | 캠페인 · 템플릿 · 운영 |
