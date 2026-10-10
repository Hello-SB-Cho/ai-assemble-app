# 릴리스 점검표

이 저장소는 공개 배포 전용입니다. 비공개 앱 소스 저장소를 복사하거나 공개로 전환하지 않습니다.

1. 비공개 소스에서 `public-distribution` 기능으로 운영체제별 설치 파일을 빌드한다.
2. 각 파일이 실행되는지 확인하고, 실행 파일에 사내 주소·자격 증명이 포함되지 않았는지 검사한다.
3. macOS 서명·공증 상태와 Windows 서명 상태를 확인하고, 미적용 사항을 릴리스 노트에 명시한다.
4. 각 파일의 SHA-256을 계산해 릴리스 노트에 적는다.
5. 공개 GitHub Release에 다음 이름으로 자산을 첨부한다. 파일이 없는 운영체제는 게시하지 않는다.

| 운영체제 | 릴리스 자산 이름 |
| --- | --- |
| macOS Apple Silicon | `AI-Assemble-macOS-Apple-Silicon.dmg` |
| Windows x64 | `AI-Assemble-Windows-x64.exe` |
| Linux amd64 | `AI-Assemble-Linux-amd64.deb` |

소개 페이지는 GitHub의 최신 공개 릴리스에 실제로 첨부된 파일만 다운로드 버튼으로 표시한다.
