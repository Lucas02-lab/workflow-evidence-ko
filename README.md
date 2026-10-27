# workflow-evidence-ko

검색 범위와 작업 완료 근거를 명확하게 보고하는 한국어 스킬입니다. 실제 전송이나 저장을 자동으로 수행하는 도구는 포함하지 않습니다.

## 사용 예

> 받은편지함에서 지난주 홍길동에게 보낸 제안서가 있는지 확인하고, 확인한 범위와 결과를 알려줘.

## Codex 설치

```sh
mkdir -p "${CODEX_HOME:-$HOME/.codex}/skills"
git clone https://github.com/Lucas02-lab/workflow-evidence-ko.git "${CODEX_HOME:-$HOME/.codex}/skills/workflow-evidence-ko"
```

같은 이름의 폴더가 있으면 기존 파일을 덮어쓰지 않습니다. 새 Codex 세션에서 `$workflow-evidence-ko`를 지정해 사용합니다. 다른 에이전트의 설치 경로는 해당 제품의 안내를 확인하세요.

[스킬 지침](SKILL.md) · [원본과 변경 내역](ORIGIN.md) · [시험 기록](tests/manual-cases.md) · [원본 MIT 라이선스](LICENSE.md)
