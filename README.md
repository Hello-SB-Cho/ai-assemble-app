# AI Assemble 다운로드

AI Assemble의 공개 배포 저장소입니다. 앱 소스 코드는 이 저장소에 포함하지 않습니다. 이 저장소에는 [소개 페이지](https://hello-sb-cho.github.io/ai-assemble-downloads/), 설치 안내, 릴리스 설치 파일만 게시합니다.

## 설치

1. [최신 릴리스](https://github.com/Hello-SB-Cho/ai-assemble-downloads/releases/latest)에서 운영체제에 맞는 파일을 받습니다.
2. 사용할 AI의 공식 CLI(Codex, Claude Code, agy)를 각각 설치하고 로그인합니다.
3. AI Assemble를 열어 작업 폴더를 고르고 **Provider 설정**에서 연결 상태를 확인합니다.

운영체제별 설치 파일이 아직 없는 경우 릴리스 페이지에 표시되지 않습니다. 각 AI 서비스의 계정 및 이용 조건은 해당 서비스에서 관리합니다.

## 데이터와 답변

- 대화 기록은 사용자의 기기에 있는 SQLite에 저장됩니다.
- 답변 생성을 위해 질문과 필요한 이전 맥락이 선택한 AI Provider로 전달됩니다.
- AI 응답은 부정확할 수 있으므로 중요한 내용은 원문과 출처로 확인해 주세요.

## 공개 범위

이 저장소의 `dist/`는 소개 페이지입니다. GitHub Release의 설치 파일은 비공개 소스 저장소에서 빌드한 결과물입니다. 소스 코드, 로컬 대화 기록, 계정 인증 정보는 게시하지 않습니다.

문제 신고는 [Issues](https://github.com/Hello-SB-Cho/ai-assemble-downloads/issues)에 남겨 주세요. 계정 토큰이나 개인 대화 내용은 첨부하지 마세요.
