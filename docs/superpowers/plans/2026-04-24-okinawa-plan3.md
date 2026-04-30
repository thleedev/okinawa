# 오키나와 Plan3 여행 계획서 작성 계획

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** 설계 문서(2026-04-24-okinawa-plan3-design.md)를 바탕으로 Plan3 여행 계획서 최종본을 작성한다.

**Architecture:** Plan2 구조를 기반으로 하되, 전원 활동 기본 + 아기 컨디션 분리 원칙, 나하 1회(아기 제외), 각 날 대체 루트 A~D, 전체 일정 날짜 교체 대안 섹션을 포함한 완전한 계획서를 작성한다.

**Tech Stack:** Markdown 문서 작성, 설계 스펙 파일 참조

---

### Task 1: Plan3 폴더 및 기본 문서 생성

**Files:**
- Create: `Plan3/okinawa-plan.md`

- [ ] **Step 1: Plan3 폴더 생성 확인**

```bash
ls /Users/thlee/GoogleDrive/okinawa/okinawa/
```

- [ ] **Step 2: Plan3/okinawa-plan.md 파일 작성 — 헤더·기본정보·운영원칙**

파일 상단에 아래 내용 작성:
- Plan1 vs Plan2 vs Plan3 비교 표
- 기본 정보 표 (기간·숙소·차량·구성·비행)
- 조 편성·휴식 리듬 표 (전원 기본, 아기 분리 조건)
- 아기 동반 기준 표 (북부근거리 ✓ / 중부 ✓ / 얀바루 ✓ / 나하 ✗ / 남부 ✗)
- 식료품 보급 계획 표 (#1 Day1 카네히데, #2 Day5 이온차탄, #3 Day8 빅원)
- 쇼핑 포인트 표
- 골든위크 운영 원칙

- [ ] **Step 3: 커밋**

```bash
git add Plan3/okinawa-plan.md
git commit -m "docs: add Plan3 okinawa plan header and base info"
```

---

### Task 2: 전체 일정표 + Day 1~5 상세 일정 작성

**Files:**
- Modify: `Plan3/okinawa-plan.md`

- [ ] **Step 1: Plan3/okinawa-plan.md에 전체 일정 골격 표 추가**

Day Matrix 표 작성 (Day·날짜요일·구분·핵심일정·아기·이동거리·해수욕)

- [ ] **Step 2: Day 1 (4/28 화) 작성**

도착일 시간표 + 대체(+) 만자모 옵션

- [ ] **Step 3: Day 2 (4/29 수) 작성**

코우리섬 전원 시간표 + 대체 A(아기 컨디션) B(비) C(하트록 만조)

- [ ] **Step 4: Day 3 (4/30 목) 작성**

츄라우미 번들 시간표 + 대체 A(아기 컨디션) B(비/부세나) C(てつこ 휴무)

- [ ] **Step 5: Day 4 (5/1 금) 작성**

나하 원정(활동조) 시간표 + 돌봄조(차량 없음·숙소 도보권) + 대체 A(太陽 줄) B(비)

- [ ] **Step 6: Day 5 (5/2 토) 작성**

중부 전원 시간표 + 대체 A(아기 컨디션) B(아메리칸빌리지 혼잡) C(비) D(어린이나라)

- [ ] **Step 7: 커밋**

```bash
git add Plan3/okinawa-plan.md
git commit -m "docs: add Plan3 Day 1-5 detailed schedule"
```

---

### Task 3: Day 6~10 상세 일정 작성

**Files:**
- Modify: `Plan3/okinawa-plan.md`

- [ ] **Step 1: Day 6 (5/3 일) 작성**

GW 피크 경량 시간표 + 대체 A(나키진성 혼잡) B(비/부세나)

- [ ] **Step 2: Day 7 (5/4 월) 작성**

얀바루 전원(분리 옵션) 시간표 — 전원 합류 시 + 돌봄조 분리 시 + 대체 A(시간 부족) B(비)

- [ ] **Step 3: Day 8 (5/5 화) 작성**

GW 피크 경량 시간표 + 대체 A(오리온 휴무/부세나) B(비·컨디션)

- [ ] **Step 4: Day 9 (5/6 수) 작성**

모토부 반도 마무리 시간표 + 대체 A(아기 컨디션) B(3곳 과부하)

- [ ] **Step 5: Day 10 (5/7 목) 작성**

출발일 시간표

- [ ] **Step 6: 커밋**

```bash
git add Plan3/okinawa-plan.md
git commit -m "docs: add Plan3 Day 6-10 detailed schedule"
```

---

### Task 4: 부록 섹션 작성

**Files:**
- Modify: `Plan3/okinawa-plan.md`

- [ ] **Step 1: 식당 가이드 섹션 작성**

지정 식당 표 + 지역별 대안 표 (영업시간·휴무·예산·비고 포함)

- [ ] **Step 2: 전체 일정 대안(날짜 교체) 섹션 작성**

5가지 날짜 교체 시나리오 표

- [ ] **Step 3: 해수욕·물놀이 기회 표 작성**

Day 2·3·7·8 비치 정보

- [ ] **Step 4: 플랜 B 요약 표 작성**

상황별 대응 (아기 보챔·비·컨디션 저하·식당 줄·혼잡)

- [ ] **Step 5: Plan3 Day Matrix 최종 표 작성**

전체 요약 (Day·날짜요일·구분·핵심일정·해수욕·이동)

- [ ] **Step 6: 동선 최적화 요약·날씨·예산 섹션 작성**

- [ ] **Step 7: 최종 커밋**

```bash
git add Plan3/okinawa-plan.md
git commit -m "docs: complete Plan3 okinawa plan with all appendix sections"
```

---
