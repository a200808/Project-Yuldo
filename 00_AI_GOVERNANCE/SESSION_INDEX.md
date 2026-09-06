# 세션 역할표

Status: [CONFIRMED]

각 세션의 AI는 작업 시작 시 `00_AI_GOVERNANCE/PROMPTS/`의 해당 부트스트랩 프롬프트를 읽는다.

| 세션 | 담당 | 부트스트랩 프롬프트 |
|---|---|---|
| 00 | 총괄·프로젝트 운영·우선순위·캐논 관리 | `PROMPTS/00_GENERAL.md` |
| 01 | 세계관 | `PROMPTS/01_WORLD.md` |
| 02 | 스토리 | `PROMPTS/02_STORY.md` |
| 03 | 퀘스트 | `PROMPTS/03_QUEST.md` |
| 04 | 플레이어·전투·핵심 게임플레이 | `PROMPTS/04_GAMEPLAY.md` |
| 05 | 무기·장비·성장 | `PROMPTS/05_EQUIPMENT.md` |
| 06 | 의병·동료 | `PROMPTS/06_ALLIES.md` |
| 07 | 월드 설계 | `PROMPTS/07_WORLD_DESIGN.md` |
| 08 | NPC·세력 | `PROMPTS/08_NPC_FACTIONS.md` |
| 09 | 검수 | `PROMPTS/09_REVIEW.md` |
| 10 | 콘텐츠 | `PROMPTS/10_CONTENT.md` |
| 99 | 인수인계 | `PROMPTS/99_HANDOVER.md` |

세션 번호는 작업 편의를 위한 담당 영역 식별자다. 세션이 담당한다고 해서 해당 영역의 내용을 사용자 승인 없이 확정할 권한이 생기는 것은 아니다.

## AI 호출 방식
새 세션에서는 사용자 또는 운영자가 해당 프롬프트 파일의 이름만 전달하면 된다. AI는 프롬프트가 지정한 Governance 문서와 관련 활성 문서를 스스로 읽고 작업을 시작한다.
