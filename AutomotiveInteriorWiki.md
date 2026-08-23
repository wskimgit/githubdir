# 자동차 실내 동향 Wiki

최근 갱신: 2026-08-23

> 날짜별 보고서는 Change Log로 보존하고, 이 Wiki에는 자동차 실내 디자인·HMI·인포테인먼트·좌석·공간·소재·안전·품질의 **현재 유효한 상태와 의미 있는 변화**만 누적한다.

## 현재 핵심 변화

- [Tesla](brands/Tesla.md)·[XPeng](brands/XPeng.md)·[Xiaomi](brands/Xiaomi.md) 등 중국 EV 브랜드에서 [비상 도어 릴리스](topics/비상-도어-릴리스.md)의 식별·조작성 문제가 약 430만 대 규모 리콜로 확대됐다. 색상·표식·사고 후 창문 하강/잠금 해제 전략이 새로운 실내 안전 HMI로 부상했다.
- [Tesla](brands/Tesla.md) Model 3·Y 약 274만 대는 스티어링휠 토크 감지에 실내 카메라 기반 운전자 주의 모니터링을 추가하는 OTA 리콜이 시행된다.
- [Genesis](brands/Genesis.md) GV90 — 2026-08-23 Tech Brief에서 B필러 기능을 도어 내부로 옮기고 롤케이지 원리를 적용한 차체 구조, 일반 GV90보다 12% 높은 Neolun 차체 강성, 시속 110km 전복 시험의 Roof Airbag 전개 근거가 추가 공개됐다.
- 미국 NHTSA는 OEM 기본 인터페이스와 Apple CarPlay·Android Auto를 동일 차량에서 비교해 시선 추적·작업시간·오류율로 주의 분산을 평가하는 연구를 추진하고 있다.
- [Hyundai](brands/Hyundai.md) 2025~2026 Tucson/Tucson Hybrid/Tucson PHEV — NHTSA `26V400000`, Hyundai `304` 계기판 표시 실패 리콜이 2026-08-22 소유자 통지 예정일에 도달했다. 약 96,310대가 대상이며 OTA 또는 딜러 소프트웨어 업데이트로 수정한다.
- Cinemo·Dolby·SmashLabs — 게임 이벤트를 사운드·조명·햅틱·공조와 실시간 연동하는 **차량 전체 반응형 게임 HMI**를 2026-08-21 공개했다. 현재 OEM 평가 단계다.
- [Stellantis](brands/Stellantis.md) — 2026~2027년형 Chrysler·Dodge·Jeep·Ram 다수 차종 약 95만5천 대에서 라디오 소프트웨어가 후방카메라 표시를 방해할 수 있어 OTA 리콜이 진행 중이다.
- [Mercedes-Benz](brands/Mercedes-Benz.md) 2027 C-Class — 물리식 볼륨 스크롤러를 복원하면서 MB.OS OTA와 ChatGPT·Microsoft Bing·Google Gemini 기반 MBUX를 강화했다.
- [Ford](brands/Ford.md) F-150·F-250 Super Duty — SYNC 화면 메뉴가 후방카메라 영상을 가릴 수 있는 APIM 결함으로 FMVSS 111 부적합 리콜이 진행 중이다.

## 기술 변화 지도

### HMI·디스플레이
- [HMI](topics/HMI.md)는 화면 크기 경쟁에서 **표시 우선순위·상태 전환·물리 조작·AI·캐빈 하드웨어 연동·비상 조작계**로 범위가 확대되고 있다.
- 중국 대규모 [비상 도어 릴리스](topics/비상-도어-릴리스.md) 리콜은 평상시 거의 쓰지 않는 기계식 손잡이도 색상·표식·위치가 안전 HMI의 일부임을 보여준다.
- NHTSA의 OEM UI·CarPlay·Android Auto 비교 연구는 화면 사용성 평가가 시선·작업시간·오류율 같은 정량 지표로 이동하는 흐름을 보여준다.
- Hyundai Tucson 계기판 리콜은 디지털 클러스터 표시 실패가 FMVSS 101 `Controls and Displays` 위반으로 직접 연결될 수 있음을 보여준다.
- Ford·Stellantis 후방카메라 리콜은 안전 영상에서 일반 인포테인먼트 UI보다 표시 우선순위와 복구 경로를 강제해야 함을 보여준다.
- Genesis GV90은 주행·정차 상태에 따라 화면 역할을 달리하는 상태 가변형 디스플레이를 양산차에 적용한다.
- Mercedes-Benz C-Class, Volkswagen, Volvo 사례는 고빈도 기능의 물리 조작 복원 흐름을 강화한다.

