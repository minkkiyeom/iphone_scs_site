SCS-C03 문제은행 - 아이폰 Safari 사용 안내

이 HTML은 JavaScript로 문제 목록과 버튼 동작을 구현한 단일 페이지입니다.
iPhone 파일 앱에서 HTML을 탭하면 Safari가 아니라 파일 미리보기(Quick Look)로 열릴 수 있으며,
이 미리보기 환경에서는 JavaScript가 정상 실행되지 않아 버튼이 작동하지 않을 수 있습니다.

권장 방법: 이 폴더의 index.html을 HTTPS 정적 웹 호스팅에 올린 뒤, 발급된 https:// 주소를 Safari에서 여세요.
GitHub Pages 예시:
1. GitHub에서 새 저장소(repository)를 만듭니다.
2. index.html을 저장소 최상위에 업로드합니다.
3. Settings > Pages에서 배포 소스를 설정합니다.
4. 생성된 https://...github.io/... 주소를 iPhone Safari와 PC에서 엽니다.

원본 문제 데이터와 HTML 내용은 유지했습니다. 파일 앱 미리보기 자체의 JavaScript 제한은 HTML 코드 수정만으로 해제할 수 없습니다.
