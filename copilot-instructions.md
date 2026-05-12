# GitHub Copilot Instructions

## Language Rule
- 모든 자연어 응답은 반드시 한국어로 작성한다.
- All natural language output must be written in Korean.
- PR overview, reviewed changes, file summaries, inline review comments, suggested changeset explanations, and all code review comments must be written in Korean.
- 코드, 식별자, 클래스명, 메서드명, API 경로, 에러 메시지 원문은 영어 그대로 유지할 수 있다.
- Do not write review explanations in English.

## Code Review Rule
- When reviewing code or proposing code changes, **a `suggestion` block must always be included.**
- Do not provide only explanations — **always include actual code changes using a `suggestion` block.**
- A `suggestion` block must contain **code only**.
- Any explanation must be written **outside** the `suggestion` block.
