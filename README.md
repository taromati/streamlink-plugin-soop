# streamlink-plugin-soop
Soop(구 아프리카TV) streamlink plugin

* 사용법
1. 터미널에서 streamlink 호출하는 위치에 plugins 폴더를 만들어 soop.py 파일을 추가
2. streamlink 실행 시 --plugin-dirs ./plugins 옵션 추가.

```
streamlink --plugin-dirs ./plugins --ffmpeg-copyts https://play.sooplive.co.kr/{streamer-id} best -o C:\download.ts
```

* 주의

급한대로 기존 플러그인에서 주소만 변경한 버전으로 id/password 등 기존 옵션이 동작하는지는 검증 안함
