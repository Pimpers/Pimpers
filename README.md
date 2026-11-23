# 박태원 | Game Developer

Unity / C# 기반 게임 시스템 구현

| | |
|---|---|
| **지망** | 게임 개발자 (Unity, C#) |
| **관심 분야** | 카드 빌드, 난이도, 보스 AI 같은 게임 시스템 구현 |
| **학교** | 유한대학교 |
| **대표 작업** | [고양이 용병단](https://github.com/Pimpers/team) — Unity 2D 로그라이크 |

---

## 대표 프로젝트

### 고양이 용병단 (Unity 2D 로그라이크)

| | |
|---|---|
| **개요** | 스테이지를 돌파하며 카드로 빌드를 만들고, 마을에서 영구 강화를 하는 픽셀 로그라이크 |
| **기간 / 형태** | 2026 · 팀 프로젝트 |
| **담당** | 코드 (게임플레이 · 시스템) |
| **기술** | Unity 6, C#, URP 2D, Input System, PowerShell |
| **규모** | C# 스크립트 164개 (약 2만 줄), 씬 17개, 커밋 180개 |
| **저장소** | [Pimpers/team](https://github.com/Pimpers/team) |

**주요 시스템**

| 시스템 | 내용 | 코드 |
|---|---|---|
| 카드 · 스킬 | 4종류 × 3등급 카드, 태그 세트 보너스. 카드 수치는 JSON으로 분리해 코드 수정 없이 밸런스 조정 | [CardPool](https://github.com/Pimpers/team/blob/master/Assets/CS/CardPool.cs) |
| 난이도 (타락도) | 5단계. 체력·속도·골드 수치와 함정 2배, 엘리트 분노, 보스 2페이즈 시작 같은 규칙을 단계별로 변경 | [Corruption](https://github.com/Pimpers/team/blob/master/Assets/CS/Corruption.cs) |
| 보스 AI | 3페이즈 상태머신, 그로기 시스템, 플레이테스트에서 발견한 발판 캠핑 대응 | [BossBrain](https://github.com/Pimpers/team/blob/master/Assets/CS/BossBrain.cs) |
| 영구 성장 · 저장 | 골드 업그레이드, 세이브 데이터 마이그레이션 | [MetaProgress](https://github.com/Pimpers/team/blob/master/Assets/CS/MetaProgress.cs) |
| 개발 도구 | Editor 스크립트와 PowerShell로 씬 생성, 에셋 후처리 자동화 | [Editor](https://github.com/Pimpers/team/tree/master/Assets/Editor), [Tools](https://github.com/Pimpers/team/tree/master/Tools) |

**개발 방식**: Claude Code와 Unity MCP를 활용한 AI 협업 개발입니다. 활용 범위는 [저장소 README](https://github.com/Pimpers/team#readme)에 적었습니다.

---

## 협업 경험

| 프로젝트 | 내용 |
|---|---|
| [Git 브랜치 협업 (2025oss)](https://github.com/Pimpers/2025oss) | 2026-06 · 4인 팀 팀장 · C++. `main`과 팀원별 `dev/*` 브랜치를 병합하며 충돌 2건 해결 |

같은 과제의 다른 저장소: [team10](https://github.com/Pimpers/team10), [Team-Project-](https://github.com/Pimpers/Team-Project-)

---

## 기술

| 구분 | 내용 |
|---|---|
| 주 사용 | C#, Unity |
| 그 외 언어 | C++, C, Java, Python, SQL |
| 도구 | Git / GitHub, Visual Studio, Android Studio |

---

## 학습 기록

| 저장소 | 내용 |
|---|---|
| [unitygame](https://github.com/Pimpers/unitygame) | Unity 미니 게임 6종 (플랫포머, 리듬, 보드, 슈팅, 경마, 타워 디펜스) |
| [c_sharp_theory](https://github.com/Pimpers/c_sharp_theory) | C# 문법 정리 (상속, 인터페이스, delegate 등) |
| [Login](https://github.com/Pimpers/Login) | Android 앱 로그인·회원가입 (Firebase), Smart App Challenge 2022 준비작 |
| [university_C](https://github.com/Pimpers/university_C), [homework](https://github.com/Pimpers/homework), [report](https://github.com/Pimpers/report) | C언어 강의 실습과 콘솔 게임 과제 |
| [youtube](https://github.com/Pimpers/youtube) | Python pygame 게임 실습 |
| [SQL](https://github.com/Pimpers/SQL), [http](https://github.com/Pimpers/http) | SQL, HTML 실습 |
