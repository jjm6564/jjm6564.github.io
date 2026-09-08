# jjm6564.github.io

전종민 (Jong Min Jeon) 개인 홈페이지 — GitHub Pages.

배포됨: <https://jjm6564.github.io>

## 구성

| 파일 | 설명 |
|---|---|
| `index.html` | 페이지 전체 (HTML + CSS 한 파일) |
| `jmJeon.jpg` | 헤더 프로필 사진 |
| `boksuli.png` | 푸터 마스코트 |

## 수정 후 배포

```bash
git add -A && git commit -m "메시지" && git push
```

push 후 1~2분이면 반영된다.

## 수정할 때

- 논문 추가: `index.html`의 `<ol class="pubs">` 안에 `<li class="pub">` 블록 하나를 복사해 채운다.
- 프로필 사진 crop 위치: `.avatar`의 `object-position:center 25%` 값을 조절한다 (숫자가 작을수록 위쪽).
- 다크 모드는 방문자 OS 설정을 따라 자동으로 전환된다.
