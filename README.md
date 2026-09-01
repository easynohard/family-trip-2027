# 2027년 1월 가족여행

- `index.html` — 일정표 + 사진 갤러리 (이 파일이 페이지 첫 화면)
- `여행계획.md` / `여행계획.txt` — 일정 원본 (일정이 바뀌면 여기부터 수정)
- `photos/` — 여행 중 직접 찍은 사진, Day별 폴더 (자세한 사용법은 `photos/README.md` 참고)
- `reference/` — 숙소 사진·예약 링크, 투어 사전조사 자료, 도시별 폴더 (분류 기준은 `reference/README.md` 참고)

## GitHub Pages로 공개하는 법 (나중에 할 일)

1. GitHub에 새 저장소 생성 (예: `family-trip-2027`)
2. 이 폴더 전체를 그 저장소에 push
   ```
   git init
   git add .
   git commit -m "가족여행 일정 페이지"
   git branch -M main
   git remote add origin <저장소 URL>
   git push -u origin main
   ```
3. 저장소 Settings → Pages → Source에서 `main` 브랜치 / `/ (root)` 선택 후 저장
4. 잠시 후 `https://<계정>.github.io/<저장소명>/` 주소로 접속 가능

사진을 추가·수정한 뒤에도 같은 방식으로 커밋 후 push하면 페이지에 반영됩니다.
