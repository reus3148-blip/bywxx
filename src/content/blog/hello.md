---
title: '블로그를 시작하며'
description: 'Astro로 만든 첫 번째 글입니다.'
pubDate: 'May 13 2026'
---

안녕하세요. 이 공간은 제가 배우고 만든 것들을 기록하기 위해 만든 블로그입니다.

## 어떻게 만들었나요

- 프레임워크: [Astro](https://astro.build)
- 글: 마크다운(`.md`) 파일로 작성하고 `src/content/blog/` 폴더에 두면 자동으로 페이지가 생성됩니다.
- 배포: GitHub Pages

## 새 글 쓰는 법

`src/content/blog/` 폴더에 마크다운 파일을 하나 추가하기만 하면 됩니다. 파일 맨 위의 frontmatter에 제목과 날짜를 적어주세요.

```markdown
---
title: '내 새 글'
description: '글 설명'
pubDate: 'May 14 2026'
---

여기에 본문을 씁니다.
```

저장하고 푸시하면 GitHub Actions가 자동으로 배포해줘요.
