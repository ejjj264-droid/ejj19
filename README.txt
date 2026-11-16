新西游记 중국 여행 3D 방탈출

구성: index.html, style.css, questions.js, game.js
8개 장소, 24문제 / 개인별 탐험 / 힌트와 해설 / 브라우저 진행상황 저장

실행 방법:
1. 네 파일을 같은 폴더에 둡니다.
2. GitHub에 공개 저장소를 만들고 네 파일을 업로드합니다.
3. Settings → Pages → Deploy from a branch → main / (root) → Save.
4. 생성된 https://계정.github.io/저장소/ 링크를 학생에게 공유합니다.

로컬 테스트: VS Code Live Server 또는 python -m http.server 8000 실행 후 http://localhost:8000 접속.
주의: 3D 라이브러리 Three.js를 CDN에서 불러오므로 인터넷 연결이 필요합니다.
학생별 기록은 각자의 브라우저(localStorage)에 저장됩니다. 서버 기반 학급 관리나 실시간 동기화 기능은 없습니다.
문제 수정: questions.js 파일의 q/options/a/h/why를 수정하세요. a는 정답 번호(첫 번째=0)입니다.
