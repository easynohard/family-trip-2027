# 사진 폴더 안내

Day별 · 도시별로 폴더가 미리 만들어져 있습니다. (일정표의 Day 번호와 1:1로 대응)

```
photos/
  day01-barcelona/   Day 1  인천 → 바르셀로나
  day02-barcelona/   Day 2  사그라다 파밀리아
  day03-salerno/     Day 3  바르셀로나 → 살레르노
  day04-salerno/     Day 4  신들의 길 → 로마
  day05-rome/        Day 5  트레비·콜로세움
  day06-rome/        Day 6  바티칸
  day07-rome/        Day 7  판테온·포로로마노
  day08-paris/       Day 8  → 파리·에펠탑
  day09-paris/       Day 9  개선문·오르세
  day10-paris/       Day 10 루브르
  day11-paris/       Day 11 베르사유
  day12-paris/       Day 12 귀국
```

## 사진 추가하는 법

1. 해당 Day 폴더에 사진 파일을 복사합니다. (예: `photos/day02-barcelona/01.jpg`)
2. `index.html`을 열어 `<script>` 안의 `PHOTOS` 객체를 찾습니다.
3. 해당 day 키의 배열에 방금 넣은 파일명을 문자열로 추가합니다.

```js
var PHOTOS = {
  "day02-barcelona": ["01.jpg", "02.jpg"], // 여기에 파일명 추가
  ...
};
```

파일명을 추가하고 저장하면 갤러리 화면에 바로 나타납니다. (목록에 없는 파일은 표시되지 않습니다)

## 사진 올리기 전 팁

- 스마트폰 원본 사진은 용량이 커서 GitHub 저장소/페이지 속도에 부담을 줄 수 있습니다. 업로드 전 긴 변 2000px 내외로 리사이즈하는 것을 권장합니다.
- 파일명은 영문/숫자로 (`01.jpg`, `02.jpg` 또는 `eiffel-night.jpg` 등) — 한글 파일명은 일부 환경에서 깨질 수 있습니다.
- jpg/png/webp 형식을 권장합니다.
