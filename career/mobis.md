[<Back](./../index)

## Career - Hyundai Mobis ##

- 한국의 자동차 부품 전문 회사
- 기간 : 2014/06 ~ 재직중
- 주요 업무
    + 현대/기아 자동차에 공급하는 인포테인먼트 단말 (AVN, Audio Video Navigation) 시스템 개발 
    + AOSP 기반 AVN에 탑재되는 Firmware Update, Automotive Framework, Settings, CAN 기반 연동 사양 개발 및 유지보수
    + Linux / QT 기반 AVN에 탑재되는 Home/Favorite 사양 개발
    + 차종 Project Leader
- 주요 기술
    + C/C++, Java, Android SDK, Android Framework (AOSP), Linux, QT, Git, Confluence/Jira, Docker


### AOSP(GB) 기반 AVN : Firmware Update 보안 개발 및 유지보수 ###
- 기간 : 2014/06 ~ 2017/04
- 참여시점 : 양산 개발, 테스트, 출시, 정기 업데이트
- 프로젝트 내용 : AOSP Recovery Mode를 이용한 System Update 및 Module Update 개발 및 Firmware 보안 강화
- 참여 인원 : 1명
- 사용 기술 : Java, C, Make 기반 Build Script, Recovery Mode, Android Framework, Serial Communication, CAN Network, Cryptography(RSA, SHA), Git (Gerrit)
- 주요 활동 :
    + AOSP 내 Recovery Mode를 활용하여 개발된 System Update 기능 유지 보수 및 신규 사양 반영
    + 시리얼 통신, CAN Network 등 다양한 방법으로 통신하는 AVN 주변 모듈에 대한 Update 기능 유지 보수 및 신규 모듈 사양 반영
    + Update를 위한 Firmware Packaging, Verify Toolchain 개발 (MFC, Java, Shell Script)
    + 유출 위험이 높은 인증 개인키를 운용하는 상황에서 개인키 교체 진행 및 Firmware 보안 강화 절차를 고안하고 기존 기기의 하위 호환이 가능하도록 개발하여 적용
- 성과
    + Android UI 뿐만 아니라 Recovery Mode, Build Script, Module 간 통신, Firmware Packaging 등 다양한 분야를 다루어 Embedded SW 전반에 걸쳐 이해의 폭이 넓어짐
    + 보안 강화 사양을 개발하면서 암호학을 이해하고 양산 개발에 적용해보는 경험


### AOSP(GB) 기반 AVN : 외장 CDP 사양을 위한 Automotive Framework 개발 ###
- 기간 : 2014/10 ~ 2015/12
- 참여시점 : 양산 개발, 테스트, 출시
- 프로젝트 내용 : CAN 통신 사양의 외장 CDP 모듈과 연동하는 Automotive Framework 개발
- 참여 인원 : 1명
- 사용 기술 : Java, CAN Network, Automotive Framework, Git (Gerrit)
- 주요 활동 :
    + CAN 통신 사양의 외장 CDP 모듈이 신규 추가되어, 새로운 인터페이스에 맞추어 AVN과 연동 개발
    + 전용 통신 사양의 기존 내장 CDP와 인터페이스가 같지 않으나, 호환성 보장이 필요하여, Adapter Parttern 활용하여 Framework 단 설계 및 개발함
    + Throughput 한계가 있는 CAN 통신 하에서 원활한 작동을 위해 CAN Msg 처리 루틴 개선 (Multi-threading)
- 성과
    + 차량 분야에서 많이 사용하는 CAN 통신에 대한 이해가 넓어짐
    + 기존 Legacy Code 가능한 활용하여 개발하기 위한 Design Pattern 도입 경험


### AOSP(GB) 기반 AVN : Automotive Framework 신규 사양 적용 및 유지보수 ###
- 기간 : 2018/04 ~ 2019/01
- 참여시점 : 정기 업데이트
- 프로젝트 내용 : 정기 업데이트에 따른 Automotive Framework 신규 사양 반영 및 이슈 대응
- 참여 인원 : 1명
- 사용 기술 : Java, CAN Network, Automotive Framework, Git (Gerrit), Confluence/Jira
- 주요 활동 :
    + Mode Management, Application Management, Power Control, Micom Control, CAN Network Interface 등 Automotive Framework 전반에 걸쳐 발생하는 이슈 사항에 대해 분석 및 수정 대응
    + StatusBar, Activity Life Cyclemanagement, Low Memory Kill, Audio Focus Handling 등 AOSP의 Android Framework 전반에 걸쳐 발생하는 이슈 사항에 대해 분석 및 수정 대응
    + 신규 사양 개발 대응
