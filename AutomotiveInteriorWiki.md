# 자동차 실내 동향 Wiki

최근 갱신: 2026-08-17

> 날짜별 보고서는 변화 로그로 보존하고, 이 Wiki에는 자동차 실내 디자인·HMI·인포테인먼트·좌석·공간·소재·안전·품질의 현재 유효한 지식과 의미 있는 변화만 누적한다.

## 현재 핵심 변화

- [Ford](brands/Ford.md) F-150·F-250 Super Duty — 8인치 SYNC 화면에서 인포테인먼트 홈 메뉴가 후방카메라 영상을 일부 가릴 수 있는 APIM 소프트웨어 결함으로 FMVSS 111 부적합 리콜이 진행 중이며, 공개 리콜 정보상 2026-08-17이 임시 소유자 통지 예정일이다.
- [Acura](brands/Acura.md)의 [NEXERA Vision](brands/Acura.md#nexera-vision) — 단일 곡면 운전자 화면, 고정 좌석과 가변 스티어링휠·페달, 최소 물리 버튼을 결합해 ‘화면 수 축소 + 패키징 재설계’라는 미래 콘셉트를 제시했다.
- [Lamborghini](brands/Lamborghini.md)의 [Revuelto SV](brands/Lamborghini.md#revuelto-sv) — 카본 도어·시트와 SV 전용 화면 그래픽·애니메이션, 5단계 트랙션 제어 `Pilota` 모드를 결합해 고성능 트림 차별화를 HMI 로직까지 확대했다.
- [Lucid](brands/Lucid.md)의 [Gravity GT-S](brands/Lucid.md#gravity-gt-s) — 기존 디지털 콕핏 구조를 유지하면서 블루 안전벨트·스티칭·파이핑·헤드레스트 엠보싱으로 고성능 정체성을 실내 소재에 집중했다.
- [Mahindra](brands/Mahindra.md)의 [BE 6 SPORTEQ](models/Mahindra-BE6-SPORTEQ.md) — 3화면 콕핏과 Google Gemini 기반 `TEQ_Talk`를 양산 사양으로 확정하면서 [생성형 AI HMI](topics/생성형AI-HMI.md)가 보급형 EV까지 확장되기 시작했다.
- [Aston Martin](brands/Aston%20Martin.md) Valen — [3D 프린팅](topics/3D-프린팅.md) 부품·경량 카본 시트·운전자 지향 중앙 화면·카메라 후방 시야를 결합해 경량화와 디지털 시야 보완을 함께 설계한다.
- [McLaren](brands/McLaren.md) McL 6GT와 [Koenigsegg](brands/Koenigsegg.md) CCGT1 — 수동·순차변속, 유압식 스티어링 등 [물리 피드백 HMI](topics/물리-피드백-HMI.md)를 핵심 사용자 경험으로 다시 전면화했다.
- [Ferrari](brands/Ferrari.md) CZ26 — 기능성 직물·카본·3D 프린팅 시트 인서트를 결합해 원오프 실내 맞춤화를 공정·형상 수준으로 확대했다.
- [Kia](brands/Kia.md) EV3 — 보급형 EV에서도 계기판·공조·인포테인먼트를 분리한 약 30인치 통합 디지털 영역을 실제 판매 사양으로 유지한다.
- [Kia](brands/Kia.md) Telluride — 전동시트 스위치 손상이 모터 과열·화재로 이어질 수 있어 좌석 편의장치의 전류 감시·전자퓨즈·fail-safe 중요성이 커졌다.
- [Toyota](brands/Toyota.md) Camry Hybrid — 디지털 계기판 표시 불량 리콜은 클러스터 고장안전과 필수 경고정보 이중화 필요성을 보여준다.

## 기술 변화 지도

### HMI·디스플레이
- [HMI](topics/HMI.md)는 대형 화면 일변도에서 화면·물리 조작·음성·조명을 역할별로 배치하는 혼합 구조로 이동한다.
- Ford F-150·F-250 리콜은 후방카메라처럼 법규상 안전 화면에서 일반 인포테인먼트 메뉴보다 **안전 화면 레이어와 상태 전환을 강제 우선**해야 함을 보여준다.
- Acura NEXERA Vision은 화면을 하나로 줄이고 운전자에게 조작계를 맞추는 방향을, Lamborghini Revuelto SV는 기존 화면에 트림 전용 그래픽·제어 로직을 추가하는 방향을 보여준다.
- [물리 피드백 HMI](topics/물리-피드백-HMI.md)는 [Volvo](brands/Volvo.md)의 터치 과의존 재검토, [Volkswagen](brands/Volkswagen.md)의 다기능 물리 다이얼, Koenigsegg·McLaren의 변속 조작 중심 설계에서 반복 확인돼 독립 Topic으로 승격됐다.
- 카메라 기반 rear-view system처럼 디지털 화면이 직접 시야를 대체하면서 전원·센서·표시장치 장애에 대한 대체 설계가 중요해진다.

### AI·인포테인먼트
- [생성형 AI HMI](topics/생성형AI-HMI.md)가 음성명령을 넘어 차량 설정·콘텐츠·개인화를 통합하는 양산 단계로 진입했다.
- Mahindra BE 6 SPORTEQ는 3화면 콕핏, 차량 AI, karaoke·gaming·Dolby, Digital Car Key를 하나의 스마트캐빈 경험으로 묶는다.
- [인포테인먼트](topics/인포테인먼트.md) 경쟁은 화면 크기뿐 아니라 AI·콘텐츠·스마트폰/키 연동, 트림별 전용 그래픽과 주행상태 표현으로 확대된다.

### 좌석·공간
- 마사지·통풍·오토만·헤드레스트 오디오 등 좌석 체감 기능이 프리미엄 차별화 수단으로 강화된다.
- Acura NEXERA Vision은 좌석을 바닥에 고정하고 스티어링휠·페달을 운전자에게 이동시키는 반대 접근을 제시한다. 아직 콘셉트 단계이며 체형 대응·승하차·충돌 자세 검증이 핵심 과제다.
- [Audi](brands/Audi.md) Q7처럼 좌석 이동과 3열 접근을 MMI·물리 버튼·조명과 연동하는 ‘좌석 HMI’가 확대된다.
- [NIO](brands/NIO.md) ES8처럼 3열을 삭제하고 2열 휴식성과 적재공간을 강화한 5인승 패키지, [Jaguar](brands/Jaguar.md) Type 01의 4인 독립 공간 등 EV 전용 공간 전략이 다변화된다.

### 소재·조명
- [3D 프린팅](topics/3D-프린팅.md)이 Ferrari CZ26의 시트 인서트에서 Aston Martin Valen의 경량 부품으로 반복 등장해 독립 추적 주제로 승격했다.
- Acura는 재활용 알루미늄과 핑크 앰비언트 포인트, Lamborghini는 카본파이버와 대비 가죽, Lucid는 블루 안전벨트·스티칭·파이핑을 사용해 소재와 컬러를 브랜드/트림 정체성으로 적극 활용한다.
- 아라미드·카본 복합재, 기능성 직물, semi-aniline leather·Alcantara 등 경량·촉감·고급감을 동시에 겨냥한 소재 조합이 확대된다.
- [Cadillac](brands/Cadillac.md)의 대규모 색·트림 개인화와 Singer × Louis Vuitton의 패션 공예 결합처럼 프리미엄 실내가 소재 선택에서 공정·패턴·브랜드 협업으로 확장된다.

### 안전·규제·품질
- [자동차안전](topics/자동차안전.md) 이슈가 에어백·벨트뿐 아니라 전동시트 모터·디지털 클러스터·DSP·후방카메라·화면 레이어 관리 등 실내 전장 전체로 확대된다.
- Ford F-150·F-250의 후방카메라 UI 오버레이 결함은 메뉴 상태 관리 오류만으로도 FMVSS 111 후방시야 규정 위반이 될 수 있음을 보여준다.
- 화면이 필수 안전정보나 실제 시야를 대신할수록 부팅·복구·전원 이중화·고장 상태 표시뿐 아니라 UI 우선순위와 화면 전환 회귀시험이 중요해진다.
- 생성형 AI HMI는 오인식·응답 지연·과도한 대화로 인한 주의 분산을 줄이고 안전 관련 명령의 권한·확인 절차를 명확히 해야 한다.
- 고성능 주행모드·트랙션 단계가 세분화될수록 현재 제어 상태를 운전자가 즉시 이해할 수 있는 HMI가 중요하다.

## 브랜드 지도

[Ford](brands/Ford.md) · [Toyota](brands/Toyota.md) · [Lexus](brands/Lexus.md) · [Kia](brands/Kia.md) · [NIO](brands/NIO.md) · [Infiniti](brands/Infiniti.md) · [Land Rover](brands/Land%20Rover.md) · [Zoox](brands/Zoox.md) · [Mahindra](brands/Mahindra.md) · [Ferrari](brands/Ferrari.md) · [Aston Martin](brands/Aston%20Martin.md) · [Koenigsegg](brands/Koenigsegg.md) · [McLaren](brands/McLaren.md) · [Jaguar](brands/Jaguar.md) · [Cadillac](brands/Cadillac.md) · [Volkswagen](brands/Volkswagen.md) · [Audi](brands/Audi.md) · [Volvo](brands/Volvo.md) · [Acura](brands/Acura.md) · [Lamborghini](brands/Lamborghini.md) · [Lucid](brands/Lucid.md)

## 모델 지도

현재 독립 Model Wiki로 승격된 모델:

- [Mahindra BE 6 SPORTEQ](models/Mahindra-BE6-SPORTEQ.md) — 2026-08-11 티저, 2026-08-15 양산 HMI 확정으로 서로 다른 날짜에 반복 등장하고 복수 Topic과 연결돼 독립 모델로 승격.

Acura NEXERA Vision, Lamborghini Revuelto SV, Lucid Gravity GT-S는 첫 추적 단계이므로 각 Brand Wiki의 모델 섹션에서 관리한다. Ford F-150·F-250 Super Duty는 이번 리콜을 Brand Wiki와 안전 Topic에서 추적하며, 반복 후속·복수 Topic 연결이 쌓이면 독립 Model Wiki 승격을 검토한다.

## 핵심 Topic

[HMI](topics/HMI.md) · [생성형 AI HMI](topics/생성형AI-HMI.md) · [물리 피드백 HMI](topics/물리-피드백-HMI.md) · [3D 프린팅](topics/3D-프린팅.md) · [인포테인먼트](topics/인포테인먼트.md) · [스마트캐빈](topics/스마트캐빈.md) · [자동차안전](topics/자동차안전.md) · [로보택시 실내](topics/로보택시실내.md)

## 신규·관찰 키워드

- **WATCH — safety-critical display layer**: 후방카메라·충돌경고 등 안전 화면을 일반 인포테인먼트 UI보다 강제로 우선하는 화면 계층 개념. Ford 리콜에서 실제 규제 이슈로 확인돼 반복 여부를 추적한다.
- **WATCH — 카메라 후방 시야**: Aston Martin Valen처럼 후방 유리를 제거하고 카메라·디스플레이로 대체하는 사례. 반복성과 규제·고장안전 중요도를 추가 관찰한다.
- **PROMOTED — 물리 피드백 HMI**: 여러 브랜드·날짜에서 반복 확인돼 [독립 Topic](topics/물리-피드백-HMI.md)으로 승격했다.
- **WATCH — 패션 공예 실내**: Singer × Louis Vuitton처럼 자동차 외 럭셔리 공예를 실내 소재·패턴·시계·트림에 직접 결합하는 흐름.
- **WATCH — 고정 좌석·가변 조작계**: Acura NEXERA Vision에서 새로 확인된 패키징 개념. 양산 사례나 다른 브랜드 반복 여부를 관찰한다.
- **WATCH — 트림 전용 디지털 HMI**: Lamborghini Revuelto SV처럼 고성능 트림에 전용 화면 그래픽·애니메이션·제어 로직을 부여하는 방식. 반복 적용 여부를 추적한다.

## 주목할 위험과 기회

### 위험
- 생성형 AI와 다중 화면이 늘수록 응답 지연·오인식·알림 과잉에 따른 주의 분산 가능성이 커진다.
- 카메라가 실제 시야를 대체할 경우 센서·전원·디스플레이 장애뿐 아니라 UI 오버레이·상태 전환 오류도 시야 상실로 이어질 수 있다.
- 전동시트처럼 단순해 보이는 편의 기능도 스위치 고착과 모터 지속 구동이 화재로 확대될 수 있다.
- 고정 좌석·가변 조작계는 다양한 체형·승하차·충돌 자세 요구를 동시에 만족시켜야 한다.
- 특수 소재·3D 프린팅·패션 공예·트림별 전용 컬러는 장기 내구성·난연성·수리성·부품 재현성 관리가 필요하다.

### 기회
- 안전 화면을 일반 앱보다 높은 우선순위로 강제하고 메뉴 잔존·오버레이 충돌을 규제 요구사항과 연결해 자동 회귀시험하는 HMI 품질 체계가 새로운 차별화 영역이 될 수 있다.
- AI 음성비서를 공조·내비게이션·미디어·차량 설정과 통합하면 화면 터치 횟수를 줄일 수 있다.
- 단일 화면 중심 HMI가 실제 시선 분산을 줄인다면 ‘적은 화면의 고품질 UX’가 새로운 차별화 축이 될 수 있다.
- 트림별 화면 그래픽·주행 UX를 소프트웨어로 차별화하면 하드웨어 변경을 줄이면서 고성능 상품성을 강화할 수 있다.
- 3D 프린팅은 소량생산 실내의 경량화·맞춤화·부품 통합을 동시에 개선할 수 있다.
- 디지털 화면과 물리 조작을 목적별로 분리하면 최신 기능을 유지하면서 직관성과 안전성을 개선할 수 있다.
- 패션·가구·시계 산업과의 협업은 디지털 기능 외의 새로운 프리미엄 수익원을 만들 수 있다.

## 최근 변화

### 2026-08-17 Daily Change Log 반영
- [Ford](brands/Ford.md) F-150·F-250 Super Duty: 후방카메라 영상 위에 인포테인먼트 메뉴가 남을 수 있는 APIM 소프트웨어 결함과 FMVSS 111 리콜의 소유자 통지 예정일 도달을 반영.
- [HMI](topics/HMI.md)에 안전 화면 레이어·메뉴 상태 전환 우선순위 문제를 추가.
- [자동차안전](topics/자동차안전.md)에 Ford 후방카메라·안전 디스플레이 항목을 추가.
- `safety-critical display layer`를 신규 WATCH 키워드로 등록.

### 2026-08-16 Daily Change Log 반영
- [Acura](brands/Acura.md) NEXERA Vision: 단일 곡면 화면·고정 좌석·가변 조작계·재활용 알루미늄 실내를 신규 반영.
- [Lamborghini](brands/Lamborghini.md) Revuelto SV: SV 전용 화면 그래픽·Pilota 모드·카본 도어/시트를 신규 반영.
- [Lucid](brands/Lucid.md) Gravity GT-S: 블루 안전벨트·스티칭·헤드레스트 엠보싱 중심의 고성능 실내 차별화를 신규 반영.
- 신규 Brand Wiki: Acura, Lamborghini, Lucid.
- [HMI](topics/HMI.md)에 단일 화면·가변 조작계와 트림 전용 디지털 HMI 사례를 추가.

### 2026-08-16 Entity Graph + ERR-C 갱신
- Main Wiki의 브랜드명을 실제 Brand Wiki로 연결.
- [Mahindra BE 6 SPORTEQ](models/Mahindra-BE6-SPORTEQ.md)를 첫 독립 Model Wiki로 승격.
- [물리 피드백 HMI](topics/물리-피드백-HMI.md)를 WATCH에서 독립 Topic으로 승격.
- 신규 Brand Wiki: Kia, Mahindra, Ferrari, Aston Martin, Koenigsegg, McLaren, Jaguar, Cadillac, Volkswagen, Audi, Volvo.
- [생성형 AI HMI](topics/생성형AI-HMI.md), [3D 프린팅](topics/3D-프린팅.md) Topic과 Brand/Model 간 링크를 강화.

### 2026-08-15
- Mahindra BE 6 SPORTEQ: 3화면·Google Gemini 기반 TEQ_Talk의 양산 적용 확인.
- Aston Martin Valen: 3D 프린팅·경량 시트·카메라 후방 시야 반영.
- McLaren McL 6GT: 수동변속·유압식 스티어링 중심 아날로그 UX 반영.

### 2026-08-14
- Ferrari CZ26: 3D 프린팅 시트 인서트·기능성 직물·카본 적용.
- Koenigsegg CCGT1: 순차변속 인터페이스·Ghost Fibre·카본 롤케이지 반영.
- Singer × Louis Vuitton Porsche 911: 패션 공예 기반 소재·트림 개인화 반영.

### 2026-08-13
- Kia EV3: 미국 판매 사양의 3영역 디지털 HMI 확정.
- Kia Telluride: 전동시트 과열·화재 리콜의 소유자 통지 단계 반영.
- JAS Tensei: 클래식 구조와 디지털 클러스터를 결합한 원형 보존형 현대화 사례 추가.

### 2026-08-12
- Jaguar Type 01: 4인 독립 공간·센터 스파인·와이드 화면·세로형 터치패널 반영.
- Cadillac Escalade IQ Curated: 44개 실내 색상과 주문 제작 프로그램 반영.
- [Toyota](brands/Toyota.md): Camry Hybrid 계기판 리콜의 글로벌 규모·표시 상실 범위·소프트웨어 수리 방식 반영.

### 2026-08-11
- [Toyota](brands/Toyota.md): 미국 계기판 표시 불량 리콜 최초 확인.
- Volkswagen Atlas Cross Sport: 대형 화면과 다기능 물리 다이얼 결합.
- Mahindra BE 6 Sporteq: 스포츠 지향 실내 특화 트림 티저.

### 2026-08-10
- Audi Q7: MMI 연동 Comfort Entry·Interaction Light와 좌석 접근성 HMI 반영.
- Volvo: 터치스크린 과의존 재검토와 촉각 조작 복원 가능성 반영.
- 자동운전 HMI: 최소위험상태 이후 차량 상태·원격 지원 안내를 비상 UX 과제로 추가.

## 갱신 원칙

1. 최신 공개자료에서 의미 있는 새 사실을 확인한다.
2. 최근 일일 보고서와 Main/Brand/Model/Topic Wiki를 먼저 비교한다.
3. NEW / UPDATE / CONFIRM / ISSUE / TREND / NOCHANGE로 판정하며 NOCHANGE는 추가하지 않는다.
4. 신규 키워드는 기존 Topic과 동의어·유사 개념을 먼저 비교한다.
5. 반복 등장·양산 적용·안전/규제 영향·지속 추적 가치가 충분하면 독립 Topic으로 승격한다.
6. 브랜드는 의미 있는 정보가 1건 이상이면 Brand Wiki 생성 여부를 검토하고, 모델은 반복 등장·복수 Topic·안전 추적 가치가 충분할 때 독립 Model Wiki로 승격한다.
7. 일일 보고서는 변화 로그로 보존하고 Wiki에는 현재 유효한 상태를 우선한다.
8. 내부 링크는 GitHub에서 작동하는 표준 Markdown 상대경로만 사용하며 `[[...]]` 링크는 사용하지 않는다.
9. 링크 대상 파일이 실제 존재하지 않으면 링크하지 않는다.
10. 오래된 정보가 폐기·대체·단종되면 현재 상태를 수정하고 필요한 경우 과거 변화로 이동한다.

## 원자료 아카이브

[I20260817](I20260817.md) · [I20260816](I20260816.md) · [I20260815](I20260815.md) · [I20260814](I20260814.md) · [I20260813](I20260813.md) · [I20260812](I20260812.md) · [I20260811](I20260811.md) · [I20260810](I20260810.md) · [I20260809](I20260809.md) · [I20260808](I20260808.md) · [I20260807](I20260807.md) · [I20260806](I20260806.md) · [I20260805](I20260805.md) · [I20260804](I20260804.md) · [I20260803](I20260803.md) · [I20260802](I20260802.md) · [I20260801](I20260801.md)

앞으로 일일 보고서는 Change Log로 보존하고, Main/Brand/Model/Topic Wiki는 중복을 제거한 현재 지식 상태로 계속 갱신한다.