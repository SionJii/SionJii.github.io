# SionJi's Blog

개발 기록과 이런저런 생각들을 남기는 개인 블로그입니다.

🔗 https://sionjii.github.io

## 기술 스택

- [Astro](https://astro.build)
- GitHub Pages + GitHub Actions로 자동 배포 (`main` 브랜치에 push하면 자동 반영)

## 로컬 개발

```sh
npm install
npm run dev       # localhost:4321
```

| Command           | Action                        |
| :----------------- | :----------------------------- |
| `npm install`       | 의존성 설치                    |
| `npm run dev`       | 로컬 개발 서버 실행            |
| `npm run build`     | 프로덕션 빌드 (`./dist/`)      |
| `npm run preview`   | 빌드 결과 로컬 미리보기        |

## 구조

```text
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   ├── content/blog/   # 글 (Markdown/MDX)
│   ├── layouts/
│   └── pages/
├── astro.config.mjs
└── package.json
```

새 글은 `src/content/blog/`에 Markdown 파일을 추가하면 됩니다.
