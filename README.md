# oss-week03 — 모범답안

학생용 템플릿 `kw-hdi-lab/oss2026-week03` 과 파일 구성이 같고, 각 파일의 TODO 를 전부 채운 버전입니다. 각 파일 맨 위의 문제 설명(상황 / 할 일 / 실행 / 확인)은 템플릿 그대로 두었고, 채운 코드에는 왜 그렇게 썼는지를 주석으로 달아 두었습니다. 문제지 전체는 템플릿 README 를 보세요.

- `p1_order.js` — 예측·실제·이유까지 적은 상태
- `p2_convert.js` — `main()` 완성
- `p3_weather.js` — `fetchForecastRaw`, `parseForecast` 완성
- `main.js` — P3 출력 + P6 `--save` / `--offline` + P7 chalk
- `p4_compare.js` — P4 `allSettled` + P7 chalk
- `p5_kakao.js` — `searchPlace` + 출력. 실행에는 본인 키가 든 `.env` 가 필요합니다 (`.env.example` 참고)
- `http.js`, `wmo.js`, `a.txt` `b.txt` `c.txt`, `cache/` — 템플릿과 같음

실행 전 `npm install` (chalk). 네트워크가 없으면 `node main.js Busan --offline` 으로 P3/P6 출력을 볼 수 있습니다.
