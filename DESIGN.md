# DESIGN — 카페 키오스크

> 공통 디자인 시스템은 core `DESIGN.md`. 이 문서는 카페 테마와 화면 목록입니다.

## 1. 카페 테마 토큰

| 토큰 | 값 |
|---|---|
| `primary` | `#5A3A28` |
| `primary-strong` | `#3A2418` |
| `primary-tint` | `#F7EFE6` |
| `accent` | `#E0B084` |
| `ink` | `#2B1D16` |
| `ink-muted` | `#6B5A4E` |
| `background` | `#F7F3EE` |
| `line` | `#DCCFC2` |
| `discount` | `#B42318` |

공통 토큰(더치페이 파랑 `#2563EB`, 안내 노랑 `#FEF3D7` 등)은 core `DESIGN.md` 2장.

## 2. 카페 문구

| 항목 | 값 |
|---|---|
| 번호 이름 | 주문번호 (예: `C-042`) |
| 번호 규칙 | `C-001`부터 매일 다시 시작 |
| 완료 후 처음 화면 | 30초 뒤 |

## 3. 화면 목록

### 손님 — 스탠드형 (세로 800×1280)

| 화면 | 원본 | 미리보기 |
|---|---|---|
| HW 00 시작 화면 (매장/포장) | [`00-start`](design/00-start.dc.html) | [PNG](screenshots/00-start.png) |
| HW 01 메뉴 선택 | [`Main`](design/Main.dc.html) | [PNG](screenshots/Main.png) |
| HW 02 음료 옵션 (퍼스널 옵션) | [`02-option`](design/02-option.dc.html) | [PNG](screenshots/02-option.png) |
| HW 03 주문 확인 | [`03-cart`](design/03-cart.dc.html) | [PNG](screenshots/03-cart.png) |
| HW 04 결제 방법 선택 · 쿠폰 | [`04-pay-method`](design/04-pay-method.dc.html) | [PNG](screenshots/04-pay-method.png) |
| HW 05 스탬프 적립 (전화번호) | [`05-stamp`](design/05-stamp.dc.html) | [PNG](screenshots/05-stamp.png) |
| HW 06 더치페이 · 결제자별 적립 | [`06-dutch`](design/06-dutch.dc.html) | [PNG](screenshots/06-dutch.png) |
| HW 07 주문 완료 · 스탬프 · 주문서 | [`07-done`](design/07-done.dc.html) | [PNG](screenshots/07-done.png) |

### 손님 — 갤럭시탭형 (가로 1280×800)

| 화면 | 원본 | 미리보기 |
|---|---|---|
| SW 00 시작 화면 (매장/포장) | [`sw-00-start`](design/sw-00-start.dc.html) | [PNG](screenshots/sw-00-start.png) |
| SW 01 메뉴 선택 | [`sw-01-menu`](design/sw-01-menu.dc.html) | [PNG](screenshots/sw-01-menu.png) |
| SW 02 음료 옵션 | [`sw-02-option`](design/sw-02-option.dc.html) | [PNG](screenshots/sw-02-option.png) |
| SW 03 주문 확인 | [`sw-03-cart`](design/sw-03-cart.dc.html) | [PNG](screenshots/sw-03-cart.png) |
| SW 04 결제 방법 선택 · 쿠폰 | [`sw-04-pay`](design/sw-04-pay.dc.html) | [PNG](screenshots/sw-04-pay.png) |
| SW 05 스탬프 적립 (전화번호) | [`sw-05-stamp`](design/sw-05-stamp.dc.html) | [PNG](screenshots/sw-05-stamp.png) |
| SW 06 더치페이 · 결제자별 적립 | [`sw-06-dutch`](design/sw-06-dutch.dc.html) | [PNG](screenshots/sw-06-dutch.png) |
| SW 07 주문 완료 · 스탬프 · 주문서 | [`sw-07-done`](design/sw-07-done.dc.html) | [PNG](screenshots/sw-07-done.png) |

### 사장님 세팅 — 갤럭시탭형

