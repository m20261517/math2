# math2

`index.html`은 Teachable Machine 로컬 모델(`./model.json`, `./metadata.json`, `./weights.bin`)을 브라우저에서 직접 불러오는 단일 파일 웹 앱입니다.

실행 방법(권장):
- GitHub Pages로 열거나
- 로컬 HTTP 서버(예: `python -m http.server`)로 저장소 루트를 서빙한 뒤 접속하세요.

`file://`로 직접 열면 브라우저 보안 정책 때문에 모델/카메라가 동작하지 않을 수 있습니다.
