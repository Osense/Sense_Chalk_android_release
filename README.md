쎈스초크 안드로이드 배포 파일 저장소입니다.

## 내려받기 (Android)

- [SenseChalk-Android-0.9.3.apk](https://github.com/Osense/Sense_chalk_android_release/raw/main/SenseChalk-Android-0.9.3.apk) (약 3.3MB)
- 모든 버전: [Releases](https://github.com/Osense/Sense_chalk_android_release/releases)
- 제품 소개 · 라이선스: https://wsns.studio/products/sense-chalk

## 새 버전 올리는 법

1. 이전 APK를 지우고 `SenseChalk-Android-<버전>.apk`를 저장소 맨 위에 올려요.
2. 바뀐 내용을 `notes/SenseChalk-Android-<버전>.md`에 적어요. 첫 줄 `# 제목`이 알림 제목, 나머지가 본문이에요.
3. 위 README의 내려받기 줄을 새 버전으로 바꿔요.

main에 올라가면 Action이 GitHub 릴리스 `android-v<버전>`을 만들고 APK를 붙인 뒤, Supabase에 새 버전을 기록해요.
앱(0.9.0 이상)은 켤 때 이 기록을 읽고 더 높은 버전이 있으면 알림을 띄워요.

Git LFS는 쓰지 않아요. 파일 하나가 50MB를 넘으면 Action이 멈추고 알려 줘요.
