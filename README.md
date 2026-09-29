# 원불교 교구 소식 배포

[woncal.summerz.net](https://woncal.summerz.net/)의 정적 사이트를 배포하는 공개 저장소입니다.

`main`의 [정기 워크플로](.github/workflows/update.yml)가 매일 07:00 KST에 표준 macOS 러너에서 비공개 수집 코드를 실행합니다. 수집 코드와 OCR 캐시는 비공개 저장소에 보관하고, 이 저장소의 `gh-pages` 브랜치에는 사이트 빌드 결과만 저장합니다. 수동 실행 시 `backfill_limit`으로 이전 글 처리 건수를 1–20 사이에서 정할 수 있습니다.
