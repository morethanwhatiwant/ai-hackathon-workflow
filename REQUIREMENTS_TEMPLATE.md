# Requirements Traceability Template

## Type 값

Type은 다음 6종 중 하나만 사용한다.

1. `Hard Constraint` — 반드시 지켜야 하는 제한
2. `Soft Constraint` — 근거가 있으면 조정 가능한 선호
3. `Functional Requirement` — 시스템이 제공해야 하는 동작
4. `Non-functional Requirement` — 성능, 보안, 사용성, 신뢰성 조건
5. `Assumption` — 확인 전 임시로 참이라고 둔 조건
6. `Edge Case` — 경계·오류·희귀 상황의 기대 동작

## 요구사항 표

| Requirement ID | Description | Source | Type | Priority | Acceptance Criteria | Implementation Location | Test ID | Status |
|---|---|---|---|---|---|---|---|---|
| R-001 | 관찰 가능한 단일 요구사항 | 가이드/요청/데이터 | Hard Constraint | Must | 검증 가능한 완료 조건 | `path: symbol` 또는 미정 | T-001 | Proposed |

Status 권장값: `Proposed`, `Confirmed`, `Implemented`, `Verified`, `Blocked`, `Not Implemented`.

## 작성 규칙

- 한 행에 하나의 검증 가능한 요구사항만 기록한다.
- 모든 Hard Constraint는 구현 위치와 Test ID를 가져야 하며, 미구현이면 이유와 영향을 숨기지 않는다.
- Source에는 최신 시험 가이드의 위치나 사용자 요청을 적고, 충돌 시 최신 시험 가이드를 우선한다.
- Acceptance Criteria는 입력, 동작, 관찰 가능한 결과를 포함한다.
