# 🚀 Space Invaders - Web Game

This is the web-based **Space Invaders** game developed with [Amazon Q Developer CLI](https://aws.amazon.com/ko/blogs/korea/introducing-the-enhanced-command-line-interface-in-amazon-q-developer/?trk=769a1a2b-8c19-4976-9c45-b6b1226c7d20&sc_channel=el).

> 📖 관련 블로그 포스트: [Amazon Q Developer CLI를 이용한 웹 기반 게임 만들기](https://blog.naver.com/lifeandsong/223906313483)

---

## 🎮 게임 소개

클래식 아케이드 게임 Space Invaders를 웹 브라우저에서 즐길 수 있도록 구현한 게임입니다.  
Amazon Q Developer CLI의 도움을 받아 순수 HTML + JavaScript + Canvas API로 개발되었습니다.

---

## ▶️ 실행 방법

별도의 설치 없이 브라우저에서 바로 실행 가능합니다.

```bash
# 파일을 브라우저로 열기
open space_invaders.html
```

또는 `space_invaders.html` 파일을 더블클릭하여 실행하세요.

---

## 🕹️ 조작 방법

| 키 | 동작 |
|---|---|
| `←` / `→` 방향키 | 플레이어 이동 |
| `SPACEBAR` | 총알 발사 |
| `ENTER` | 게임 시작 / 재시작 |

---

## 🌟 주요 기능

### 4단계 스테이지 시스템
| 스테이지 | 적 유형 | 특징 |
|---|---|---|
| Stage 1 | 소형 외계인 (30마리) | 단발 총알, 느린 속도 |
| Stage 2 | 중형 외계인 (32마리) | HP 2, 중간 속도 |
| Stage 3 | 대형 외계인 (4마리) | HP 5, 7방향 산탄 발사 |
| Stage 4 | 보스 몬스터 (1마리) | HP 10, 파이어볼 8방향 난사 |

### 기타 특징
- UFO 랜덤 등장 (격추 시 100점 보너스)
- 스테이지별 방어막 (파괴 가능한 블록 구조)
- 피격 후 무적 시간 (2초)
- 목숨 3개 시스템
- Web Audio API 기반 효과음 (발사, 피격, 폭발, 스테이지 클리어, 게임 오버)
- localStorage 기반 Top 3 하이스코어 랭킹
- 게임 시작 전 스테이지 프리뷰 화면

---

## 🛠️ 기술 스택

- HTML5 Canvas API
- Vanilla JavaScript (ES6+)
- Web Audio API
- localStorage

---

## 🤖 개발 도구

이 게임은 [Amazon Q Developer CLI](https://aws.amazon.com/ko/blogs/korea/introducing-the-enhanced-command-line-interface-in-amazon-q-developer/?trk=769a1a2b-8c19-4976-9c45-b6b1226c7d20&sc_channel=el)를 활용하여 개발되었습니다.  
Amazon Q Developer CLI는 터미널에서 AI 어시스턴트와 대화하며 코드를 생성하고 개선할 수 있는 도구입니다.

자세한 개발 과정은 블로그 포스트를 참고하세요:  
👉 [Amazon Q Developer CLI를 이용한 웹 기반 게임 만들기](https://blog.naver.com/lifeandsong/223906313483)
