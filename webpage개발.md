firebase login
firebase init

계속해서 npm warn tar TAR_ENTRY_ERROR UNKNOWN: unknown error, write 오류가 발생하는 경우는,
대부분 다음 세 가지 원인 중 하나입니다. 반복적으로 나타난다면 환경을 바꾸는 게 정답입니다.

✅ 해결 전략 요약 (실제로 잘 통하는 순서)
🔴 1. 현재 경로가 Google Drive, OneDrive, 네트워크 드라이브라면? → 실패 100%
G 드라이브 (G:\내 드라이브\설화\...) = Google Drive
→ npm의 tar 모듈이 파일 해제 도중 충돌 발생

📦 해결법 → 반드시 로컬 디스크(C:)로 옮기세요!
