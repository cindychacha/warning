# 깜짝 소식 GitHub Pages 업로드 안내

1. github.com 에서 새 Public 저장소를 만듭니다. 예: baby-news
2. 이 폴더 안의 `index.html`, `og-image.png` 파일 두 개를 **저장소 최상위(root)**에 업로드합니다 (Add file → Upload files → Commit changes).
3. 저장소의 Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: main, /(root) → Save.
4. 공개 주소는 `https://사용자명.github.io/저장소이름/` 입니다. 저장소가 `사용자명.github.io`이면 `https://사용자명.github.io/`입니다.
5. 저장소의 index.html → 편집(연필) 클릭. 아래 두 줄의 `YOUR_USERNAME` / `YOUR_REPOSITORY`를 실제 값으로 변경 후 Commit changes:

   `<meta property="og:image" content="https://YOUR_USERNAME.github.io/YOUR_REPOSITORY/og-image.png">`

   `<meta name="twitter:image" content="https://YOUR_USERNAME.github.io/YOUR_REPOSITORY/og-image.png">`

   예: 사용자명이 `myid`이고 저장소가 `baby-news`라면 `https://myid.github.io/baby-news/og-image.png`.
   저장소가 `myid.github.io`라면 `<... content="https://myid.github.io/og-image.png">` 형식으로 바꿉니다.
6. 업로드 후 `https://사용자명.github.io/저장소이름/og-image.png` 에 접속해 이미지가 열리는지 확인합니다.
7. 카카오톡 링크 미리보기가 이전처럼 보이면 카카오 공유 디버거 https://developers.kakao.com/tool/debugger/sharing 에서 주소를 입력해 캐시를 갱신해 보세요.

주의: GitHub Pages에 공개한 파일은 누구나 볼 수 있습니다. HTML에 포함된 이름·개인정보를 공개해도 괜찮은지 확인하세요.
