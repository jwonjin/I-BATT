I-BATT v1.5 iPhone/iPad PWA — GitHub Pages 배포 안내

이 ZIP은 완성된 iOS 네이티브 IPA가 아닌 Safari 홈 화면 추가용 PWA 소스입니다.
기준: 기존 I-BATT v1.5 iphone_ipad/index.html 및 기존 아이콘. 학습/퀴즈 HTML 본문은 변경하지 않았습니다.

[교수자: GitHub Pages 배포]
1. 이 ZIP 압축을 풀고 index.html, manifest.webmanifest, service-worker.js, PNG 아이콘 3개를 확인합니다.
2. GitHub에서 새 저장소를 만듭니다. GitHub Pages 무료 배포를 위해 저장소 공개 여부 및 학교 저작권 정책을 확인합니다.
3. 압축을 푼 파일들을 저장소의 최상위(root)에 업로드합니다. ZIP 파일만 업로드하면 웹앱이 실행되지 않습니다.
4. Settings > Pages > Build and deployment > Deploy from a branch > main / (root) > Save를 선택합니다.
5. 배포 완료 후 Settings > Pages에서 표시되는 HTTPS 주소로 접속해 확인합니다.
   일반적인 URL 형태: https://계정명.github.io/저장소명/
6. 변경 버전 업로드 시 브라우저 캐시와 홈 화면 웹앱 업데이트를 실제 기기에서 확인합니다.

[학생: iPhone/iPad 설치]
1. iPhone/iPad Safari에서 안내받은 HTTPS 주소를 엽니다.
2. 공유 버튼 > 홈 화면에 추가 > 추가를 선택합니다. (iOS 버전에 따라 메뉴 위치가 다를 수 있음)
3. 홈 화면의 I-BATT 아이콘으로 실행합니다. 최초 온라인 실행 후 비행기 모드에서 오프라인 실행을 확인합니다.

[검증 체크리스트]
- iPhone/iPad 세로/가로 화면에서 메뉴와 퀴즈 조작
- 퀴즈 8유형, 유형 6의 두 출제 방식, 정답/오답/점수 표시
- 최초 접속 후 비행기 모드에서 재실행
- 학습기록 저장 후 종료/재실행, 업데이트 후 유지 여부

[주의]
- 실제 iPhone/iPad에서 실행 및 오프라인 동작은 아직 검증되지 않았습니다.
- 학습기록이 localStorage 등에 저장되는 경우 Safari/웹앱 데이터 삭제나 저장 공간 정리 시 손실될 수 있으며 기기 간 동기화되지 않습니다.
- GitHub Pages 공개 저장소에는 누구나 소스/콘텐츠를 볼 수 있으므로 학교의 저작권 및 공개 정책을 먼저 확인하세요.
- HTTPS 배포가 필요합니다. 파일을 로컬에서 더블클릭하는 것만으로는 서비스 워커 오프라인 캐시가 활성화되지 않습니다.
