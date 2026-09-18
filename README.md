# 사주풀이

성별, 생년월일, 태어난 시각(십이지시)을 입력하면 띠·오행 기반으로 오늘의 사주 운세를 보여주는 정적 웹앱입니다.

- `fortune-app/index.html` — 앱 본체 (순수 HTML/CSS/JS, 빌드 불필요)
- `assets/` — 띠·오행·운세 문구 등 참고 데이터

## 실행 방법

`fortune-app/index.html`을 정적 서버로 열면 됩니다.

```bash
cd fortune-app
python -m http.server 8000
```

모든 계산은 브라우저 안에서만 이루어지며, 입력 정보는 외부로 전송되지 않습니다.
