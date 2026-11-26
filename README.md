# dayna-k.github.io

Personal homepage of Dayeon Kim: https://dayna-k.github.io/

## 파일 구성

| 파일 | 내용 |
|---|---|
| `index.html` | 사이트 내용 전부 (About, News, Publications, Education …) |
| `style.css` | 디자인 (색, 글꼴, 레이아웃) |
| `images/` | 프로필 사진(`profile.jpg`)과 논문 그림 |
| `cv/Dayeon_Kim_CV.pdf` | 사이트의 CV 링크가 여는 파일 |
| `.nojekyll` | GitHub Pages가 파일을 그대로 배포하게 하는 빈 파일 (지우지 마세요) |

수정은 GitHub 웹에서 파일을 열고 연필 아이콘(Edit)으로 고친 뒤 **Commit changes**를 누르면 됩니다.
커밋 후 보통 1~2분, 길면 10분 안에 사이트에 반영되고, 진행 상황은 **Actions** 탭에서 볼 수 있어요.

## 자주 하는 수정

**사진 바꾸기**: `images` 폴더 → **Add file → Upload files** → 본인 사진을 `profile.jpg` 이름으로 올려 덮어쓰기.
정사각형, 400px 이상을 권장합니다 (원형으로 잘려 보입니다).

**LinkedIn 추가**: `index.html`에서 `LinkedIn`을 검색 → 주석 처리된 줄에서 `YOUR-ID`를 본인 주소로 바꾸고,
그 줄 앞의 `<!--`와 끝의 `-->`를 지우기.

**CV 업데이트**: 새 PDF를 `cv` 폴더에 `Dayeon_Kim_CV.pdf` 이름으로 올려 덮어쓰기. 사이트 링크는 그대로 둬도 됩니다.

**뉴스 추가**: `index.html`의 `<ol class="news">` 바로 아래에 기존 `<li>` 한 줄을 복사해 맨 위에 붙이고 날짜·내용 수정.

**논문 추가**: `<article class="pub">` 블록 하나를 통째로 복사해 Publications 맨 위에 붙이고 제목·저자·링크·그림 경로 수정.
그림은 `images` 폴더에 올리세요 (가로:세로 16:10 권장).

내용을 바꾸면 맨 아래 `Last updated` 날짜도 같이 바꿔 주세요.
