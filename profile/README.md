<img src="https://github.com/user-attachments/assets/7432aae4-41d0-4560-b46e-59ea1d0adace" style="width:100%; max-width:1000px;" />

# RePlant

**RePlant**는 마약중독자의 회복 여정을 지원하는 Apple Watch 연동 헬스케어 애플리케이션입니다.
일일 미션, 단계별 회복 트래킹, 커뮤니티 상담 기능을 통해 사용자 스스로 건강한 생활을 관리하고 기록할 수 있습니다.

## 📱 주요 기능

- **일일 미션**: 매일 수행할 수 있는 간단한 회복 습관 미션 제공
- **단계별 회복 트래킹**: 도트 생명체를 키우며 단계별로 성취를 시각화
- **Apple Watch 연동**: 심박수, 활동량 등을 기반으로 회복 상태 감지 및 알림
- **커뮤니티 및 상담소통**: 일일 소통, 월간 회고, 상담사 전용 채널
- **기록 일지**: 감정, 활동, 회복 상황을 일지 형태로 저장

## 🧩 기술 스택

### 📱 모바일 클라이언트
[![React Native](https://img.shields.io/badge/React%20Native-%5E0.73.0-61dafb?logo=react)](https://reactnative.dev/)
[![Swift](https://img.shields.io/badge/Swift-iOS%20%2B%20WatchOS-orange?logo=swift)](https://developer.apple.com/swift/)

- React Native – 크로스 플랫폼 앱 개발
- Swift – iOS 전용 기능 (HealthKit, WatchConnectivity), Apple Watch 앱 개발


### ⌚️ Apple Watch 앱
[![WatchKit](https://img.shields.io/badge/WatchKit-SwiftUI-lightgrey?logo=apple)](https://developer.apple.com/documentation/watchkit)

- WatchKit + SwiftUI – 미션 알림, 트래킹 인터페이스


### 🌐 백엔드
[![Node.js](https://img.shields.io/badge/Node.js-Express-339933?logo=node.js)](https://expressjs.com/)
[![MongoDB](https://img.shields.io/badge/MongoDB-%5E7.0-brightgreen?logo=mongodb)](https://www.mongodb.com/)
[![Socket.IO](https://img.shields.io/badge/Socket.io-RealTime-black?logo=socket.io)](https://socket.io/)

- Node.js + Express – API 서버
- MongoDB – 사용자 데이터 저장
- Socket.IO – 커뮤니티 실시간 통신 (선택)


### ☁️ 인프라 및 배포
[![Firebase](https://img.shields.io/badge/Firebase-Cloud%20Messaging-FFCA28?logo=firebase)](https://firebase.google.com/)
[![AWS](https://img.shields.io/badge/AWS-Lambda%20%7C%20S3-orange?logo=amazon-aws)](https://aws.amazon.com/)
[![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-CI%2FCD-blue?logo=githubactions)](https://github.com/features/actions)
[![Fastlane](https://img.shields.io/badge/Fastlane-iOS%20Build-red?logo=fastlane)](https://fastlane.tools/)

- Firebase Auth / FCM – 인증 및 푸시
- AWS Lambda & S3 – 서버리스 처리, 이미지 저장
- GitHub Actions + Fastlane – 자동 배포


### 🔐 인증 및 보안
[![OAuth2](https://img.shields.io/badge/OAuth2-JWT%20Auth-blue)](https://oauth.net/2/)
[![Security](https://img.shields.io/badge/Security-AES--256%20%7C%20TLS-green)](#)

- OAuth 2.0 / JWT – 인증
- HTTPS + AES-256 – 전송 및 저장 데이터 암호화

---


## 🛠️ 향후 계획

- [ ] 응급상황 발생 시 보호자 자동 알림
- [ ] 상담사 전용 관리자 웹페이지
- [ ] 회복 통계 시각화
