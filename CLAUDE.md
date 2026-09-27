# 신혼부부 주택 공고 확인 (Newlywed housing notice check)

LH·SH 신혼부부 대상 주택 공고를 확인하고 기록하는 프로젝트.

- `notices.json` — 현재 진행 중인 공고 데이터
- `seen_notices.md` — 이미 확인한 공고 기록 (중복 알림 방지)
- `index.html` — 공고 목록 페이지

## GitHub 자동 갱신 규칙

이 폴더의 파일을 수정하면 작업이 끝날 때마다 사용자에게 묻지 않고 바로 커밋하고 `origin main`으로 푸시한다.

```
git add -A
git commit -m "<변경 내용 요약>"
git push origin main
```

푸시가 실패하면(인증 문제, 원격 저장소 없음 등) 사용자에게 알린다.
