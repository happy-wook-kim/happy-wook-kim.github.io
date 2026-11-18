# 김진욱 — 개발자 포트폴리오

개발부터 배포·운영까지 혼자 하는 풀스택 개발자 포트폴리오 사이트입니다.

🌐 **Live:** https://happy-wook-kim.github.io/

## 소개

시안을 받아 살아 움직이는 서비스로 구현하고, 실서비스 배포·운영까지 이어서 책임집니다.
정부기관 공식 웹사이트 개발 사례를 중심으로 구성한 정적 포트폴리오 페이지입니다.

## 수록 프로젝트

### 외주 프로젝트

- **K-건설안전 AI 콘텐츠 공모전** — 국토교통부·국토안전관리원 공식 웹사이트 (ai-kalis.com)
  - 역할: 개발 · 배포 · 운영 / 공모 안내부터 국민 참여, 수상 후보작 공개검증까지 공모 기간 동안 실서비스로 운영
- **국민건강보험공단 명절카드** — 국민이 직접 문구를 써서 만들고 보내는 공식 명절 카드 (nhisletter.kr, 운영 종료)
  - 역할: 개발 · 인프라 · 배포 · 운영 / 15일 운영에 저장·공유 6,528건, 20만 요청을 서버 오류 0건으로 처리

### 개인 프로젝트

- **뽑기 (bbobgi)** — 캐주얼 랜덤 추첨 게임 (React·TypeScript, [라이브](https://happy-wook-kim.github.io/bbobgi/))
  - 카드·룰렛·사다리·경마·주사위 5종 미니게임
- **속보 청첩장** — 누르면 뉴스 속보처럼 터지는 모바일 청첩장 (HTML 파일 하나, [라이브](https://happy-wook-kim.github.io/wedding-congrats/))
- **JODEN** — 브라우저에서 1:1~2:2로 붙는 실시간 픽셀아트 대전 게임 (TypeScript·React·Canvas·socket.io)
  - 챔피언 13명, 증강 38종, 아이템 49종, 봇 대전

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
  nhisletter.html   # 국민건강보험공단 명절카드
  bbobgi.html       # 뽑기 — 랜덤 추첨 게임
  wedding.html      # 속보 청첩장
  joden.html        # JODEN — 실시간 대전 게임
styles.css          # 공통 스타일 (디자인 토큰 · 브라우저 프레임 · 반응형 · print)
assets/
  img/              # 스크린샷 · 카드 썸네일
  video/            # 데모 영상
```

## 연락처

catdog6210@gmail.com
