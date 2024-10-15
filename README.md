# streamlink-plugin-soop
Soop(구 아프리카TV) streamlink plugin

* 사용법
1. 터미널에서 streamlink 호출하는 위치에 plugins 폴더를 만들어 soop.py 파일을 추가
2. streamlink 실행 시 --plugin-dirs ./plugins 옵션 추가.

```
streamlink --plugin-dirs ./plugins --ffmpeg-copyts https://play.sooplive.co.kr/{streamer-id} best -o C:\download.ts
```