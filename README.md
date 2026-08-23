# AIMHYUK.github.io

조준혁 포트폴리오 사이트의 소스입니다. 내용은 아래 주소에서 보시는 편이 낫습니다.

**https://aimhyuk.github.io**

## 구조

```
index.html        프로젝트 카드 목록. 여기가 사이트의 첫 화면이다
projects/*.html   프로젝트별 상세 페이지. 카드의 "상세 보기"가 여기로 온다
assets/
  portfolio.css   전 페이지 공용 스타일. 페이지마다 CSS를 두지 않는다
  images/         스크린샷 · 썸네일
  video/          시연 영상
```

빌드 도구를 쓰지 않습니다. 정적 HTML과 CSS 한 장뿐이라 파일을 열면 그대로 보입니다.

## 페이지 구성

상세 페이지는 프로젝트마다 같은 뼈대를 씁니다.

| 절 | 내용 |
|---|---|
| 기능 | 구현 · 화면 · 성과. 기능 하나가 한 절 |
| 트러블슈팅 | 막혔던 지점을 문제 · 원인 · 해결 순으로 |
| 마무리 | 그 프로젝트의 판단을 한 문장으로 |

기능과 트러블슈팅은 서로 링크로 이어집니다. 기능 아래의 "이 기능에서 막힌 것"이 해당
트러블슈팅 항목으로 내려가고, 반대로 트러블슈팅 제목이 그 기능으로 올라갑니다.

## 프로젝트 저장소

사이트에 실린 프로젝트 중 코드가 공개된 것들입니다.

- [SpriteBatchDemo](https://github.com/AIMHYUK/SpriteBatchDemo) — Direct3D 11로 만든 2D 스프라이트 렌더러. 배칭 · 인스턴싱 · 컬링 실측
- [MiniD3D11Renderer](https://github.com/AIMHYUK/MiniD3D11Renderer) — 위 프로젝트의 바닥. 창부터 셰이더까지 직접
- [MiniOscReceiver](https://github.com/AIMHYUK/MiniOscReceiver) — UDP 소켓과 OSC 파서를 직접 만들어 RPC와 비교 측정
- [GASPractice](https://github.com/AIMHYUK/GASPractice) — Gameplay Ability System과 CommonUI 레이어 프레임워크
- [MdCalling-Showcase](https://github.com/AIMHYUK/MdCalling-Showcase) — 팀 프로젝트에서 맡은 부분의 설계와 판단 근거

---

조준혁 · 게임 클라이언트 프로그래머
