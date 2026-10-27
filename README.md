# lunch-catch

org 공통 설정 레포. 여기 둔 파일은 자기 파일이 없는 모든 레포가 상속한다.

- `.github/ISSUE_TEMPLATE/` — 이슈 템플릿 3종(기능 / 버그 / 작업)과 config
- `.github/PULL_REQUEST_TEMPLATE.md` — PR 템플릿

특정 레포만 다르게 쓰려면 그 레포에 같은 경로로 파일을 두면 그쪽이 우선한다.

## 상속이 아니라 체크아웃해서 쓰는 것

- `.github/llm-verify/gen_items.py` — 가이드 문서에서 점검 항목 레지스트리(`items.yml`)를 만드는 생성기

이것은 상속되지 않는다. 쓰는 레포의 워크플로가 이 저장소를 함께 체크아웃해서 돌린다. `lc-infra` 의 `registry-check.yml` 이 그렇게 쓴다. 생성기를 여기 두는 이유는 레포마다 복사해 두면 판정 규칙이 갈라지기 때문이다.
