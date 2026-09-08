# jjm6564.github.io

전종민 (Jong Min Jeon) 개인 홈페이지 — GitHub Pages.

## 배포 방법

1. GitHub에서 **`jjm6564.github.io`** 이름으로 public 리포지토리를 새로 만든다 (README 체크 없이 빈 리포로).
2. 이 폴더에서:

```bash
git remote add origin https://github.com/jjm6564/jjm6564.github.io.git
git branch -M main
git push -u origin main
```

3. 리포 Settings → Pages → Source가 `Deploy from a branch` / `main` / `/ (root)`인지 확인.
4. 1~2분 뒤 <https://jjm6564.github.io> 에서 확인.

`<username>.github.io` 리포는 별도 설정 없이 바로 루트 도메인으로 서비스된다.

## 구성

| 파일 | 설명 |
|---|---|
| `index.html` | 페이지 전체 (HTML + CSS + 스크립트 한 파일) |
| `cv.png` | CV 이미지. 헤더의 `CV` 버튼이 이걸 연다 |
| `profile.jpg` | (선택) 넣어두면 헤더 이니셜 자리가 자동으로 사진으로 바뀐다 |

## 수정할 때

- 논문 추가: `index.html`의 `<ol class="pubs">` 안에 `<li class="pub">` 블록 하나를 복사해 채운다.
- 프로필 사진: 정사각형으로 자른 `profile.jpg`를 이 폴더에 두고 push하면 끝.
- CV를 PDF로 바꾸려면 `cv.pdf`를 넣고 헤더의 `href="cv.png"`를 `cv.pdf`로 고친다.
- 다크 모드는 방문자 OS 설정을 따라 자동으로 전환된다.