| 화면 | 원본 | 미리보기 |
|---|---|---|
| SW 세팅 1 사장님 시작 | [`set-01-start`](design/set-01-start.dc.html) | [PNG](screenshots/set-01-start.png) |
| SW 세팅 2 카페 정보 | [`set-02-store`](design/set-02-store.dc.html) | [PNG](screenshots/set-02-store.png) |
| SW 세팅 3 메뉴 · 음료 옵션 등록 | [`set-03-menu`](design/set-03-menu.dc.html) | [PNG](screenshots/set-03-menu.png) |
| SW 세팅 4 결제 단말 · 프린터 연결 | [`set-04-devices`](design/set-04-devices.dc.html) | [PNG](screenshots/set-04-devices.png) |
| SW 세팅 5 키오스크 모드 · 스탬프 | [`set-05-kiosk`](design/set-05-kiosk.dc.html) | [PNG](screenshots/set-05-kiosk.png) |

### 쿠폰

| 화면 | 원본 | 미리보기 |
|---|---|---|
| 쿠폰 1 사장님 쿠폰 관리 대시보드 (반응형) | [`coupon-dashboard`](design/coupon-dashboard.dc.html) | [PNG](screenshots/coupon-dashboard.png) |
| 쿠폰 2 사장님 쿠폰 발행 (반응형) | [`coupon-create`](design/coupon-create.dc.html) | [PNG](screenshots/coupon-create.png) |
| 쿠폰 3 손님 · 스탠드형 시리얼 입력 | [`hw-coupon-serial`](design/hw-coupon-serial.dc.html) | [PNG](screenshots/hw-coupon-serial.png) |
| 쿠폰 4 손님 · 스탠드형 바코드 스캔 | [`hw-coupon-scan`](design/hw-coupon-scan.dc.html) | [PNG](screenshots/hw-coupon-scan.png) |
| 쿠폰 5 손님 · 갤럭시탭 시리얼 입력 | [`sw-coupon-serial`](design/sw-coupon-serial.dc.html) | [PNG](screenshots/sw-coupon-serial.png) |
| 쿠폰 6 손님 · 갤럭시탭 바코드 스캔 | [`sw-coupon-scan`](design/sw-coupon-scan.dc.html) | [PNG](screenshots/sw-coupon-scan.png) |

### 기획 문서 (참고용)

| 화면 | 원본 | 미리보기 |
|---|---|---|
| 08 결제 단계 플로우차트 | [`08-flow`](design/08-flow.dc.html) | [PNG](screenshots/08-flow.png) |
| 09 시스템 구조도 | [`09-structure`](design/09-structure.dc.html) | [PNG](screenshots/09-structure.png) |
| 10 반응형 구간 · 폰트 기준 | [`10-responsive`](design/10-responsive.dc.html) | [PNG](screenshots/10-responsive.png) |
| 설치 방식 비교 (HW vs SW) | [`install-compare`](design/install-compare.dc.html) | [PNG](screenshots/install-compare.png) |

## 4. 카페 전용 컴포넌트

| 컴포넌트 | 설명 | 디자인 |
|---|---|---|
| `DrinkOptionSheet` | 온도 · 사이즈 · 샷 · 시럽 · 얼음 · 컵 | `02-option` |
| `TempTag` | HOT · ICE / ICE ONLY 표시 | `Main` |
| `StampBoard` | 10칸 스탬프 판 (기존 · 이번 적립 구분) | `05-stamp`, `07-done` |
| `PhoneKeypad` | 전화번호 숫자 키패드 + 동의 | `05-stamp` |
| `PayerStampRow` | 더치페이 결제자별 번호 · 적립 | `06-dutch` |

공통 컴포넌트는 core `DESIGN.md` 6장.

## 5. 디자인과 명세 차이

| 화면 | 디자인 원본 | 구현 기준 |
|---|---|---|
| `set-03-menu` 메뉴 등록 | 분류 칩 `커피 · 음료 · 디저트` | 손님 화면 분류(`추천 · 에스프레소 · 콜드브루 · 블렌디드 · 티 · 푸드`)를 기준으로 통일 |
| 시작 화면 | `한국어 · English`, `큰 글씨` 버튼 | MVP에서는 숨김 (core D8, task-026) |
| `05-stamp` 스탬프 색 | 기존 스탬프 칸이 제이드 그린(`#007A64`) | 카페 테마 `primary` 또는 별도 스탬프 색 토큰으로 정리 (task-019) |
