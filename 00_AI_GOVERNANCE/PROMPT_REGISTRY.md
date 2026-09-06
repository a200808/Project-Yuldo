# AI Prompt Registry

Status: [CONFIRMED]

이 문서는 프로젝트 율도에서 사용하는 AI별 공식 작업 프롬프트의 목록과 호출명을 관리한다.

## 사용 원칙

AI 세션은 아래 호출명을 전달받으면 해당 프롬프트 파일을 먼저 읽고 작업한다.

프롬프트 파일은 AI의 역할과 작업 절차를 정의한다. 게임 설정 자체의 Source of Truth가 아니다.

프롬프트에 없는 설정을 임의로 캐논으로 만들 수 없다. 캐논과 문서 우선순위는 `SOURCE_OF_TRUTH.md`와 `CANON_STATUS.md`를 따른다.

## 호출명 규칙

형식: `YULDO-AI-<영역>`

예:

- `YULDO-AI-GENERAL`
- `YULDO-AI-WORLD`
- `YULDO-AI-STORY`
- `YULDO-AI-QUEST`
- `YULDO-AI-GAMEPLAY`
- `YULDO-AI-EQUIPMENT`
- `YULDO-AI-ALLIES`
- `YULDO-AI-NPC`
- `YULDO-AI-CONTENT`
- `YULDO-AI-REVIEW`

## 등록 절차

1. 담당 영역을 확정한다.
2. 해당 영역의 프롬프트를 작성한다.
3. 공통 AI 규칙 및 Source of Truth 규칙을 반드시 준수하도록 한다.
4. 사용자 승인 후 공식 프롬프트로 등록한다.
5. 프롬프트 변경 시 변경 이유를 기록한다.

## 주의

프롬프트 하나에 세계관/스토리/시스템의 캐논을 중복해서 저장하지 않는다. 프롬프트는 필요한 공식 문서를 읽도록 지시하고, 실제 캐논은 담당 문서에서 관리한다.
