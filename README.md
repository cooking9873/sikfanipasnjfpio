# 졸라맨 키우기 — Android APK

업로드된 HTML 게임을 Capacitor Android 앱으로 감싼 GitHub Actions 빌드 프로젝트입니다.

## GitHub에서 APK 만들기

1. 이 폴더 전체를 새 GitHub 저장소에 업로드합니다.
2. `Actions` 탭에서 `Build Android APK`를 실행합니다.
3. 빌드가 끝나면 해당 실행의 `Artifacts`에서 `jolaman-study-warrior-debug-apk`를 내려받습니다.
4. 압축을 풀면 `app-debug.apk`가 있습니다.

앱 ID: `com.jolaman.studywarrior`
앱 이름: `졸라맨 키우기`

## 포함된 게임
`www/index.html`은 업로드된 HTML 원본을 그대로 앱의 웹 콘텐츠로 사용합니다.

## 주의
이 GitHub Actions는 서명되지 않은 Debug APK를 만듭니다. 개인 기기 테스트용으로는 바로 사용할 수 있지만, Play 스토어 정식 배포에는 별도의 Release 서명/키스토어와 AAB 설정이 필요합니다.
