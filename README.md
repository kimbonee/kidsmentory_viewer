# 통합 미디어 뷰어 (Integrated Media Viewer)

다양한 미디어 콘텐츠를 한 곳에서 탐색할 수 있는 통합 웹 뷰어입니다.

## 🎯 주요 기능

### 📚 TunTun Books
- Book0101부터 Book0110까지의 영어 미디어 콘텐츠 탐색
- 실시간 검색 및 필터링
- 클릭 시 새 창에서 콘텐츠 열기

### 🎬 Vimeo Videos
- [Vimeo 채널](https://vimeo.com/user104908181)의 영상 목록 표시
- 썸네일 그리드 레이아웃으로 영상 탐색
- 영상 제목으로 실시간 검색
- 페이지네이션으로 모든 영상 탐색
- 일괄 작업 (모든 영상 열기)

### 🎯 키즈엠 (KidsM)
- ID 1-39까지의 키즈엠 컨텐츠 자동 로드
- 실시간 검색 및 필터링
- 클릭 시 새 창에서 컨텐츠 열기
- 일괄 작업 (모든 컨텐츠 열기)

## 🚀 사용법

1. **웹 브라우저에서 `tuntun_book_viewer.html` 파일을 열기**
2. **탭을 클릭하여 원하는 미디어 타입 선택**
3. **검색 기능을 사용하여 원하는 콘텐츠 찾기**
4. **썸네일이나 링크를 클릭하여 새 창에서 콘텐츠 열기**

## 🔧 기술 스택

- **HTML5**: 웹 페이지 구조
- **CSS3**: 반응형 디자인 및 스타일링
- **JavaScript (ES6+)**: 동적 콘텐츠 로딩 및 상호작용
- **Vimeo API**: 영상 데이터 가져오기
- **Fetch API**: 비동기 데이터 요청

## 📝 주요 특징

- **반응형 디자인**: 모바일, 태블릿, 데스크톱 모든 기기 지원
- **탭 기반 인터페이스**: 직관적인 네비게이션
- **실시간 검색**: 타이핑과 동시에 결과 필터링
- **자동 로딩**: 탭 전환 시 자동으로 콘텐츠 로드
- **오류 처리**: API 실패 시 샘플 데이터로 대체
- **레이트 리미트 대응**: API 호출 간격 조절

## ⚠️ 주의사항

- **Vimeo API 제한**: 무료 계정은 15분당 250개 요청 제한
- **CORS 정책**: 일부 외부 API는 브라우저에서 직접 호출 시 제한
- **네트워크 의존성**: 인터넷 연결이 필요합니다

## 🌐 라이브 데모

GitHub Pages를 통해 웹에서 바로 사용할 수 있습니다:
[https://your-username.github.io/kidsmentory_viewer/tuntun_book_viewer.html](https://your-username.github.io/kidsmentory_viewer/tuntun_book_viewer.html)

## 📄 라이선스

이 프로젝트는 MIT 라이선스 하에 배포됩니다.

## 🤝 기여하기

1. 이 리포지토리를 포크합니다
2. 새로운 기능 브랜치를 생성합니다 (`git checkout -b feature/amazing-feature`)
3. 변경사항을 커밋합니다 (`git commit -m 'Add some amazing feature'`)
4. 브랜치에 푸시합니다 (`git push origin feature/amazing-feature`)
5. Pull Request를 생성합니다

## 📞 문의

프로젝트에 대한 질문이나 제안사항이 있으시면 이슈를 생성해 주세요.