### AI·인포테인먼트
- [생성형 AI HMI](topics/생성형AI-HMI.md)는 단일 음성비서를 넘어 다중 AI 에이전트 조합으로 확장되고 있다.
- Cinemo·Dolby·SmashLabs의 차량 전체 반응형 게임 HMI는 화면 콘텐츠를 조명·햅틱·공조·공간 음향까지 확장한다.
- [인포테인먼트](topics/인포테인먼트.md)는 AI·게임·OTA·개인화·트림별 그래픽·캐빈 하드웨어 동기화로 확장된다.

### 물리 인터페이스
- [물리 피드백 HMI](topics/물리-피드백-HMI.md)는 다이얼·스크롤러·수동/순차변속·유압식 스티어링처럼 촉각 피드백을 사용자 경험의 핵심으로 복원하는 흐름을 추적한다.
- 비상 도어 릴리스는 ‘평상시 조작감’이 아니라 **충돌 시 즉시 찾고 작동할 수 있는 물리 인터페이스**가 규제 대상이 되는 사례다.
- 최신 방향은 디지털을 줄이는 것이 아니라 **즉시 조작은 물리 입력, 복합 검색·추천은 AI**로 역할을 나누는 쪽에 가깝다.

### 좌석·공간
- Genesis GV90의 4/6인승·회전식 앞좌석·히든 B필러 코치도어는 대형 럭셔리 EV의 이동형 라운지 패키징을 양산 단계로 옮겼다.
- 2026-08-23 Tech Brief는 B필러 삭제가 개방감뿐 아니라 차체 강성·전복 안전·비상탈출까지 함께 재설계해야 하는 문제임을 구체화했다.
- NIO ES8의 2열 중심 5인승, Jaguar Type 01의 4인 독립 공간, Acura NEXERA Vision의 고정 좌석·가변 조작계처럼 미래차 패키징이 다변화된다.

### 소재·조명
- [3D 프린팅](topics/3D-프린팅.md)은 Ferrari CZ26과 Aston Martin Valen에서 반복돼 독립 추적 주제로 승격됐다.
- 조명은 앰비언트 연출을 넘어 Cinemo·Dolby·SmashLabs 사례처럼 게임 이벤트에 반응하는 실시간 HMI 출력 채널로 확장되고 있다.

### 안전·규제·품질
- [자동차안전](topics/자동차안전.md) 이슈는 에어백·벨트뿐 아니라 디지털 클러스터, 후방카메라, 화면 레이어·소프트웨어·커넥터·비상 도어 조작계·운전자 모니터링까지 실내 전체로 확대된다.
- 중국의 약 430만 대 비상 도어 릴리스 리콜은 실내 색상·표식·촉각 식별이 충돌 후 탈출 성능과 직접 연결될 수 있음을 보여준다.
- Tesla의 실내 카메라 DMS 추가는 운전자 주의 감지가 조향 입력에서 시선·주의 상태 측정으로 확대되는 흐름이다.
- Genesis GV90의 Roof Airbag은 실제 사고 데이터와 고속 전복 시험을 기반으로 상부 탑승자 보호 영역을 확장한다.
- Hyundai Tucson 리콜은 계기판 단일 표시점의 고장안전·대체 표시 필요성을 다시 부각시켰다.
- Lotus Emira 2L 등 3차종의 프리텐셔너 하네스 커넥터 무상수리는 구속장치의 커넥터 신뢰성 중요성을 보여준다.

## 브랜드 지도

[Tesla](brands/Tesla.md) · [XPeng](brands/XPeng.md) · [Xiaomi](brands/Xiaomi.md) · [Genesis](brands/Genesis.md) · [Hyundai](brands/Hyundai.md) · [Mercedes-Benz](brands/Mercedes-Benz.md) · [Ford](brands/Ford.md) · [Stellantis](brands/Stellantis.md) · [Lotus](brands/Lotus.md) · [Toyota](brands/Toyota.md) · [Lexus](brands/Lexus.md) · [Kia](brands/Kia.md) · [NIO](brands/NIO.md) · [Infiniti](brands/Infiniti.md) · [Land Rover](brands/Land%20Rover.md) · [Zoox](brands/Zoox.md) · [Mahindra](brands/Mahindra.md) · [Ferrari](brands/Ferrari.md) · [Aston Martin](brands/Aston%20Martin.md) · [Koenigsegg](brands/Koenigsegg.md) · [McLaren](brands/McLaren.md) · [Jaguar](brands/Jaguar.md) · [Cadillac](brands/Cadillac.md) · [Volkswagen](brands/Volkswagen.md) · [Audi](brands/Audi.md) · [Volvo](brands/Volvo.md) · [Acura](brands/Acura.md) · [Lamborghini](brands/Lamborghini.md) · [Lucid](brands/Lucid.md)

