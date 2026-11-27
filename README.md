# 빵빵이네 합동 비서실

빵빵이네 베이커리 4구역(해썹 생산실 · 베이킹 클래스실 · 즉판업 택배·포장존 · 서무 업무실)에서 피클들이 함께 일하는 방을 한 장으로 정리한 정적 페이지입니다.

- `index.html` — 페이지 전체 (외부 라이브러리 없이 단일 파일)
- `.nojekyll` — GitHub Pages가 Jekyll 없이 그대로 올리도록 하는 표시 파일

## 보기

https://fc4gptm8j8-ux.github.io/pickle-office/

GitHub Pages가 꺼져 있다면 **Settings → Pages**에서 Source를 `Deploy from a branch`, 브랜치를 `main` / 폴더 `(root)`로 저장하면 위 주소에서 열립니다.
(2026-11-27 기준 Pages는 아직 꺼져 있어서, 그때까지는 rawcdn.githack.com 주소로 열립니다.)

## 실시간 DB

Firebase 프로젝트 `bbangine-pickle-office`의 **Realtime Database**(싱가포르, Spark 무료)에 연결되어 있습니다.
`databaseURL`: https://bbangine-pickle-office-default-rtdb.asia-southeast1.firebasedatabase.app
경로: `pickleOffice/{방}/presence`, `pickleOffice/{방}/notes`
