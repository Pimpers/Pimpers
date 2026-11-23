# 박태원

Unity / C# 게임 개발자 지망생 · 유한대학교

로그라이크 게임의 시스템(카드 빌드, 난이도, 보스 AI)을 설계하고 구현하는 일을 하고 싶습니다.
아래 첫 번째 프로젝트가 그 방향으로 만든 결과물입니다.

## 대표 프로젝트

### 고양이 용병단 — Unity 2D 로그라이크

[저장소](https://github.com/Pimpers/team) · 2026 · 팀 프로젝트(코드 담당) · Unity 6, C#

스테이지를 돌파하며 카드로 빌드를 만들고, 마을에서 영구 강화를 하는 픽셀 로그라이크입니다.
C# 스크립트 164개(약 2만 줄), 씬 17개, 커밋 180개.

코드 담당으로 다룬 주요 시스템

- **카드·스킬**: 4종류 × 3등급 카드, 태그 세트 보너스. 카드 수치는 JSON으로 분리
- **난이도(타락도) 5단계**: 수치뿐 아니라 함정·엘리트·보스 페이즈 같은 규칙도 단계별로 변경
- **보스 AI**: 3페이즈 상태머신, 그로기 시스템, 플레이테스트에서 발견한 "발판 캠핑" 대응
- **영구 성장·저장**: 골드 업그레이드와 세이브 데이터 마이그레이션
- **개발 도구**: Editor 스크립트와 PowerShell로 씬 생성·에셋 후처리 자동화

AI 도구(Claude Code, Unity MCP)를 활용해 개발했고, 활용 방식은 저장소 README에 적었습니다.

### Git 브랜치 협업 — 병합과 충돌 해결

[저장소](https://github.com/Pimpers/2025oss) · 2026-06 · 4인 팀, 팀장 · C++

`main`과 팀원별 `dev/*` 브랜치를 병합하면서 충돌 2건을 직접 해결했습니다.
같은 과제의 다른 저장소: [team10](https://github.com/Pimpers/team10), [Team-Project-](https://github.com/Pimpers/Team-Project-)

## 기술

| 구분 | 내용 |
|---|---|
| 주 사용 | C#, Unity |
| 그 외 언어 | C++, C, Java, Python, SQL |
| 도구 | Git / GitHub, Visual Studio, Android Studio |

## 학습 기록

| 저장소 | 내용 |
|---|---|
| [unitygame](https://github.com/Pimpers/unitygame) | Unity 미니 게임 6종 (플랫포머, 리듬, 보드, 슈팅, 경마, 타워 디펜스) |
| [c_sharp_theory](https://github.com/Pimpers/c_sharp_theory) | C# 문법 정리 (상속, 인터페이스, delegate 등) |
| [Login](https://github.com/Pimpers/Login) | Android 앱 로그인·회원가입 (Firebase), Smart App Challenge 2022 준비작 |
| [university_C](https://github.com/Pimpers/university_C), [homework](https://github.com/Pimpers/homework), [report](https://github.com/Pimpers/report) | C언어 강의 실습과 콘솔 게임 과제 |
| [youtube](https://github.com/Pimpers/youtube) | Python pygame 게임 실습 |
| [SQL](https://github.com/Pimpers/SQL), [http](https://github.com/Pimpers/http) | SQL, HTML 실습 |
