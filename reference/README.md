# 참고자료(reference) 폴더 안내

`photos/`가 "여행 중에 직접 찍은 사진"을 Day 기준으로 모아두는 곳이라면, `reference/`는 **여행 전에 미리 조사·예약하며 모이는 자료**(숙소 사진, 예약 링크, 투어/명소 사전조사 자료)를 도시 기준으로 모아두는 곳입니다.

```
reference/
  barcelona/
    accommodation/   ← 숙소 사진 + links.md(예약 링크·가격·메모)
    tours/            ← 투어/액티비티/명소 사전조사 자료
  salerno/...
  rome/...
  paris/...
```

## 분류 기준

**1. 언제 만들어진 자료인가 — 이게 가장 중요한 기준**
- 예약을 결정하려고 여행 "전에" 모은 자료(숙소 매물 사진, 예약 사이트 캡처, 가격 비교, 투어 상품 정보) → `reference/`
- 여행 "중에" 실제로 그 장소에 있으면서 찍은 사진 → `photos/dayXX-city/` (자세한 규칙은 `../photos/README.md` 참고)
- 예: 예약 전 Agoda에서 저장한 호텔 로비 사진은 `reference/rome/accommodation/`. 체크인해서 내가 직접 찍은 로비 사진은 `photos/day04-salerno/`처럼 해당 Day 폴더.

**2. 숙소(accommodation) vs 투어(tours)**
- `accommodation/`: 그 도시에서 묵을 숙소에 관한 모든 것 — 후보 숙소 사진, 확정 숙소 사진, 예약 확인서 캡처
- `tours/`: 특정 Day에 얽매이지 않는, "예약이 필요한 액티비티"에 대한 사전조사 — 가이드 투어, 입장권 예매 확인, 하이킹 코스 지도 캡처 등. (일반 관광지 방문 자체는 여기 대상이 아니고, 그 관광에 대해 사전에 표를 사거나 투어를 예약한 경우에만 해당)

**3. 링크(URL)는 이미지가 아니므로 `links.md`에 텍스트로**
- 각 `accommodation/`, `tours/` 폴더 안의 `links.md`에 예약 URL, 가격, 체크인/아웃 날짜, 후보 여부 등을 마크다운으로 정리
- 사진 파일은 같은 폴더에 이미지 파일로 직접 넣기 (예: `reference/paris/accommodation/option1-magda-01.jpg`)

**4. 숙소 후보가 여러 곳일 때**
- 파일명 앞에 `option1-`, `option2-` 접두어를 붙여 구분
- `links.md`에도 후보별로 `##` 소제목을 나눠 기록하고, 확정되면 제목 옆에 "(확정)"만 추가 — 나머지 후보는 지우지 말고 "(미선택)"으로 남겨두면 나중에 왜 그 숙소를 골랐는지 추적 가능

## 파일명 규칙

`photos/README.md`와 동일 — 영문/숫자 파일명 권장(`01.jpg`, `option1-lobby.jpg` 등), 업로드 전 리사이즈 권장.
