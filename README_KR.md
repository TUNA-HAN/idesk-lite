# iDesk Lite 무료 웹앱

돈을 내지 않고 친구 iPhone에서 바로 쓰게 하려면 네이티브 iOS 앱이 아니라 웹앱으로 가야 합니다.

## 핵심 한계

- App Store/TestFlight가 아닙니다.
- iPhone 화면과 HDMI 모니터가 분리되지 않습니다.
- 모니터에는 iPhone 화면이 미러링됩니다.
- 대신 웹 UI 자체를 가로/큰 화면용으로 만들어서 글자를 더 많이 보이게 합니다.

## 친구 사용법

1. Safari에서 배포 URL 열기
2. 공유 버튼 누르기
3. 홈 화면에 추가
4. 홈 화면의 iDesk Lite 실행
5. iPhone을 가로로 돌리기
6. HDMI 허브 연결
7. 앱에서 `모니터 모드` 누르기
8. 키보드로 Notes에 입력

## GitHub Pages에 무료 배포

1. GitHub 계정 생성
2. 새 저장소 만들기: `idesk-lite`
3. 이 폴더의 파일을 저장소 루트에 업로드
   - `index.html`
   - `manifest.json`
   - `icon-192.png`
   - `icon-512.png`
4. Settings → Pages
5. Deploy from a branch
6. Branch: `main`, folder: `/root`
7. 저장 후 몇 분 기다리기
8. 표시되는 URL을 친구에게 보내기

## 테스트할 것

- HDMI 연결 시 화면이 뜨는지
- iPhone을 가로로 돌리면 모니터에서 보기 좋은지
- 키보드 입력이 되는지
- 마우스 클릭/스크롤 로그가 찍히는지
- 모니터 모드에서 글자 수가 충분히 보이는지
