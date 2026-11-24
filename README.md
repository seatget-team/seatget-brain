# SeatGet Brain

SeatGet 팀의 프로젝트 컨텍스트, CS 학습 기록, AI 협업 지침을 관리합니다. 처음 합류했다면 [프로젝트 소개](context/project-overview.md)와 [문서 위치](context/source-index.md)부터 읽으세요.

[팀 온보딩 안내서](https://seatget-team.github.io/seatget-brain/)에서 Brain을 쓰는 이유, SeatGet 적용 구조, 적용 전후 실험을 한눈에 볼 수 있습니다. 브라우저에서 **A4 가로 인쇄**를 선택하거나 [HTML 원본](docs/index.html)을 내려받아 열 수 있습니다. [실험 원본 결과](docs/ab-results.json)와 [재현 스크립트](scripts/compare-context.mjs)도 함께 관리합니다.

| 경로 | 내용 |
| --- | --- |
| [context/](context/source-index.md) | 프로젝트 소개, 용어, 원본 문서 안내 |
| [knowledge/](knowledge/README.md) | 재사용할 수 있는 CS 지식과 학습 기록 |
| [harness/](harness/README.md) | 공통 AI 작업 지침, 검증 절차와 평가 기준 |
| [adapters/](adapters/README.md) | Codex, Claude Code, ChatGPT에 지침을 전달하는 방법 |
| [templates/](templates/README.md) | PAAR, ADR, 실험 기록 양식 |

공통 지침은 PR로 수정합니다. 서비스 저장소는 `.brain` 서브모듈에서 검증한 커밋을 선택하고, 동기화한 지침과 함께 PR에서 검토합니다.
