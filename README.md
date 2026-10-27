# (주)코리아식품 생산 작업 기록 — GitHub Pages 배포

원료육 출고 → 세척 → 포장을 현장 태블릿·PC에서 입력하고, 작업일지 · 생산일지 · 해당일 기록 · 제품 1차 수량 확인용을 자동으로 만드는 웹앱입니다.

## 배포 방법 (무료, 약 5분)

1. GitHub에 로그인 → 오른쪽 위 **+** → **New repository**
2. Repository name 예: `kf-worklog` → **Public** 선택 → **Create repository**
3. 새 저장소 화면에서 **uploading an existing file** 클릭
4. 이 폴더의 파일을 **모두** 끌어다 놓기 (`index.html`, `manifest.webmanifest`, `icon-*.png`, `apple-touch-icon.png`, `favicon.png`, `.nojekyll`, `README.md`)
   - `.nojekyll`처럼 점으로 시작하는 파일이 안 보이면 없어도 동작합니다.
5. 아래 **Commit changes** 클릭
6. 저장소 **Settings → Pages** → Source: **Deploy from a branch** → Branch: **main** / **/(root)** → **Save**
7. 1~2분 뒤 같은 화면 위쪽에 주소가 나타납니다: `https://<GitHub아이디>.github.io/kf-worklog/`

## 로그인

- 아이디: `kor178` / 비밀번호: `0123!` (화면 키패드의 `!` 키, PC는 키보드로 입력)
- 태블릿(갤럭시탭 · 아이패드)에서 처음 로그인하면 지문(얼굴) 로그인을 쓸지 묻습니다. 켜 두면 다음부터 손가락만 대면 열립니다.

## 태블릿에 앱처럼 설치

- 아이패드(Safari): 공유 버튼 → **홈 화면에 추가**
- 갤럭시탭(Chrome · 삼성 인터넷): 메뉴 → **홈 화면에 추가 / 앱 설치**

## 꼭 알아 둘 점

- **기록은 각 기기(브라우저)에만 저장됩니다.** GitHub Pages는 파일만 보여 주는 무료 호스팅이라 서버 저장소가 없습니다. 태블릿에서 입력한 기록은 그 태블릿에서만 보입니다. 여러 기기가 같은 기록을 보려면 별도 데이터 서버(예: Firebase · Supabase 무료 요금제)를 붙여야 합니다.
- 브라우저의 "인터넷 사용 기록 · 사이트 데이터 삭제"를 하면 그 기기의 기록도 지워집니다. 중요한 기록은 **기록 → 엑셀로 받기**로 백업하세요.
- 공개(Public) 저장소의 GitHub Pages는 주소를 아는 사람 누구나 열 수 있습니다. 로그인 화면은 기기 잠금 수준이며, 검색엔진에는 노출되지 않도록 설정되어 있습니다.
- 시연 후 기록을 비우려면 **설정 → 기록 초기화 → 전체 기록 지우기** (두 번 확인).
