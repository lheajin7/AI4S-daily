# AI·ST 정책 — AI for Science 데일리

국가AI·ST정책연구센터가 과기정통부 인공지능혁신과에 보내는 **AI for Science 일간 동향**의
공개 열람면입니다.

**https://kist-aix.github.io/ai-st-policy/**

## 무엇이 실리나

- 확인된 사실과 수치, **발표일**, **원문 링크**만 싣습니다.
- 해석·판단 근거, 미확정 사항, 내부 작업 기록은 싣지 않습니다.
- 발표일을 확인하지 못했거나 원문을 붙이지 못한 항목은 올리지 않습니다.

탭은 둘입니다 — **뉴스레터**(그날 호)와 **아카이브**(전체 항목 검색).

## 갱신

발행일마다 `index.html` 한 파일을 교체합니다. 빌드 도구·프레임워크·서버가 필요 없는
정적 파일 하나이며, 데이터도 그 안에 들어 있습니다.

```
python scripts/bundle.py --root <사이트루트> --date YYYY-MM-DD \
  -o <이 저장소>/index.html
git add index.html && git commit -m "YYYY-MM-DD 호" && git push
```

`.nojekyll` 은 GitHub Pages 가 이 파일들을 Jekyll 로 다시 처리하지 않게 막습니다.

## 문의

국가AI·ST정책연구센터
