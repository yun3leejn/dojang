# 나를 찾고 내일을 잇다 — 반별 도장판

신도림중학교 3학년 고교 전환기 진로프로젝트 · 12개 반 실시간 도장판

- 사이트: https://yun3leejn.github.io/dojang/
- 저장소: Firebase Firestore (실시간), 선생님 로그인: Google + 8자리 2차 인증
- `main` 브랜치에 올리면 GitHub Pages로 자동 배포돼요.

## 주의
- Firestore 보안 규칙(`firestore.rules`)은 2차 인증 암호를 담고 있어 이 공개 저장소에 올리지 않아요.
  규칙은 Firebase 콘솔 → Firestore → 규칙에서 관리해요.
- `index.html`의 Firebase 설정값은 공개돼도 되는 값이에요. 실제 권한은 보안 규칙이 지켜요.