- 성과
    + Side Effect에 대한 Risk를 최우선으로 관리하며 이슈 수정 진행 경험

### AOSP(GB) 기반 AVN : 성능 개선 TFT ###
- 기간 : 2018/05 ~ 2018/11
- 참여시점 : 정기 업데이트
- 프로젝트 내용 : 구 세대 AVN 기기에 대한 성능 개선 포인트 도출 및 개선 진행
- 참여 인원 : 2명
- 사용 기술 : Java, Automotive Framework, Git (Gerrit)
- 주요 활동 :
    + 구 세대 AVN 기기에 대한 전체 Process Profiling 및 부하 Method 도출하여 개선
    + Automotive Framework 내 Msg Queue 처리 개선
- 성과
    + 가시적인 성능 개선이 어려운 프로젝트 여건 속에서 의미있는 개선 포인트를 찾고 개선 진행함

### AOSP(ICS) 기반 AVN : Setting 기능 개발 및 유지보수 ###
- 기간 : 2016/01 ~ 2017/04
- 참여시점 : 양산 개발, 테스트, 출시
- 프로젝트 내용 : Settings 기능 사양 개발 및 유지 보수 진행
- 참여 인원 : 1명
- 사용 기술 : Java, Android SDK, Android Framework, Automotive Framework, Git (Gerrit)
- 주요 활동 :
    + Scene 개수가 가장 많은 기능인 Setting 기능 개발을 담당하여, 효과적으로 UI 적용을 위해 구조 개선
    + 잦은 사양 변경에 대한 대응 진행
    + 인도 연구소 내 인도인 개발자들과 협업 진행
- 성과
    + 다양하고 잦은 사양 변경에 대해 원활히 대응했으며, 외국인 개발자와 실제로 협업해보는 경험

### AOSP(ICS) 기반 AVN : 드라이브 모드 사양을 위한 Automotive Framework/UI 개발 ###
- 기간 : 2016/05 ~ 2017/01
- 참여시점 : 양산 개발, 테스트, 출시
- 프로젝트 내용 : 드라이브 모드를 AVN에서 표시하고 제어하는 신규 사양을 위한 Automotive Framework 및 UI 개발
- 참여 인원 : 1명
- 사용 기술 : Java, Android SDK, Android Framework, Automotive Framework, CAN Network, Git (Gerrit)
- 주요 활동 :
    + 드라이브 모드 기능을 신규로 개발하면서 향후 여러 모델에 대해 공통적으로 사용할 수 있도록 설계함
    + 드라이브 모드 기능의 종류와 설정 사양 변경, 차종에 따른 CAN 통신 사양 변경을 공통적으로 대응할 수 있도록 Framework 및 UI SW 설계 및 구현함
- 성과
    + 다양한 차종에 확대 전개되어 구현된 모듈이 사용 중임

### Embedded Linux/QT 기반 AVN : 홈/메뉴 기능 개발 ###
- 기간 : 2018/09 ~ Present
- 참여시점 : 선행 개발, 양산 개발, 테스트
- 프로젝트 내용 : Embedded Linux/QT 기반의 AVN 신규 플랫폼의 홈/메뉴 기능 개발 진행
- 참여 인원 : 1명
- 사용 기술 : C++, QT, Linux, Automotive Framework, Git (Gerrit), Confluence/Jira, Docker
- 주요 활동 :
    + 신규 UI Framework인 QT 활용하여 신규 플랫폼 개발 진행 중
    + 협력 개발사, 인도 연구소 내 개발자 등과 협업 진행
    + 기존 플랫폼과 다른 신규 사양 구현 진행 중
    + Docker를 활용하여 기존 플랫폼과 함께 Multi-Build할 수 있는 환경 구축 진행
- 성과
    + 새로운 개발 환경 및 UI Framework에 대해 경험하는 중


### 차종 Project Leader ###
- 기간 : 2015/01 ~ 2016/03
- 참여시점 : 양산 개발
- 프로젝트 내용 : 차종 출시를 위해 프로젝트 관리 업무 수행
- 참여 인원 : 1명
- 사용 기술 : Git (Gerrit), 사내 시스템
- 주요 활동 :
    + 프로젝트 일정 관리
    + 신규 사양 적용 및 차종 종류에 따른 변경 사양 관리
    + 고객사 대응(설계, 품질)
    + 최종 출시 후 사후 관리 진행
- 성과
    + 개발 업무 이외에 프로젝트 관리 업무에 대한 경험

[<Back](./../index)
