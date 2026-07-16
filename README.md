# 김진욱 — 개발자 포트폴리오

개발부터 배포·운영까지 한 사람이 맡는 풀스택 개발자 포트폴리오 사이트입니다.

🌐 **Live:** https://happy-wook-kim.github.io/

## 소개

시안을 받아 살아 움직이는 서비스로 구현하고, 실서비스 배포·운영까지 이어서 책임집니다.
정부기관 공식 웹사이트 개발 사례를 중심으로 구성한 정적 포트폴리오 페이지입니다.

## 수록 프로젝트

- **K-건설안전 AI 콘텐츠 공모전** — 국토교통부·국토안전관리원 공식 웹사이트 (ai-kalis.com)
  - 역할: 개발 · 배포 · 운영 / 공모 안내부터 국민 참여, 수상 후보작 공개·검증까지 공모 기간 동안 실서비스로 운영
- **뽑기 (bbobgi)** — 개인 프로젝트, 캐주얼 랜덤 추첨 게임 (React·TypeScript, [라이브](https://happy-wook-kim.github.io/bbobgi/))
  - 카드·룰렛·사다리·경마·주사위 5종 미니게임을 직접 기획·제작·배포

프로젝트는 하나씩 계속 추가됩니다.

## 기술

- 순수 **HTML + 손수 작성한 CSS** (프레임워크·빌드 도구 없음)
- 폰트: Pretendard, IBM Plex Mono
- 반응형 + 인쇄(PDF) 대응
- GitHub Pages 배포

## 로컬 미리보기

정적 파일이라 아무 정적 서버로 열면 됩니다.

```bash
python3 -m http.server 8090
# → http://localhost:8090
```

## PDF로 저장

브라우저에서 `Cmd/Ctrl + P` → **배경 그래픽** 켜기 → PDF로 저장.
`@media print` 스타일이 적용되어 영상은 포스터 이미지로, 스크롤 영역은 펼쳐진 형태로 출력됩니다.

## 구조

```
index.html          # 홈 (프로젝트 카드 목록)
work/
  ai-kalis.html     # K-건설안전 AI 콘텐츠 공모전
  bbobgi.html       # 뽑기 — 랜덤 추첨 게임
styles.css          # 공통 스타일 (디자인 토큰 · 브라우저 프레임 · 반응형 · print)
assets/
  img/              # 스크린샷 · 카드 썸네일
  video/            # 데모 영상
```

## 연락처

catdog6210@gmail.com
