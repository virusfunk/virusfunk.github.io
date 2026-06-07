# virusfunk.github.io

[virusfunk](https://github.com/virusfunk)의 개인 포트폴리오 사이트입니다.
Jekyll로 만들어졌고 GitHub Pages로 배포됩니다 → **https://virusfunk.github.io**

## 내용 수정하기

코드를 몰라도 대부분 아래 파일만 고치면 됩니다.

| 무엇을 바꾸나 | 파일 |
| --- | --- |
| 이름·소개·연락처·소셜 링크 | `_config.yml` |
| 메인 문구 / About / 섹션 텍스트 | `index.html` |
| 기술 스택 | `_data/skills.yml` |
| 프로젝트 카드 | `_data/projects.yml` |
| 색상·폰트·디자인 | `assets/css/style.css` |

## 로컬에서 미리보기 (pixi)

[pixi](https://pixi.sh)가 Ruby 환경을 자동으로 관리합니다.

```bash
pixi run install   # 최초 1회 — gem 설치
pixi run serve     # http://localhost:4000 에서 미리보기 (저장하면 자동 새로고침)
```

기타 명령:

```bash
pixi run build     # _site/ 로 정적 빌드
pixi run clean     # 빌드 캐시 정리
```

## 배포

`main` 브랜치에 push 하면 GitHub Pages가 자동으로 빌드·배포합니다.
별도 설정은 필요 없습니다. (Settings → Pages → Source: `Deploy from a branch`, `main` / `root`)