## 모델 지도

- [Mahindra BE 6 SPORTEQ](models/Mahindra-BE6-SPORTEQ.md) — 반복 등장·복수 Topic 연결로 독립 Model Wiki 승격.
- Genesis GV90, Tesla Model 3/Y/S/X, XPeng G6/P7+/X9, Xiaomi SU7, Mercedes-Benz C-Class, Hyundai Tucson, Acura NEXERA Vision, Lamborghini Revuelto SV, Lucid Gravity GT-S, Ford F-150·F-250 Super Duty는 현재 Brand Wiki/Topic에서 추적하며 후속이 누적되면 독립 Model Wiki 승격을 검토한다.

## 핵심 Topic

[HMI](topics/HMI.md) · [비상 도어 릴리스](topics/비상-도어-릴리스.md) · [생성형 AI HMI](topics/생성형AI-HMI.md) · [물리 피드백 HMI](topics/물리-피드백-HMI.md) · [3D 프린팅](topics/3D-프린팅.md) · [인포테인먼트](topics/인포테인먼트.md) · [스마트캐빈](topics/스마트캐빈.md) · [자동차안전](topics/자동차안전.md) · [로보택시 실내](topics/로보택시실내.md)

## 신규·관찰 키워드

- **PROMOTED — 비상 도어 릴리스**: 다브랜드·수백만 대 리콜과 규제 영향이 확인돼 [독립 Topic](topics/비상-도어-릴리스.md)으로 승격.
- **WATCH — 실내 카메라 DMS**: Tesla의 대규모 OTA 리콜에서 스티어링휠 토크 감지에 실내 카메라 모니터링을 추가. 반복·타브랜드 확산 시 독립 Topic 승격 검토.
- **WATCH — 스마트폰 투영 HMI 주의 분산**: NHTSA가 OEM UI와 CarPlay·Android Auto를 동일 조건에서 비교하는 연구를 추진. 규제·평가기준으로 발전하는지 추적.
- **WATCH — 차량 전체 반응형 게임 HMI**: 게임 이벤트를 사운드·조명·햅틱·공조까지 동기화하는 구조. 현재 OEM 평가 단계이며 반복·양산 적용 시 독립 Topic 승격을 검토한다.
- **WATCH — 상태 가변형 디스플레이**: Genesis GV90의 팝업 OLED처럼 주행·정차 상태에 따라 화면 위치·크기·역할을 바꾸는 HMI.
- **WATCH — Roof Airbag**: Genesis GV90에서 양산 적용이 발표된 상부 탑승자 보호 에어백. 2026-08-23 Tech Brief에서 전복시험 근거가 추가 공개됐다.
- **WATCH — 다중 AI 차량 비서**: ChatGPT·Bing·Gemini처럼 여러 AI 서비스를 한 차량 HMI에서 조합하는 구조.
- **WATCH — safety-critical display layer**: 후방카메라·충돌경고 등 안전 화면을 일반 인포테인먼트 UI보다 강제로 우선하는 화면 계층 개념.
- **WATCH — 카메라 후방 시야**: 후방 유리를 카메라·디스플레이로 대체하는 사례의 규제·고장안전 문제.
- **PROMOTED — 물리 피드백 HMI**: 반복 확인돼 [독립 Topic](topics/물리-피드백-HMI.md)으로 승격.

## 주목할 위험과 기회

### 위험
- 전자식 도어가 늘어날수록 충돌·전원 상실 시 비상 기계식 릴리스가 눈에 띄지 않으면 탈출·구조가 지연될 수 있다.
- 실내 카메라 DMS는 안전성을 높일 수 있지만 오인식·사생활·데이터 처리 기준을 함께 관리해야 한다.
- 디지털 계기판·후방카메라 등 필수 정보가 단일 디스플레이 경로에 집중될수록 표시 실패가 법규·안전 문제로 확대된다.
- 엔터테인먼트가 조명·햅틱·공조까지 제어하면 운전자 주의 분산과 기능 우선순위 충돌 가능성이 커질 수 있다.
- AI·게임·OTA 등 서비스가 늘수록 개인정보·네트워크 장애·복구 경로 관리가 복잡해진다.

### 기회
- 비상 손잡이의 색상 대비·야광/조명·촉각 표식·표준 아이콘과 사고 후 창문 하강/잠금 해제를 통합한 비상 시나리오 UX가 새로운 안전 설계 영역이 될 수 있다.
- CarPlay·Android Auto·OEM UI의 정량적 주의 분산 데이터가 축적되면 화면 구조와 물리 버튼 배치의 설계 기준이 더 명확해질 수 있다.
- 계기판·후방카메라 안전 기능을 OTA로 수정하는 구조는 하드웨어 교체 없이 결함을 빠르게 개선할 수 있다.
- 안전 화면을 일반 앱보다 높은 우선순위로 강제하고 법규 요구사항과 연결한 자동 회귀시험은 HMI 품질 차별화 요소가 될 수 있다.
- 표준 In-Car Game API가 확산되면 OEM은 조명·햅틱·공조·사운드를 콘텐츠 플랫폼으로 재활용할 수 있다.

