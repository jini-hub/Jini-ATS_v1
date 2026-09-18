# Jini ATS 3.0 — iOS 27 Edition

## 실행
- GitHub Pages: `docs/index.html`
- Android/Capacitor: `www/index.html`

## Gemini API Key 입력
프로젝트 루트의 `config.js` 파일을 열고 아래 값에 키를 넣습니다.

```js
window.JINI_ATS_CONFIG = {
  GEMINI_API_KEY: "여기에_GEMINI_API_KEY",
  GEMINI_MODEL: "gemini-2.5-flash"
};
```

공개 GitHub 저장소에 실제 API 키를 커밋하지 마세요.

## 주요 기능
- 대시보드
- 채용공고 CRUD
- 지원자 관리
- ATS 계산
- 리포트
- LocalStorage 자동 저장
- JSON 백업 다운로드
- Gemini API 연동 함수 포함
- 모바일 하단 내비게이션
- Capacitor APK용 `www/` 동기화
