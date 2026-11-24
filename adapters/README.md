# AI 도구별 적용

공통 작업 지침의 원본은 [harness/instructions/common.md](../harness/instructions/common.md)입니다.

| 도구 | 전달 방법 |
| --- | --- |
| Codex | 서비스 루트의 `AGENTS.md` |
| Claude Code | 서비스 루트의 `CLAUDE.md` |
| ChatGPT | 필요한 원본 문서와 관련 부분을 선택해 대화에 첨부하거나 허용된 GitHub 연결로 참조 |

Node.js 22 이상을 사용합니다. 서비스 루트에서 아래 명령으로 두 지침 파일을 생성하고, PR에서는 두 파일의 내용이 고정된 Brain 버전과 일치하는지 확인합니다.

```sh
node .brain/scripts/sync.mjs
node .brain/scripts/sync.mjs --check
```

독립적으로 복제한 Brain에서 실행하려면 `--target <서비스-루트>`를 지정하세요. 동기화 명령은 팀에서 직접 작성한 기존 지침 파일이 있는 경우 해당 파일을 유지하고 종료합니다.