## 최근 변화

### 2026-08-23
- [Tesla](brands/Tesla.md)·[XPeng](brands/XPeng.md)·[Xiaomi](brands/Xiaomi.md) 브랜드 Wiki 신규 생성 및 중국 비상 도어 릴리스 리콜 반영.
- [비상 도어 릴리스](topics/비상-도어-릴리스.md)를 독립 Topic으로 승격.
- [Tesla](brands/Tesla.md) Model 3·Y 실내 카메라 DMS OTA 리콜 반영.
- [Genesis](brands/Genesis.md) GV90 Tech Brief의 코치도어 차체 보강·Roof Airbag 전복시험 근거 반영.
- NHTSA의 OEM UI vs CarPlay/Android Auto 주의 분산 비교 연구를 HMI WATCH로 등록.

### 2026-08-22
- [Hyundai](brands/Hyundai.md) 2025~2026 Tucson 계기판 표시 실패 리콜의 소유자 통지 예정일 도달 반영.
- Cinemo·Dolby·SmashLabs의 차량 전체 반응형 게임 HMI를 신규 WATCH로 등록.
- [HMI](topics/HMI.md)와 [자동차안전](topics/자동차안전.md)에 관련 내용을 연결.

### 2026-08-21
- [Genesis](brands/Genesis.md) GV90의 코치도어·팝업 OLED·Pleos Connect·회전 좌석·Roof Airbag 양산 사양 확정 반영.

### 2026-08-20
- [Stellantis](brands/Stellantis.md) 후방카메라/라디오 소프트웨어 리콜, [Lotus](brands/Lotus.md) 프리텐셔너 하네스 커넥터 무상수리 반영.

### 2026-08-19
- [Hyundai](brands/Hyundai.md) 2027 Tucson 공식 실내 디자인 공개 반영.

### 2026-08-18
- [Mercedes-Benz](brands/Mercedes-Benz.md) 2027 C-Class의 물리 볼륨 스크롤러와 다중 AI MBUX 반영.

### 2026-08-17
- [Ford](brands/Ford.md) F-150·F-250 Super Duty 후방카메라 UI 오버레이 리콜 반영.

## 갱신 원칙

1. 최신 공개자료에서 의미 있는 새 사실을 확인한다.
2. 최근 일일 보고서와 Main/Brand/Model/Topic Wiki를 먼저 비교한다.
3. NEW / UPDATE / CONFIRM / ISSUE / TREND / NOCHANGE로 판정하며 NOCHANGE는 추가하지 않는다.
4. 신규 키워드는 기존 Topic과 동의어·유사 개념을 먼저 비교한다.
5. 반복 등장·양산 적용·안전/규제 영향·지속 추적 가치가 충분하면 독립 Topic으로 승격한다.
6. 브랜드는 의미 있는 정보가 1건 이상이면 Brand Wiki 생성 여부를 검토하고, 모델은 반복 등장·복수 Topic·안전 추적 가치가 충분할 때 독립 Model Wiki로 승격한다.
7. 내부 링크는 GitHub 표준 Markdown 상대경로만 사용하며 `[[...]]` 링크는 사용하지 않는다.
8. 링크 대상 파일이 실제 존재하지 않으면 링크하지 않는다.

## 원자료 아카이브

[I20260823](I20260823.md) · [I20260822](I20260822.md) · [I20260821](I20260821.md) · [I20260820](I20260820.md) · [I20260819](I20260819.md) · [I20260818](I20260818.md) · [I20260817](I20260817.md) · [I20260816](I20260816.md) · [I20260815](I20260815.md) · [I20260814](I20260814.md) · [I20260813](I20260813.md) · [I20260812](I20260812.md) · [I20260811](I20260811.md) · [I20260810](I20260810.md) · [I20260809](I20260809.md) · [I20260808](I20260808.md) · [I20260807](I20260807.md) · [I20260806](I20260806.md) · [I20260805](I20260805.md) · [I20260804](I20260804.md) · [I20260803](I20260803.md) · [I20260802](I20260802.md) · [I20260801](I20260801.md)

앞으로 일일 보고서는 Change Log로 보존하고, Main/Brand/Model/Topic Wiki는 중복을 제거한 현재 지식 상태로 계속 갱신한다.