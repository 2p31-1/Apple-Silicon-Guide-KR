<p align="center">
<img src="https://github.com/mikeroyal/Apple-Silicon-Guide/assets/45159366/41de57da-156b-428c-b4b3-29b4594ae256">
<br />
</p>

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/213074824-9155501e-75bc-4557-9cff-b517211dd421.jpeg">
<br />
</p>

<h1 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/157356993-34a7e1fa-ac06-49aa-991a-bf797a745e64.png">
  <br />
  Apple 실리콘 가이드
</h1>

 <a href="https://github.com/mikeroyal?tab=followers">
         <img alt="followers" title="업데이트를 위해 Github에서 나를 팔로우하세요" src="https://custom-icon-badges.demolab.com/github/followers/mikeroyal?color=236ad3&labelColor=1155ba&style=for-the-badge&logo=person-add&label=Follow&logoColor=white"/></a>

![유지관리](https://img.shields.io/maintenance/yes/2024?style=for-the-badge)


#### Apple Silicon 기반 장치를 더 효율적이고 효율적으로 사용할 수 있도록 도와주는 응용 프로그램, 라이브러리 및 도구를 포함하여 Apple Silicon을 다루는 가이드입니다.

**참고: 이 편리한 확장 프로그램 [Markdown PDF](https://marketplace.visualstudio.com/items?itemName=yzane.markdown-pdf)을 사용하면 [VSCode](https://code.visualstudio.com/)에서 이 마크다운 파일을 PDF로 쉽게 변환할 수 있습니다.**


<p align="center">
<img src="https://github.com/mikeroyal/Apple-Silicon-Guide/assets/45159366/bc1a4580-6500-44f8-ac84-0d746719a423">
<br />
Apple M3/M3 Pro/M3 Max/M3 Ultra 아키텍처.
</p>

<p align="center">
<img src="https://github.com/mikeroyal/Apple-Silicon-Guide/assets/45159366/05a63ff1-c221-415c-a563-0476cbe28f95">
<br />
Apple M2/M2 Pro/M2 Max/M2 Ultra 아키텍처.
</p>

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/157364203-a6c998b9-f15d-465e-81f4-ef888e7c8910.png">
<br />
Apple M1/M1 Pro/M1 Max/M1 Ultra 아키텍처.
</p>

# 목차

1. [Apple Silicon 시작하기](https://github.com/mikeroyal/Apple-Silicon-Guide#getting-started-with-apple-silicon)
   * [A17 Pro](#a17-pro)
   * [A16 Bionic](https://github.com/mikeroyal/Apple-Silicon-Guide#A16-Bionic)
   * [H2](https://github.com/mikeroyal/Apple-Silicon-Guide#H2)
   * [S9](#s9)
   * [U1](https://github.com/mikeroyal/Apple-Silicon-Guide#U1)
   * [R1](#R1)
   * [M1](https://github.com/mikeroyal/Apple-Silicon-Guide#m1)
   * [M1 Pro](https://github.com/mikeroyal/Apple-Silicon-Guide#m1-pro)
   * [M1 Max](https://github.com/mikeroyal/Apple-Silicon-Guide#m1-max)
   * [M1 Ultra](https://github.com/mikeroyal/Apple-Silicon-Guide#m1-ultra)
   * [M2](https://github.com/mikeroyal/Apple-Silicon-Guide#m2)
   * [M2 Pro](#M2-프로)
   * [M2 Max](#M2-최대)
   * [M2 Ultra](#M2-울트라)
   * [M3](#m3)
   * [M3 Pro](#m3-pro)
   * [M3 Max](#m3-최대)
   * [M3 Ultra](#m3-울트라)
   * [Apple AR 및 Vision Pro 헤드셋](#apple-ar-and-vision-pro-headset)
   * [Apple Silicon 기반 장치](https://github.com/mikeroyal/Apple-Silicon-Guide#Devices-powered-by-Apple-Silicon)
   * [소프트웨어 다운로드](https://github.com/mikeroyal/Apple-Silicon-Guide#Getting-Software)
     - [생산성 및 워크플로 앱](https://github.com/mikeroyal/Apple-Silicon-Guide#Productivity--Workflow-Apps)
     - [보안 및 개인정보 보호에 중점을 둔 웹 브라우저](https://github.com/mikeroyal/Apple-Silicon-Guide#secure--privacy-focused-web-browsers)
        * [개인정보 보호 및 보안에 중점을 둔 브라우저 확장 프로그램](https://github.com/mikeroyal/Apple-Silicon-Guide#privacy--security-focused-browser-extensions)
        * [개인정보 보호에 중점을 둔 검색엔진](https://github.com/mikeroyal/Apple-Silicon-Guide#privacy-focused-search-engines)
     - [Microsoft Office 대안](https://github.com/mikeroyal/Apple-Silicon-Guide#microsoft-office-alternatives)
   * [유니버설 컨트롤](https://github.com/mikeroyal/Apple-Silicon-Guide#Universal-Control)
   * [스테이지 매니저](https://github.com/mikeroyal/Apple-Silicon-Guide#Stage-Manager)
   * [파일 동기화/전송](#File-SyncTransfer)
   - [iCloud를 Nexcloud로 교체하기](#Replacing-iCloud-with-Nexcloud)
   * [저장소 추가(외부)](https://github.com/mikeroyal/Apple-Silicon-Guide#Adding-External-Storage)
   * [백업](#백업)
   * [SSD 드라이브 상태/데이터 복구](https://github.com/mikeroyal/Apple-Silicon-Guide#SSD-Drive-HealthData-Recovery)
   * [배터리 상태 확인](https://github.com/mikeroyal/Apple-Silicon-Guide#Checking-Battery-Health)
      - [저전력 모드 켜기](#low-power-mode)
   * [충전/충전기](#ChargingPowerbanks)
      - [USB-C 어댑터](#usb-c-adapters)
      - [USB-C 고속 충전 케이블(3.3~10피트)](#usb-c-fast-charge-cables)
   * [MacOS/iOS 보안 강화](https://github.com/mikeroyal/Apple-Silicon-Guide#macosios-security-hardening)
   
 1. [게임](https://github.com/mikeroyal/Apple-Silicon-Guide#gaming)
      
      - [Apple Silicon 기반 게임 리소스](#gaming-on-apple-silicon-resources)
      - [MacOS 게임 모드](#macos-game-mode)
      - [게임 포팅 툴킷](#game-porting-toolkit)
      - [위스키 와인 래퍼](#위스키)
      - [MacOS용 CrossOver](#CrossOver-for-MacOS)
      - [Xbox Game Pass의 게임](#gaming-on-xbox-game-pass)
      - [온도/팬 관리(CPU 및 GPU)](#Manage-TempsFans-CPU-and-GPU)
      - [게임 주변기기](#게임 주변기기)
        * [게임용 마우스, 키보드 및 헤드셋](#RGB-장치)
        * [게임 컨트롤러](#game-controllers)
      - [OBS Studio 설정하기](#Setting-up-OBS-Studio)
          * [유용한 OBS Studio 타사 플러그인 및 테마](#useful-obs-studio-3rd-party-plugins-and-themes)
      - [불협화음](#Discord)
      - [트위치](#트위치)
      - [게임 스토어 및 런처](#Game-Stores--런처)
        * [애플 아케이드](#apple-arcade)
        * [플레이커버](#플레이커버)
        * [스팀](#스팀)
        * [히어로익 게임 런처](#heroic-game-launcher)
        * [에픽게임즈 스토어](#Epic-games-store)
        * [블리자드 Battle.net](#블리자드-배틀넷)
        * [오리진](#오리진)
        * [EA 플레이](#EA-Play)
        * [Ubisoft Connect](#Ubisoft-Connect)
        * [GOG 갤럭시 스토어](#GOG-갤럭시)
        * [잇치오 스토어](#잇치오스토어)
        * [FF XIV용 Mac의 XIV](#XIV-on-Mac)
      - [게임 스트리밍](#게임 스트리밍)
        * [클라우드 게임 스트리밍](#Cloud-Game-Streaming)
        * [로컬 게임 스트리밍](#로컬-게임-스트리밍)
      - [안드로이드 게임하기](#Android-Games)
      - [게임 에뮬레이터](#game-emulators)
        * [에뮬레이터 프런트엔드](#프런트엔드)
        * [닌텐도 게임큐브 & Wii](#Nintendo-GameCube--Wii)
        * [닌텐도 스위치](#Nintendo-Switch)
        * [닌텐도 64](#닌텐도-64)
        * [닌텐도 3DS](#닌텐도-3DS)
        * [슈퍼 닌텐도 엔터테인먼트 시스템(SNES)](#Super-Nintendo-Entertainment-System-SNES)
        * [Nintendo Entertainment System(NES)](#Nintendo-Entertainment-System)
        * [게임보이 어드밴스](#Game-Boy-Advance)
        * [TWO](#TWO)
        * [아타리](#아타리)
        * [세가 드림캐스트](#세가-드림캐스트)
        * [PlayStation Portable](#PlayStation-Portable)
        * [플레이스테이션 1](#PlayStation-1)
        * [플레이스테이션 2](#PlayStation-2)
        * [플레이스테이션 3](#PlayStation-3)
        * [엑스박스](#엑스박스)
        * [마메](#마메)
      - [성능 벤치마크](#performance-benchmarks)

2. [웨이퍼 레벨 멀티칩 패키징 기술](https://github.com/mikeroyal/Apple-Silicon-Guide#wafer-level-multi-chip-packaging-technology)
 
    - [InFO(Integrated Fan-Out) 웨이퍼 레벨 패키징](https://github.com/mikeroyal/Apple-Silicon-Guide#info-integrated-fan-out-wafer-level-packaging)
    - [기판 위 웨이퍼 칩(CoWoS)](https://github.com/mikeroyal/Apple-Silicon-Guide#chip-on-wafer-on-substrate-cowos)

3. [Xcode 개발](https://github.com/mikeroyal/Apple-Silicon-Guide#xcode-development)

4. [핵심 ML 개발](https://github.com/mikeroyal/Apple-Silicon-Guide#core-ml-development)

5. [금속개발](https://github.com/mikeroyal/Apple-Silicon-Guide#Metal-development)

6. [비주얼 스튜디오 스튜디오(VSCode) 개발](#vscode-development)

     - [개발자 생산성을 위한 VS 코드 확장](#VS-Code-Extensions-for-Developer-Productivity)

7. [언리얼 엔진 5 개발](#Unreal-Engine-5-Development)
 
8. [Unity 개발](#Unity-Development)
 
9. [블렌더 개발](#블렌더-개발)

10. [가상화](https://github.com/mikeroyal/Apple-Silicon-Guide#virtualization)

11. [도커](https://github.com/mikeroyal/Apple-Silicon-Guide#docker)

12. [쿠버네티스](https://github.com/mikeroyal/Apple-Silicon-Guide#kubernetes)

13. [앤서블](https://github.com/mikeroyal/Apple-Silicon-Guide#ansible)

14. [애플 실리콘에서 리눅스 실행하기](https://github.com/mikeroyal/Apple-Silicon-Guide#running-linux-on-the-apple-silicon)
     * [Apple Silicon에서의 Linux 가상화](#Linux-Virtualization-on-Apple-Silicon)
     * [아사히 리눅스 개발](#Asahi-Linux-개발)
     * [Fedora Linux 개발](#Fedora-Linux-Development)
     * [NixOS 리눅스 개발](#NixOS-Linux-개발)
     * [데비안 리눅스 개발](#Debian-Linux-개발)
     * [우분투 리눅스 개발](#Ubuntu-Linux-개발)

15. [Apple Silicon에서 Windows 10/11 실행](https://github.com/mikeroyal/Apple-Silicon-Guide#running-windows-1011-on-the-apple-silicon)

16. [게임 개발](https://github.com/mikeroyal/Apple-Silicon-Guide#game-development)

17. [전문 오디오/비디오 개발](https://github.com/mikeroyal/Apple-Silicon-Guide#professional-audiovideo-development)

18. [3D 그래픽 및 디자인](https://github.com/mikeroyal/Apple-Silicon-Guide#3d-graphics-and-design)

19. [신속한 개발](https://github.com/mikeroyal/Apple-Silicon-Guide#swift-development)

20. [Objective-C 개발](https://github.com/mikeroyal/Apple-Silicon-Guide#objective-c-development)

21. [C/C++ 개발](https://github.com/mikeroyal/Apple-Silicon-Guide#cc-development)

# 애플 실리콘 시작하기
[맨 위로 돌아가기](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

- [ARM인가요? Apple Silicon을 지원하는 것으로 보고된 앱](https://doesitarm.com)

- [기본 Apple 실리콘을 지원하는 앱 목록](https://isapplesiliconready.com/for/m1)

- [M1 호환 게임 마스터 목록 | AppleGamingWiki](https://www.applegamingwiki.com/wiki/M1_compatible_games_master_list)

- [M1 Parallels Windows 호환 게임 목록 | AppleGamingWiki](https://www.applegamingwiki.com/wiki/M1_Parallels_Windows_compatible_games_list)

- [게임 포팅 툴킷을 사용하여 게임을 Mac으로 가져오세요 ](https://developer.apple.com/videos/play/wwdc2023/10123/)

- [애플 실리콘 게임즈](https://applesilicongames.com/games)
  
- [포팅 키트 | Mac에 Windows 앱 설치](https://www.portingkit.com/)

- [Apple Silicon의 게임 및 앱(호환성 시트) 작성자: Thomas Schranz(@__tosh on Twitter) ](https://docs.google.com/spreadsheets/d/1er-NivvuIheDmIKBVRu3S_BzA_lZT5z3Z-CxQZ-uPVs)

- [Jeff Geerling의 Mac 개발 Ansible 플레이북](https://github.com/geerlingguy/mac-dev-playbook)

- [Apple Silicon Mac의 가상 머신에서 macOS 실행](https://developer.apple.com/documentation/virtualization/running_macos_in_a_virtual_machine_on_apple_silicon_macs?language=objc)

- [Rosetta를 사용하여 Linux VM에서 Intel 바이너리 실행](https://developer.apple.com/documentation/virtualization/running_intel_binaries_in_linux_vms_with_rosetta?language=objc)

- [Mac에서 macOS 가상화](https://developer.apple.com/documentation/virtualization/virtualize_macos_on_a_mac?language=objc)

- [Mac에서 Linux 가상화](https://developer.apple.com/documentation/virtualization/virtualize_linux_on_a_mac?language=objc)

- [Apple Silicon에서의 Core ML을 통한 안정적인 확산](https://machinelearning.apple.com/research/stable-diffusion-coreml-apple-silicon)

- [CrossOver® 맥](https://www.codeweavers.com/crossover)

- [DevToysMac](https://github.com/ObuchiYuki/DevToysMac)은 [Windows용 DevToys](https://github.com/veler/DevToys)의 Mac 앱 버전입니다.

- [asitop](https://github.com/tlkh/asitop)은 Apple Silicon용 성능 모니터링 CLI 도구입니다.

- [macOS 보안 및 개인 정보 보호 가이드](https://github.com/drduh/macOS-Security-and-Privacy-Guide#openbsm-audit)는 최신 버전의 macOS를 실행하는 최신 MacBook의 보안 및 개인 정보 보호를 향상하기 위한 기술 모음입니다.
 
- [macOS 보안 규정 준수 프로젝트](https://github.com/usnistgov/macos_security)는 보안 지침 생성에 대한 프로그래밍 방식의 접근 방식을 제공하기 위한 오픈 소스 노력입니다. 이 문서의 구성 설정은 NIST(National Institute of Standards and Technology) 특별 간행물(SP) 800-53, 정보 시스템 및 조직에 대한 보안 및 개인 정보 보호 제어, 개정 5에서 파생되었습니다.

[Apple Hypervisor](https://developer.apple.com/documentation/hypervisor)는 타사 커널 확장 없이 경량 하이퍼바이저 위에 가상화 솔루션을 구축하는 프레임워크입니다. 하이퍼바이저는 커널 확장(KEXT)을 작성하지 않고도 사용자 공간에서 가상화 기술과 상호 작용할 수 있도록 C API를 제공합니다. 결과적으로 이 프레임워크를 사용하여 만든 앱은 [Mac App Store](https://www.appstore.com/) 배포에 적합합니다.

[Apple A 시리즈](https://www.apple.com/)는 iPhone 및 iPad에 사용되는 Apple의 64비트 ARM 기반 SoC(시스템 온 칩)입니다. 하지만 WWDC 2020에서는 [Apple Silicon](https://developer.apple.com/documentation/apple_silicon)이 [Mac 노트북으로 전환](https://www.apple.com/newsroom/2020/06/apple-announces-mac-transition-to-apple-silicon/)할 것이라고 발표되었습니다.

## 애플 실리콘 칩

### A17 Pro
[맨 위로 돌아가기](#목차)

<p align="center">
 <img src="https://github.com/mikeroyal/Apple-Silicon-Guide/assets/45159366/23206325-fc71-4d3d-9203-798275475176">
</br>
</p>

**A17 Pro**는 새로운 3nm 아키텍처를 기반으로 제작되었습니다. **6-CPU 코어**를 갖추고 있으며 2성능 코어는 10% 더 빠르고 4효율 코어는 훨씬 더 효율적입니다. A16 Bionic(iPhone 15 및 15 Plus 모델)보다 20% 더 빠른 6코어 GPU와 함께 제공됩니다. Neural Engine은 A16 Bionic보다 거의 두 배 빠릅니다. Apple은 또한 A17 Pro GPU에 하드웨어 가속 레이 트레이싱을 추가했습니다. A17 Pro 칩은 iPhone 15 Pro 및 15 Pro Max에서 사용할 수 있습니다.

<p align="center">
 <img src="https://github.com/mikeroyal/Apple-Silicon-Guide/assets/45159366/ee123e8c-37f1-4f00-8322-4b2202233968">
</br>
Apple A17 Pro 아키텍처. 이미지 크레디트: 애플
</p>

### A16 Bionic
[맨 위로 돌아가기](#목차)

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/189012041-b2d83612-780f-4b57-97ef-c5042cdd7605.png">
<br />
</p>

**[A16 Bionic Chip](https://www.apple.com/iphone-14-pro/specs/)**은 **6코어 CPU에 2개의 성능 코어와 4개의 고효율 코어**를 갖춘 Apple 최초의 iPhone 14 Pro 및 Max용 4nm SoC입니다. **5코어 GPU** 및 **16코어 신경 엔진**과 함께 제공됩니다.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/189012045-f4f64b59-1b43-4b78-86aa-57b018e19040.png">
<br />
A16 Bionic 칩 아키텍처
</p>

### H2
[맨 위로 돌아가기](#목차)

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/193443812-2ea26b51-afa5-4843-a9ef-d595321f2d90.png">
<br />
</p>

**[H2 칩](https://www.apple.com/newsroom/2022/09/apple-announces-the-next-generation-of-airpods-pro/)**은 AiPods Pro용 Apple SoC로, 2배 더 강력해진 능동형 소음 제거, 맞춤형 공간 오디오, 전화 통화 중 더 나은 성능을 제공합니다.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/193443814-c360663c-799b-406c-a3e9-4f4ea57a6d7a.png">
<br />
</p>

AirPods Pro에 전원을 공급하는 H2 칩. 크레딧: [Apple](https://www.apple.com/newsroom/2022/09/apple-announces-the-next-generation-of-airpods-pro/)

### S9

[맨 위로 돌아가기](#목차)

<p align="center">
 <img src="https://github.com/mikeroyal/Apple-Silicon-Guide/assets/45159366/849aaf59-93f2-4ea1-bb9f-efbc646ad65d">
</br>
</p>

S9 칩은 Series 8보다 CPU에 60% 더 많은 트랜지스터를, GPU에 30% 더 많은 트랜지스터를 가지고 있습니다. Apple Watch Series 9의 25% 더 빨라진 음성 받아쓰기를 포함하여 Siri 요청에 대한 기기 내 처리를 강화하는 신경 엔진과 함께 제공됩니다.

<p align="center">
 <img src="https://github.com/mikeroyal/Apple-Silicon-Guide/assets/45159366/b1ea6161-ca66-48bc-9570-0b6a0fa756cd">
</br>
Apple Watch Series 9용 S9 칩. 이미지 출처: Apple
</p>


### U1
[맨 위로 돌아가기](#목차)

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/193443686-279114d1-789a-4b88-bd5b-1ba9b1f153e1.png">
<br />
</p>

[U1 초광대역(UWB) 칩](https://support.apple.com/en-us/HT212274)은 공간 인식을 위한 초광대역 기술이 적용된 Apple이 설계한 실리콘 칩입니다. U1 칩은 방향성 [AirDrop](https://support.apple.com/en-us/HT204144) 기능을 활성화합니다.

 * **UWB(초광대역)**는 다른 UWB 장착 장치 사이의 거리를 정확하게 찾아내고 측정하는 단거리 무선 기술입니다.
  
**U1 칩이 탑재된 Apple 기기**
 
 * [애플 에어태그](https://www.apple.com/airtag/)
 * 아이폰 11
 * 아이폰 11 프로
 * 아이폰 11 프로 맥스
 * 아이폰 12미니
 * 아이폰 12
 * 아이폰 12 프로
 * 아이폰 12 프로 맥스
 * 아이폰 13 미니
 * 아이폰 13
 * 아이폰 13 프로
 * 아이폰 13 프로 맥스
 * 아이폰 14
 * 아이폰 14 플러스
 * 아이폰 14 프로
 * 아이폰 14 프로 맥스
 * 애플워치 시리즈 6
 * 애플워치 시리즈 7
 * 애플워치 시리즈 8
 * 애플워치SE(2세대)
 * 애플워치 울트라
 * 애플 홈팟 미니

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/193443690-4bd78390-fe78-4053-8cf0-1be757486f08.png">
<br />
U1 칩 다이
</p>

### R1

[맨 위로 돌아가기](#목차)

<p align="center">
<img src="https://github.com/mikeroyal/Apple-Silicon-Guide/assets/45159366/eacf3128-cc30-4cf8-9d77-12e5bda15e48">
<br />
</p>

**R1 칩**은 실시간 센서 처리 전용으로, Vision Pro 헤드셋의 카메라 12개, 센서 5개(LIDAR 센서 포함) 및 마이크 6개로부터 입력을 받습니다.

<p align="center">
<img src="https://github.com/mikeroyal/Apple-Silicon-Guide/assets/45159366/425ff971-6fa4-4ba9-a594-932367662b23)">
<br />
Vision Pro 헤드셋의 R1 및 M2 칩
</p>


### M1
[맨 위로 돌아가기](#목차)

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/168941790-7886c405-ec76-4900-a405-ab29868485cb.png">
<br />
</p>

[Apple M1 칩](https://www.apple.com/mac/m1/)은 ARM Mac 제품용으로 특별히 설계된 Apple의 첫 번째 SoC 칩으로, 놀라운 성능(8코어 CPU 및 8코어 GPU), 맞춤형 기술 및 뛰어난 전력 효율성을 제공합니다. 이제 M1 칩은 [M1이 포함된 Macbook Pro 13](https://www.apple.com/macbook-pro-13/), [M1이 포함된 Macbook Air 13](https://www.apple.com/macbook-air/), [M1이 포함된 Mac Mini](https://www.apple.com/mac-mini/), [iPad Pro](https://www.apple.com/ipad-pro/) 및 [iPad Air](https://www.apple.com/ipad-air/)에서 사용할 수 있습니다.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/138614045-f20a4858-0460-49c1-8d80-0ae815e8bc93.png">
<br />
</p>

**M1 칩. 출처: [Apple](https://www.apple.com/newsroom/2020/11/apple-unleashes-m1/)**

### M1 Pro
[맨 위로 돌아가기](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/168941797-887664ba-8184-4849-8379-07113032ef40.png">
<br />
</p>

[Apple M1 Pro 칩](https://www.apple.com/newsroom/2021/10/introducing-m1-pro-and-m1-max-the-most-powerful-chips-apple-has-ever-built/)은 [MacBook Pro 14"](https://www.apple.com/shop/buy-mac/macbook-pro/14-inch)의 전문가용 시스템용으로 설계된 8 또는 10코어 SoC(시스템 온 칩) 아키텍처입니다. 이 칩은 빠른 통합 메모리, 업계 최고의 와트당 성능, 놀라운 전력 효율성과 함께 향상된 메모리 대역폭 및 용량을 제공합니다. M1 Pro는 최대 32GB의 통합 메모리와 최대 200GB/s의 메모리 대역폭을 제공합니다. GPU(14코어 또는 16코어 옵션).

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/138614048-949a4fa8-71f8-4a2e-97fe-f8db874b3d13.png">
<br />
</p>

**M1 Pro 칩. 출처: [Apple](https://www.apple.com/newsroom/2021/10/introducing-m1-pro-and-m1-max-the-most-powerful-chips-apple-has-ever-built/)**

### M1 맥스
[맨 위로 돌아가기](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/168941803-e81f20f6-0bda-4a50-9f2c-7f149b67fbeb.png">
<br />
</p>

[Apple M1 Max 칩](https://www.apple.com/newsroom/2021/10/introducing-m1-pro-and-m1-max-the-most-powerful-chips-apple-has-ever-built/)은 [MacBook Pro 16"](https://www.apple.com/shop/buy-mac/macbook-pro/16-inch)의 전문가용 시스템용으로 설계된 10코어 SoC(시스템 온 칩) 아키텍처입니다. 이 칩은 빠른 통합 메모리, 업계 최고의 와트당 성능, 놀라운 전력 효율성과 함께 증가된 메모리 대역폭 및 용량을 특징으로 합니다. M1 Pro는 최대 64GB의 통합 메모리 및 GPU를 지원하여 최대 400GB/s의 메모리 대역폭을 제공합니다. (16코어 또는 32코어 옵션)

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/138614049-eff86f41-cb0c-41c8-8a93-c9590b711227.png">
<br />
</p>

**M1 Max 칩. 출처: [Apple](https://www.apple.com/newsroom/2021/10/introducing-m1-pro-and-m1-max-the-most-powerful-chips-apple-has-ever-built/)**

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/138614054-fc5dfb69-fa4e-4a1d-a39d-4145466a6a70.png">
<br />
</p>

**M1/ M1 Pro/ M1 Max CPU 성능. 출처: [Apple](https://www.apple.com/newsroom/2021/10/introducing-m1-pro-and-m1-max-the-most-powerful-chips-apple-has-ever-built/)**

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/138614056-784f775d-2b4d-4273-99ab-6a1025157704.png">
<br />
</p>

**M1/ M1 Pro/ M1 Max GPU 성능. 출처: [Apple](https://www.apple.com/newsroom/2021/10/introducing-m1-pro-and-m1-max-the-most-powerful-chips-apple-has-ever-built/)**

### M1 Ultra
[맨 위로 돌아가기](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/168941808-d00d49e6-d6d5-4301-b4ac-7a8d4f2552de.png">
<br />
</p>

[Apple M1 Ultra Chip](https://www.apple.com/newsroom/2022/03/apple-unveils-m1-ultra-the-worlds-most-powerful-chip-for-a-personal-computer/)은 M1 시리즈 라인업에서 Apple의 가장 강력한 실리콘 칩입니다. M1 Ultra는 [Apple의 UltraFusion Architecture](https://github.com/mikeroyal/Apple-Silicon-Guide/files/8248834/US20220013504A1.pdf) 패키징을 사용하여 함께 연결된 **2개의 M1 Max 칩**으로 구성됩니다. 즉, M1 Ultra는 **20코어 CPU, 64코어 GPU(800GB/s 메모리 대역폭) 및 32코어 Neural Engine**에서 액세스할 수 있는 최대 128GB의 고대역폭, 저지연 통합 메모리로 구성할 수 있습니다. M1 Ultra는 현재 Apple의 **[Mac Studio](https://www.apple.com/shop/buy-mac/mac-studio)**에서 사용할 수 있습니다.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/157358150-c0e1b60d-787d-4e36-ba12-b4d4c5ea8bd2.png">
<br />
</p>

**M1 Ultra 칩. 출처: [Apple](https://www.apple.com/newsroom/2022/03/apple-unveils-m1-ultra-the-worlds-most-powerful-chip-for-a-personal-computer/)**

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/157357074-8767aba7-a5ca-43a4-b44f-b22bf38c3e57.png">
<br />
</p>

**M1 Ultra CPU 성능. 출처: [Apple](https://www.apple.com/newsroom/2022/03/apple-unveils-m1-ultra-the-worlds-most-powerful-chip-for-a-personal-computer/)**

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/157357079-029db757-9d39-41c7-88d8-bed769b14ec8.png">
<br />
</p>

**M1 Ultra GPU 성능. 출처: [Apple](https://www.apple.com/newsroom/2022/03/apple-unveils-m1-ultra-the-worlds-most-powerful-chip-for-a-personal-computer/)**

###M2
[맨 위로 돌아가기](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/210165269-01041deb-4178-40b4-85d7-f84d14ed33c5.png">
<br />
</p>

[Apple M2 칩](https://www.apple.com/newsroom/)은 기본 [M1 칩](https://github.com/mikeroyal/Apple-Silicon-Guide#M1)**보다 **18% 더 빠른 CPU, 35% 더 빠른 GPU, 40% 더 빠른 신경 엔진을 갖추고 있습니다. **8코어 CPU, 10코어 GPU(100GB/s 메모리 대역폭) 및 16코어 Neural Engine**에서 액세스할 수 있는 최대 **24GB**의 고대역폭, 저지연 통합 메모리로 구성할 수 있습니다. M2는 Apple의 새로운 **[MacBook Air](https://www.apple.com/macbook-air/)**, 이전 디자인의 **[MacBook Pro 13"](https://www.apple.com/macbook-pro/)** 및 **[M2가 탑재된 iPad Pro ](https://www.apple.com/ipad-pro/)**에서 사용할 수 있습니다.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/172230405-e6e015e7-5271-43ef-b097-87ca374db5f2.png">
<br />
</p>

**M2. 출처: [Apple](https://www.apple.com/newsroom/)**

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/172234868-ea4e4975-fb96-47da-a0cc-6bb5d8fba5af.png">
<br />
</p>

**M2 CPU 성능. 출처: [Apple](https://www.apple.com/newsroom/)**

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/172230446-6fd70598-8dd9-4e5a-b92d-2e1e4ac92791.png">
<br />
</p>

**M2 GPU 성능. 출처: [Apple](https://www.apple.com/newsroom)**

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/172230507-c469930a-7a4e-4289-bb39-d6dddf7ecdcb.png">
<br />
</p>

**M1 대 M2. 출처: [Apple](https://www.apple.com/newsroom)**

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/172230463-b1578f4a-6cce-4738-9835-28d0ac7529ef.png">
<br />
</p>

**M2 게이밍 성능. 출처: [Apple](https://www.apple.com/newsroom)**

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/172230480-80b23096-4db5-467c-97b2-dc52427d49f7.png">
<br />
</p>

**M2 이미지 처리 성능. 출처: [Apple](https://www.apple.com/newsroom)**

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/172230485-094fc112-efbd-4b21-90db-d66ac70bafbb.png">
<br />
</p>

**M2 비디오 편집 성능. 출처: [Apple](https://www.apple.com/newsroom)**

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/172230490-c8c9b8de-54f6-46a8-9f0c-e8375cd9dbea.png">
<br />
</p>

**M2 이미지 필터 및 효과 성능. 출처: [Apple](https://www.apple.com/newsroom)**

### M2 Pro

[맨 위로 돌아가기](#목차)

 <p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/216295418-13381e71-6839-42e1-99ae-b22552374348.png">
</p>

[Apple M2 Pro 칩](https://www.apple.com/newsroom/)은 기본 [M1 Pro 칩](https://github.com/mikeroyal/Apple-Silicon-Guide#M1-Pro)**보다 **20% 더 빠른 CPU, 30% 더 빠른 GPU, 40% 더 빠른 신경 엔진을 갖추고 있습니다. **12코어 CPU, 19코어 GPU(200GB/s 메모리 대역폭) 및 16코어 Neural Engine**에서 액세스할 수 있는 최대 **32GB**의 고대역폭, 저지연 통합 메모리로 구성할 수 있습니다. M2 Pro는 Apple의 **[MacBook Pro 14"](https://www.apple.com/macbook-pro-14-and-16/)**, **[MacBook Pro 16"](https://www.apple.com/macbook-pro-14-and-16/)** 및 **[Mac mini](https://www.apple.com/mac-mini/)**에서 사용할 수 있습니다.

  <p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/213024040-d9389326-f84d-4702-8056-afe6046dd5fe.png">
</p>

M2 Pro 칩. 이미지 출처: [Apple](https://www.apple.com/newsroom/)

### M2 맥스

[맨 위로 돌아가기](#목차)

 <p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/216295429-7cb0f4ce-3b83-4c61-b9da-a937eceb2b27.png">
</p>

[Apple M2 Max 칩](https://www.apple.com/newsroom/)은 현재 Apple의 M2 시리즈 중 가장 강력한 실리콘 칩입니다. M2는 기본 [M1 Max 칩](https://github.com/mikeroyal/Apple-Silicon-Guide#M1-Max)**보다 **20% 더 빠른 CPU, 30% 더 빠른 GPU, 40% 더 빠른 신경 엔진을 갖추고 있습니다. **12코어 CPU, 38코어 GPU(400GB/s 메모리 대역폭) 및 16코어 Neural Engine**에서 액세스할 수 있는 최대 **96GB**의 고대역폭, 저지연 통합 메모리로 구성할 수 있습니다. M2 Max는 Apple의 **[MacBook Pro 14"](https://www.apple.com/macbook-pro-14-and-16/)**, **[MacBook Pro 16"](https://www.apple.com/macbook-pro-14-and-16/)** 및 **[Mac mini](https://www.apple.com/mac-mini/)**에서 사용할 수 있습니다.


  <p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/213024048-db42c02f-1379-497f-b96a-7446b31b5f69.png">
</p>

M2 맥스 칩. 이미지 출처: [Apple](https://www.apple.com/newsroom/)


### M2 Ultra

[맨 위로 돌아가기](#목차)

 <p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/210165270-8609f92a-8765-4b19-9956-cd04b0593159.png">
</p>

M2 Ultra는 [Apple의 UltraFusion 아키텍처](https://github.com/mikeroyal/Apple-Silicon-Guide/files/8248834/US20220013504A1.pdf) 패키징을 사용하여 서로 연결된 **2개의 M2 Max 칩**으로 구성됩니다.

M2 Ultra는 **24코어 CPU, 76코어 GPU(800GB/s 메모리 대역폭) 및 32코어 Neural Engine**에서 액세스할 수 있는 최대 **192GB**의 고대역폭, 저지연 통합 메모리로 구성할 수 있습니다. M2 Ultra는 [Mac Studio](https://www.apple.com/mac-studio/) 및 [Mac Pro](https://www.apple.com/mac-pro/)에서 사용할 수 있습니다.

###M3‌

[맨 위로 돌아가기](#목차)

<p align="center">
 <img src="https://github.com/mikeroyal/Apple-Silicon-Guide/assets/45159366/81a6ba78-0096-416b-9976-677a6c7e7778">
</br>
</p>

**Apple M3 칩**은 기본 [M1 칩](https://github.com/mikeroyal/Apple-Silicon-Guide#M1)**보다 **35% 더 빠른 CPU, 65% 더 빠른 GPU, 40% 더 빠른 신경 엔진을 갖추고 있습니다. **8코어 CPU(4개의 고성능 및 4개의 에너지 효율), 10코어 GPU(100GB/s 메모리 대역폭) 및 16코어 Neural Engine**에서 액세스할 수 있는 최대 **24GB**의 고대역폭, 저지연 통합 메모리로 구성할 수 있습니다. [MacBook Pro 14”](https://www.apple.com/shop/buy-mac/macbook-pro/14-inch-m3) 및 [iMac](https://www.apple.com/shop/buy-mac/imac)에서 사용 가능합니다.

<p align="center">
 <img src="https://github.com/mikeroyal/Apple-Silicon-Guide/assets/45159366/05f0c5e5-76f4-488d-995f-468f81e980e6">
</br>
M3 칩 아키텍처. 이미지 크레디트: 애플
</p>

<p align="center">
 <img src="https://github.com/mikeroyal/Apple-Silicon-Guide/assets/45159366/0fdff7fa-348b-4716-b615-12c0b848b337">
</br>
M3 칩 제품군 효율 코어 성능. 이미지 크레디트: 애플
</p>

<p align="center">
 <img src="https://github.com/mikeroyal/Apple-Silicon-Guide/assets/45159366/8030518f-2e79-4418-b66e-970cd1c74cd4">
</br>
M3 칩 제품군 신경 엔진 성능. 이미지 크레디트: 애플
</p>

### M3 Pro

[맨 위로 돌아가기](#목차)

<p align="center">
 <img src="https://github.com/mikeroyal/Apple-Silicon-Guide/assets/45159366/6f0bcd5b-38f4-4243-bbb3-7ec4191758bb">
</br>
</p>

**Apple M3 Pro 칩**은 기본 [M1 Pro 칩](https://github.com/mikeroyal/Apple-Silicon-Guide#M1-Pro)**보다 **30% 더 빠른 CPU, 40% 더 빠른 GPU, 40% 더 빠른 신경 엔진을 갖추고 있습니다. **12코어 CPU(고성능 6개, 에너지 효율 6개), 18코어 GPU(150GB/s 메모리 대역폭) 및 16코어 Neural Engine**에서 액세스할 수 있는 최대 **36GB**의 고대역폭, 저지연 통합 메모리로 구성할 수 있습니다. [MacBook Pro 14”](https://www.apple.com/shop/buy-mac/macbook-pro/14-inch-m3-pro) 및 [MacBook Pro 16”](https://www.apple.com/shop/buy-mac/macbook-pro/16-inch-m3-pro)에서 사용 가능합니다.

<p align="center">
 <img src="https://github.com/mikeroyal/Apple-Silicon-Guide/assets/45159366/d588605b-c665-4949-aa1c-ee721d68b0d4">
</br>
M3 Pro 칩 아키텍처. 이미지 크레디트: 애플
</p>

### M3 맥스

[맨 위로 돌아가기](#목차)

<p align="center">
 <img src="https://github.com/mikeroyal/Apple-Silicon-Guide/assets/45159366/30dd49e5-9f86-4b29-9b4f-c89e13ef8ee3">
</br>
</p>

**Apple M3 Max 칩**은 기본 [M1 Max 칩](https://github.com/mikeroyal/Apple-Silicon-Guide#M1-Max)**보다 **80% 더 빠른 CPU, 50% 더 빠른 GPU, 40% 더 빠른 신경 엔진을 갖추고 있습니다. **16코어 CPU(고성능 12개, 에너지 효율 4개), 40코어 GPU(400GB/s 메모리 대역폭) 및 16코어 Neural Engine**에서 액세스할 수 있는 최대 **128GB**의 고대역폭, 저지연 통합 메모리로 구성할 수 있습니다. [MacBook Pro 14”](https://www.apple.com/shop/buy-mac/macbook-pro/14-inch-m3-max) 및 [MacBook Pro 16”](https://www.apple.com/shop/buy-mac/macbook-pro/16-inch-m3-max)에서 사용 가능합니다.

<p align="center">
 <img src="https://github.com/mikeroyal/Apple-Silicon-Guide/assets/45159366/5410b9e9-a150-4425-b285-e91222c06ca5">
</br>
M3 Max 칩 아키텍처. 이미지 크레디트: 애플
</p>

### M3 Ultra

[맨 위로 돌아가기](#목차)

<p align="center">
 <img src="https://github.com/mikeroyal/Apple-Silicon-Guide/assets/45159366/8e8f62d9-31f7-4852-a5af-c45c8847c037">
</br>
</p>

**Apple M3 Ultra Chip**은 Apple의 M3 시리즈 라인업에서 가장 강력한 실리콘 칩입니다. M3 Ultra는 [Apple의 UltraFusion Architecture](https://github.com/mikeroyal/Apple-Silicon-Guide/files/8248834/US20220013504A1.pdf) 패키징을 사용하여 서로 연결된 **2개의 M3 Max 칩**으로 구성됩니다. 즉, M1 Ultra는 **32코어 CPU(24코어, 8코어 에너지 효율), 80코어 GPU(800GB/s 메모리 대역폭) 및 32코어 Neural Engine**에서 액세스할 수 있는 최대 256GB의 고대역폭, 저지연 통합 메모리로 구성할 수 있습니다.

<p align="center">
 <img src="https://github.com/mikeroyal/Apple-Silicon-Guide/assets/45159366/0e80d38b-9619-482e-b9af-a60e9e51a56a">
</br>
M3 Ultra 칩 아키텍처.
</p>


## Apple AR 및 Vision Pro 헤드셋

[맨 위로 돌아가기](#목차)

**알아두어야 할 중요한 용어**

 * [증강현실(AR)](https://en.wikipedia.org/wiki/Augmented_reality)은 컴퓨터가 생성한 지각 정보를 통해 현실 세계에 존재하는 사물이 강화되는 현실 세계 환경의 대화형 경험입니다.
 * [가상현실(VR)](https://en.wikipedia.org/wiki/Virtual_reality)은 현실 세계와 유사할 수도 있고 전혀 다를 수도 있는 시뮬레이션 경험입니다. 가상 현실의 응용 분야에는 엔터테인먼트(비디오 게임), 교육(의료 또는 군사 훈련) 및 비즈니스(가상 회의)가 포함됩니다.
 * [혼합 현실(MR)](https://en.wikipedia.org/wiki/Mixed_reality)은 실제 세계와 가상 세계를 병합하여 물리적 객체와 디지털 객체가 공존하고 실시간으로 상호 작용하는 새로운 환경과 시각화를 생성하는 것입니다.
 * [확장현실(XR)](https://en.wikipedia.org/wiki/Extended_reality)은 컴퓨터 기술과 웨어러블 기기에 의해 생성되는 현실과 가상이 결합된 모든 환경과 인간-기계 상호작용을 지칭하는 개념입니다. 증강현실(AR), 혼합현실(MR), 가상현실(VR) 등이 포함된다.

<p align="center">
 <img src="https://github.com/mikeroyal/Apple-Silicon-Guide/assets/45159366/1eb8474d-ed6b-4c57-a88c-6879db9df78b">
  <br />
 비전 프로 헤드셋. 이미지 크레디트: 애플
</p>

<p align="center">
 <img src="https://github.com/mikeroyal/Apple-Silicon-Guide/assets/45159366/4fa96b25-effe-4dc2-a5c9-3c43bcdda285)">
  <br />
 배터리 팩이 포함된 Vision Pro 헤드셋. 이미지 크레디트: 애플
</p>

<p align="center">
<img src="https://github.com/mikeroyal/Apple-Silicon-Guide/assets/45159366/425ff971-6fa4-4ba9-a594-932367662b23)">
<br />
Vision Pro 헤드셋의 R1 및 M2 칩. 이미지 크레디트: 애플
</p>

<p align="center">
 <img src="https://github.com/mikeroyal/Apple-Silicon-Guide/assets/45159366/e1f5d708-87a8-4b45-bfc9-03860cb6ebea">
  <br />
 VisionOS. 이미지 크레디트: 애플
</p>

* [visionOS](https://developer.apple.com/visionos/)는 Apple의 Silicon M2 및 R1 칩으로 구동되는 곧 출시될 AR/VR(증강 현실/가상 현실) 헤드셋을 위한 Apple의 iOS와 유사한 운영 체제입니다. **[메시지](https://support.apple.com/messages), [FaceTime](https://support.apple.com/facetime), [지도](https://www.apple.com/maps/), [Apple Arcade](https://www.apple.com/apple-arcade/)**의 AR/VR 게임과 같은 핵심 Apple 앱의 혼합 현실 버전을 포함하는 앱이 있는 App Store를 갖게 됩니다. 사용자 경험의 중심이 될 수 있는 [Memojis](https://apps.apple.com/us/story/id1445637997) 및 [SharePlay](https://support.apple.com/guide/iphone/use-shareplay-to-watch-and-listen-together-iphb657eb791/ios)와 같은 기능과 함께.
 
 **visionOS 리소스**
 
 * [visionOS SDK](https://developer.apple.com/visionos/)
 * [visionOS에 대해 자세히 알아보기](https://developer.apple.com/visionos/learn/)
 * [Apple Vision Pro 개발자 키트](https://developer.apple.com/visionos/developer-kit/)
 * [Apple Vision Pro 개발자 연구소](https://developer.apple.com/visionos/labs/)
 * [공간 컴퓨팅용 앱 구축 시작하기](https://developer.apple.com/videos/play/wwdc2023/10260/)
 * [Apple Vision Pro 호환성 평가](https://developer.apple.com/visionos/compatibility-evaluations/)
 * [기존 앱이 VisionOS와 호환되는지 확인 중](https://developer.apple.com/documentation/visionOS/checking-whether-your-app-is-compatible-with-visionos/)
 * [기존 앱을 VisionOS와 호환되게 만들기](https://developer.apple.com/documentation/visionos/making-your-app-compatible-with-visionos/)
 * [기존 앱을 VisionOS로 가져오기](https://developer.apple.com/documentation/visionos/bringing-your-app-to-visionos/)
 * [visionOS 시뮬레이터에서 앱과 상호작용](https://developer.apple.com/documentation/visionOS/interacting-with-your-app-in-the-visionos-simulator/)
 * [실행 중인 앱의 버그 진단 및 해결](https://developer.apple.com/documentation/xcode/diagnosing-and-resolving-bugs-in-your-running-app/)
 * [시뮬레이터 또는 기기에서 앱 실행](https://developer.apple.com/documentation/xcode/running-your-app-in-simulator-or-on-a-device/)
 * [실행 중인 앱의 버그 진단 및 해결](https://developer.apple.com/documentation/xcode/diagnosing-and-resolving-bugs-in-your-running-app/)
 * [앱 성능 개선](https://developer.apple.com/documentation/metrickit/improving_your_app_s_performance/)
 * [Metal 앱 성능 분석](https://developer.apple.com/documentation/xcode/analyzing-the-performance-of-your-metal-app/)
 * [UIRequiredDeviceCapability 설정](https://developer.apple.com/documentation/bundleresources/information_property_list/uirequireddevicecapabilities/)
 * [게임 컨트롤러(GCSupportsControllerUserInteraction)](https://developer.apple.com/design/human-interface-guidelines/game-controllers/)
 * [Vision Pro 휴먼 인터페이스 지침](https://developer.apple.com/design/human-interface-guidelines/designing-for-visionos/)
 * [첫 번째 VisionOS 앱 만들기](https://developer.apple.com/documentation/visionos/creating-your-first-visionos-app/)
 * [앱에 3D 콘텐츠 추가](https://developer.apple.com/documentation/visionos/adding-3d-content-to-your-app)
 * [개인정보 보호 및 사용자 기본 설정에 대한 모범 사례 채택](https://developer.apple.com/documentation/visionos/adopting-best-practices-for-privacy)
 * [visionOS 앱의 접근성 지원 개선](https://developer.apple.com/documentation/visionos/improving-accessibility-support-in-your-app)
 * [visionOS에 대한 Unity 지원: 알아야 할 사항](https://blog.unity.com/engine-platform/unity-support-for-visionos)
 * [몰입형 Unity 앱 만들기](https://developer.apple.com/videos/play/wwdc2023/10088/)
 * [Unity VR 앱을 완전히 몰입할 수 있는 공간으로 가져오세요](https://developer.apple.com/videos/play/wwdc2023/10093/)

 

 **Apple Vision Pro 헤드셋 사양:**
   
   * M2 칩 및 **R1 칩(Vision Pro 헤드셋의 카메라 12개 및 센서 5개에 대한 실시간 센서 처리 전용)**으로 구동됩니다.
   * 고해상도 4K 마이크로 OLED 디스플레이.
   * 디스플레이 새로 고침 빈도는 [90Hz이며 24fps 비디오를 위한 특수 96Hz 모드를 지원합니다](https://developer.apple.com/videos/play/wwdc2023/10071/?time=143).
   * 디스플레이 픽셀 크기는 3000ppi~4000ppi입니다.
   * 디스플레이는 5,000니트의 밝기를 제공합니다.
   * 색재현율은 DCI > 97% DCI로 표시됩니다.
   * 96W USB-C 전원 어댑터.
   * 데이터 전송을 위한 USB-C 포트.
   * [배터리 팩](https://www.amazon.com/Apple-MJWY3AM-A-MagSafe-Battery/dp/B099BWY7WT)을 부착하기 위한 독자적인 마그네틱 포트(MagSafe)입니다.
   * 예상 배터리 수명은 **팩당 약 2시간**입니다.
   * 움직임을 추적하고, 환경을 매핑하고, 시각적 경험을 투영하기 위한 12개의 광학 카메라와 5개의 센서.
   * Wi-Fi 6E는 2.4GHz 및 5GHz 대역에 6GHz 스펙트럼을 추가하여 대역폭을 늘리고 장치 간섭을 줄입니다.

OLEDoS(OLED on Silicon)는 일반적으로 대각선 길이가 1인치 미만이고 AR/VR 장치 디스플레이의 3000ppi~4000ppi 해상도 기준을 충족하는 디스플레이 패널입니다. 기존 OLED 디스플레이는 유리 기판을 기반으로 LTPS(Low-Temperature-Poly-Silicon) 또는 Oxide TFT를 사용합니다. OLEDoS는 실리콘 웨이퍼 기반 CMOS 기판을 사용합니다. 실리콘 기판을 사용하면 반도체 공정에서 흔히 사용되는 초미세 회로 구조를 재현할 수 있고, 그 위에 유기물을 증착하면 초고해상도 OLED를 만들 수 있다.

 **LG 및 Sony OLEDoS 디스플레이 사양:**
 
   * 고해상도 4K 마이크로 OLED 디스플레이.
   * 디스플레이 픽셀 크기는 3000ppi~4000ppi입니다.
   * 디스플레이는 5,000니트의 밝기를 제공합니다.
   * 색재현율은 DCI > 97% DCI로 표시됩니다.

### LG OLEDOS

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/194017317-b1dbda21-5935-47ef-8843-137cc5540b60.png">
  <br />
 OLEDoS: 초고해상도를 위한 솔루션
</p>

크레딧: [LG](https://www.lgdisplay.com/eng/technology/oled)

### 소니 OLEDoS

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/194017320-f7631398-a661-401d-9e6f-77d061c8d303.png">
  <br />
  OLED 및 OLEDoS 사양
</p>

크레딧: [Sony](https://www.sony.com/en/SonyInfo/research/technologies/OLED_microdisplay/)

### 도구 및 프레임워크

 * [Reality Composer Pro](https://developer.apple.com/videos/play/wwdc2023/10083/)는 Reality Composer Pro를 사용하여 3D 콘텐츠를 쉽게 구성, 편집 및 미리 보는 방법을 알아볼 수 있는 도구입니다. 새 프로젝트를 설정하고, 장면을 구성하고, 입자 방출기와 오디오를 추가하고, 장치에서 콘텐츠를 미리 보는 등 이 개발자 도구를 탐색해 보세요.
 * [Reality Composer](https://developer.apple.com/augmented-reality/tools/)는 이전에 3D 경험이 없어도 대화형 증강 현실 경험을 쉽게 만들 수 있게 해주는 강력한 도구입니다. Reality Converter는 기존 3D 모델을 [USDZ](https://graphics.pixar.com/usd/files/USDZFileFormatSpecification.pdf)로 빠르게 변환하므로 당사 도구와 모든 AR 지원 iPhone 및 iPad 기기에서 원활하게 작동합니다.
 * [Apple Vision](https://developer.apple.com/documentation/vision)은 얼굴 및 얼굴 랜드마크 감지, 텍스트 감지, 바코드 인식, 이미지 등록, 일반 특징 추적을 수행하는 프레임워크입니다. Vision을 사용하면 분류 또는 객체 감지와 같은 작업에 맞춤형 Core ML 모델을 사용할 수도 있습니다.
 * [Metal 셰이더 변환기](https://developer.apple.com/metal/shader-converter/)는 LLVM IR 바이트코드의 셰이더 중간 표현을 Metal에 로드하기에 적합한 바이트코드로 변환하는 도구입니다. 라이브러리와 독립 실행형 실행 파일로 제공됩니다. 라이브러리 인터페이스를 통해 노출된 모든 기능은 독립 실행형 실행 파일을 통해 사용할 수 있습니다.
 * [USDZ](https://graphics.pixar.com/usd/release/spec_usdz.html)는 Apple과 Pixar Animation Studios에서 개발한 USDZ Universal 형식으로 저장된 3D 장면이나 개체가 포함된 파일 형식입니다. 3D 형상 및 음영 데이터가 포함된 범용 장면 설명(.USD, USDA 또는 USDC) 파일을 저장하는 압축 및 암호화되지 않은 .ZIP 아카이브입니다. USDZ 파일에는 .PNG 및 .JPEG 이미지 텍스처와 3D 개체 또는 장면에 사용되는 .M4A, .MP3 또는 .WAV 오디오 파일도 포함될 수 있습니다.
 * [ARKit](https://developer.apple.com/augmented-reality/arkit/)은 개발자가 Apple에서 개발한 iOS용 증강 현실 앱을 구축할 수 있도록 지원하는 소프트웨어 개발 도구 세트입니다. 최신 버전 ARKit 3.5는 iPad Pro(2020)의 새로운 LiDAR 스캐너와 깊이 감지 시스템을 활용하여 향상된 장면 이해 및 객체 폐색을 위해 장면 기하학을 사용하는 차세대 AR 앱을 지원합니다.
 * [RealityKit](https://developer.apple.com/documentation/realitykit)은 ARKit 프레임워크에서 제공하는 정보로 고성능 3D 시뮬레이션 및 렌더링을 구현하여 가상 객체를 현실 세계에 원활하게 통합하는 프레임워크입니다.
 * [RealityUI](https://github.com/maxxfrazer/RealityUI)는 RealityKit에서 렌더링된 증강 현실 또는 가상 현실 장면에서 친숙한 UI 요소 및 애니메이션을 생성하기 위한 Swift 패키지입니다.
 * [SceneKit](https://developer.apple.com/scenekit/)은 iOS 앱에서 3D 애니메이션 장면과 효과를 만드는 데 도움이 되는 고급 3D 그래픽 프레임워크입니다.
 * [SwiftUI](https://developer.apple.com/documentation/swiftui)는 앱의 사용자 인터페이스를 선언하기 위한 보기, 컨트롤 및 레이아웃 구조를 제공하는 사용자 인터페이스 툴킷입니다. SwiftUI 프레임워크는 탭, 제스처 및 기타 유형의 입력을 애플리케이션에 전달하기 위한 이벤트 핸들러를 제공합니다.
 * [UIKit](https://developer.apple.com/documentation/uikit)은 iOS 또는 tvOS 앱에 필요한 인프라를 제공하는 프레임워크입니다. 이는 인터페이스 구현을 위한 창 및 보기 아키텍처, 멀티 터치 및 기타 유형의 입력을 앱에 제공하기 위한 이벤트 처리 인프라, 사용자, 시스템 및 앱 간의 상호 작용을 관리하는 데 필요한 기본 실행 루프를 제공합니다.
 * [SpriteKit](https://developer.apple.com/documentation/spritekit)은 모양, 입자, 텍스트, 이미지 및 비디오를 2차원으로 그리기 위한 범용 프레임워크입니다. Metal을 활용하여 고성능 렌더링을 달성하는 동시에 간단한 프로그래밍 인터페이스를 제공하여 게임 및 기타 그래픽 집약적인 앱을 쉽게 만들 수 있습니다.
 * [MetalFX](https://developer.apple.com/videos/play/wwdc2022/10103/)는 Metal 애플리케이션을 위한 플랫폼 최적화 그래픽 효과를 제공하는 새로운 API입니다. MetalFX 업스케일링을 사용하면 이제 응용 프로그램에서 렌더링 품질 저하 없이 렌더링 시간을 단축하면서 더 낮은 해상도로 프레임을 렌더링할 수 있습니다. 또한 상당한 성능 향상을 제공하는 공간적 업스케일링과 최고 품질의 렌더링을 제공하는 시간적 AA 및 업스케일링이라는 두 가지 효과를 언제, 어떻게 사용하는지 보여드리겠습니다.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/172254747-9308be59-4d79-4677-a5ec-cf40f5762cf7.png">
  <br />
 MetalFX 렌더링. 이미지 크레디트: 애플
</p>

 * [Apple Core Animation Framework](https://developer.apple.com/documentation/quartzcore)는 CPU에 부담을 주거나 앱 속도를 저하시키지 않으면서 높은 프레임 속도와 부드러운 애니메이션을 제공하는 그래픽 렌더링 및 애니메이션 인프라입니다.
 * [Apple Core Graphics Framework](https://developer.apple.com/documentation/coregraphics)는 Quartz 고급 드로잉 엔진을 기반으로 한 프레임워크입니다. 비교할 수 없는 출력 충실도로 낮은 수준의 가벼운 2D 렌더링을 제공합니다.
 * [GPUImage3](https://github.com/BradLarson/GPUImage3)은 Mac 및 iOS에서 GPU 가속 이미지 및 비디오 처리를 수행하기 위한 오픈 소스 프로젝트인 [GPUImage 프레임워크](https://github.com/BradLarson/GPUImage)의 3세대입니다. 이 3세대는 OpenGL** 대신 **[Apple's Metal](https://developer.apple.com/metal/)을 사용하도록 재설계되었습니다.
 * [XR Interaction Toolkit 패키지](https://docs.unity3d.com/Packages/com.unity.xr.interaction.toolkit@2.3/manual/index.html)는 VR 및 AR 경험을 만들기 위한 상위 수준의 구성 요소 기반 상호 작용 시스템입니다. Unity 입력 이벤트에서 3D 및 UI 상호 작용을 사용할 수 있도록 하는 프레임워크를 제공합니다. 이 시스템의 핵심은 기본 Interactor 및 Interactable 구성 요소 집합과 이러한 두 가지 유형의 구성 요소를 함께 연결하는 Interaction Manager입니다.
* [입력 시스템](https://docs.unity3d.com/Packages/com.unity.inputsystem@1.6/manual/index.html)은 사용자가 기기, 터치 또는 동작을 사용하여 게임이나 앱을 제어할 수 있는 도구입니다.
* [XR Hands 패키지](https://docs.unity3d.com/Packages/com.unity.xr.hands@1.1/manual/index.html)는 핸드 트래킹을 지원하는 장치에서 핸드 트래킹 데이터에 액세스할 수 있는 API입니다. 손 추적 데이터에 액세스하려면 XR 손 추적 하위 시스템을 구현하는 공급자 플러그인도 활성화해야 합니다.

### 개발자 리소스

 * [AR 제작 도구 - 증강현실 | Apple 개발자](https://developer.apple.com/augmented-reality/tools/)
 * [증강현실 애플리케이션 | 애플](https://www.apple.com/augmented-reality/)
 * [공간 경험 생성을 위한 Unity 베타 프로그램](https://create.unity.com/spatial)
 * [Unity Learn 교육 프로그램](https://learn.unity.com)
 * [유니티 매뉴얼: XR](https://docs.unity3d.com/Manual/XR.html)
 * [XR 소개: VR, AR, MR 기초 - Unity Learn](https://learn.unity.com/course/introduction-to-xr-vr-ar-and-mr-foundations)
 * [Unity XR: VR 및 AR 앱 구축](https://unity3d.com/learn/unity-xr-apps)


## Apple Silicon 기반 장치
[맨 위로 돌아가기](#목차)

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/216298135-374b55aa-566c-412a-a2b5-787ec03d5d6f.png">
<br />
Apple Silicon으로 구동되는 장치.
</p>

### 맥OS

[macOS](https://www.apple.com/macos)는 Apple의 데스크톱 및 노트북 시리즈를 위한 고급 데스크톱 운영 체제(OS)입니다.

<p align="center">
<img src="https://github.com/mikeroyal/Apple-Silicon-Guide/assets/45159366/5cfa8b3e-1dd9-49d6-bd11-0422252632f7">
<br />
</p>

**macOS 소노마. 출처: [Apple](https://www.apple.com/macos/sonoma/)**

**다음은 macOS Sonoma와 호환되는 Mac 컴퓨터입니다:**

  * iMac 2019 이상
  * 아이맥 프로 2017
  * Mac Pro 2019 이상
  * Mac Studio 2022 이상
  * MacBook Air 2018 이상
  * MacBook Pro 2018 이상
  * Mac mini 2018 이상

### iOS

[iOS](https://www.apple.com/ios/)는 Apple의 iPhone 제품 시리즈를 위한 고급 모바일 운영 체제(OS)입니다.

<p align="center">
<img src="https://github.com/mikeroyal/Apple-Silicon-Guide/assets/45159366/df41724d-e26a-4bf9-8d1c-7548c8f4b7bf">
<br />
</p>

**iOS 17. 출처: [Apple](https://www.apple.com/ios)**

### 아이패드OS

[iPadOS](https://www.apple.com/ipados/)는 Apple의 iPad 제품 시리즈를 위한 고급 모바일 운영 체제(OS)입니다.

<p align="center">
<img src="https://github.com/mikeroyal/Apple-Silicon-Guide/assets/45159366/d446af0b-00c3-455f-85fa-8694f340e780">
<br />
</p>

**iPadOS 17. 출처: [Apple](https://www.apple.com/ipados)**

### 워치OS

[watchOS](https://www.apple.com/watchos/)는 Apple Watch 제품 시리즈를 위한 고급 모바일 운영 체제(OS)입니다.

<p align="center">
<img src="https://github.com/mikeroyal/Apple-Silicon-Guide/assets/45159366/5779ce06-9441-4502-a8d9-1d4fd034d61e">
<br />
</p>

**watchOS 10. 출처: [Apple](https://www.apple.com/watchos/)**

### tvOS

[tvOS](https://www.apple.com/tv-home/)는 Apple의 TV 스트리밍 장치 시리즈를 위한 고급 모바일 운영 체제(OS)입니다.

<p align="center">
<img src="https://github.com/mikeroyal/Apple-Silicon-Guide/assets/45159366/7e3fc9e5-cc4b-49e2-ba5c-028dc42fccb3">
<br />
</p>

**tvOS. 출처: [Apple](https://www.apple.com/tv-home/)**

### 비전OS

[visionOS](https://www.apple.com/newsroom/2023/06/introducing-apple-vision-pro/)는 Apple의 Silicon M2 및 R1 칩으로 구동되는 곧 출시될 AR/VR(증강 현실/가상 현실) 헤드셋을 위한 Apple의 iOS와 유사한 운영 체제입니다. **[메시지](https://support.apple.com/messages), [FaceTime](https://support.apple.com/facetime), [지도](https://www.apple.com/maps/), [Apple Arcade](https://www.apple.com/apple-arcade/)**의 AR/VR 게임과 같은 핵심 Apple 앱의 혼합 현실 버전을 포함하는 앱이 있는 App Store를 갖게 됩니다. 사용자 경험의 중심이 될 수 있는 [Memojis](https://apps.apple.com/us/story/id1445637997) 및 [SharePlay](https://support.apple.com/guide/iphone/use-shareplay-to-watch-and-listen-together-iphb657eb791/ios)와 같은 기능과 함께.

<p align="center">
 <img src="https://github.com/mikeroyal/Apple-Silicon-Guide/assets/45159366/e1f5d708-87a8-4b45-bfc9-03860cb6ebea">
  <br />
 VisionOS. 이미지 크레디트: 애플
</p>

## 소프트웨어 받기

[맨 위로 돌아가기](#목차)

[애플 앱스토어](https://www.apple.com/app-store/)

[App Store용 개발](https://www.apple.com/app-store/developing-for-the-app-store/)

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/183509416-3f094b9d-7e9d-4d72-baa7-106cbf360efd.png">
<br />
</p>

[Homebrew](https://brew.sh)는 macOS, Linux 및 Windows 10([Linux용 Windows 하위 시스템(WSL)](https://docs.microsoft.com/en-us/windows/wsl/) 포함) 시스템에 누락된 패키지 관리자입니다. Homebrew는 모든 개발자/엔지니어에게 필수적인 도구입니다.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/183512138-68b919fe-a970-431d-801e-6982049e9e92.png">
  <br />
</p>

[MacPorts 프로젝트](https://www.macports.org/)는 macOS에서 명령줄, X11 또는 Aqua 기반 오픈 소스 소프트웨어를 컴파일, 설치 및 업그레이드하기 위한 사용하기 쉬운 시스템을 설계하기 위한 오픈 소스 커뮤니티 이니셔티브입니다.

[Nix 패키지 관리자](https://nixos.org/)는 암호화 해시를 통해 생성된 고유 디렉터리에 소프트웨어가 설치되는 순수 기능 배포 모델을 활용하는 크로스 플랫폼 패키지 관리자입니다. 수천 개의 패키지 중에서 선택 Nix 패키지 컬렉션(Nixpkgs)은 Nix 패키지 관리자를 위한 80,000개 이상의 패키지 세트입니다.

 * **[Nix-darwin](https://github.com/LnL7/nix-darwin)**은 darwin의 경우 Nix 모듈이고 macOS의 경우 ```/etc/nixos/configuration.nix```입니다.

**macOS의 다중 사용자 설치:**

```$ sh <(curl -L https://nixos.org/nix/install)```

**Note:** Nix will install all it's packages within ```/nix/store```.

**Note 2:** You may need to source the nix profile at this point.

```source /nix/var/nix/profiles/default/etc/profile.d/nix-daemon.sh```

```source /nix/var/nix/profiles/default/etc/profile.d/nix.sh```


### Productivity & Workflow Apps

[Back to the Top](#table-of-contents)

[Signal](https://www.signal.org/) is a state-of-the-art end-to-end encryption (powered by the open source [Signal Protocol](https://github.com/signalapp)) messaging app that keeps your conversations secure. 

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/188287855-d92f2bb8-1839-4ded-8412-a255061292cc.png">
  <br />
  Signal
</p>

[NordVPN](https://nordvpn.com/) is a VPN service and the flagship product of the cybersecurity company Nord Security. It's available for wireless routers, NAS devices, and other platforms. 

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/188287860-8ad40bd7-3820-498f-bd08-6f91dee43013.png">
  <br />
  NordVPN
</p>

[WireGuard](https://www.wireguard.com/) is a fast, open-source, and secure VPN tunnel. WireGuard allows users to manage and use WireGuard tunnels. The app can import new tunnels from archives and files, from QR codes, or you can create one from scratch.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/188287871-b77d5135-e329-4921-ba8e-f037f18ec165.png">
  <br />
 WireGuard
</p>

[Tailscale](https://tailscale.com/) is a open-source mesh VPN alternative built on WireGuard® that makes it easy to connect your devices. It includes features like automatic key rotation, NAT traversal, and single sign-on with two-factor authentication.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/188288048-e972845a-51a6-4782-9771-8cf423b6bcf8.png">
  <br />
 Tailscale
</p>

[BitWarden](https://bitwarden.com/) is a free and open-source password management service that stores sensitive information such as website credentials(logins and passwords) in an encrypted vault while conveniently keeping them synced between all of your devices.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/188288085-27fa54f7-3f3f-4e6c-9435-15548d24deff.png">
  <br />
  BitWarden
</p>

[1Blocker](https://1blocker.com/) is a fast, secure, and robust tool for iPhone, iPad, and Mac that empowers users to put a stop to invasive online content.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/188287874-3ed8144d-9103-47b8-80c5-bd33a8bca1cb.png">
  <br />
  1Blocker
</p> 

[Matrix](https://matrix.org/) is a client tool that gives you simple HTTP APIs and SDKs (iOS, Android, Web) to create chatrooms, direct chats and chat bots, complete with end-to-end encryption, file transfer, synchronized conversation history, formatted messages, read receipts and more.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/188303122-2160d3f4-0fb4-4936-b475-7f015181dbf3.png">
  <br />
 Matrix
</p>

[Element](https://element.io/) is a Matrix web client built using the [Matrix React SDK](https://github.com/matrix-org/matrix-react-sdk). It is a robust and reliable hosting service for fast, secure real time communication.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/188302916-c73507e5-e34c-4a47-9b1e-d43c180a10a4.png">
  <br />
 Element
</p>

[Nextcloud](http://nextcloud.com/) is a suite of client-server software for creating and using file hosting services. It offers an on-premise Universal File Access and sync platform with powerful collaboration capabilities and desktop, mobile and web interfaces.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/188302917-dc12e604-33c5-413b-be52-4ada05eb5041.png">
  <br />
 Nextcloud
</p> 

[Synology](https://www.synology.com/) is a tool that allows you to easily access and manage files in your Synology Drive on the go. Apart from common file types, such as documents, images, videos and music, you can also open Synology Office document, spreadsheets and slides in the user-friendly viewer provided by Drive.
 
<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/188302924-a7a4291c-33da-48ed-9459-c0e82b42d1de.png">
  <br />
 Synology
</p>

[Adobe Lightroom Photo Editor](https://apps.apple.com/us/app/lightroom-photo-video-editor/id878783582) is a free, powerful photo & video editor and camera app that empowers you to capture and edit stunning images. It offers photo & video editing tools like sliders to retouch your images, apply photo filters, fine-tune backgrounds, and use transformative presets to quickly add unique adjustments.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/188288045-b50e41f2-557d-490a-aa73-758e17c7aaa1.png">
  <br />
  Adobe Lightroom Photo Editor
</p>

[Things](https://culturedcode.com/things/) is an app that helps you plan your day, manage your projects, and make real progress toward your goals.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/185707448-44b5bc1b-96d8-4b1e-b33b-fb8a3157c092.png">
<br />
Things
</p>

[Airbuddy 2](https://v2.airbuddy.app/) is a utility that let's you simply open your AirPods case next to your Mac and see the current status right away, just like how it works on your iPhone. A single click gets you connected, a swipe down lets you connect and change listenings modes at the same time. It has a fully customizable battery alerts help you keep track of your device's batteries.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/185706944-562df794-d9f7-4c3b-ab92-adf19e078d0f.png">
<br />
Airbuddy 2
</p>

[Fantastical 3](https://flexibits.com/fantastical) is a calendar app that works seamlessly across your Mac, iPad, iPhone, and Apple Watch. 

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/185706724-d9bde5a3-36fc-453e-80fd-5a6d2a1e1f13.png">
<br />
Fantastical 3
</p>

[Bartender](https://www.macbartender.com/) is an app for macOS that superpowers your menu bar, giving you total control over your menu bar items, what's displayed, and when, with menu bar items only showing when you need them. It improves your workflow with quick reveal, search, custom hotkeys and triggers, and lots more. 

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/183509489-c6941bff-7f2a-4a5b-a5e4-a8c24bca3b1d.png">
  <br />
  Bartender menu bar tray
</p>

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/183511213-02d08283-7432-4afc-988e-f933dc1bd4a5.png">
  <br />
  Bartender Settings
</p>

[Magnet](https://magnet.crowdcafe.com/) is an app that keeps your workspace organized. magnet is activated by dragging, customizable keyboard shortcuts or via menu bar, it declutters your screen by snapping windows into organized tiles.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/183509955-d6249063-5d17-49c3-bb99-8c952086a6a7.png">
  <br />
  Magnet
</p>

[AltTab](https://alt-tab-macos.netlify.app/) is an app that brings the power of Windows’s “alt-tab” window switcher to macOS.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/183509490-8def09c4-b8a8-4112-b24a-aa9feeb8a3de.jpg">
  <br />
  AltTab
</p>


[MonitorControl](https://monitorcontrol.app/) is an app that controls your external display brightness and volume and shows native OSD. Use menulet sliders or the keyboard, including native Apple keys.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/183509539-7d839f11-a975-441d-a683-ca58031ac9f8.png">
  <br />
  MonitorControl
</p>


[WebCatalog](https://webcatalog.io/webcatalog/) is an app that turns any Website into Real Desktop Apps. 

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/183509551-bbac5da8-0e77-4a62-89df-19e9a19f9be0.png">
  <br />
  WebCatalog
</p>


[Maccy](https://maccy.app/) is a lightweight clipboard manager for macOS. It keeps the history of what you copy and lets you quickly navigate, search, and use previous clipboard contents.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/183509534-1843f439-9738-4e40-a6bf-72bf10fa9f5d.png">
  <br />
  Maccy clipboard manager
</p>

[Daisydisk](https://daisydiskapp.com/) is a utility that provides a visual breakdown of your disk space in form of an interactive map, reveal the biggest space wasters, and remove them with a simple drag and drop. It supports all kinds of local drives, as well as the most popular cloud disks.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/185706628-3f546149-0505-4c10-a75a-295274eb590c.png">
<br />
Daisydisk
</p>

[Page screenshot for Safari](https://alexdenk.eu/mywork/pagescreenshot.html) is an awesome extension, just a click away, ready to use every time you need to capture a webpage screenshot, either the full page or just part of it. Along with your pictures will also automatically open in Preview for easy editing (annotations, blurring sensitive info, printing, drawing, sharing).

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/185706686-c3caa3b0-9855-4c53-b890-c144fd53b1a4.png">
<br />
Page screenshot for Safari
</p>

[Paste](https://pasteapp.io/) is a Clipboard manager for Mac, iPhone, and iPad. 

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/188302928-e30c9dbc-90df-47cc-a6e4-79edceb928ec.png">
<br />
Paste
</p>

[PasteBot](https://tapbots.com/pastebot/) is an indispensable tool to improve your productivity. It quickly recalls clippings that you have copied before and apply powerful text filters to format before pasting. Queue up multiple clippings to paste in sequence. 

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/185706657-79fd7243-c323-4326-9d4f-d716a97b55b6.png">
<br />
PasteBot
</p>

[Speedcut](https://www.speedcut.app/) is a tool that lets your remove backgrounds from photos straight from your Mac's menu bar.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/188302929-d87607fa-c0ca-4eee-95b9-e758b21b968a.png">
<br />
Speedcut
</p>

[Pulse](https://kean.blog/pulse/home) is a powerful logging system for Apple Platforms builtin in SwiftUI. It allows you to record and inspect logs and ```URLSession``` network requests right from your iOS app. Shared logs and view them in [Pulse Pro](https://kean.blog/pulse/pro) or use remote logging to see them in real-time. Logs are stored locally and never leave your devices.

p align="center">
<img src="https://user-images.githubusercontent.com/45159366/218423398-52ed3e3c-fa49-46c7-a6ea-03ba7c431224.png">
<br />
Pulse
</p>

[Cleaner One Pro](https://cleanerone.trendmicro.com/cleaner-one-pro-for-mac/) is an all-in-one Mac Master Cleaner App. It can optimize your disk usage, free up space on your Mac, keep the hard drive clean, remove duplicate photos and other files, manage your apps, and much more. 

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/185706738-fafc320d-72b4-4b68-86df-a4d1ccf92ec0.png">
<br />
Cleaner One Pro
</p>

[Yabai](https://github.com/koekeishiya/yabai) is a window management utility that is designed to work as an extension to the built-in window manager of macOS.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/185481311-dd5edd37-1bbc-4f86-95ea-f3c3aaee6001.png">
  <br />
</p>

[Bear](https://bear.app/) is a Private Markdown Editor for iPhone, iPad and Mac. It uses todos to stay on task across every device. Organize easily Link notes to each other to build a body of work. Add hashtags to organize the way you think. Use Face/Touch ID to protect sensitive notes.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/185707343-717aabae-21bf-4f43-b179-68ae339e9d3f.png">
<br />
Bear
</p>

[Obsidian](https://obsidian.md/) is a powerful knowledge base that works on top of a local folder of plain text Markdown files. It comes with 25 core plugins, 638 community plugins, and 130 themes, plus custom styling, you can tweak Obsidian to work and look exactly how you want it. 

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/185707401-7ed042a1-9658-45dc-ac16-ffb454eb3be7.png">
<br />
Obsidian
</p>

[MarkText](https://github.com/marktext/marktext) is a simple and elegant open-source markdown editor that focused on speed and usability.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/185707405-6bc1da24-e8b9-4713-949b-d0a29732224e.png">
<br />
MarkText
</p>

[1Focus](https://onefocusapp.com/) is an App and Website Blocker to keep you focused on your work. Block specific apps such as email, games or unsupported web browsers. Also, block internet access by blocking the installed web browsers and the App Store.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/185707348-f16430fb-9847-4c58-ba11-80446c293705.png">
<br />
1Focus
</p>

[Harvest](https://www.getharvest.com/) is an easy Time Tracking Software With Invoicing. It creates a project Create entries for your projects and tasks, or import them via one of our integrations.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/185707378-d412d134-05f6-4a97-affc-cfb3f20b2633.png">
<br />
Harvest
</p>

[MindNode](https://www.mindnode.com/) is a map and brainstorming tool that lets you capture, organize, style and share your thoughts. Capture your thoughts Organize your ideas Style your mind map Discreetly Powerful All the features you need.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/185707637-0d5c7bd1-9968-4079-9941-8809af3a306e.png">
<br />
MindNode
</p>

[Unclutter](https://apps.apple.com/us/app/unclutter/id577085396?mt=12) is a 3-in-1 productivity app to power up your efficiency and comfort on Mac during the day. It's a smart and super handy place on your desktop for storing notes, files and pasteboard clips.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/185707426-c385b6ab-5494-45bb-8ddf-5f031fd2cf5d.png">
<br />
Unclutter
</p>

[Warp terminal](https://www.warp.dev/) is a blazingly fast, rust-based terminal reimagined from the ground up to work like a modern app.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/185707428-351705e2-15bd-4913-80a9-87bf8e0df945.png">
<br />
Warp
</p>

[Jettison](https://www.stclairsoft.com/Jettison/) is a tool that automatically ejects external disks from your Mac before your computer goes to sleep. Simply close the lid of your MacBook and Jettison will automatically eject your backup drive, iPod, or whatever is connected so you can safely unplug it.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/185707387-4ba9bba2-305e-4976-986d-bf3e2a1113b9.png">
<br />
Jettison
</p>

[Numi](https://numi.app/) is a calculator that magically combines calculations with text, and allows you to freely share your computations. Numi combines text editor and calculator Support plain English.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/185706707-31ca1206-bfe5-4888-8b83-bbd80961b8ed.png">
<br />
NuMi
</p>

[Dropzone](https://aptonic.com/) is a productivity app for the Mac that makes it faster and easier to move and copy files, launch applications, upload to many different services, and more.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/185707368-7a3aeeda-79f5-4ad3-af40-f2eeedd3c236.png">
<br />
Dropzone
</p>

[System Color Picker](https://sindresorhus.com/system-color-picker) is the macOS color picker as an app with lots of extra features.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/185812204-2bb6073c-0e2f-40f8-83bc-6e981daf33ee.png">
<br />
System Color Picker
</p>

[Raycast](https://www.raycast.com/) is a blazingly fast, totally extendable launcher. It lets you complete tasks, calculate, share common links, and much more.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/185707470-4473a12f-f17a-419e-af1c-4662db395e09.png">
<br />
</p>

[Tinkertool](https://www.bresink.com/osx/TinkerTool.html) is an application that gives you access to additional preference settings Apple has built into MacOS. This allows to activate hidden features in the operating system and in some of the applications delivered with the system.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/185707461-1b4e46bb-86d7-4cfc-9d61-6c8d6182a434.png">
<br />
Tinkertool
</p>

[App Cleaner](https://app-cleaner.com/) is an application that uninstall/remove applications from Mac entirely with all their preferences, caches and other bits and pieces.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/187094108-4a5c0931-db42-479e-9061-467ca8891bfb.png">
<br />
App Cleaner
</p>

[Infuse](https://firecore.com/) is a Video Player for iOS, Apple TV, and Mac. It plays every video file ever created to avoid wasting hours converting and transcoding files.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/200111122-5e263a8c-2b1b-4425-b599-58ba7016fe20.png">
<br />
Infuse Video Player
</p>

## Secure & Privacy Focused Web Browsers

[Back to the Top](#table-of-contents)

**Note: While [Safari](https://www.apple.com/safari/) is a great browser that comes included on all Apple devices. It may not have all the extensions you need for your workflow so I recommend checking out the several great options below.**

[Mozilla Firefox](https://www.mozilla.org/firefox/) is a free and open-source web browser developed by the Mozilla Foundation.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/158266387-04609c3f-1324-4c21-9186-5ed338835260.png">
  <br />
  Firefox
</p>

[Brave](https://brave.com/) is a fast, private and secure web browser for PC, Mac and mobile. It comes with [Brave Search](https://brave.com/search/), which is a private search engine that puts you first, not big tech for those that don't want to use Google Search.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/158266393-8891913c-5acd-4a3a-98cf-ce214282126d.png">
  <br />
  Brave
</p>

[Ungoogled-Chromium](https://www.techspot.com/downloads/7181-ungoogled-chromium.html) is a lightweight approach to removing Google web service dependency.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/173683899-a91b5b02-533f-4ad2-ba84-c3a70108e0dd.png">
  <br />
 Ungoogled-Chromium
</p>

[Vivaldi](https://vivaldi.com/) is a fast, private and secure web browser for PC, Mac and mobile. It comes with built-in features like Notes, Screen Capture, Image Properties and (a lot) more.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/158266396-25f48ceb-9868-4d8f-80a3-30bbd0bbf092.png">
  <br />
  Vivaldi
</p>

[Ghostery Dawn](https://www.ghostery.com/dawn) is a fast, private and secure web browser for PC, Mac and mobile. It comes with the complete Ghostery Privacy Suite including [Ghostery Glow](https://www.ghostery.com/glow) a private search engine that does not log your search history, which means you get served objective results, not results that are filtered by the likelihood you’ll click on them.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/183509605-9e486350-315c-4c9c-ab65-261cda0dac7f.png">
  <br />
  Ghostery Dawn
</p>

[DuckDuckGo Privacy Browser](https://apps.apple.com/us/app/duckduckgo-privacy-browser/id663592361) is a fast, private and secure web browser for MacOS and mobile(iOS and Android).

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/183509601-0d8382cb-bf4f-41e7-9531-9946c8749a7c.png">
  <br />
 DuckDuckGo
</p>

### Privacy & Security Focused Browser extensions

[Back to the Top](#table-of-contents)

[UBlock Origin](https://ublockorigin.com/) is a free and open-source, cross-platform browser extension for content filtering primarily aimed at neutralizing privacy invasion in an efficient, user-friendly method.

 * [Firefox extension](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/)
 * [Chrome extension](https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm)
 
[Privacy Badger](https://privacybadger.org/) is a browser extension that automatically learns to block invisible trackers.

 * [Firefox extension](https://addons.mozilla.org/en-US/firefox/addon/privacy-badger17/)
 * [Chrome extension](https://chrome.google.com/webstore/detail/privacy-badger/pkehgijcmpdhfbdbbnkijodmdjhbjlgp)
 
[DuckDuckGo Privacy Essentials](https://duckduckgo.com/app) is an extension that seamlessly helps prevent your personal information from being exposed during everyday online activity. 

 * [Firefox extension](https://addons.mozilla.org/en-US/firefox/addon/duckduckgo-for-firefox/)
 * [Chrome extension](https://chrome.google.com/webstore/detail/duckduckgo-privacy-essent/bkdgflcldnnnapblkhphbgpggdiikppg?hl=fr)
 
[Ghostery](https://www.ghostery.com/ghostery-browser-extension) is a comprehensive privacy protection Ad Blocker browser extension.
 
 * [Firefox extension](https://www.ghostery.com/ghostery-ad-blocker-firefox)
 * [Chrome extension](https://www.ghostery.com/ghostery-ad-blocker-chrome)
 
[HTTPS Everywhere](https://www.eff.org/https-everywhere)  is an extension created by EFF and the Tor Project which automatically switches thousands of sites from insecure "http" to secure "https".

 * [Firefox extension](https://addons.mozilla.org/en-US/firefox/addon/https-everywhere/)
 * [Chrome extension](https://chrome.google.com/webstore/detail/https-everywhere/gcbommkclmclpchllfjekcdonpmejbdp?hl=en)
 
[CleanURLs](https://gitlab.com/KevinRoebert/ClearUrls) is an extension will automatically remove tracking elements from URLs to help protect your privacy when browsing through the Internet.

 * [Firefox extension](https://addons.mozilla.org/en-US/firefox/addon/clearurls/)
 * [Chrome extension](https://chrome.google.com/webstore/detail/clearurls/lckanjgmijmafbedllaakclkaicjfmnk/)
 
**PixelBlock** is an Gmail extension that blocks email tracking attempts used to detect when you open and read emails. 

 * [Chrome extension](https://chrome.google.com/webstore/detail/pixelblock/jmpmfcjnflbcoidlgapblgpgbilinlem/)

[Sitejabber](https://www.sitejabber.com/) is an extension for consumers to find trustworthy online businesses and avoid scams.

[Firefox extension](https://addons.mozilla.org/en-US/firefox/addon/sitejabber/)

[Chrome extension](https://chrome.google.com/webstore/detail/sitejabber-ratings-review/ckiddbafgcfifpioacgfijgicacanflo)
 
[1Password](https://1password.com/) is a password manager that provides a place for users to store various passwords, software licenses, and other sensitive information in a virtual vault that is locked with a PBKDF2-guarded master password.

 * [Firefox extension](https://addons.mozilla.org/en-US/firefox/addon/1password-x-password-manager/)
 * [Chrome extension](https://chrome.google.com/webstore/detail/1password-%E2%80%93-password-mana/aeblfdkhhhdcdjpifhhbdiojplfjncoa?hl=en)
 
[Bitwarden](https://bitwarden.com/) is a free and open-source password management service that stores sensitive information such as website credentials in an encrypted vault.

 * [Firefox extension](https://addons.mozilla.org/en-US/firefox/addon/bitwarden-password-manager/)
 * [Chrome extension](https://chrome.google.com/webstore/detail/bitwarden-free-password-m/nngceckbapebfimnlniiiahkandclblb)
 
[Guardio](https://guard.io/) is a lightweight extension designed to help you browse quickly and securely. It will clean your browser, speed it up, and protect your private information.

 * [Chrome extension](https://chrome.google.com/webstore/detail/guardio-protection-for-ch/gjfpmkejnolcfklaaddjnckanhhgegla)
 
[OneTab](https://www.one-tab.com/) is an extension that converts your tabs to a list and speeds up your browser.
 
 * [Firefox extension](https://addons.mozilla.org/en-US/firefox/addon/onetab/)
 * [Chrome extension](https://chrome.google.com/webstore/detail/onetab/chphlpgkkbolifaimnlloiipkdnihall)
 
### Privacy-focused Search Engines

[Back to the Top](#table-of-contents)

 * [Brave Search](https://brave.com/search/)
 
<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/187009061-21142683-0943-4ef2-9ca1-a66831410ae4.png">
  <br />
 
</p>
 
 * [Ghostery Glow](https://www.ghostery.com/glow)
 
 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/187009065-2d360d4f-9712-4f80-9da2-e8808773ba7f.png">
  <br />
 
</p>
 
 * [DuckDuckGo](https://duckduckgo.com/)
 
 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/187009064-2d753a92-6e80-48a5-9e88-deb9d886162e.png">
  <br />
 
</p>
 
 * [Startpage](https://www.startpage.com/)
 
 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/187009074-7e0ae42e-84b2-4815-9280-d56ff289462b.png">
  <br />
 
</p>
 
 * [Qwant](https://www.qwant.com/)
 
 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/187009070-b652dab1-0f4a-4020-b231-bc7da3897c04.png">
  <br />
 
</p>
 
 * [Ecosia](https://www.ecosia.org/)
 
 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/187009066-d81594fe-873f-4aed-ac0f-2f9f6673ebc9.png">
  <br />
 
</p>

 * [Swisscows](https://swisscows.com/)
 
 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/187009076-74c38325-077d-4511-be75-981646dd11c8.png">
  <br />
 
</p>
 
 * [searX](https://searx.info/)
 
 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/187009072-54539257-92f9-4f7e-9515-3cb14a2e8695.png">
  <br />
 
</p>
 
 * [Mojeek](https://www.mojeek.com/)
 
 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/187009069-afd5a4e2-aea5-4143-87ba-8882c31476a8.png">
  <br />
 
</p>

## Microsoft Office Alternatives

[Back to the Top](#table-of-contents)

[OnlyOffice](https://www.onlyoffice.com/) is a secure offline/online office suite highly compatible with MS Office formats for Windows, Mac and Linux.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/158472597-9ca73786-4e28-497f-9c6d-0a0040e8c3da.png">
  <br />
  OnlyOffice
</p>

[FreeOffice](https://www.freeoffice.com/) is a secure office suite highly compatible with MS Office formats for Windows, Mac and Linux.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/158266331-321a1004-14cb-473f-a01f-9a9a6e67623a.png">
  <br />
  FreeOffice
</p>

[LibreOffice](https://www.libreoffice.org/) is a free and open-source office productivity software suite similar to Microsoft Office.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/158470268-2834d32d-72ef-4e5e-8cd6-02db51a5dcfa.png">
  <br />
  LibreOffice
</p>

## Universal Control
[Back to the Top](#table-of-contents)

[Universal Control](https://www.apple.com/newsroom/2021/10/macos-monterey-is-now-available/) is a software feature for Apple devices such as MacBooks and iPads that makes it possible to use a single keyboard, mouse, and trackpad with your Mac and iPad as long as they're side-by-side. Much like SideCar, there are limited settings for Universal Control. Without a second device connected, you can go to System Preferences -> Displays and click Advanced to pull up Universal Control settings. If a device is already connected, you'll have to go to Displays -> Display Settings -> Advanced.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/153113830-cf6380b4-af80-4252-894a-84a4eada82e6.png">
<br />
</p>

Bluetooth, Wi-Fi, and Handoff must be enabled on each device, and they must be within 30 feet. If you prefer to use Universal Control wired, the devices can be connected via USB and you must trust your Mac on your iPad. At the moment, Apple does not mention support for Ethernet but we will test this ourselves during the beta period.

You must also have supported devices. Apple says supported devices include:

 - MacBook Pro (2016 and later)
 - MacBook (2016 and later)
 - MacBook Air (2018 and later)
 - iMac (2017 and later)
 - iMac (5K Retina 27-inch, Late 2015)
 - iMac Pro, Mac mini (2018 and later)
 - Mac Pro (2019)
 - Any iPad Pro
 - iPad Air (3rd generation and later)
 - iPad (6th generation and later)
 - iPad mini (5th generation and later)

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/153113829-d6ba2c62-4639-4576-90c5-0456b1e2f06e.png">
<br />
</p>

## Stage Manager

[Back to the Top](#table-of-contents)

Stage Manager is an iPadOS feature that provides better support for external displays. Stage Manager allows the iPad Air(**M1 chip**) and iPad Pro(**M1 chip**):

  *  **Fast access to windows and apps**: The windows of the apps you’re working in are displayed prominently in the center, and other apps are arranged on the left side in order of recent use.
  *  **Resizable windows**: Resize your windows to make them the perfect size for your task.
  *  **Center app**: Focus on the app you’re working with without going full screen.
  *  **Overlapping windows**: Create overlapping windows of different sizes in a single view, giving you the control to arrange your ideal workspace.
  *  **Group apps together**: Drag and drop windows from the side or open apps from the Dock to create app sets that you can always get back to.
  
<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/179672909-4c040435-65db-4522-8846-1d0b87b4a6fa.png">
<br />
</p>

## File Sync/Transfer

[Back to Top](#table-of-contents)

[Syncthing](https://syncthing.net/) is a continuous file synchronization program. It synchronizes files between two or more computers in real time.

[Seafile](https://www.seafile.com) is an open source file sync&share solution designed for high reliability, performance and productivity. Sync, share and collaborate across devices and teams. 

[Synology](https://www.synology.com/) is a tool that allows you to easily access and manage files in your Synology Drive on the go. Apart from common file types, such as documents, images, videos and music, you can also open Synology Office document, spreadsheets and slides in the user-friendly viewer provided by Drive.

[Nextcloud](http://nextcloud.com/) is a suite of client-server software for creating and using file hosting services. It offers an on-premise Universal File Access and sync platform with powerful collaboration capabilities and desktop, mobile and web interfaces. 

[TeraCopy for Mac](https://www.codesector.com/teracopy-for-mac) is a program to copy and paste large files at a high speed. The program is used for frequent file transfers, large file sizes, moving files from separate SSD drives/Hard drives.

[FileRun](https://hub.docker.com/r/filerun/filerun) is a self-hosted Google Drive alternative. It is a full featured web based file manager with an easy to use user interface.

[FileBrowser](https://hub.docker.com/r/filebrowser/filebrowser) provides a file managing interface within a specified directory and it can be used to upload, delete, preview, rename and edit your files. It allows the creation of multiple users and each user can have its own directory.

[Rsync](https://rsync.samba.org/) is a utility in the command line which enables users to transfer and synchronize files efficiently between a computer and an external hard drive in the entire connected network.

[rsync.net](https://rsync.net/) is a Cloud Storage for Offsite Backup that give you an empty UNIX filesystem to access with any SSH tool. Built on ZFS for data security and fault tolerance with support for rsync/sftp/scp/borg/rclone/restic/git-annex.

[Warpinator](https://github.com/linuxmint/warpinator) is a free, open-source tool for sending and receiving files between computers that are on the same network. 

[FileZilla Client](https://filezilla-project.org/) is a fast and reliable cross-platform FTP, FTPS and SFTP client with lots of useful features and an intuitive graphical user interface. 

[WinFsp](https://github.com/winfsp/winfsp) is a set of software components for Windows computers that allows the creation of user mode file systems. In this sense it is similar to FUSE (Filesystem in Userspace), which provides the same functionality on UNIX-like computers.

[SSHFS-Win](https://github.com/winfsp/sshfs-win) is a minimal port of SSHFS to Windows. Looking under the hood it uses Cygwin for the POSIX environment and WinFsp for the FUSE (Filesystem in Userspace) functionality.

[RiftShare](https://riftshare.app) is a cross platform (Windows, MacOS, Linux) file sharing tool that supports fully encrypted transfers both on the local network and off network using a simple passphrase. RiftShare uses [magic-wormhole](https://github.com/magic-wormhole/magic-wormhole) under the hood and is compatible with other magic-wormhole clients. It is also fully open source and licensed under the GPLv3. 

[Usermode FTP Server](https://gitlab.com/ergoithz/umftpd) is a tool that let's you start an FTP server as user and transfer files with any FTP client. Allowing you to access your files directly with many file browsers' builtin FTP support: Windows File Explorer, Thunar, Gnome Files, Dolphin and many more. 

[TagSpaces](https://www.tagspaces.org/) is a free, no vendor lock-in, open source application for organizing, annotating and managing local files with the help of tags. It features advanced note taking functionalities and some capabilities of to-do apps. It's available for Windows, Linux, Mac OS and Android. 

## Replacing iCloud with Nexcloud

[Back to the Top](#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/218290801-af7efb7b-fd9e-452e-a18e-72e643bdf044.png">
  <br />
  
</p>

**Replacing these iCloud services:**

  * File sync (“iCloud Drive”) -> [Nextcloud Files](https://nextcloud.com/files/)
  * Photos (“iCloud Photo Library”) -> [Nextcloud Photos](https://github.com/nextcloud/photos)
  * Mail -> [Nextcloud Mail](https://apps.nextcloud.com/apps/mail) + [SnappyMail](https://apps.nextcloud.com/apps/snappymail)
  * Contacts -> [Nextcloud Contacts](https://apps.nextcloud.com/apps/contacts)
  * Calendar -> [Nextcloud Calendar](https://apps.nextcloud.com/apps/calendar)
  * Reminders -> [SnappyMail](https://apps.nextcloud.com/apps/snappymail)
  * Browser sync (“Safari”) -> [Nextcloud Bookmarks](https://apps.nextcloud.com/apps/bookmarks) or [Floccus](https://floccus.org/)
  * Notes -> [Nextcloud Notes](https://apps.nextcloud.com/apps/notes)
  * Password sync (“Keychain”) -> [KeePass DB on Nextcloud](https://apps.nextcloud.com/apps/keeweb)
  * Remote access (“Back to my mac”) -> [Tailscale](https://tailscale.com/) + [docker-ddns](https://github.com/dprandzioch/docker-ddns)
  * Find my iPhone -> [Nextcloud PhoneTrack](https://apps.nextcloud.com/apps/phonetrack)
  * iWork for iCloud -> [Nextcloud with Onlyoffice](https://nextcloud.com/onlyoffice/) or [Collabora Online in Nextcloud](https://nextcloud.com/collaboraonline/)
  * News -> [Miniflux](https://miniflux.app/) with [Fever API](https://miniflux.app/docs/services.html)
  * Audiobooks (“iBooks”) -> [audiobookshelf](https://www.audiobookshelf.org/)
  * Repository Hosting -> [GitLab](https://gitlab.com/)


[Nextcloud](https://nextcloud.com) is an industry-leading, on-premises content collaboration platform for file sync & share and communication server. It is fully open source and you can host it yourself or pay a company to do it for you. Also checkout the following links below:

   - [Nextcloud App Store](https://apps.nextcloud.com)

   - [Nextcloud GitHub](https://github.com/nextcloud)

   - [Nextcloud Developer Program](https://nextcloud.com/developer)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/150701961-ac8be115-34c1-4012-bd69-d1f22a10e48c.png">
  <br />
Nexcloud login screen
</p>

[Nextcloud Hub](https://nextcloud.com/hub/) is a tool that allows you to share and collaborate on documents, send and receive email, manage your calendar and have video chats without data leaks. As fully on-premises solution, Nextcloud Hub provides the benefits of online collaboration without the compliance and security risks.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/150701964-df1dd8d9-1d3a-4376-81e8-f49439fb4356.png">
  <br />
Nexcloud Hub
</p>

[Nextcloud AIO (All In One)](https://github.com/nextcloud/all-in-one) is a tool that provides easy deployment and maintenance with most features included in this one Nextcloud instance. 

**Features it includes:**

   * Nextcloud
   * Nextcloud Office
   * High performance backend for Nextcloud Files
   * High performance backend for Nextcloud Talk
   * Backup solution (based on BorgBackup)
   * Imaginary
   * ClamAV
   * Fulltextsearch

[Nextcloud Desktop Client](https://nextcloud.com/install/#install-clients) is a tool to synchronize files from Nextcloud Server with your computer.

[Nextcloud Deck](https://apps.nextcloud.com/apps/deck) is a kanban style organization tool aimed at personal planning and project organization for teams integrated with Nextcloud.

[Nextcloud Files](https://nextcloud.com/files/) is a tool tool that allows your employees have easy access to their files, photos and documents to work and can share and collaborate with team members, customers and partners. So IT knows nobody besides those they shared with has access to those files.

[Nextcloud Talk](https://nextcloud.com/talk/) is a tool that protects your communication better than other team collaboration platforms like Microsoft Teams or Slack, making sure your data stays on your servers. It also goes further than other encrypted communication technologies by keeping even metadata from leaking.

[Nextcloud Home](https://nextcloud.com/athome/) is a tool that allows you store your documents, calendar, contacts and photos on your server at home, at one of at one Nextcloud's providers or in a data center you trust.

[Nextcloud Enterprise](https://nextcloud.com/enterprise/) is a service that gives professional organizations software optimized and tested for mission critical environments.

[Nextcloud Outlook Integration](https://nextcloud.com/outlook/) is a tool that automatically upload files to replace large attachments or integrate Calendars and Contacts in Microsoft Outlook.

[Collabora Online in Nextcloud](https://nextcloud.com/collaboraonline/) is a powerful LibreOffice-based online office suite with collaborative editing, which supports all major document, spreadsheet and presentation file formats and works in all modern browsers.

[ONLYOFFICE integration in Nextcloud](https://nextcloud.com/onlyoffice/) is a service that empowers your users to collaborate on office documents with team members in real time. It has compatibility with Microsoft Office formats means perfect documents, every time.

[Nextcloud VM(virtual machine appliance)](https://download.nextcloudvm.com/) is a set of carefully crafted family of [*nix](https://bit.ly/2UaCC7b) scripts, which interactively guide you through a quality-controlled installation of a Nextcloud instance for Home/SME Server and scripts for Raspberry Pi 4. It is Community developed and maintained.

## Adding External Storage

[Back to the Top](#table-of-contents)

[Sabrent XTRM Q](https://www.sabrent.com/rocket-xtrmq/) is a perfect SSD for all your creative pursuits: high-res photos, videos, sound files, etc. It's perfect for saving, creating and editing available in 500GB, 1TB, 2TB, and 4TB drives.

[Shell Thunder](https://m.fledging.net/products/shell-thunder) is a high-performance Intel-Certified Thunderbolt 3 SSD Enclosure engineered for active cooling with smart fan technology. Shell Thunder is designed for 2280 and 2260 m.2 NVME SSDs for macOS and Windows.

[Orico USB4.0 NVMe SSD Enclosure](https://www.orico.cc/us/product/detail/7328.html) is a high-performance SSD Enclosure engineered with up to a 40Gbps transmission rate and 2 TB capacity. It supports Windows, macOS, and Linux devices.

[USB-C to Lightning Cable (2 m)](https://www.apple.com/shop/product/MQGH2AM/A/usb-c-to-lightning-cable-2-m) is cable to connect your iPhone, iPad, or iPod with Lightning connector to your USB-C or Thunderbolt 3 (USB-C) enabled Mac for syncing and charging, or to your USB-C enabled iPad for charging.

[SanDisk Phone Drive (iPhone, iPad, or MacBook) up to 256GB](https://www.westerndigital.com/products/usb-flash-drives/sandisk-phone-drive-lightning-usb-c?sku=SDIX70N-064G-GG6NN).

**More fast External Storage options for MacOS/iOS/iPadOS:**

 * [Kingston XS2000 Portable SSD](https://www.amazon.com/Kingston-Performance-Pocket-Sized-SXS2000-2000G/dp/B09F6279PY)
 * [Crucial X8](https://www.amazon.com/Crucial-X8/s?k=Crucial+X8)
 * [Samsung Portable SSD X5](https://www.samsung.com/us/computing/memory-storage/portable-solid-state-drives/portable-ssd-x5-1tb-mu-pb1t0b-am/)
 * [Samsung Portable SSD T7 Touch](https://www.samsung.com/us/computing/memory-storage/portable-solid-state-drives/portable-ssd-t7-touch-usb-3-2-500gb-black-mu-pc500k-ww/)
 * [SanDisk Professional Pro-G40 SSD](https://www.westerndigital.com/products/portable-drives/sandisk-professional-pro-g40-ssd)
 * [SanDisk Professional G-Drive ArmorATD](https://www.westerndigital.com/products/portable-drives/sandisk-professional-g-drive-armoratd-usb-3-1-hdd)
 * [WD Black P10](https://www.westerndigital.com/products/portable-drives/wd-black-p10-game-drive-usb-3-2-hdd)
 * [WD Black D10](https://www.westerndigital.com/products/external-drives/wd-black-d10-game-drive-usb-3-2-hdd)
 * [WD My Passport (5TB)](https://www.westerndigital.com/products/portable-drives/wd-my-passport-usb-3-0-hdd)
 * [OWC Envoy Pro EX With USB-C](https://www.amazon.com/OWC-Envoy-External-Storage-Solution/dp/B07T7X7HRK)
 * [LaCie Rugged SSD Pro](https://www.lacie.com/products/rugged/)
 * [LaCie Rugged RAID Shuttle](https://www.lacie.com/products/rugged/)
 * [LaCie 2big RAID](https://www.lacie.com/products/big/2big/)
 * [LaCie Mobile Drive](https://www.lacie.com/products/mobile-drive/)
 * [CalDigit AV Pro 2](https://www.caldigit.com/av-pro-2/)

## Backups

[Back to the Top](#table-of-contents)

[Proxmox Backup Server](https://www.proxmox.com/en/proxmox-backup-server) is an enterprise backup solution for backing up and restoring VMs, containers, and physical hosts. The open-source solution supports incremental backups, deduplication, Zstandard compression, and authenticated encryption.

[Borgmatic](https://github.com/modem7/docker-borgmatic) is a simple, configuration-driven backup software for servers and workstations. It protects your files with client-side encryption. Backup your databases too. Monitor it all with integrated third-party services. 

[BorgWarehouse](https://borgwarehouse.com/) is a  fast and modern WebUI for a BorgBackup's central repository server.

[Emborg](https://emborg.readthedocs.io/en/latest/) is a simple command line utility to orchestrate backups. It is built as a front-end to Borg, a powerful and fast de-duplicating backup program. 

[Vorta](https://vorta.borgbase.com/) is a backup client for macOS and Linux desktops. It integrates the mighty Borg Backup with your favorite desktop environment to protect your data from disk failure, ransomware and theft. 

[rsync.net](https://rsync.net/) is a Cloud Storage for Offsite Backup that give you an empty UNIX filesystem to access with any SSH tool. Built on ZFS for data security and fault tolerance with support for rsync/sftp/scp/borg/rclone/restic/git-annex.

[BackupPC](https://github.com/backuppc/backuppc) is a high-performance, enterprise-grade system for backing up Linux, Windows and macOS PCs and laptops to a server's disk. BackupPC is highly configurable and easy to install and maintain.

[UrBackup](https://www.urbackup.org/) is an easy to setup Open Source client/server backup system, that through a combination of image and file backups accomplishes both data safety and a fast restoration time. File and image backups are made while the system is running without interrupting current processes. Available for Windows, macOS, and Linux. 

[Kopia](https://kopia.io/) is a user-friendly desktop app for Windows, macOS, and Linux which allows you to create snapshots, define policies, and restore files quickly with Fast and Encrypted Backups. 

[rsnapshot](https://rsnapshot.org/) is a filesystem snapshot utility based on rsync. This makes it easy to make periodic snapshots of local machines, and remote machines over ssh.

[Proton Drive](https://drive.proton.me/) is an end-to-end encrypted Swiss storage space for your files, photos, and videos, ensuring that nobody, except those authorized by you, can access your data. 

[pCloud](https://www.pcloud.com/) is a secure place for your photos, videos and documents from every device, anywhere you go. pCloud starts with 10 GB free storage and automatically backup your photos and videos and free up space from your device. 

## SSD Drive Health/Data Recovery

[Back to the Top](#table-of-contents)

- [How to create a bootable installer for macOS](https://support.apple.com/en-us/HT201372)

 * Restore from Time Machine: [Restore your files](https://support.apple.com/kb/HT203981) from a Time Machine backup.

 * Reinstall macOS: Download and [reinstall MacOS](https://support.apple.com/kb/HT204904).

 * Safari (or Get Help Online): Use Safari to browse the web and find help for your Mac. Links to [Apple's support website](https://support.apple.com/) are included. Browser plug-ins and extensions are disabled.

 * Disk Utility: Use Disk Utility to [repair your disk](https://support.apple.com/kb/HT210898) or [erase your disk](https://support.apple.com/kb/HT208496) or other storage device.

 * Additional utilities are available from the Utilities menu in the menu bar, including [Startup Security Utility](https://support.apple.com/kb/HT208198) (or [Firmware Password Utility](https://support.apple.com/kb/HT204455)), and Terminal. 
 
<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/182049332-16b132a4-a02f-42d7-a234-3cc1088c25d6.png">
<br />
MacOS Recovery Options
</p>

[Disk Drill](https://www.cleverfiles.com/) is a free tool that can scan and recover data from virtually any storage device — including internal Macintosh hard drives, external hard drives, cameras, iPhones, iPads, iPods, Android devices, USB flash drives, Kindles, and memory cards. It can read your device even if it is failing, unreadable, or has lost a partition. Combining several powerful scanning algorithms, Disk Drill provides a complete Mac data recovery solution.

[DriveDx](https://binaryfruit.com/drivedx) is an advanced drive-health diagnostic and monitoring utility. It not only monitors the drive’s built-in S.M.A.R.T. status, but also analyzes the changes of all drive health indicators that are closely related to SSD or HDD failures (like SSD wear out / endurance, reallocated bad sectors, offline bad sectors, pending sectors, I/O errors, and more) and alerts the user immediately if anything goes wrong.

[AmorphousDiskMark](https://apps.apple.com/us/app/amorphousdiskmark/id1168254295?mt=12) is a tool that measures storage performance.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/218423387-eee6e655-2e19-414b-bb5c-0c9a6d3215a3.png">
</p>

## Checking Battery Health

[Back to the Top](#table-of-contents)

[coconutBattery](https://www.coconut-flavour.com/coconutbattery/) is a tool that keeps you aware of your current battery health. It shows you live information about the battery quality in your Mac, iPhone and iPad.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/182049312-aeebad9f-c226-4c77-9461-50f41d6100a0.png">
<br />
Checking Battery on your Mac device.
</p>

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/182049316-87385a01-d26e-46c6-bbfc-ae5043c57763.png">
<br />
Checking Battery on your iOS device.
</p>

### Low Power Mode

**If you have a Mac laptop, you can change the options below to reduce energy use and optimize the lifespan of your battery.**

 **On your Mac, choose Apple menu  > System Settings, then click Battery in the sidebar. (You may need to scroll down.)**

 **Do any of the following:**

   * Click the pop-up menu next to Low Power Mode on the right, then choose “Always,” “Only on battery,” or “Only on power adapter.”

   * Click the Info button next to Battery Health on the right, then turn on Optimized Battery Charging and “Manage battery longevity.”

   * Click Options on the right, then turn on “Put hard disks to sleep when possible” and “Automatic graphics switching.”
        
   
<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/234225969-7bce4b07-a55a-4cb9-aace-6a2f8ed1972f.png">
<br />
</p>
        
        
[Cooldown](https://goodsnooze.gumroad.com/l/cooldown) is a simple menu bar app that allows you to quickly toggle Low Power Mode on and off.

**Planned features**

  * Automatically toggle LPM at certain times.
  * Automatically toggle LPM when certain apps are opened.
  * Design improvements.
  
 <p align="center">
<img src="https://user-images.githubusercontent.com/45159366/234226010-78ab7711-3785-4152-a3da-7f193b293041.png">
<br />
</p>
      

## Charging/Powerbanks

[Back to the Top](#table-of-contents)

While the Apple Silicon Macbooks, iPhones, iPads, and Air Pods have great battery life. It's always good to have a portable USB-C powerbank for charging your device when you're traveling, conferences, etc..

* [Using USB-C cables with your Mac](https://support.apple.com/guide/mac-help/use-usb-c-cables-mchl447b9239/mac)
* [Apple USB-C Charge Cable (2m) on Amazon](https://www.amazon.com/Apple-USB-C-Charge-Cable-2m/dp/B01MQ5Z080)
* [USB-C to Lightning Cable (2 m)](https://www.apple.com/shop/product/MQGH2AM/A/usb-c-to-lightning-cable-2-m)
* [About the Apple USB-C to Lightning Cable](https://support.apple.com/en-us/HT205807)

[Anker PowerCore III (45W USB-C PD output)](https://www.amazon.com/Anker-PowerCore-Capacity-Delivery-Portable/dp/B08FX8GKJ5)

[Anker 747 Charger (GaNPrime 150W)](https://www.anker.com/products/a2340)

[Anker 737 Charger (GaNPrime 120W)](https://www.anker.com/products/a2148)

[Anker 736 Charger (Nano II 100W)](https://www.anker.com/products/a2145)
 
[Anker 735 Charger (GaNPrime 65W)](https://www.anker.com/products/a2668)
 
[Anker 733 Power Bank (GaNPrime PowerCore 65W)](https://www.anker.com/products/a1651)

[Anker 525 Power Bank 20000mAh](https://www.anker.com/products/a1287?listingPlan=b&variant=41110977642646&discount=WS24A1287011)

[Omni 20+ 20000mAh Laptop Power Bank](https://www.omnicharge.co/products/omni-20/)

[MAXOAK Portable Laptop Charger(26756mAh/99Wh), Portable Power Station with AC Outlet PD 45W USB-C Solar Generator Battery Backup Power Supply](https://www.amazon.com/Portable-TSA-Approved-MAXOAK-26756mAh-Lighting-Bluetti/dp/B07VWNV5S6)

[MAXOAK K2 185Wh/50000mAh Power Bank for Laptop](https://maxoak.net/products/maxoak-k2-185Wh-50000mah-power-bank)

[HenHot 65W USB-C Portable Charger](https://www.amazon.com/HenHot-20000mAh-Laptop-Portable-Charger/dp/B09SLCV819)

[Baseus 65W USB-C Power Bank with Built-in Cable](https://www.amazon.com/Portable-Charger-Baseus-20000mAh-Charging/dp/B08THFDRSZ)

### USB-C Adapters

[Back to Top](#table-of-contents)

 * [JSAUX USB-C to USB Adapter (2 Pack)](https://www.amazon.com/JSAUX-Adapter-Compatible-MacBook-Samsung/dp/B07BS8SRWH/)

 * [Anker USB-C Adapter (2 Pack)](https://www.amazon.com/Adapter-Anker-High-Speed-Transfer-Notebook/dp/B08HZ6PS61/)

 * [Basesailor USB to USB-C Adapter (2 Pack)](https://www.amazon.com/Female-Adapter-Charger-Airpods-Samsung/dp/B079LYHNSR/)

 * [Syntech USB-C to USB Adapter (2 Pack)](https://www.amazon.com/Syntech-Adapter-Thunderbolt-Compatible-MacBook/dp/B07CVX3516/)

 * [Apple USB-C to USB Adapter](https://www.amazon.com/Apple-USB-C-to-USB-Adapter/dp/B00VU2OID2/)

### USB-C Fast Charging Cables

[Back to Top](#table-of-contents)

 * [Apple Thunderbolt 4 (USB‑C) Pro Cable (1 m) | Apple](https://www.apple.com/shop/product/MU883AM/A/thunderbolt-4-usb%E2%80%91c-pro-cable-1-m)
   
 * [Apple Thunderbolt 4 (USB-C) Pro Cable (1.8 m) | Amazon](https://www.amazon.com/Apple-Thunderbolt-Pro-Cable-1-8/dp/B09V3KPJGZ)
   
 * [Baseus Minimalist USB-C to USB-C Cable 100W](https://www.baseus.com/products/minimalist-usb-c-to-usb-c-cable-100w)

 * [Baseus USB-C Fast Charging Cable 240W](https://www.baseus.com/products/usb-c-fast-charging-cable-240w)

 * [Baseus PD 100W USB C to USB C Cable(6.6 ft), 5A Fast Charging USB C Cable with LED Display](https://www.amazon.com/Baseus-Charging-Display-Braided-Compatible/dp/B0B6CF1YYF?th=1)

 * [Baseus Cafule USB-C to USB-C Cable( 6.6 ft) 100W](https://www.baseus.com/products/cafule-usb-c-to-usb-c-cable-100w-6-6-ft)

 * [Anker 333 USB C to USB C Cable (6ft 100W, 2-Pack)](https://www.amazon.com/Anker-2-Pack-Charging-MacBook-Samsung/dp/B09LCJPZ1P/)

 * [JSAUX USB C to USB C Cable 100W/5A [2-Pack 6.6ft+6.6ft], QC 4.0/USB PD Type-C Fast Charging](https://www.amazon.com/JSAUX-Charging-Braided-Compatible-Matebook/dp/B07GZH2WTV/)

 * [USB C to USB C Cable, 3.2 Gen 2 USB-C Cable 10ft - 4K UHD 20Gbps USB C Cable 100W PD Fast Charging Cable](https://www.amazon.com/USB-Cable-3-1-USB-C-10ft/dp/B089FV33QX/)

 * [AINOPE 100W USB C to USB C Cable 10ft, USB C Charger Cable](https://www.amazon.com/AINOPE-Charging-Braided-compatible-MacBook/dp/B094YDZQ1C/)


## MacOS/iOS Security Hardening

[Back to the Top](#table-of-contents)

### Resources

 * [Signed system volume security in iOS, iPadOS, and macOS](https://support.apple.com/guide/security/signed-system-volume-security-secd698747c9/web)
 * [Protecting against malware in macOS](https://support.apple.com/guide/security/protecting-against-malware-sec469d47bd8/web)
 * [CIS(Center for Internet Security) Apple iOS Benchmarks](https://www.cisecurity.org/benchmark/apple_ios)
 * [CIS(Center for Internet Security) Apple macOS Benchmarks](https://www.cisecurity.org/benchmark/apple_os)
 * [NIST Security Technical Implementation for macOS](https://ncp.nist.gov/checklist/1017)
 * [Setting a custom umask in macOS](https://support.apple.com/en-us/HT201684)
 * [Personal Security Checklist](https://github.com/Lissy93/personal-security-checklist) is a curated checklist of 300+ tips for protecting digital security and privacy in 2022.

### Enable full disk encryption

Full disk encryption is pretty much self-explanatory. You want to encrypt your disk, so you prevent unauthorized access to your data.

To turn on full disk encryption on macOS:

1. Go to System Preferences > Security & Privacy > FileVault
2. Click on the lock on the bottom left side of the screen to authenticate (you need to authenticate to make changes, in this case, to turn on full disk encryption)
3. Click Turn On FileVault... and follow the procedure step by step

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/187093922-072076a7-7c4d-4fc4-a00f-e80d12d31bc2.png">
<br />
File Vault
</p>

[Hardened Runtime](https://developer.apple.com/documentation/security/hardened_runtime) is a tool that along with System Integrity Protection (SIP), protects the runtime integrity of your software by preventing certain classes of exploits, like code injection, dynamically linked library (DLL) hijacking, and process memory space tampering. 

[System Integrity Protection (SIP)](https://support.apple.com/en-us/HT204899) is a security technology in OS X El Capitan and later that's designed to help prevent potentially malicious software from modifying protected files and folders on your Mac.

[Effaceable Storage](https://support.apple.com/guide/security/aside/sec0183122de/1/web/1) is a dedicated area of NAND storage, used to store cryptographic keys, that can be addressed directly and wiped securely.

[SepOS](https://support.apple.com/guide/security/aside/secc3e4f7a43/1/web/1) is the Secure Enclave firmware, based on an Apple-customized version of the L4 microkernel.

[Pulse](https://kean.blog/pulse/home) is a powerful logging system for Apple Platforms builtin in SwiftUI. It allows you to record and inspect logs and ```URLSession``` network requests right from your iOS app. Shared logs and view them in [Pulse Pro](https://kean.blog/pulse/pro) or use remote logging to see them in real-time. Logs are stored locally and never leave your devices.

[Lynis](https://cisofy.com/lynis/) is a security auditing tool for systems based on UNIX like Linux, macOS, BSD, and others. It performs an in-depth security scan and runs on the system itself. The primary goal is to test security defenses and provide tips for further system hardening. It will also scan for general system information, vulnerable software packages, and possible configuration issues. 

[Pareto Security](https://paretosecurity.com/) is a MenuBar app to automatically audit your Mac for basic security hygiene.

[GRR Rapid Response](https://grr-doc.readthedocs.io/) is an incident response framework focused on remote live forensics. 

[mac_apt](https://github.com/ydkhatri/mac_apt) is a DFIR (Digital Forensics and Incident Response) tool for macOS/iOS to process Mac computer full disk images (or live machines) and extract data/metadata useful for forensic investigation. It is a python based framework, which has plugins to process individual artifacts (such as Safari internet history, Network interfaces, Recently accessed files & volumes, etc..)

[AdGuard DNS](https://adguard-dns.io/en/welcome.html) is a tool that let's you control all web traffic on your devices, block ads, trackers, and malicious domains.

[Quad9](https://www.quad9.net/) is a free service that replaces your default ISP or enterprise Domain Name Server (DNS) configuration. When your computer performs any Internet transaction that uses the DNS (and most transactions do), Quad9 blocks lookups of malicious host names from an up-to-the-minute list of threats. This blocking action protects your computer, mobile device, or IoT systems against a wide range of threats such as malware, phishing, spyware, and botnets, and it can improve performance in addition to guaranteeing privacy. 


### MacOS Forensic Analysis

[Back to The Top](#table-of-contents)

**MacOS Forensic Analysis** is the process of building in-depth digital forensics knowledge of MacOS and iOS systems.
 - [SANS FOR518: Mac and iOS Forensic Analysis and Incident Response Course](https://www.sans.org/cyber-security-courses/mac-and-ios-forensic-analysis-and-incident-response/)

* [Memoryze for Mac](https://www.fireeye.com/services/freeware/memoryze.html) - Memoryze for Mac is Memoryze but then for Macs. A lower number of features, however.
* [Knockknock](https://objective-see.com/products/knockknock.html) - Displays persistent items(scripts, commands, binaries, etc.) that are set to execute automatically on MacOS.
* [macOS Artifact Parsing Tool (mac_apt)](https://github.com/ydkhatri/mac_apt) - Plugin based forensics framework for quick mac triage that works on live machines, disk images or individual artifact files.
* [MacOS Auditor](https://github.com/jipegit/OSXAuditor) - Free Mac MacOScomputer forensics tool.
* [MacOS Collector](https://github.com/yelp/osxcollector) - MacOS Auditor offshoot for live response.
* [The ESF Playground](https://themittenmac.com/the-esf-playground/) - A tool to view the events in Apple Endpoint Security Framework (ESF) in real time.

### VPN

[Back to The Top](#table-of-contents)

**VPN (Virtual Private Network)** is a service that encrypts your internet traffic on unsecured networks to protect your online identity, hide your IP address, and shield your online data from third parties. 

* [Wireguard](https://www.wireguard.com/) - A new minimal VPN Solution that is very fast.
* [Tailscale](https://tailscale.com/) - The easiest, most secure way to use WireGuard and 2FA. Tailscale helps you manage and access private or shared resources from anywhere in the world. 
* [NetBird](https://netbird.io/) - An open-source VPN management platform built on top of WireGuard® making it easy to create secure private networks for your organization or home.
* [SoftEther](https://www.softether.org/) - Multi-protocol software VPN with advanced features.
* [OpenVPN](https://community.openvpn.net) - Uses a custom security protocol that utilizes SSL/TLS for key exchange.
* [Pritunl](https://pritunl.com/) - OpenVPN based solution that's easy to set up.
* [sshuttle](https://github.com/apenwarr/sshuttle) - Poor man's VPN.
* [strongSwan](https://www.strongswan.org/) - Complete IPsec implementation for Linux.
* [tinc](https://www.tinc-vpn.org/) - Distributed p2p VPN.

### SSH

[Back to The Top](#table-of-contents)

**Secure Shell Protocol (SSH)** is a cryptographic network protocol for operating network services securely over an unsecured network.

* [Tailscale SSH](https://tailscale.com/kb/1193/tailscale-ssh/) is a service that allows Tailscale to manage the authentication and authorization of SSH connections on your tailnet.
* [SSHrc](https://github.com/Russell91/sshrc) - sources ~/.sshrc on your local computer after logging in remotely.
* [StormSSH](https://stormssh.readthedocs.org) - A command line tool to manage SSH connections.
* [Advanced SSH config](https://pypi.python.org/pypi/advanced-ssh-config/) - Enhances ssh_config file capabilities, completely transparent.
* [AutoSSH](https://www.harding.motd.ca/autossh/) - Automatically respawn ssh session after network interruption.
* [Cluster SSH](https://sourceforge.net/projects/clusterssh/) - Controls a number of xterm windows via a single graphical console.
* [DSH](https://www.netfort.gr.jp/~dancer/software/dsh.html.en) - Dancer's shell / distributed shell - Wrapper for executing multiple remote shell commands from one command line.
* [Mosh](https://mosh.org/) - is a command-line program, like SSH. You can use it inside xterm, gnome-terminal, urxvt, Terminal.app, iTerm, emacs, screen, or tmux.
* [Parallel SSH](https://parallel-ssh.org/) is an asynchronous parallel SSH library designed for large scale automation. It differentiates ifself from alternatives, other libraries and higher level frameworks like Ansible or Chef.


### Firewall Filtering

[Back to The Top](#table-of-contents)

**Firewall** is a system that provides network security by filtering incoming and outgoing network traffic based on a set of user-defined rules. In general, the purpose of a firewall is to reduce or eliminate the occurrence of unwanted network communications while allowing all legitimate communication to flow freely.

[Little Snitch](https://www.obdev.at/products/littlesnitch/index.html) is a host-based application firewall for macOS. It can be used to monitor applications, preventing or permitting them to connect to attached networks through advanced rules.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/236665250-e9ecfa42-771e-4e65-962b-6caf8972836c.png">
<br />
</p>

### MFA

[Back to The Top](#table-of-contents)

**Multifactor Authentication (MFA)** is when you sign into your online accounts - a process we call "authentication" - you're proving to the service that you are who you say you are. Traditionally that's been done with a username and a password.

[YubiKey](https://www.yubico.com/) is a security device that makes two-factor authentication as simple as possible. Instead of a code being texted to you, or generated by an app on your phone, you simply press a button on your YubiKey. Each device has a unique code built on to it, which is used to generate codes that help confirm your identity. The YubiKey USB authenticator includes NFC and has multi-protocol support including FIDO2, FIDO U2F, Yubico OTP, OATH-TOTP, OATH-HOTP, Smart card (PIV), OpenPGP, and Challenge-Response capability to give you strong hardware-based authentication.

[Authelia](https://www.authelia.com/) is an open-source authentication and authorization server providing two-factor authentication and single sign-on (SSO) for your applications via a web portal. It acts as a companion for [reverse proxies](https://github.com/authelia/authelia#proxy-support) by allowing, denying, or redirecting requests. 

[ZITADEL](https://zitadel.com/) is an open-source authentication and authorization server providing two-factor authentication combining the best of Auth0 and Keycloak. Built for the serverless era. It includes Multi-tenancy with branding customization, secure login, self-service, OpenID Connect, OAuth2.x, SAML2, LDAP, Passwordless with FIDO2 (including Passkeys), OTP, U2F, and an unlimited audit trail is there for you, ready to use.

[Microsoft Authenticator](https://support.microsoft.com/en-us/account-billing/download-and-install-the-microsoft-authenticator-app-351498fc-850a-45da-b7b6-27e523b8702a) is an app helps you sign in to your accounts when you're using two-step verification. Two-step verification helps you to use your accounts more securely because passwords can be forgotten, stolen, or compromised.

[Google Authenticator](https://support.google.com/accounts/answer/1066447?hl=en&co=GENIE.Platform%3DAndroid) is a software authenticator developed by Google that implements multi-factor authentication services using the Time-based one-time password and HMAC-based one-time password, for authenticating users of software applications.

### Disk Image Creation Tools

[Back to Top](#table-of-contents)

**Disk Image Creation** - is a process of Data backup and recovery where creating an image ensures that the original data on the disk is preserved. With an exact copy, you can extract the data from the disk image anytime you need.

* [Bitscout](https://github.com/vitaly-kamluk/bitscout) - Bitscout by Vitaly Kamluk helps you build your fully-trusted customizable LiveCD/LiveUSB image to be used for remote digital forensics (or perhaps any other task of your choice). It is meant to be transparent and monitorable by the owner of the system, forensically sound, customizable and compact.
* [Magnet ACQUIRE](https://www.magnetforensics.com/magnet-acquire/) - ACQUIRE by Magnet Forensics allows various types of disk acquisitions to be performed on Windows, Linux, and macOS as well as mobile operating systems (Android and iOS).

### Evidence Collection

[Back to Top](#table-of-contents)

 **Evidence Collection** - is a set of protocols that apply to both pre-collection and post-collection evidence. This process helps with Preserving & Collecting Evidence making sure the evidence is not destroyed or devalued as a source of information.

* [Acquire](https://github.com/fox-it/acquire) - Acquire is a tool to quickly gather forensic artifacts from disk images or a live system into a lightweight container. This makes Acquire an excellent tool to, among others, speedup the process of digital forensic triage. It uses [Dissect](https://github.com/fox-it/dissect) to gather that information from the raw disk, if possible.
* [artifactcollector](https://github.com/forensicanalysis/artifactcollector) - The artifactcollector project provides a software that collects forensic artifacts on systems.
* [bulk_extractor](https://github.com/simsong/bulk_extractor) - Computer forensics tool that scans a disk image, a file, or a directory of files and extracts useful information without parsing the file system or file system structures. Because of ignoring the file system structure, the program distinguishes itself in terms of speed and thoroughness.
* [Forensic Artifacts](https://github.com/ForensicArtifacts/artifacts) - Digital Forensics Artifact Repository
* [Live Response Collection](https://www.brimorlabs.com/tools/) - Automated tool that collects volatile data from Windows, macOS, and \*nix based operating systems.
* [Margarita Shotgun](https://github.com/ThreatResponse/margaritashotgun) - Command line utility (that works with or without Amazon EC2 instances) to parallelize remote memory acquisition.
* [UAC](https://github.com/tclahr/uac) - UAC (Unix-like Artifacts Collector) is a Live Response collection script for Incident Response that makes use of native binaries and tools to automate the collection of AIX, Android, ESXi, FreeBSD, Linux, macOS, NetBSD, NetScaler, OpenBSD and Solaris systems artifacts.

### Incident Management

[Back to Top](#table-of-contents)

**Incident Management** - is the process used by development and IT Operations teams to respond to an unplanned event or service interruption and restore the service to its operational state.

* [Catalyst](https://github.com/SecurityBrewery/catalyst) - A free SOAR system that helps to automate alert handling and incident response processes.
* [CyberCPR](https://www.cybercpr.com) - Community and commercial incident management tool with Need-to-Know built in to support GDPR compliance while handling sensitive incidents.
* [Cyphon](https://medevel.com/cyphon/) - Cyphon eliminates the headaches of incident management by streamlining a multitude of related tasks through a single platform. It receives, processes and triages events to provide an all-encompassing solution for your analytic workflow — aggregating data, bundling and prioritizing alerts, and empowering analysts to investigate and document incidents.
* [CORTEX XSOAR](https://www.paloaltonetworks.com/cortex/xsoar) - Palo Alto security orchestration, automation and response platform with full Incident lifecycle management and many integrations to enhance automations.
* [DFTimewolf](https://github.com/log2timeline/dftimewolf) - A framework for orchestrating forensic collection, processing and data export.
* [DFIRTrack](https://github.com/dfirtrack/dfirtrack) - Incident Response tracking application handling one or more incidents via cases and tasks with a lot of affected systems and artifacts.
* [Fast Incident Response (FIR)](https://github.com/certsocietegenerale/FIR/) - Cybersecurity incident management platform designed with agility and speed in mind. It allows for easy creation, tracking, and reporting of cybersecurity incidents and is useful for CSIRTs, CERTs and SOCs alike.
* [RTIR](https://www.bestpractical.com/rtir/) - Request Tracker for Incident Response (RTIR) is the premier open source incident handling system targeted for computer security teams. We worked with over a dozen CERT and CSIRT teams around the world to help you handle the ever-increasing volume of incident reports. RTIR builds on all the features of Request Tracker.
* [Sandia Cyber Omni Tracker (SCOT)](https://github.com/sandialabs/scot) - Incident Response collaboration and knowledge capture tool focused on flexibility and ease of use. Our goal is to add value to the incident response process without burdening the user.
* [Shuffle](https://github.com/frikky/Shuffle) - A general purpose security automation platform focused on accessibility.
* [threat_note](https://github.com/defpoint/threat_note) - Lightweight investigation notebook that allows security researchers the ability to register and retrieve indicators related to their research.
* [Zenduty](https://www.zenduty.com) - Zenduty is a novel incident management platform providing end-to-end incident alerting, on-call management and response orchestration, giving teams greater control and automation over the incident management lifecycle.


### Sandboxing/Reversing Tools

[Back to Top](#table-of-contents)

**Sandboxing** - is a security practice in which you use an isolated environment, or a "sandbox," for testing. Within the sandbox you run code, analyze the code in a safe, isolated environment without affecting the application, system or platform.

**Reverse-engineering** - is the process of dismantling a device, system, or piece of software to see how it works. It's done primarily to analyze and gain knowledge about the way a product works but often is used to duplicate or enhance the product.

* [Any Run](https://app.any.run/) - Interactive online malware analysis service for dynamic and static research of most types of threats using any environment.
* [CAPEv2](https://github.com/kevoreilly/CAPEv2) - Malware Configuration And Payload Extraction.
* [Cutter](https://github.com/radareorg/cutter) - Reverse engineering platform powered by Radare2.
* [Ghidra](https://github.com/NationalSecurityAgency/ghidra) - Software Reverse Engineering Framework.
* [Hybrid-Analysis](https://www.hybrid-analysis.com/) - Free powerful online sandbox by CrowdStrike.
* [Intezer](https://analyze.intezer.com/#/) - Intezer Analyze dives into Windows binaries to detect micro-code similarities to known threats, in order to provide accurate yet easy-to-understand results.
* [Joe Sandbox (Community)](https://www.joesandbox.com/) - Joe Sandbox detects and analyzes potential malicious files and URLs on Windows, Android, MacOS, Linux, and iOS for suspicious activities; providing comprehensive and detailed analysis reports.
* [Mastiff](https://github.com/KoreLogicSecurity/mastiff) - Static analysis framework that automates the process of extracting key characteristics from a number of different file formats.
* [Metadefender Cloud](https://www.metadefender.com) - Free threat intelligence platform providing multiscanning, data sanitization and vulnerability assessment of files.
* [Radare2](https://github.com/radareorg/radare2) - Reverse engineering framework and command-line toolset.
* [Reverse.IT](https://www.reverse.it/) - Alternative domain for the Hybrid-Analysis tool provided by CrowdStrike.
* [StringSifter](https://github.com/fireeye/stringsifter) - A machine learning tool that ranks strings based on their relevance for malware analysis.
* [Threat.Zone](https://app.threat.zone) - Cloud based threat analysis platform which include sandbox, CDR and interactive analysis for researchers. 
* [Valkyrie Comodo](https://valkyrie.comodo.com) - Valkyrie uses run-time behavior and hundreds of features from a file to perform analysis.
* [Viper](https://github.com/viper-framework/viper) - Python based binary analysis and management framework, that works well with Cuckoo and YARA.
* [Virustotal](https://www.virustotal.com) - Free online service that analyzes files and URLs enabling the identification of viruses, worms, trojans and other kinds of malicious content detected by antivirus engines and website scanners.

# Gaming
[Back to the Top](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

<p align="center">
  <img src="https://github.com/mikeroyal/Apple-Silicon-Guide/assets/45159366/0a5dc137-c500-420e-8296-d2d25e97feb0">
 <br />
</p>

## Gaming on Apple Silicon Resources

 * **[Apple Game Porting Toolkit 1.0](https://github.com/apple/homebrew-apple/tree/main/Formula)**
 * **[ALL WORKING GAMES LIST (Game Porting Toolkit = Windows DX12 Latest Games for Apple Silicon)](https://docs.google.com/spreadsheets/d/1t_E04Qt411f9mEZJVku_OJsEe6XCqZZsdqtjVaMCcgk/edit?usp=sharing)**
 * **[Bring your game to Mac, Part 1: Make a game plan](https://developer.apple.com/videos/play/wwdc2023/10123)**
 * **[Bring your game to Mac, Part 2: Compile your shaders](https://developer.apple.com/videos/play/wwdc2023/10124/)**
 * **[Bring your game to Mac, Part 3: Render with Metal](https://developer.apple.com/videos/play/wwdc2023/10125)**
 * **[Apple Silicon Games](https://applesilicongames.com/games)** 
 * **[M1 Parallels Windows compatible games list | AppleGamingWiki](https://www.applegamingwiki.com/wiki/M1_Parallels_Windows_compatible_games_list)**
 * **[M1 compatible Games Master List | AppleGamingWiki ](https://www.applegamingwiki.com/wiki/M1_compatible_games_master_list)**
 * **[Games and Apps on Apple Silicon (Compatibility Sheet) by Thomas Schranz(@__tosh on Twitter) ](https://docs.google.com/spreadsheets/d/1er-NivvuIheDmIKBVRu3S_BzA_lZT5z3Z-CxQZ-uPVs)** 
 * **[Porting Kit | Install Windows apps in Mac](https://www.portingkit.com/)**
 * **[MacGaming Subreddit](https://www.reddit.com/r/macgaming)**
 * **[iOS Gaming Subreddit](https://www.reddit.com/r/iosgaming/)**
 * **[Apple Arcade Subreddit](https://www.reddit.com/r/AppleArcade/)**
 
 
## MacOS Game Mode

[Back to the Top](#table-of-contents)

 
**[Game Mode](https://www.apple.com/newsroom/2023/06/macos-sonoma-brings-new-capabilities-for-elevating-productivity-and-creativity/)** is a tool enabled in **macOS 14**, it prioritizes CPU and GPU power for the game title you're running. Optimizing your gaming experience across the board with smoother and more consistent frame rates. For example, Game Mode makes gaming on Mac more immersive by lowering audio latency with AirPods, and significantly reducing input latency with popular game controllers like those for Xbox and PlayStation by doubling the Bluetooth sampling rate. 

 * [Game Controller](https://developer.apple.com/documentation/gamecontroller) is an Apple framework to support users interacting with your app using a physical or virtual game controller. Game controllers include third-party products, such as the DualShock 4, DualSense, and Xbox, as well as the mouse, keyboard, Siri Remote, and racing wheels. 

<p align="center">
  <img src="https://github.com/mikeroyal/Apple-Silicon-Guide/assets/45159366/fa3f2a70-df44-4e94-99cd-93fd7de1adf7">
 <br />
 Game Mode. Image Credit: Apple
</p>

## Game Porting Toolkit

[Back to the Top](#table-of-contents)

<h3 align="center">
 <img src="https://github.com/mikeroyal/Apple-Silicon-Guide/assets/45159366/375b3bc6-3a9a-4a71-90a1-8181254260ff">
  <br />
 
</h3>

[Game Porting Toolkit](https://github.com/apple/homebrew-apple/tree/main/Formula) is Apple's new translation layer which combines Wine with Apple's own D3DMetal which supports [DirectX 9 through 12](https://en.wikipedia.org/wiki/DirectX). Games that use anti-cheat([Easy Anti-Cheat](https://www.easy.ac/) and [BattleEye](https://www.battleye.com/)) or aggressive [DRM](https://en.wikipedia.org/wiki/Digital_rights_management) generally don't work. Games that require [AVX/AVX 2](https://en.wikipedia.org/wiki/Advanced_Vector_Extensions) CPUs also don't work.

 * The Game Porting Toolkit builds a [dxil](https://github.com/Microsoft/DirectXShaderCompiler/blob/main/docs/DXIL.rst) to [metallib](https://developer.apple.com/documentation/metal) converter and DirectX11/DirectX12 to Metal runtime translator. Non-graphics APIs are translated by Wine and do not use any tech from [moltenVK](https://github.com/KhronosGroup/MoltenVK), [DXVK](https://github.com/doitsujin/dxvk); or [SPIRV-Cross](https://github.com/KhronosGroup/SPIRV-Cross). The Metal shader converter can be shipped by games and can be used in the game developer asset pipelines.
 
 * [Metal shader converter](https://developer.apple.com/metal/shader-converter/) is a tool that converts shader intermediate representations in LLVM IR bytecode into bytecode suitable to be loaded into Metal. It’s available as a library and a standalone executable. All the functionality exposed through the library interface is available via the standalone executable.


<p align="center">
  <img src="https://github.com/mikeroyal/Apple-Silicon-Guide/assets/45159366/c04de75d-b1ad-4e8f-8f44-e750ca479081">
 <br />
 Game Porting Toolkit running Cyberpunk 2077 on a  M1 Macbook. Image Credit: Isaac Marovitz
</p>

[![Game Porting Toolkit gets a BIG SURPRISE update! | Andrew Tsai](https://ytcards.demolab.com/?id=Nl12azxMbFc&lang=en&background_color=%230d1117&title_color=%23ffffff&stats_color=%23dedede&width=240 "Game Porting Toolkit gets a BIG SURPRISE update! | Andrew Tsai")](https://www.youtube.com/watch?v=Nl12azxMbFc)
[![The Mac gaming DirectX 12 Revolution is NOW!](https://ytcards.demolab.com/?id=CcYyvzHtJVM&lang=en&background_color=%230d1117&title_color=%23ffffff&stats_color=%23dedede&width=250 "The Mac gaming DirectX 12 Revolution is NOW!")](https://www.youtube.com/watch?v=CcYyvzHtJVM)
[![Play ANY Windows Game on Mac with the Game Porting Toolkit! | Step-by-Step Guide](https://ytcards.demolab.com/?id=jUvDPCxkHIU&lang=en&background_color=%230d1117&title_color=%23ffffff&stats_color=%23dedede&width=250 "Play ANY Windows Game on Mac with the Game Porting Toolkit! | Step-by-Step Guide")](https://www.youtube.com/watch?v=jUvDPCxkHIU)

**Working Games:**

 * **[ALL WORKING GAMES LIST (Game Porting Toolkit = Windows DX12 Latest Games for Apple Silicon)](https://docs.google.com/spreadsheets/d/1t_E04Qt411f9mEZJVku_OJsEe6XCqZZsdqtjVaMCcgk/edit?usp=sharing)**

 *  Cyberpunk 2077
 *  Elden Ring  
 *  Diablo IV 
 *  Hogwarts Legacy
 *  Crysis Remastered
 *  Cuphead
 *  Halo 3 (No Online due to Easy Anti-Cheat Compatibility)
 *  Metal Gear Solid V: The Phantom Pain
 *  Final Fantasy VII Remake Intergrade (~50 FPS on High settings at 1080p with M1 Pro.)
 *  God of War (Works somewhat well on M1 Pro (16gb), wouldn't recommend lesser hardware.)
 *  Deep Rock Galactic
 *  Sonic Omens
 *  Sonic P-06
 *  Scarlet Nexus
 *  Dyson Sphere Program (some objects and main character weren't visible before)
 *  Derail Valley (good performance, no missing manuals, and in-game objects for train operation like on CrossOver)
 *  Spider-Man (2018)
 *  Spider-Man Miles Morales - requires Windows version fix.
 *  Warframe - To get installer/launcher working add dwrite (disabled) to library overrides in winecfg.
 *  QUBE 2
 *  Deceive Inc. - works well if launched without EAC.
 *  Risk of Rain 2 (does not require `-disable-gpu-skinning` like Crossover 22.)
 *  Tetris Effect: (Connected - Game window doesn't like retina mode, works otherwise.)
 *  Bloodstained: Ritual of the Night
 
### System Requirements
 
   * macOS Sonoma should be used, currently it is in beta. 
   * macOS Ventura causes large numbers of issues with steamwebhelper.exe crashing so it isn't recommended, use the macOS Sonoma beta.
   * [Visit Apple Developer Downloads site](https://developer.apple.com/downloads), these files are now free to download use for any logged in Apple account.
       - Search for Command Line Tools for Xcode 15 beta and download the dmg file, then install it.
       - If you have an old version Xcode installed, remove it.
       - Search for Game Porting Toolkit and download it. Open the dmg file and then run the pkg.
       
### Using Homebrew

**Note:** if you have ever installed Homebrew before, then it is advisable to remove arm64 Homebrew as this can interfere with this build process. Either use a Homebrew uninstall script or delete the folder ```/opt/homebrew/bin```.

Open Terminal (search in Spotlight on macOS).

**Install Rosetta:**

```softwareupdate --install-rosetta```

Rosetta 환경에서 다음 단계를 계속하려면 x86_64 셸을 입력하세요. 모든 후속 명령은 이 셸 내에서 실행되어야 합니다.

```arch -x86_64 zsh```

Install the x86_64 version of Homebrew if you don't already have it.

```/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"```

**brew 명령이 경로에 있는지 확인하세요.**

```which brew```

**If this command does not print ```/usr/local/bin/brew```, you should use this command:**

```export PATH=/usr/local/bin:${PATH}```

### 짓다

**Apple 탭을 다운로드하려면 다음 명령을 실행하세요.**

```brew tap apple/apple http://github.com/apple/homebrew-apple```

Install the game-porting-toolkit formula. This formula downloads and compiles several large software projects. How long this takes will depend on the speed of your computer. It can take over 1 hour to complete depending on the speed of your Mac.

```brew -v install apple/apple/game-porting-toolkit```

설치 중에 "오류: game-porting-toolkit: 알 수 없거나 지원되지 않는 macOS 버전: :dunno"와 같은 오류가 표시되면 사용 중인 Homebrew 버전에 macOS Sonoma가 지원되지 않는 것입니다. 최신 버전의 Homebrew로 업데이트하고 다시 시도하세요.

```brew update brew -v install apple/apple/game-porting-toolkit```

### Wine prefix 

A Wine prefix contains a virtual C: drive. You will install the toolkit and your game into this virtual C: drive. Run the following command to create a new Wine prefix named my-game-prefix in your home directory.

```WINEPREFIX=~/my-game-prefix `brew --prefix game-porting-toolkit`/bin/wine64 winecfg```

   * 화면에 "와인 구성" 창이 나타납니다.
   * Windows 버전을 Windows 10으로 변경하세요.
   * 적용을 선택한 다음 확인을 선택하여 winecfg를 종료합니다.

"와인 구성" 창이 나타나지 않고 Dock에 새 아이콘이 나타나지 않으면 x86_64 버전의 Homebrew와 게임 포팅 툴킷 공식이 올바르게 설치되었는지 확인하세요.

**툴킷 준비 중**

앞서 다운로드한 Game Porting Toolkit dmg가 ```/Volumes/Game Porting Toolkit-1.0```에 마운트되어 있는지 확인하세요. 이 스크립트를 사용하여 Game Porting Toolkit 라이브러리 디렉터리를 Wine의 라이브러리 디렉터리에 복사하세요.

```ditto /Volumes/Game\ Porting\ Toolkit-1.0/lib/ `brew --prefix game-porting-toolkit`/lib/```

**Put the 3 scripts from the Game Porting Toolkit DMG into here /usr/local/bin using this command:**

```cp /Volumes/Game\ Porting\ Toolkit*/gameportingtoolkit* /usr/local/bin```

### 스팀 설치

<h3 align="center">
 <img src="https://github.com/mikeroyal/Apple-Silicon-Guide/assets/45159366/7c41f9fc-6195-44ac-9398-d1d32da78749">
  <br />
 
</h3>

Steam 웹사이트로 이동하여 Windows 버전의 [Steam](https://cdn.cloudflare.steamstatic.com/client/installer/SteamSetup.exe)을 다운로드하고 다운로드 폴더에 넣으세요.

**스팀 설치**

```gameportingtoolkit ~/my-game-prefix ~/Downloads/SteamSetup.exe```

**Run Steam**

```gameportingtoolkit ~/my-game-prefix 'C:\Program Files (x86)/Steam/steam.exe'```

Steam에 로그인 일반적인 문제는 Steam에 빈 검은색 창이 표시된다는 것입니다.

Steam을 시작하는 다른 방법(설치 후):

```MTL_HUD_ENABLED=1 WINEESYNC=1 WINEPREFIX=~/my-game-prefix /usr/local/Cellar/game-porting-toolkit/1.0/bin/wine64 'C:\Program Files (x86)/Steam/steam.exe'```

If this continues then close the Terminal window and then re-open and try again, repeat until the login screen opens. Now you should be able to download and launch Windows games through Steam.

## Epic/Heroic Games and GOG support

<h3 align="center">
 <img src="https://github.com/mikeroyal/Apple-Silicon-Guide/assets/45159366/992edc00-18e8-4f51-ab7b-0f047ffb6f84">
  <br />
 
</h3>

This is particularly useful because as it currently, the real Epic Games Launcher fails to install under the Game Porting Toolkit. Heroic supports Epic and GOG.com games.

   * Install the native [macOS Heroic Games Launcher](https://github.com/Heroic-Games-Launcher/HeroicGamesLauncher/releases) or from Homebrew.
   * Open Heroic, and log into your Epic Games and/or GOG.com account.
   * Go to the "Wine Manager" and install a numbered version of Wine, such that it won't auto update- we are going to modify it. 
   * At the time of writing this, the newest numbered version of Wine-Crossover is ```Wine-Crossover-Wine-22.1.0```
   * Press the folder icon that appears after installing it to open the directory containing Heroic's Wine installations.
   * Right-click on the version of Wine you just installed and press "Show Package Contents".
   * Open this directory in the Terminal.
       * If you have **"OpenInTerminal"** this is one button, otherwise press **"Show Path Bar"** and navigate where it says with **"cd"**.
       * It should be something like ```cd ~/Library/Application\ Support/heroic/tools/wine/Wine-crossover-wine-22.1.0```.

   ```cd Contents/MacOS```

   **기존 와인 제거:**

   ```rm wine```

  ###  Create a symlink to Game Porting Toolkit's Wine
        
   **If using Game Porting Toolkit Wineprefix:**

   ```ln -s `/usr/local/bin/brew --prefix game-porting-toolkit`/bin/wine64 wine```

   **위스키를 사용하는 경우:**

   ```ln -s /Applications/Whisky.app/Contents/Resources/Libraries/Wine/bin/wine64 wine```
      
   ``` cd ../Resources```

  **기존 와인 제거:**

  ```rm -rfv wine```

   ### Create a symlink to Game Porting Toolkit's Wine
    
   **If using Game Porting Toolkit Wineprefix:**

   ```ln -s `/usr/local/bin/brew --prefix game-porting-toolkit` wine```

   **위스키를 사용하는 경우:**

   ```ln -s /Applications/Whisky.app/Contents/Resources/Libraries/Wine wine```

   * You are now done with Terminal. Install any games you want to try playing.
   * Select the game you want to play, and press the settings button in the top-right.
   * Make sure the version of Wine you just downloaded and modified is selected.
   * Make sure your Game Porting Toolkit Wine Prefix is selected. If you followed Apple's guide this is ```/Users/you/my-game-prefix```.
   * If you Open the "Other" section you can also add any environment variables you want like ```WINEESYNC=1"``` and ```"MTL_HUD_ENABLED=1"```
   * Close the settings and try running the game.
 
 
## Battle.net

<h3 align="center">
 <img src="https://github.com/mikeroyal/Apple-Silicon-Guide/assets/45159366/fc90046c-797d-47cb-9073-25af1d847660">
  <br />
 
</h3>

Please download the [Windows version of Battle.net](https://download.battle.net/en-gb/?platform=windows).

**Make a new Wineprefix for Battle.net - we will refer to this as battle-net from now:**

```WINEPREFIX=~/battle-net `brew --prefix game-porting-toolkit`/bin/wine64 winecfg```

  * 화면에 "와인 구성" 창이 나타납니다.
  * Windows 버전을 Windows 10으로 변경하세요.
  * 적용을 선택한 다음 확인을 선택하여 winecfg를 종료합니다.

Battle.net 런처 실행

```gameportingtoolkit ~/battle-net ~/Downloads/Battle.net-Setup.exe```

Please be aware that there is an issue launching Battle.net once installed, the only current way to re-login is to 'install' the launcher again.

Start individual game without the launcher using this command:

```arch -x86_64 gameportingtoolkit-no-hud ~/battle-net 'C:\Program Files (x86)\Diablo IV\Diablo IV Launcher.exe'```

### 개별 게임 출시

Finder ```(open ~/my-game-prefix/drive_c)```에서 Wine 접두사의 가상 C: 드라이브를 열고 게임을 적절한 하위 디렉터리에 복사하세요.

**에이. 표준 출시**

```gameportingtoolkit ~/my-game-prefix 'C:\Program Files\MyGame\MyGame.exe'```

This launches the given Windows game binary with a visible extended Metal Performance HUD and filters logging to output from the Game Porting Toolkit.

**B. Launching without a HUD**

```gameportingtoolkit-no-hud ~/my-game-prefix 'C:\Program Files\MyGame\MyGame.exe'```

**기음. Wine ESYNC 비활성화로 실행**

```gameportingtoolkit-no-esync ~/my-game-prefix 'C:\Program Files\MyGame\MyGame.exe'```

### Logging 

The provided ```bin/gameportingtoolkit*``` scripts can be copied onto your path to facilitate different forms of logging and launching. You can run these scripts from any shell; you don’t need to switch to the Rosetta environment first.

Logging output will appear in the Terminal window in which you launch your game as well as the system log, which can be viewed with the Console app found in Applications ▸ Utilities. Log messages from the Game Porting Toolkit are prefixed with D3DM. By default the gameportingtoolkit* scripts will filter to just the D3DM-prefixed messages.
Troubleshooting • Link

### Steam login black screen

Close the Terminal window and then reopen and retry the command, repeat several times.

Alternate way of launching Steam (after installing):

```MTL_HUD_ENABLED=1 WINEESYNC=1 WINEPREFIX=<path to the Wine bottle you set up> /usr/local/Cellar/game-porting-toolkit/1.0/bin/wine64 'C:\Program Files (x86)/Steam/steam.exe'```

그래도 작동하지 않으면 CrossOver를 사용하여 Steam 병을 만든 다음 이 WINEPREFIX를 해당 병으로 리디렉션하세요.

```WINEPREFIX="/Users/[username]/Library/Application Support/CrossOver/Bottles/Steam/"```

**Steam crashes straight after opening:** Disconnect any external monitors.

**Battle.net launcher won't re-launch:** Re-install the launcher to reopen, no other fix at the moment.

Game won’t run because it thinks the version of Windows is too old. Some games detect specific minimum versions of Windows and need to be updated. Use this script to update your wineprefix with build 19042 which should work for most games e.g. Spider-Man Remastered.

```WINEPREFIX=~/my-game-prefix `brew --prefix game-porting-toolkit`/bin/wine64 reg add 'HKEY_LOCAL_MACHINE\Software\Microsoft\Windows NT\CurrentVersion' /v CurrentBuild /t REG_SZ /d 19042 /f```

```WINEPREFIX=~/my-game-prefix `brew --prefix game-porting-toolkit`/bin/wine64 reg add 'HKEY_LOCAL_MACHINE\Software\Microsoft\Windows NT\CurrentVersion' /v CurrentBuildNumber /t REG_SZ /d 19042 /f```

```WINEPREFIX=~/my-game-prefix `brew --prefix game-porting-toolkit`/bin/wineserver -k```

**steamwebhelper.exe 충돌**

이는 Steam이 macOS Ventura 이하에서 실행되고 있기 때문에 발생합니다. macOS Sonoma로 업그레이드하세요.

**잘못된 명령으로 인해 게임이 실행되지 않고 충돌합니다**

**잘못된 지침** 충돌은 종종(항상 그런 것은 아님) Rosetta 2가 AVX/AVX2 지침을 번역할 수 없을 때 발생합니다. 이 오류가 발생했을 때 Game Porting Toolkit을 사용하여 Apple Silicon에서의 잠재력을 평가하기 위해 AVX/AVX2 지침 없이 게임 버전을 다시 컴파일할 수 있습니다. 코드를 기본적으로 Apple Silicon으로 포팅할 때 NEON 명령어는 AVX/AVX2를 고성능으로 대체합니다.

**안티치트 또는 DRM 소프트웨어가 Wine 번역과 호환되지 않기 때문에 게임이 실행되지 않습니다.**

자체 평가 목적으로 치트 방지 또는 DRM을 비활성화한 상태로 Windows 개발 환경에서 게임의 사용자 지정 버전을 다시 빌드할 수 있습니다. 코드를 기본적으로 Apple Silicon 및 macOS로 포팅하는 경우 치트 방지 또는 DRM 제공업체에 문의하세요. 대부분은 기본 빌드에 대한 기본 Apple Silicon 솔루션을 갖추고 있습니다.

**Mono, .NET 또는 MSVCRT 런타임이 필요하기 때문에 게임이 실행되지 않습니다.**

게임 포팅 툴킷의 평가 환경은 이러한 런타임 지원 패키지를 사전 설치하지 않습니다. 게임에서 이러한 패키지 중 하나를 사용하는 경우 적절한 설치 프로그램(.exe 또는 .msi)을 검색하고 다운로드하여 평가 환경에 설치하는 것이 좋습니다. 설치 프로그램을 실행하고 설치 지침을 따르면 환경에서 추가 런타임 설치 프로그램을 실행할 수 있습니다.

```WINEPREFIX=~/my-game-prefix `brew --prefix game-porting-toolkit`/bin/wine64 <some-installer.exe>```

And .MSI packages can be installed by launching the Windows uninstaller application and choosing to install a downloaded .msi package:

```WINEPREFIX=~/my-game-prefix `brew --prefix game-porting-toolkit`/bin/wine64 uninstaller```

**컨트롤러 문제**

Steam 베타에 등록하면 문제가 해결될 수 있습니다.


## 위스키

[맨 위로 돌아가기](#목차)

[Whisky](https://github.com/IsaacMarovitz/Whisky)는 기본 SwiftUI에 내장된 Wine용 깔끔하고 사용하기 쉬운 그래픽 래퍼를 제공하는 도구입니다. 병을 만들고 관리할 수 있으며 Windows 앱과 게임을 설치하고 실행할 수 있습니다. 위스키는 [CrossOver 22.1.1](https://www.codeweavers.com/crossover/download-now)과 [Isaac Marovitz](https://twitter.com/isaacmarovitz)가 개발한 Apple의 [Game Porting Toolkit](https://github.com/apple/homebrew-apple/tree/main/Formula)과 [Gcenx](https://github.com/Gcenx)의 도움을 바탕으로 구축되었습니다.

<p align="center">
<img src="https://github.com/mikeroyal/Apple-Silicon-Guide/assets/45159366/7c44f35b-78a1-4d48-a01a-cf065b458a0b">
<br />
</p>

### MacOS용 크로스오버

[맨 위로 돌아가기](#목차)

[MacOS용 CrossOver](https://www.codeweavers.com/store)는 MacOS 시스템에서 많은 인기 Windows 게임을 실행할 수 있게 해주는 도구입니다. 사용하기 쉬운 단일 클릭 인터페이스가 제공되므로 게임을 간단하고 빠르게 설치할 수 있습니다. CrossOver는 CodeWeavers와 오픈 소스 Wine 커뮤니티의 기여를 바탕으로 최신 버전의 Wine을 기반으로 구축되었습니다.

 * [크로스오버 앱 호환성 데이터베이스](https://www.codeweavers.com/compatibility?browse=&app_desc=&company=&rating=&platform=&date_start=&date_end=&name=ea&search=app#results)
 
 * **권장:** [Microsoft Visual C++ 재배포 가능 ARM64 버전](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170)

[![5가지 새로운 기능 공개 - CrossOver 23으로 게임 수준을 높이세요](https://ytcards.demolab.com/?id=wtHJ3TReI-4&lang=en&background_color=%230d1117&title_color=%23ffffff&stats_color=%23dedede&width=240 "5가지 새로운 기능 공개 - CrossOver 23으로 게임 수준을 높이세요")](https://www.youtube.com/watch?v=wtHJ3TReI-4)
[![CrossOver 23을 사용하여 Mac에서 Astroneer를 플레이하는 방법](https://ytcards.demolab.com/?id=Mr2az2vGWtY&lang=en&background_color=%230d1117&title_color=%23ffffff&stats_color=%23dedede&width=240 "CrossOver 23을 사용하여 Mac에서 Astroneer를 플레이하는 방법")](https://www.youtube.com/watch?v=Mr2az2vGWtY)
[![이것은 CrossOver를 게임 포팅 툴킷보다 더 좋게 만듭니다!](https://ytcards.demolab.com/?id=AxKK3ctISnk&lang=en&background_color=%230d1117&title_color=%23ffffff&stats_color=%23dedede&width=240 "이것은 CrossOver를 게임 포팅 툴킷보다 더 좋게 만듭니다!")](https://www.youtube.com/watch?v=AxKK3ctISnk)

<img src="https://github.com/mikeroyal/Apple-Silicon-Guide/assets/45159366/b7315971-bf00-4070-8c3f-12ea38a3e1fd">

## Xbox Game Pass에서의 게임

[맨 위로 돌아가기](#목차)

**참고:** Xbox Game Pass Cloud Gaming은 [Apple의 Safari 브라우저](https://support.xbox.com/help/games-apps/cloud-gaming/setup-cloud-gaming-apple)를 통해 macOS, iPadOS 및 iOS에서 액세스할 수 있습니다. 하지만 최고의 성능을 위해서는 [Microsoft의 Edge 브라우저](https://www.microsoft.com/edge/download?form=MA13FJ)를 사용하는 것이 좋습니다. 또한 [Parallels](https://www.parallels.com/)를 사용하여 macOS 내 Windows 11에서 게임을 실행할 수 있습니다. 하지만 2D(Hollow Knight, Celeste 등) 및 낮은 그래픽 게임만 Parallels에서 기본적으로 잘 실행됩니다.

[Xbox Game Pass](https://xbox.com/xbox-game-pass)는 Microsoft의 비디오 게임 구독 서비스로, [Ultimate Pass](https://www.xbox.com/en-US/xbox-game-pass/ultimate)의 경우 $9.99 및 $14.99부터 시작합니다.

<p align="center">
 <img src="https://github.com/mikeroyal/Apple-Silicon-Guide/assets/45159366/a3c67440-bce6-45b2-b18b-8fb5b1c9ba4f">
</br>
</p>

### 플레이할 수 있는 훌륭한 [Game Pass](https://www.xbox.com/) 게임 목록입니다.

**5월 23일**

  * Planet of Lana(Xbox Series X|S 최적화, Xbox One, Windows PC 및 Xbox 클라우드 게임)

**5월 25일**

  * Cassette Beasts(Xbox Series X|S, Xbox One 및 Windows PC)

**5월 30일**

   * 치커리: 다채로운 이야기(Xbox Series X|S 최적화, Xbox One, Windows PC 및 Xbox 클라우드 게임)
   * Farworld Pioneers(Xbox Series X|S, Xbox One 및 Windows PC)
    
**6월 1일**

   * 자동차 정비사 시뮬레이터 2021(Xbox Series X|S 최적화, Xbox One, Windows PC 및 Xbox 클라우드 게임)
   * Slayers X: Terminal Aftermath: Vengeance of the Slayer(Xbox Series X|S, Xbox One, Windows PC 및 Xbox Cloud Gaming)
   * 빅콘(Xbox Series X|S 최적화, Xbox One, Windows PC 및 Xbox 클라우드 게임)

**6월 6일**

   * Amnesia: The Bunker(Xbox Series X|S, Xbox One, Windows PC 및 Xbox 클라우드 게이밍)
   * 최면 공간 무법자(Xbox Series X|S, Xbox One, Windows PC 및 Xbox 클라우드 게임)


**6월 8일**

   * Rune Factory 4 스페셜(Xbox Series X|S, Xbox One, Windows PC 및 Xbox 클라우드 게이밍)
   * 스태킹(Xbox Series X|S, Xbox One 및 Xbox 클라우드 게임)
    
**6월 13일**

   * 도르도뉴(Xbox Series X|S, Xbox One, Windows PC 및 Xbox 클라우드 게이밍)
   
**6월 22일**

   * 북워커: 도둑 이야기(Xbox Series X|S, Xbox One, Windows PC 및 Xbox Cloud Gaming)
   * Need for Speed: 언바운드(Xbox Series X|S 최적화, Windows PC 및 Xbox 클라우드 게이밍)(**EA Play** 통해)

**6월 27일**

   * Bramble: The Mountain King(Xbox Series X|S 최적화, Xbox One, Windows PC 및 Xbox 클라우드 게임)
   * F.I.S.T.: Forged in Shadow Torch(Xbox Series X|S, Windows PC 및 Xbox Cloud Gaming)

**6월 29일**

   * 계절 이야기: 미네랄 타운의 친구들(Xbox Series X|S, Xbox One, Windows PC)

**7월 3일**

   * 아케이드 파라다이스(Xbox Series X|S, Xbox One 및 Windows PC)

**7월 5일**

   * Grand Theft Auto V(Xbox Series X|S, Xbox One 및 Xbox 클라우드 게이밍)

   * Sword and Fairy: Together Forever(Xbox Series X|S, Xbox One 및 Windows PC)
   
**7월 6일**

 * McPixel 3(Xbox Series X|S, Xbox One, Windows PC 및 Xbox 클라우드 게이밍)
 
**7월 11일**

 * 공통점(Xbox Series X|S, Xbox One, Windows PC 및 Xbox 클라우드 게이밍)
 * 인서전시: 샌드스톰(윈도우 PC)
 
**7월 14일**
 
 * 엑소프라이멀(Xbox Series X|S, Xbox One, Windows PC 및 Xbox 클라우드 게이밍)
 
**7월 18일**

   * Techtonica(Xbox Series X|S, Xbox One 및 Windows PC)
   * The Cave(Xbox Series X|S, Xbox One 및 Xbox 클라우드 게이밍)
   
**7월 31일**
    
   * Venba(Xbox Series X|S, Xbox One 및 Windows PC)

**8월 1일**

 * Celeste(클라우드, Xbox Series X|S 및 PC)

**8월 3일**

 * 짧은 하이킹(클라우드, Xbox Series X|S 및 PC)

**8월 8일**

 * Broforce Forever(클라우드, Xbox Series X|S 및 PC)

**8월 9일**

 * Limbo(클라우드, (Xbox Series X|S 및 PC)

**8월 10일**

 * 에어본 킹덤(클라우드, Xbox Series X|S, PC)

**8월 15일**

 * Everspace 2(클라우드 및 Xbox Series X|S)

**8월 18일**

 * 텍사스 전기톱 학살(Xbox Series X|S, PC, 클라우드)

**8월 29일**

 * 바다의 별(Xbox Series X|S, 클라우드)
 
**9월 5일**

 * Gris(클라우드, 콘솔, PC)
   
**9월 6일** 또는 **9월 1일 [스타필드 프리미엄 에디션 업그레이드](https://www.xbox.com/games/store/starfield-premium-edition-upgrade/9PB4ZWV7S2MG/0017)**

   * 스타필드 다이렉트(Xbox Series X|S, 클라우드 및 Windows PC)
   
** 9월 19일**

 * P의 거짓말(Xbox Series X|S, 클라우드 및 Windows PC)

** 9월 20일**

 * 파티 동물(Xbox Series X|S, Xbox One 및 Windows PC)

** 9월 23일**

 * Payday 3(Xbox Series X|S, 클라우드 및 Windows PC)
 
**9월 29일**
 
   * 누에고치(Xbox Series X|S, Xbox One 및 Windows PC)

**10월 3일**

   * 램프라이터 리그(콘솔, PC)

**10월 4일**
  
  * 워해머 40,000 다크타이드(콘솔 [Xbox Series X|S])

**10월 10일**
   
  * 포르자 모터스포츠(콘솔[Xbox Series X|S], PC, 클라우드)
    
**10월 24일**

  * 시티즈 스카이라인 2(콘솔[Xbox Series X|S], PC, 클라우드)

**10월 26일**
    
  * 미네코 야시장 (콘솔[Xbox Series X|S], PC)

**10월 31일**
  
  * Headbangers Rhythm Royale(콘솔[Xbox Series X|S])
  * 주산트(콘솔[Xbox Series X|S], PC, 클라우드)

**11월 1일**

 * Age of Empires II: Definitive Edition – The Mountain Royals(클라우드, 콘솔 및 PC)

**11월 2일**

 * 플레이트업! (콘솔)
 * 목마른 구혼자(클라우드, 콘솔, PC)

** 11월 6일**

 * 풋볼매니저 2024 (PC)
 * Football Manager 2024 콘솔(클라우드, 콘솔 및 PC)
 
**11월 7일**

 * 로보퀘스트 1.0 (클라우드, 콘솔, PC)

**11월 9일**

 * 던전 4(클라우드, 콘솔, PC)
 * 용 외전처럼: 이름을 지운 남자 (클라우드, 콘솔, PC)
 * Wild Hearts(클라우드, 콘솔, PC) EA Play

**11월 13일**

 * Spirittea(클라우드, 콘솔, PC)

**11월 14일**

 * 산호섬(클라우드 및 Xbox Series X|S)

**2023년 11월 15일에 종료되는 게임**

 * 커피톡(클라우드, 콘솔, PC)
 * 엑사펑크(PC)
 * 고스트송(클라우드, 콘솔, PC)
 * Gungrave G.O.R.E (클라우드, 콘솔, PC)
 * 풋볼매니저 2023(PC)
 * Football Manager 2023 콘솔(클라우드, 콘솔 및 PC)
 * 라핀(클라우드, 콘솔, PC)
 * 타운스케이퍼(클라우드, 콘솔, PC)

**11월 28일**

 * Rollerdrome(PC, 클라우드 및 Xbox Series X|S)

**12월 1일**

 * Remnant: From the Ashes (클라우드, 콘솔, PC)
 * Spirit of the North (클라우드, 콘솔, PC)
 * SteamWorld 빌드(클라우드, 콘솔 및 PC)

**12월 5일**

 * 위험 지역의 클론 드론(클라우드, PC 및 Xbox Series X|S)
 * Rise of the Tomb Raider(클라우드, 콘솔, PC)
 * While the Iron's Hot (클라우드, 콘솔, PC)
 * World War Z: Aftermath (클라우드, 콘솔, PC)

**12월 6일 - Game Pass Core에 출시 예정**
 * 기사도 2
 * 완전히 신뢰할 수 있는 배송 서비스

**12월 7일**

 * Goat Simulator 3(클라우드, PC 및 Xbox Series X|S)

**12월 8일**

 * 폭풍에 맞서 (PC)

**12월 13일**

 * Tin Hearts(클라우드, 콘솔, PC)

**12월 14일**

 * Far Cry 6(클라우드, 콘솔, PC)

**12월 15일 출발**

다음 게임이 곧 종료됩니다. 해당 게임을 최대 20% 할인된 가격으로 라이브러리에 보관하세요.

  * 연결된 에코(클라우드, 콘솔 및 PC)
  * 위대한 일(PC)
  * 물약 제작: 연금술사 시뮬레이터(클라우드, 콘솔, PC)
  * 러버밴디트(클라우드, 콘솔, PC)

**2024년 초**
    
   * 바운티 스타(Xbox Series X|S, Xbox One 및 Windows PC)
   * Ghostbike(Xbox Series X|S, Xbox One 및 Windows PC)
   * 무리(Xbox Series X|S, Xbox One 및 Windows PC)
   * A T(Xbox Series X|S, Xbox One 및 Windows PC)

   
## 오프라인 사용을 위한 Game Pass 설정(Windows에만 해당)
 
 * **macOS에서 Windows 11을 실행하려면 [Parallels](https://www.parallels.com/)를 사용해야 합니다. 또한 2D(Hollow Knight, Celeste 등..) 및 낮은 그래픽 게임만 Parallels에서 기본적으로 잘 실행됩니다.**

 * **참고:** 캠페인 모드가 있는 대부분의 게임은 오프라인으로 플레이할 수 있지만, 네트워크 협동 또는 멀티플레이어 기능이 있는 게임은 오프라인인 동안 작동하지 않습니다. 오프라인으로 전환하기 전에 Xbox 네트워크에 연결하여 최신 게임 저장을 클라우드에 동기화하세요. 오프라인으로 플레이하는 동안 게임 저장 진행 상황은 계속해서 로컬에 저장되며 다음에 Xbox에 로그인할 때 동기화됩니다. 다른 장치에서 계속 플레이하려면 온라인으로 접속하여 Xbox 네트워크에 연결하여 로컬에 저장된 게임이 클라우드와 다시 동기화되도록 해야 합니다.

 * **참고 2:** PC Game Pass 게임 라이선스는 오프라인으로 플레이할 때 30일 후에 만료되며, 소유한 게임의 라이선스는 14일 후에 만료됩니다. 오프라인으로 게임을 계속 플레이하려면 온라인으로 돌아가서 게임을 시작하세요. 이렇게 하면 장치의 게임 라이선스가 갱신되고 오프라인으로 다시 플레이할 수 있게 됩니다.

지정된 오프라인 장치로는 하나의 장치만 사용할 수 있습니다. **기기를 지정된 오프라인 기기로 설정하려면:**

  * 온라인 상태인지 확인하세요.
  * 장치에 최신 Windows 업데이트가 있는지 확인하세요. **시작 -> 설정 -> 업데이트 및 보안 -> Windows 업데이트로 이동하여 관련 업데이트가 있는지 확인하세요**.
  * 마이크로소프트 스토어를 엽니다. 아직 로그인하지 않았다면 로그인하라는 메시지가 표시됩니다.
  * 오른쪽 상단의 프로필 아이콘을 선택하세요.
  * 앱 설정을 선택한 다음 오프라인 권한에서 토글이 켜짐으로 설정되어 있는지 확인하세요.

이를 설정하면 이전에 오프라인으로 지정되었던 모든 장치가 꺼짐으로 전환되고 해당 장치에서는 더 이상 오프라인으로 게임을 플레이할 수 없습니다.

**게임 준비**

장치가 설정되면 Xbox 네트워크에 로그인한 상태에서 오프라인으로 플레이하려는 각 게임을 시작해야 합니다. 이 작업은 게임당 한 번만 수행하면 되며, 장치에서 이미 게임을 시작한 경우에도 이 작업을 수행해야 합니다.

  * 온라인 상태인지, 기기가 지정된 오프라인 기기로 설정되어 있는지 확인하세요. (이 작업을 수행하는 방법에 대한 자세한 내용은 위의 단계를 참조하세요.)
  * 오프라인으로 플레이하고 싶은 게임을 실행하세요. 메시지가 표시되면 Xbox에 로그인합니다.
  * 게임을 시작한 후에는 언제든지 종료할 수 있습니다.

오프라인으로 플레이하려는 각 게임에 대해 이 과정을 반복하세요. 완료되면 매번 온라인으로 로그인할 필요 없이 언제든지 오프라인으로 전환하여 플레이하고 싶을 때마다 해당 게임을 실행할 수 있습니다.

 
## 온도/팬 관리(CPU 및 GPU)

[맨 위로 돌아가기](#목차)

[통계](https://github.com/exelban/stats)는 메뉴 모음에서 macOS 시스템을 모니터링할 수 있는 도구입니다.

 * 배터리 잔량
 * 블루투스 장치
 * CPU 활용도
 * 디스크 활용도
 * 팬 제어
 * GPU 활용도
 * 메모리 사용량
 * 네트워크 사용량
 * 센서 정보(온도/전압/전력)
 
 <p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/224650106-1be2ae52-e54d-48b1-acbd-a71a9fc1d1d1.png">
</p>


[iStat 메뉴](https://bjango.com/mac/istatmenus/)는 macOS 밝은 메뉴 막대 모드와 어두운 메뉴 표시줄 모드를 완벽하게 지원하는 고도로 구성 가능한 도구입니다. CPU 모니터, GPU, 메모리, 네트워크 사용량, 디스크 사용량, 디스크 활동, 날짜 및 시간, 배터리 등을 포함한 광범위한 통계를 다룹니다.

<p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/208856211-94234e2c-35c0-41e1-9d9e-a0ecaa844c6a.png">
</p>

<p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/208857140-af14f17a-3f18-49a3-a413-ca692b88e745.png">
</p>

 
## 게임 주변기기

### RGB 장치

[맨 위로 돌아가기](#목차)

[Logitech G Hub](https://www.logitechg.com/en-us/innovation/g-hub.html)는 Logitech G 게이밍 마우스, 키보드, 헤드셋, 스피커 및 기타 장치를 사용자 정의할 수 있는 소프트웨어 도구입니다.

<p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/208275997-2b60eac7-0fa3-43d0-a5c6-d49ae2447d61.png">
</p>

[Corsair iCUE](https://www.corsair.com/us/en/icue-mac)는 컴퓨터 케이스 팬, RGB 조명, 게임용 헤드셋, 게임용 키보드, 게임용 마우스, 재매핑 버튼 및 스위치, RAM DIMMS 및 AIO CPU 쿨러를 포함한 게임 주변 장치 및 개인용 컴퓨터 구성 요소를 함께 사용할 수 있는 도구입니다.
<p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/208275999-4904fece-56c6-4a04-a2de-04bb587d7c1b.png">
</p>
 
### 게임 컨트롤러

[맨 위로 돌아가기](#목차)
 
<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/196628394-d6bd6113-ee45-4e68-a035-678bcec4cdfd.png">
<br />
게임 컨트롤러용 MacOS Ventura 설정
</p>

 * [게임 컨트롤러](https://developer.apple.com/documentation/gamecontroller)는 사용자가 실제 또는 가상 게임 컨트롤러를 사용하여 앱과 상호작용할 수 있도록 지원하는 Apple 프레임워크입니다. 게임 컨트롤러에는 DualShock 4, DualSense 및 Xbox와 같은 타사 제품은 물론 마우스, 키보드, Siri Remote 및 레이싱 휠이 포함됩니다.

[Xbox 무선 컨트롤러 + USB-C® 케이블](https://www.xbox.com/en-us/accessories/controllers/xbox-wireless-controller-usb-c)

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/187094245-3c406751-4e4b-42fd-bd2c-a72181722fad.png">
<br />
Xbox 컨트롤러
</p>

[PlayStation 5 DualSense™ 무선 컨트롤러](https://www.playstation.com/en-us/accessories/dualsense-wireless-controller/)

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/187094347-109c80cd-5cc3-4a97-8a8f-0181687ab0d4.png">
<br />
PS 5 DualSense™ 컨트롤러
</p>

[ROG Raikiri Pro PC 컨트롤러](https://rog.asus.com/controllers/rog-raikiri-pro-model/)는 내장 OLED 디스플레이, 3중 모드 연결, 후면 버튼 4개, 선택 가능한 스텝 트리거, ESS DAC, 조정 가능한 조이스틱 감도 및 응답 곡선을 갖춘 Xbox 라이선스 PC 컨트롤러입니다.

 <p align="center">
 <img src="https://github.com/mikeroyal/Asus-ROG-Ally-Guide/assets/45159366/84654474-00db-4653-9398-7d0f26c510dc">
</p>

[Nintendo Switch Pro 컨트롤러](https://www.amazon.com/Nintendo-Switch-Pro-Controller/dp/B01NAWKYZ0)

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/194023448-09e74efa-67f8-4503-87f5-5b7e59289608.png">
<br />
닌텐도 스위치 프로 컨트롤러
</p>

[8BitDo SN30 Pro+ 컨트롤러](https://www.8bitdo.com/sn30-pro-plus/)

  <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/226544985-d0c0301c-e927-4845-abf8-5d728943e674.png">
</br>
8BitDo SN30 Pro+ 컨트롤러
</p>

  <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/226544994-7628f14d-f558-48f6-92b5-940905ab3fd9.png">
 </br>
 8BitDo SN30 Pro+ 컨트롤러 버튼 매핑
</p>

[eBay의 Google Stadia 컨트롤러](https://www.ebay.com/sch/i.html?_nkw=google+stadia+controller&_sop=12&mkevt=1&mkcid=1&mkrid=711-53200-19255-0&campid=5336728181&customid=&toolid=10001)
 
 **Stadia 컨트롤러를 [블루투스 모드](https://stadia.google.com/controller/)**로 전환하여 Stadia가 종료된 후에도 즐겨 사용하는 기기와 서비스에서 무선으로 게임을 계속하세요.
 
 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/218290131-3346f2d5-ee93-4dba-b8ed-e28f05c9055f.png">
</p>

[스팀 컨트롤러](https://www.ebay.com/sch/i.html?_from=R40&_trksid=p2380057.m570.l1313&_nkw=steam+controller&_sacat=0)

 * **참고:** Steam Controller는 2019년 11월 26일에 단종되었지만 여전히 eBay에서 구입할 수 있습니다.

 * [스팀 컨트롤러 설정](https://help.steampowered.com/en/faqs/view/41C5-7D8C-1671-411E)

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/211141385-fe44e2a3-ebc2-41d7-acc1-4d14957ef9aa.png">

</p>

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/211141386-8054ef27-e7de-4ecc-96e9-b8a46e45a9ea.png">

</p>


[Amazon Luna 컨트롤러](https://www.amazon.com/luna/getting-started)

* **루나 컨트롤러**는 Amazon의 클라우드 게임 서비스용으로 제작되었습니다. Cloud Direct 기술 기반 Luna에서 플레이할 때 Amazon의 맞춤형 게임 서버에 직접 연결하면 Windows PC, Mac 및 Fire TV 간의 로컬 Bluetooth 연결에 비해 왕복 대기 시간이 17~30밀리초 단축됩니다.

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/218290132-7a548dea-8c9b-4c96-8efb-24b9d8c7f74c.png">
</p>

 
## OBS 스튜디오 설정

[맨 위로 돌아가기](#목차)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/185703842-0926e10a-467a-471c-b5f6-b74df4e460d9.png">
  <br />
</p>

[OBS(오픈 브로드캐스터 소프트웨어)](https://obsproject.com/)는 동영상 녹화 및 라이브 스트리밍을 위한 무료 오픈 소스 소프트웨어입니다. Twitch, YouTube 및 기타 여러 제공업체로 스트리밍하거나 고품질 H264/AAC 인코딩으로 자신만의 비디오를 녹화하세요. [OBS Studio 버전 28](https://projectobs.com/en/news/obs-studio-28-0/)부터 [AV1](https://aomedia.org/av1-features/) 및 [HEVC](https://apps.apple.com/us/app/hevc/id768692338)에 대한 10비트 및 HDR 비디오 인코딩을 지원하고 **macOS에서 기본 Apple Silicon 지원**을 제공합니다.

**OBS Studio 29의 새로운 macOS 기능:**

 * 상향식 압축기 필터가 추가되었습니다.
 * 3밴드 이퀄라이저 필터가 추가되었습니다.
 * [P010](https://learn.microsoft.com/en-us/windows/win32/medfound/10-bit-and-16-bit-yuv-video-formats) 및 [HDR](https://www.adobe.com/creativecloud/photography/discover/hdr.html)을 포함하여 macOS에 기본 HEVC 및 ProRes 인코더에 대한 지원이 추가되었습니다.
 * macOS 데스크 뷰에 대한 지원이 추가되었습니다.
 
 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/185704748-217443ac-57e3-4ab3-ba74-6d09c2fe62fb.png">
  <br />
  노트 스튜디오
</p>

 
 ### 유용한 OBS Studio 타사 플러그인 및 테마.
 
  * **[OBS 스튜디오 테마](https://obsproject.com/forum/resources/categories/themes.10/)**
 
  * **[터치 포털 아이콘 팩](https://www.touch-portal.com/assetsdb/show-all.php?cat=i)**
 
  * **[Streamlink](https://streamlink.github.io/)**는 다양한 서비스의 비디오 스트림을 VLC와 같은 비디오 플레이어로 연결하는 CLI 유틸리티입니다.

  * **[고급 장면 전환기](https://github.com/WarmUpTill/SceneSwitcher)** 플러그인; 자동화된 장면 전환기.
  * **[오디오 팬](https://github.com/norihiro/obs-audio-pan-filter)** 플러그인; 오디오 소스의 스테레오 팬을 제어합니다.
  * **[브라우저](https://github.com/obsproject/obs-browser)** 플러그인; CEF 기반 OBS Studio 브라우저 플러그인.
  * **[디렉터리 시청 미디어](https://github.com/exeldro/obs-dir-watch-media)** 플러그인; 필터를 미디어 소스에 추가하여 디렉터리에서 가장 오래되었거나 최신 파일을 로드할 수 있습니다.
  * **[다운스트림 키어](https://github.com/exeldro/obs-downstream-keyer)** 플러그인; 다운스트림 키어 도크를 추가합니다.
  * **[동적 지연](https://github.com/exeldro/obs-dynamic-delay)** 플러그인; 비디오 소스를 동적으로 지연시키기 위한 필터입니다.
  * **[필터 고정](https://github.com/exeldro/obs-freeze-filter)** 플러그인; 필터를 사용하여 소스를 고정합니다.
  * **[그라디언트 소스](https://github.com/exeldro/obs-gradient-source)** 플러그인; 그라디언트를 소스로 추가합니다.
  * **[GStreamer](https://github.com/fzwoch/obs-gstreamer)** 플러그인; GStreamer 실행 파이프라인을 OBS Studio에 공급하고 GStreamer 인코더 요소를 사용합니다.
  * **[전환 전환](https://github.com/exeldro/obs-move-transition)** 플러그인; 장면 전환 중에 소스를 새 위치로 이동합니다.
  * **[멀티 소스 효과](https://github.com/norihiro/obs-multisource-effect)** 플러그인; 여러 소스를 렌더링하는 사용자 정의 효과를 제공합니다.
  * **[AND](https://github.com/Palakis/obs-ndi)** 플러그인; NewTek의 NDI를 통한 네트워크 A/V.
  * **[NvFBC](https://gitlab.com/fzwoch/obs-nvfbc)** 플러그인; NVIDIA FBC API를 통한 화면 캡처. 소비자급 GPU의 경우 [Nvidia 드라이버용 NvFBC 패치](https://github.com/keylase/nvidia-patch)가 필요합니다.
  * **[사운드보드](https://github.com/cg2121/obs-soundboard)** 플러그인; 사운드보드 도크를 추가합니다.
  * **[소스 복사](https://github.com/exeldro/obs-source-copy)** 플러그인; 도구 메뉴에 복사 및 붙여넣기 옵션을 추가합니다.
  * **[소스 독](https://github.com/exeldro/obs-source-dock)** 플러그인; 오디오 레벨을 확인하고, 볼륨을 변경하고, 미디어를 제어할 수 있는 소스용 Dock을 생성하세요.
  * **[재귀 효과](https://github.com/exeldro/obs-recursion-effect)** 플러그인; 재귀 효과 필터.
  * **[재생 소스](https://github.com/exeldro/obs-replay-source)** 플러그인; 슬로우 모션은 메모리의 비동기 소스를 재생합니다.
  * **[RGB 레벨](https://github.com/petrifiedpenguin/obs-rgb-levels-filter)** 플러그인; RGB 레벨을 조정하는 간단한 필터.
  * **[RTSP서버](https://github.com/iamscottxu/obs-rtspserver/)** 플러그인; RTSP 스트림으로 인코딩하고 게시합니다.
  * **[소리에 맞게 크기 조절](https://github.com/Qufyy/obs-scale-to-sound)** 플러그인; 선택한 오디오 소스의 오디오 레벨을 기반으로 소스 크기를 조정하는 필터를 추가합니다.
  * **[장면 컬렉션 관리자](https://github.com/exeldro/obs-scene-collection-manager)** 플러그인; 장면 컬렉션을 필터링, 백업 및 복원합니다.
  * **[장면 노트 독](https://github.com/exeldro/obs-scene-notes-dock)** 플러그인; 현재 활성 장면에 대한 메모를 표시하고 편집하기 위한 Dock을 만듭니다.
  * **[소스 레코드](https://github.com/exeldro/obs-source-record)** 플러그인; 필터를 통해 소스를 녹음할 수 있도록 합니다.
  * **[소스 전환기](https://github.com/exeldro/obs-source-switcher)** 플러그인; 소스 목록 간을 전환합니다.
  * **[분광기](https://github.com/univrsal/spectralizer)** 플러그인; fftw를 이용한 오디오 시각화
  * **[StreamFX](https://github.com/Xaymar/obs-StreamFX)** 플러그인; 최신 효과 필터 및 전환을 수집합니다.
  * **[텔레포트](https://github.com/fzwoch/obs-teleport)** 플러그인; NDI와 유사한 대체를 엽니다.
  * **[텍스트 Pango](https://github.com/kkartaltepe/obs-text-pango)** 플러그인; 다국어 지원, 이모티콘 지원, 수직 렌더링 및 RTL 지원을 갖춘 Pango를 사용하여 렌더링된 텍스트 소스를 제공합니다.
  * **[텍스트 PThread](https://github.com/norihiro/obs-text-pthread)** 플러그인; 다양한 고급 기능을 갖춘 리치 텍스트 소스 플러그인.
  * **[타임워프 스캔](https://github.com/exeldro/obs-time-warp-scan)** 플러그인; 타임워프 스캔 필터.
  * **[전환 테이블](https://github.com/exeldro/obs-transition-table)** 플러그인; 장면 전환을 사용자 정의합니다.
  * **[가상 캠 필터](https://github.com/exeldro/obs-virtual-cam-filter)** 플러그인; 필터를 통해 가상 카메라에서 소스를 사용할 수 있도록 합니다.
  * **[VNC 소스](https://github.com/norihiro/obs-vnc)** 플러그인; 소스로 작동하는 VNC 뷰어입니다.
  * **[웹소켓](https://github.com/Palakis/obs-websocket)** 플러그인; [StreamControl](https://play.google.com/store/apps/details?id=dev.t4ils.obs_remote&hl=en)과 호환되는 WebSocket을 통해 OBS Studio를 원격 제어합니다.

## 불화

[맨 위로 돌아가기](#목차)

[Discord](https://discord.com/)는 최신 음성 및 문자 채팅 앱을 갖춘 애플리케이션입니다. 선명한 음성, 다중 서버 및 채널 지원, 모바일 앱 등을 제공합니다. Linux, macOS, Windows, iOS, Android 및 웹 브라우저에서 사용할 수 있습니다.

<p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/203752975-d489f776-2039-474d-82ce-1cdd3dcdeff7.png">
</p>

## 트위치

[맨 위로 돌아가기](#목차)

[MacOS/iOS용 Twitch](https://apps.apple.com/us/app/twitch-live-game-streaming/id460177396)는 우리가 좋아하는 스트리머를 위해 수천 개의 커뮤니티가 함께 모여 수백만 명이 라이브 게임, 음악, 스포츠, e스포츠, 팟캐스트, 요리 쇼, IRL 스트림 등을 즐기는 애플리케이션입니다.

  * [macOS에서 iOS 앱/게임 실행](https://developer.apple.com/documentation/apple-silicon/running-your-ios-apps-in-macos)

<p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/203753175-0aaea65d-013e-4a4e-b67d-19a6ca52ff56.png">
</p>


## 게임 스토어 및 런처

### 애플 아케이드
[맨 위로 돌아가기](#목차)

[Apple Arcade](https://www.apple.com/apple-arcade/)는 최대 6명의 가족 구성원이 100개 이상의 매우 재미있는 게임에 무제한으로 액세스할 수 있는 게임 구독 서비스입니다. 모든 게임에는 광고나 인앱 구매가 없습니다.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/112693074-377cb100-8e3d-11eb-910c-1095c91da6d5.png">
</p>

### 플레이커버

[맨 위로 돌아가기](#목차)

[PlayCover](https://github.com/PlayCover/PlayCover)는 마우스, 키보드, 컨트롤러를 지원하는 Apple Silicon Mac(macOS 12.0 이상)에서 iOS 앱과 게임을 실행할 수 있는 도구입니다.

**다음 칩이 탑재된 장치가 지원됩니다:**

  * M1
  * M1 Pro
  * M1 맥스
  * M1 Ultra
  *M2

<p align="center">
 <img src="https://github.com/mikeroyal/Apple-Silicon-Guide/assets/45159366/2cfa0e1a-8cbe-435d-aa2f-b4b1365f6c4d">
</p>

### 스팀
[맨 위로 돌아가기](#목차)

[CrossOver를 통해 Steam 설치](https://www.codeweavers.com/compatibility/crossover/steam)

 <img src="https://user-images.githubusercontent.com/45159366/106686402-13100100-657f-11eb-9012-6bdac264a808.png">

 [Steam Link 앱](https://store.steampowered.com/steamlink/about)을 무료로 사용하여 Steam PC 게임을 휴대폰, 태블릿, TV로 스트리밍할 수 있습니다.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/112692999-14ea9800-8e3d-11eb-964a-6bee4e665900.png">
</p>

 ### 영웅적인 게임 실행기
[맨 위로 돌아가기](#목차)

[Heroic Game Launcher](https://heroicgameslauncher.com/)는 Linux, Windows 및 MacOS용 오픈 소스 게임 런처입니다(Crossover를 사용하는 네이티브 및 Windows 게임용). Epic Games Store 및 GOG.com Store의 게임 출시를 지원합니다.

<p align="center">
 <img src="https://github.com/mikeroyal/Apple-Silicon-Guide/assets/45159366/95b64ae6-1bf5-494d-a2bf-0a4e16786270">
</p>

 ### 에픽게임즈 스토어
[맨 위로 돌아가기](#목차)

[Epic Games Store](https://www.epicgames.com/store/)는 Epic Games에서 운영하는 Microsoft Windows 및 macOS용 디지털 비디오 게임 매장입니다.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/111918016-3fed7a00-8a40-11eb-964e-930c801c1c72.png">
</p>

### 블리자드 Battle.net
[맨 위로 돌아가기](#목차)

[Blizzard Battle.net](https://www.blizzard.com/apps/battle.net/desktop)은 Activision과 Blizzard Entertainment가 개발한 인터넷 기반 온라인 게임, 디지털 배포 및 디지털 권한 관리 플랫폼입니다. Battle.net은 월드 오브 워크래프트, 디아블로 III, 스타크래프트 II, 하스스톤, 히어로즈 오브 더 스톰, 오버워치, 콜 오브 듀티의 런처입니다.

<img src="https://user-images.githubusercontent.com/45159366/189614458-d51a15cb-d02d-4b1f-9e77-e712dcdb1d73.png">

### 기원
[맨 위로 돌아가기](#목차)
 
[MacOS용 Origin](https://www.ea.com/origin-for-mac#)은 Electronic Arts에서 개발한 온라인 게임, 디지털 배포 및 디지털 권한 관리(DRM) 플랫폼으로, 사용자가 PC 및 모바일 플랫폼용 게임을 인터넷에서 구매하고 Origin 클라이언트(이전의 EA Download Manager, EA Downloader 및 EA Link)를 통해 다운로드할 수 있습니다.

 * [CrossOver를 통한 Origin 설치 프로그램](https://www.codeweavers.com/compatibility/crossover/origin)

<img src="https://user-images.githubusercontent.com/45159366/189614468-49c4a05c-d6ca-4988-b3e6-10f0c71463d6.png">

### EA 플레이

[맨 위로 돌아가기](#목차)

[EA Play](https://www.ea.com/ea-play)는 Xbox One, Xbox Series X/S, PlayStation 4, PlayStation 5 및 Microsoft Windows 플랫폼용 Electronic Arts의 구독 기반 비디오 게임 서비스로, 추가 인센티브와 함께 Electronic Arts에서 출시한 일부 게임에 대한 액세스를 제공합니다.

 * **참고:** **Steam에서 EA Play**를 사용하는 경우에도 EA Play의 모든 EA 게임 타이틀에 액세스하려면 [Origin](https://www.ea.com/origin-for-mac#)을 설치해야 합니다.
 
 **macOS Apple Silicon에서 EA Play를 플레이하는 방법:**
 
 * [Parallels Desktop이 설치된 Mac의 Windows](https://www.parallels.com/products/desktop/)
 * [Xbox Game Pass를 통한 EA Play](https://www.xbox.com/en-US/xbox-game-pass/games?xr=shellnav#)
 * [Steam을 통한 EA 플레이](https://store.steampowered.com/subscriptions/ea)

<img src="https://user-images.githubusercontent.com/45159366/189614466-476e0c4e-bab9-44bd-86c4-8aeadd739b63.png">

### 유비소프트 커넥트

[맨 위로 돌아가기](#목차)

[Ubisoft Connect](https://itunes.apple.com/us/app/ubisoft-club/id405228226/)는 다양한 다른 게임 회사에서 제공하는 성과/트로피와 유사한 경험을 제공하기 위해 Ubisoft가 만든 디지털 배포, 디지털 권한 관리, 멀티플레이어 및 통신 서비스입니다.

**macOS Apple Silicon에서 Ubisoft Connect를 플레이하는 방법:**
 
 * [CrossOver를 통한 Ubisoft Connect 설치 프로그램(UPay)](https://www.codeweavers.com/compatibility/crossover/Ubisoft-Connect-Installer)
 * [Parallels Desktop이 설치된 Mac의 Windows](https://www.parallels.com/products/desktop/)
 * [Xbox Game Pass를 통한 Ubisoft Connect](https://www.xbox.com/en-US/xbox-game-pass/games?xr=shellnav#)
 * [Apple 실리콘이 탑재된 Mac에서 iPhone 및 iPad 앱 사용](https://support.apple.com/guide/app-store/iphone-ipad-apps-mac-apple-silicon-fird2c7092da/3.0/mac/13.0)

<img src="https://user-images.githubusercontent.com/45159366/189614471-422cbad8-1ae7-4f06-ad81-7f3b68550569.png">

### GOG 갤럭시

[맨 위로 돌아가기](#목차)

[GOG Galaxy](https://www.gog.com/galaxy)는 여러 게임 라이브러리를 한 곳으로 결합하고 콘솔을 포함한 모든 게임 플랫폼에서 친구들과 연결할 수 있는 애플리케이션입니다.

 * [CrossOver를 통한 GOG Galaxy 설치 프로그램](https://www.codeweavers.com/compatibility/crossover/gog-galaxy)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/200258282-da3cd773-c1c9-46d9-af12-aa54428be4ec.png">
</p>

### Itch.io 스토어

[맨 위로 돌아가기](#목차)

[Itch.io Store](https://itch.io/app)는 itch.io에서 게임과 소프트웨어를 쉽게 다운로드하고 실행할 수 있는 앱입니다. 모든 다운로드는 한 곳에 보관되며 자동으로 업데이트됩니다.

<p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/199429576-278a8604-7f76-4a41-abeb-84d03865daeb.png">
</p>

### Mac의 XIV

[맨 위로 돌아가기](#목차)

[XIVONMAC](https://www.xivmac.com/)은 macOS용 최신 오픈 소스 Final Fantasy XIV 클라이언트입니다.

<p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/209292818-12684fdc-c160-4e7d-828f-1f6370b6b3a0.gif">
</p>


## 게임 스트리밍

[맨 위로 돌아가기](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

### 클라우드 게임 스트리밍

[맨 위로 돌아가기](#목차)

[Xbox Cloud Gaming](https://www.xbox.com/en-US/xbox-game-pass/cloud-gaming)은 Microsoft의 클라우드 기반 Xbox 게임 스트리밍 기술**(현재 베타 버전)**입니다. **Forza Horizon 4, Halo 5: Guardians, Gears of War 4, Sea of ​​Thieves, Cuphead, Red Dead Redemption 2 및 기타 100개 이상의 게임을 모바일 기기나 Chrome 웹 브라우저에서 플레이하세요**. Xbox Cloud Gaming에는 **[Xbox Game Pass Ultimate](https://www.xbox.com/en-US/xbox-game-pass/cloud-gaming)** 구독이 필요합니다.

<img src="https://user-images.githubusercontent.com/45159366/108111388-74d56e00-7049-11eb-8aeb-3e5d65f9e832.png">

[Geforce NOW](https://www.nvidia.com/en-us/geforce-now/download/)는 NVIDIA의 클라우드 게임 서비스입니다.

<img src="https://user-images.githubusercontent.com/45159366/106686391-0f7c7a00-657f-11eb-9d0b-1ebb4d385883.jpeg">

[Amazon Luna](https://www.amazon.com/luna/landing-page)는 Amazon의 클라우드 게임 서비스입니다. Amazon Luna는 다양한 [장치 및 브라우저](https://www.amazon.com/gp/help/customer/display.html?nodeId=GUFHUSX8X324T4XE)에서 호환/지원됩니다.

<p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/112693072-364b8400-8e3d-11eb-9df0-d58af7ac9c9c.png">
</p>

[Shadow](https://shadow.tech/)는 모든 기능을 갖춘 클라우드 기반 고급 컴퓨터입니다. 로컬 PC와 경쟁할 수 있는 성능을 제공하는 유일한 원격 서비스입니다. Windows, macOS, Linux, Android/AndroidTV, iOS/tvOS에서 사용할 수 있습니다.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/200110962-dd631248-7a13-48bb-9b5a-acbbf8550e16.png">
</p>

### 로컬 게임 스트리밍

[맨 위로 돌아가기](#목차)

[Steam Remote Play Together](https://store.steampowered.com/remoteplay/#together)는 Steam 로컬 멀티 플레이어 게임을 인터넷을 통해 친구들과 무료로 공유할 수 있는 Steam 서비스입니다. Remote Play Together를 사용하면 한 명의 플레이어가 게임을 소유하고 실행하며 최대 4명의 플레이어가 참여할 수 있습니다.

[Steam Link 앱](https://store.steampowered.com/steamlink/about)을 무료로 사용하여 Steam PC 게임을 휴대폰, 태블릿, TV로 스트리밍할 수 있습니다.

<p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/112692999-14ea9800-8e3d-11eb-964a-6bee4e665900.png">
</p>


[PlayStation Remote Play](https://www.playstation.com/en-us/support/games/playstation-remote-play-on-pc-and-mac/)는 모든 PS4 및 PS5 콘솔에서 사용할 수 있는 기능으로, 고속 인터넷 연결이 가능한 곳이라면 어디에서나 PlayStation® 콘솔을 원격으로 제어할 수 있습니다.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/172946885-27f83bdf-ab1a-4eaa-ad33-0e108f92a981.png">
</p>


[Chiaki](https://git.sr.ht/~thestr4ng3r/chiaki)는 Linux, FreeBSD, OpenBSD, Android, macOS, Windows, Nintendo Switch 및 더 많은 플랫폼용 **PlayStation 4 및 PlayStation 5 Remote Play**용 무료 오픈 소스 소프트웨어 클라이언트입니다.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/208854787-3442b9df-60bc-4ed2-87e3-efaa159a6b7f.png">
</p>

[Parsec](https://parsec.app/cloud-gaming)은 비디오 게임 스트리밍 플랫폼으로, 선택할 수 있는 다양한 게임과 장르를 제공하고 고품질의 원활한 게임 플레이를 제공합니다. SParsec은 모든 광고와 게임 내 구매가 없는 동시에 고품질의 원활한 게임 플레이를 제공하기 위해 개발되었습니다.

<p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/166166858-e70ca081-8931-46f3-9dc3-fe9c719d76f8.png">
</p>

[Moonlight Game Streaming](https://moonlight-stream.org/)은 별도의 구성 없이 인터넷을 통해 PC 게임을 스트리밍할 수 있는 프로그램입니다. 다른 방에 있든, 게임 장비에서 몇 마일 떨어진 곳에 있든 거의 모든 장치에서 스트리밍하세요. [Sunshine](https://github.com/LizardByte/Sunshine)은 AMD, Intel 및 NVIDIA GPU를 지원하는 자체 호스팅, 짧은 지연 시간, 클라우드 게임 솔루션인 **Moonlight용 게임 스트림 호스트**입니다.

<p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/106686398-11463d80-657f-11eb-841a-d534829ccc3d.png">
</p>

[Greenlight](https://github.com/unknownskl/xbox-xcloud-client)는 Javascript 및 Typescript로 만들어진 xCloud 및 xHome 스트리밍용 오픈 소스 클라이언트입니다. 클라이언트는 [xbox-xcloud-player](https://github.com/unknownskl/xbox-xcloud-player) 주변의 애플리케이션 래퍼입니다. Linux, MacOS, Windows 및 Steam Deck에서 실행됩니다.

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/231686736-94adf5e6-1320-4f23-bea4-4fd05fe40da5.png">
</br>
그린라이트
</p>

## 안드로이드 게임

[맨 위로 돌아가기](#목차)

### 블루스택
[BlueStacks](https://www.bluestacks.com/download.html)는 Windows 및 macOS용 가장 빠르고 가벼운 Android 앱 플레이어입니다.

 * [BlueStacks 4 시작하기](https://support.bluestacks.com/hc/en-us/sections/360001186891-Getting-Started-with-BlueStacks-4)
 
<p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/210217487-269ce62d-49bb-4efc-ab26-61f5e2c41f72.png">
</p>

<p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/210217491-68aabb0d-a3f0-4a77-ae7b-de66937a25b5.png">
</p>

<p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/210217865-0fae0dc3-f229-49dd-9a88-14d75d154367.png">
</p>

## 게임 에뮬레이터
[맨 위로 돌아가기](#목차)

**또한 더 훌륭한 게임 에뮬레이터 권장 사항을 보려면 이 하위 레딧을 확인하세요**
  
   - [r/에뮬레이션](https://www.reddit.com/r/emulation/)
   - [r/에뮬레이션](https://www.reddit.com/r/emulators/)
   - [r/RetroArch](https://www.reddit.com/r/RetroArch/)
   - [r/DolphinEmulator](https://www.reddit.com/r/DolphinEmulator/)
   - [r/시트라](https://www.reddit.com/r/Citra/)
   - [r/cemu](https://www.reddit.com/r/cemu/)
   - [r/유즈](https://www.reddit.com/r/yuzu/)
   - [r/OpenEmu](https://www.reddit.com/r/OpenEmu/)
   - [r/MAME](https://www.reddit.com/r/MAME/)
   - [R/EMUDEV] (__ URL0__)
   - [r/롬](https://www.reddit.com/r/Roms/)
   
### 프런트엔드

[EmulationStation Desktop Edition(ES-DE)](https://www.es-de.org/)은 다중 플랫폼 게임 컬렉션에서 게임을 검색하고 실행하기 위한 프런트엔드 애플리케이션입니다. Unix/Linux, macOS(M1 & Intel) 및 Windows에서 사용할 수 있습니다.

[RetroArch](https://www.retroarch.com/)는 에뮬레이터, 게임 엔진 및 미디어 플레이어용 프런트엔드입니다. 매끄러운 그래픽 인터페이스를 통해 다양한 컴퓨터와 콘솔에서 클래식 게임을 실행할 수 있습니다. 설정도 통합되어 구성이 한 번에 완료됩니다.

[OpenEmu](https://openemu.org/)는 macOS 게임 에뮬레이션을 최고의 시민권 영역으로 가져오는 것이 목적인 오픈 소스 프로젝트입니다. 이 프로젝트는 Cocoa, Core Animation 및 기타 타사 라이브러리와 같은 최신 macOS 기술을 활용합니다.

**현재 OpenEmu는 다음 게임 엔진을 플러그인으로 로드할 수 있습니다.**

  * 아타리 2600 ([스텔라](https://stella-emu.github.io/))
  * 아타리 5200 ([Atari800](https://atari800.github.io/))
  * 아타리 7800 ([ProSystem](https://github.com/raz0red/wii7800))
  * Atari Lynx ([메드나펜](https://mednafen.github.io/))
  * 콜레코비전([CrabEmu](http://crabemu.sourceforge.net/))
  * 패미콤 디스크 시스템 ([Nestopia](https://github.com/0ldsk00l/nestopia))
  * 게임보이 / 게임보이 컬러 ([Gambatte](https://github.com/sinamas/gambatte))
  * 게임보이 어드밴스 ([mGBA](https://mgba.io/))
  * 게임기어([제네시스 플러스](https://github.com/ekeeke/Genesis-Plus-GX))
  * 인텔리비전 ([Bliss](https://github.com/jeremiah-sypult/BlissEmu))
  * 네오지오 포켓([메드나펜](https://mednafen.github.io/))
  * 닌텐도(NES) / 패미콤([FCEUX](https://github.com/TASVideos/fceux), [네스토피아](https://github.com/0ldsk00l/nestopia))
  * 닌텐도 64 ([Mupen64Plus](http://www.mupen64plus.org/))
  * 닌텐도 DS ([DeSmuME](http://desmume.org/))
  * 닌텐도 게임큐브 ([돌핀](https://dolphin-emu.org/))
  * Odyssey² / Videopac+ ([O2EM](https://sourceforge.net/projects/o2em/))
  * PC-FX ([메드나펜](https://mednafen.github.io/))
  * SG-1000 ([제네시스 플러스](https://github.com/ekeeke/Genesis-Plus-GX))
  * 세가 32X ([피코드라이브](https://github.com/notaz/picodrive))
  * 세가 CD / 메가 CD ([제네시스 플러스](https://github.com/ekeeke/Genesis-Plus-GX))
  * 세가 제네시스 / 메가 드라이브 ([제네시스 플러스](https://github.com/ekeeke/Genesis-Plus-GX))
  * 세가 마스터 시스템 ([Genesis Plus](https://github.com/ekeeke/Genesis-Plus-GX))
  * 세가 새턴 ([Mednafen](https://mednafen.github.io/))
  * 소니 PSP([PPSSPP](https://github.com/hrydgard/ppsspp))
  * 소니 플레이스테이션([Mednafen](https://mednafen.github.io/))
  * 슈퍼 닌텐도(SNES) ([BSNES](https://bsnes.dev/), [Snes9x](https://github.com/snes9xgit/snes9x))
  * TurboGrafx-16 / PC 엔진 ([Mednafen](https://mednafen.github.io/))
  * TurboGrafx-CD / PCE-CD ([메드나펜](https://mednafen.github.io/))
  * Vectrex ([VecXGL](https://github.com/james7780/VecXGL))
  * 버추얼 보이 ([Mednafen](https://mednafen.github.io/))
  * WonderSwan ([메드나펜](https://mednafen.github.io/))

[Pegasus](https://pegasus-frontend.org/)는 에뮬레이터를 실행하고 게임 라이브러리(특히 복고풍 게임)를 관리하며 한 곳에서 실행하기 위한 크로스 플랫폼, 사용자 정의 가능한 그래픽 프런트엔드입니다. 사용자 정의 가능성, 크로스 플랫폼 지원(임베디드 장치 포함) 및 고성능에 중점을 둡니다.

[Boxer](https://boxer.thec0de.com/)는 Mac에 적합한 DOSBox 게임 에뮬레이터 프런트엔드입니다.

[카트리지](https://github.com/unclebacon-live/cartridge)는 Laravel + Vue.js로 만든 자체 호스팅 게임 라이브러리입니다.

카트리지 특징

- ROM 파일을 스캔하고 IGDB 게임 정보와 일치시킵니다.
- 게임 세부 정보와 함께 ROM 다운로드 링크 제공
- 사용자 생성 및 권한(WIP)을 통해 라이브러리에 대한 액세스를 관리합니다.
- 사용자가 게임을 요청할 수 있도록 허용(예정)
- JS 에뮬레이터를 사용하여 브라우저에서 선택 ROM 재생(계획)
- 플레이한 게임과 좋아하는 게임 추적(다운로드할 수 없는 게임도 포함)(예정)

<p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/172274231-d691a850-1879-44fb-8fa0-08e549d7bb29.png">
    <br />
      카트리지 UI
</p>

### 닌텐도 게임큐브 및 Wii

[Dolphin](https://dolphin-emu.org)은 최신 Nintendo 비디오 게임 콘솔인 GameCube와 Wii를 위한 에뮬레이터입니다. 이를 통해 PC 게이머는 모든 PC 컨트롤러와의 호환성, 터보 속도, 네트워크 멀티플레이어 등 여러 가지 향상된 기능을 통해 이 두 콘솔의 게임을 풀 HD(1080p)로 즐길 수 있습니다.

[PrimeHack](https://github.com/shiiion/dolphin)은 Metroid Prime Trilogy에 최신 마우스 및 키보드 컨트롤은 물론 듀얼 스틱 게임 패드 컨트롤을 제공하는 **Dolphin Emulator**의 포크입니다. 또한 증가된 FoV 및 다양한 새로운 치트와 같은 다른 많은 기능도 제공합니다. [현재 지원되는 Metroid Prime 버전.](https://github.com/shiiion/dolphin/wiki/Frequently-Asked-Questions#what-versions-of-metroid-prime-are-supported)

### 닌텐도 스위치

[Ryujinx](https://ryujinx.org/)는 gdkchan이 만들고 C#으로 작성된 오픈 소스 Nintendo Switch 에뮬레이터입니다. 이 에뮬레이터는 뛰어난 정확성과 성능, 사용자 친화적인 인터페이스, 일관된 빌드를 제공하는 것을 목표로 합니다.

[yuzu](https://yuzu-emu.org)는 Citra 제작자가 만든 Nintendo Switch용 실험적인 오픈 소스 에뮬레이터입니다.

### 닌텐도 64

[m64p](https://m64p.github.io/)는 Nintendo 64 에뮬레이터입니다. 이는 Qt5로 작성된 새로운 mupen64plus 프론트엔드인 mupen64plus-gui를 사용합니다. 프런트엔드에서 기대할 수 있는 모든 기능(상태 저장 관리, 일시 중지, 스크린샷)을 지원합니다.

### 닌텐도 3DS

[Citra](https://citra-emu.org/)는 여러분이 좋아하는 다양한 게임을 플레이할 수 있는 Nintendo 3DS용 오픈 소스 에뮬레이터입니다.

### 닌텐도 DS

[DeSmuME](https://desmume.org/)은 Nintendo DS 에뮬레이터입니다.

[melonDS](https://github.com/melonDS-emu/melonDS)는 빠르고 정확한 Nintendo DS 에뮬레이션 제공을 목표로 하는 도구입니다. 아직 진행 중인 작업이지만 매우 견고한 기능 세트를 갖추고 있습니다.

**특징:**

    * 거의 완전한 코어(CPU, 비디오, 오디오 등...)
    * OpenGL 렌더러, 3D 업스케일링
    * RTC, 마이크, 뚜껑 닫기/열기
    * 조이스틱 지원
    * 상태 저장
    * 다양한 디스플레이 위치/크기/회전 모드
    * 온라인 연결 및 로컬 멀티플레이어를 위한 Wi-Fi 에뮬레이션 작업이 진행 중입니다.
    * Nintendo DSi의 실험적 에뮬레이션

### 슈퍼 닌텐도 엔터테인먼트 시스템(SNES)

[Snes9x](https://www.snes9x.com/)는 휴대용 프리웨어 SNES(Super Nintendo Entertainment System) 에뮬레이터입니다.

[bsnes](https://github.com/bsnes-emu/bsnes)는 성능, 기능 및 사용 편의성에 중점을 둔 Super Nintendo(SNES) 에뮬레이터입니다.

### 게임보이 어드밴스

[mGBA](https://mgba.io/)는 Game Boy Advance 게임을 실행하기 위한 새로운 에뮬레이터입니다. 기존의 많은 Game Boy Advance 에뮬레이터보다 더 빠르고 정확할 뿐만 아니라 다른 에뮬레이터에 부족한 기능을 추가하는 것을 목표로 합니다.

### 중

[Boxer](https://boxer.thec0de.com/)는 Mac에 적합한 DOSBox 게임 에뮬레이터 프런트엔드입니다.

[DOSBox](https://www.dosbox.com/)는 주로 DOS 게임 실행에 초점을 맞춘 오픈 소스 DOS 에뮬레이터입니다.

[DOSBox Staging](https://github.com/dosbox-staging/dosbox-staging)은 실제 모드나 보호 모드가 필요한 DOS 프로그램을 실행할 수 있는 완전한 x86 CPU 에뮬레이터(호스트 아키텍처와 무관)입니다.

### 아타리

[Stella](https://stella-emu.github.io/)는 GNU General Public License(GPL)에 따라 출시된 다중 플랫폼 Atari 2600 VCS 에뮬레이터입니다. Stella는 Windows MacOS, Linux 및 FreeBSD에서 사용할 수 있습니다.

[Hatari](https://hatari.tuxfamily.org/)는 SDL 라이브러리에서 지원하는 Linux, BSD, MacOS, Windows 및 기타 시스템용 Atari ST/STE/TT/Falcon 에뮬레이터입니다. Atari ST는 1985년 Atari가 처음 출시한 16/32비트 컴퓨터 시스템입니다.

### 드림캐스트 셔플

[Flycast](https://github.com/flyinghead/flycast)는 reicast에서 파생된 멀티 플랫폼 Sega Dreamcast, Naomi 및 Atomiswave 에뮬레이터입니다.


[Redream](https://redream.io/)은 Dreamcast 에뮬레이터로, 좋아하는 Dreamcast 게임을 고화질(1080p 또는 4k)로 플레이할 수 있습니다.

### PlayStation Portable

[PPSSPP](https://www.ppsspp.org/)은 풀 HD 해상도로 게임을 실행할 수 있는 PSP 에뮬레이터입니다. 원래 PSP의 작은 화면용으로 제작되었기 때문에 너무 흐릿한 텍스처를 고급화할 수도 있습니다.

### 플레이스테이션 1

[DuckStation](https://www.duckstation.org/)은 Sony PlayStation 1 콘솔의 시뮬레이터/에뮬레이터로, 플레이 가능성, 속도 및 장기적인 유지 관리 가능성에 중점을 두고 있습니다.

[Avocado](https://github.com/JaCzekanski/Avocado)는 최신 PlayStation 1 에뮬레이터입니다.

### 플레이스테이션 2

[AetherSX2](https://www.aethersx2.com/)는 ARM 기반 장치용 PlayStation 2(PS2) 콘솔의 무료(광고 없음) 에뮬레이터입니다. 이를 통해 스마트폰의 디스크에서 버린 게임을 플레이할 수 있습니다.

[PCSX2](https://pcsx2.net/)는 Playstation 2 '에뮬레이터'로, PC에서 PS2 게임을 플레이할 수 있도록 Playstation 2 콘솔을 복제하는 무료 프로그램입니다.

[Play!](https://github.com/jpd002/Play-)는 Windows, macOS, UNIX, Android, iOS 및 웹 브라우저 플랫폼용 PlayStation2 에뮬레이터입니다.

### 플레이스테이션 3

[RPCS3](https://rpcs3.net/)은 Windows 및 Linux용 C++로 작성된 실험적인 오픈 소스 Sony PlayStation 3 에뮬레이터 및 디버거입니다. RPCS3는 창립자인 DH와 Hykem에 의해 2011년 5월에 개발을 시작했습니다. 이 에뮬레이터는 현재 Vulkan 및 OpenGL을 기반으로 하는 1,800개 이상의 상업용 타이틀을 실행할 수 있습니다.

### 엑스박스

[xemu](https://xemu.app/)는 오리지널 Xbox 에뮬레이터입니다.

[Xenia](https://github.com/xenia-project/xenia)는 Xbox 360 에뮬레이터입니다.

### 마메

[MAME](https://www.mamedev.org/)은 아케이드 머신 에뮬레이터입니다.

## 성능 벤치마크
[맨 위로 돌아가기](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

[Geekbench 6](https://www.geekbench.com/download/)은 버튼을 눌러 시스템 성능을 측정하는 크로스 플랫폼 벤치마크입니다.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/220055002-0f99a8bf-6a3f-4511-9157-7bd398f623f4.png">
</p>

[GFXBench 5.0](https://gfxbench.com/result.jsp)은 모든 플랫폼에서 차세대 그래픽 기능으로 모바일 및 데스크톱 성능을 측정하는 고급 그래픽 벤치마크입니다. 진정한 교차 API 벤치마크인 GFXBench는 OpenGL, OpenGL ES, Vulkan, Metal, DirectX/Direct3D 및 DX12를 포함한 모든 업계 표준 및 공급업체별 API를 지원합니다.

[PugetBench Benchmarks](https://www.pugetsystems.com/benchmarks/)는 실제 프로젝트 및 워크플로를 사용하여 널리 사용되는 여러 전문 애플리케이션을 테스트하도록 설계된 여러 벤치마크가 포함된 애플리케이션입니다.

[Phoronix 테스트 스위트](https://www.phoronix-test-suite.com/)

[UNIGINE Superposition](https://benchmark.unigine.com/superposition)은 비디오 카드, 전원 공급 장치, 냉각 시스템 등 PC 하드웨어에 대한 최고의 성능 및 안정성 테스트입니다.

<img src="https://user-images.githubusercontent.com/45159366/107092007-8f8d2480-67b7-11eb-9c3f-a0cb02e6dfcd.png">

[asitop](https://github.com/tlkh/asitop)은 Apple Silicon용 성능 모니터링 CLI 도구입니다.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/176965986-3a2b1f88-93d6-4d1b-aa2d-545a86e5e667.png">
  <br />
</p>


# 웨이퍼 레벨 멀티칩 패키징 기술

[맨 위로 돌아가기](#목차)

## InFO(통합 팬아웃) 웨이퍼 레벨 패키징

[맨 위로 돌아가기](#목차)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/184552824-33363b75-56c4-4f1a-a348-f18f107abdc5.png">
  <br />
</p>

[InFO](https://3dfabric.tsmc.com/english/dedicatedFoundry/technology/InFO.htm)는 모바일, 고성능 컴퓨팅 등 다양한 애플리케이션에 대한 고밀도 상호 연결 및 성능을 위한 고밀도 RDL(Re-Distribution Layer) 및 TIV(Through InFO Via)를 특징으로 하는 혁신적인 웨이퍼 레벨 시스템 통합 기술 플랫폼입니다. InFO 플랫폼은 특정 애플리케이션에 최적화된 2D 및 3D의 다양한 패키지 구성을 제공합니다.

[InFO_PoP](https://3dfabric.tsmc.com/english/dedicatedFoundry/technology/InFO.htm#tbc_InFO_PoP)은 업계 최초의 3D 웨이퍼 레벨 팬아웃 패키지로, 모바일 애플리케이션을 위한 모바일 AP와 DRAM 패키지 스태킹을 통합하기 위한 고밀도 RDL 및 TIV를 갖추고 있습니다. FC_PoP에 비해 InFO_PoP는 유기 기판과 C4 범프가 없기 때문에 프로파일이 더 얇고 전기 및 열 성능이 더 좋습니다.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/184552831-604bc8ee-0bf4-434c-befe-161dbb6cf89e.png">
  <br />
  InFO_PoP
</p>

[InFO_oS](https://3dfabric.tsmc.com/english/dedicatedFoundry/technology/InFO.htm#tbc_InFO_oS)는 InFO 기술을 활용하고 5G 네트워킹 애플리케이션을 위한 여러 고급 로직 칩렛을 통합하기 위해 더 높은 밀도의 2/2μm RDL 라인 폭/공간을 특징으로 하는 패키징 프로세스입니다. 이는 65 x 65mm 이상의 기판에서 최소 40μm I/O 피치, 최소 130μm C4 Cu 범프 피치 및 > 2X 레티클 크기 InFO를 갖춘 SoC에서 하이브리드 패드 피치를 가능하게 합니다.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/184552827-aa529f79-3e44-412d-ab4d-1cd7bb81dac0.png">
  <br />
  정보_oS
</p>

## 기판 위 웨이퍼 칩(CoWoS)
[맨 위로 돌아가기](#목차)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/145732295-4c0ada4e-c237-472c-8bef-58b8eb223747.png">
  <br />
</p>

[CoWoS®](https://3dfabric.tsmc.com/english/dedicatedFoundry/technology/cowos.htm)는 고성능 컴퓨팅 애플리케이션을 위한 동종 최고의 성능과 최고의 통합 밀도를 제공하는 플랫폼입니다. 이 웨이퍼 레벨 시스템 통합 플랫폼은 광범위한 인터포저 크기, HBM 큐브 수 및 패키지 크기를 제공합니다. 이는 4개 이상의 HBM2/HBM2E 큐브와 함께 주요 SoC 칩을 통합하는 2X 레티클 크기(또는 ~1,700mm2)보다 큰 인터포저를 가능하게 할 수 있습니다.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/145732340-8195fa38-c986-4de1-baa5-e69fb06100ed.png">
  <br />
  TSMC CoWoS®-S 아키텍처
</p>

[CoWoS-R](https://3dfabric.tsmc.com/english/dedicatedFoundry/technology/cowos.htm#tbc_CoWoS-R)은 RDL 인터포저를 활용하고 특히 HBM(고대역폭 메모리) 및 SoC 이기종 통합에서 칩렛 간의 상호 연결을 제공하기 위해 InFO 기술을 활용하는 CoWoS 고급 패키징 제품군의 구성원입니다. RDL 인터포저는 폴리머와 구리 트레이스로 구성되어 있으며 상대적으로 기계적으로 유연합니다. 이러한 유연성은 C4 조인트 무결성을 향상시키고 새로운 패키지의 크기를 확장하여 보다 복잡한 기능적 요구 사항을 충족할 수 있도록 합니다.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/145732343-9645518b-69b7-4213-b6f3-934373b5176f.png">
  <br />
  TSMC CoWoS®-R 아키텍처
</p>

[CoWoS®-L](https://3dfabric.tsmc.com/english/dedicatedFoundry/technology/cowos.htm#tbc_CoWoS-L)은 CoWoS® 플랫폼의 마지막 칩 패키지 중 하나이며, CoWoS®-S와 InFO 기술의 장점을 결합하여 인터포저와 다이 간 상호 연결을 위한 LSI(Local Silicon Interconnect) 칩 및 전력 및 신호 전달을 위한 RDL 레이어를 사용하여 가장 유연한 통합을 제공합니다. 이 제품은 1x SoC + 4x HBM 큐브를 갖춘 1.5X 레티클 인터포저 크기부터 시작하여 더 많은 칩을 통합하기 위해 봉투를 더 큰 크기로 확장할 예정입니다.

**CoWoS®-L 서비스의 주요 기능은 다음과 같습니다.**

   - 서브미크론 Cu 라인의 다중 레이어를 통한 높은 라우팅 밀도의 다이-다이 상호 연결을 위한 LSI 칩입니다. LSI 칩은 각 제품 내에서 다양한 연결 아키텍처(SoC에서 SoC, SoC에서 칩렛, SoC에서 HBM… 등)를 특징으로 할 수 있으며 여러 제품에 반복적으로 사용될 수도 있습니다. 해당 금속 유형, 레이어 수 및 피치는 CoWoS®-S의 제품과 일치합니다.

   - 전면과 후면 모두 넓은 피치의 RDL 레이어와 신호 및 전력 전달을 위한 TIV(Through Interposer Via)를 적용한 몰딩 기반 인터포저로 고속 전송 시 고주파 신호 손실이 적습니다.

   - 더 나은 PI/SI와의 신호 통신을 지원하기 위해 SoC 다이 바로 아래에 추가 요소인 독립형 IPD(통합 수동 장치)를 통합하는 기능이 있습니다.

   <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/145732345-22e0a913-13de-456a-aa36-84d8f4a9c8db.png">
  <br />
  TSMC CoWoS®-L 아키텍처
</p>

# Xcode 개발
[맨 위로 돌아가기](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/141201793-f31f4899-7317-49a7-808b-6e551df23bf9.png">
  <br />
</p>

## Xcode 시작하기

**개발자 리소스:**

 * [Xcode용 Apple 개발자 문서](https://developer.apple.com/documentation/xcode)
 * [Apple 전문가 교육 과정](https://training.apple.com/)
 * [Apple 개발자 도구 및 SDK](https://developer.apple.com/download/)
 * [Apple API 참조](https://developer.apple.com/documentation/)
 * [Swift Playgrounds로 코딩 배우기](https://developer.apple.com/swift-playgrounds/)
 * [Swift 탐색으로 개발](https://apple.co/teachingcode)
 * [Swift 기본 사항으로 개발](https://apple.co/teachingcode)
 * [Swift 데이터 컬렉션 개발](https://apple.co/teachingcode)
 * [Swift 앱 디자인 워크북에서 개발](https://education-static.apple.com/coding-club-kit/appworkbook.key)
 * [스위프트 코딩 클럽](https://www.apple.com/education/k12/teaching-code/#coding-club)

[Xcode](https://developer.apple.com/xcode/)에는 개발자가 Mac, iPhone, iPad, Apple TV 및 Apple Watch용 훌륭한 응용 프로그램을 만드는 데 필요한 모든 것이 포함되어 있습니다. Xcode는 개발자에게 사용자 인터페이스 디자인, 코딩, 테스트 및 디버깅을 위한 통합 워크플로를 제공합니다. Xcode 14는 Intel 기반 CPU 및 Apple Silicon에서 기본적으로 100% 실행되는 범용 앱으로 구축되었습니다. 여기에는 Apple Silicon 및 Intel x86_64 CPU에서 기본적으로 실행되는 앱을 구축하는 데 필요한 모든 프레임워크, 컴파일러, 디버거 및 기타 도구를 갖춘 통합 macOS SDK가 포함되어 있습니다.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/176965201-6573e818-3b14-42b9-a1c2-5159d4aa33a9.png">
<br />
Xcode 14에서 SwiftUI를 사용하여 개발
</p>

[Xcode Cloud](https://developer.apple.com/xcode-cloud/)는 Xcode에 내장되어 Apple 개발자를 위해 특별히 설계된 지속적인 통합 및 제공 서비스입니다. 앱을 구축하고, 자동화된 테스트를 병렬로 실행하고, 테스터에게 앱을 제공하고, 사용자 피드백을 보고 관리하는 데 도움이 되는 클라우드 기반 도구를 통합하여 고품질 앱의 개발 및 제공을 가속화합니다.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/176965198-b5e29ebf-4c75-4c2f-b10c-32a840371d26.jpg">
<br />
</p>

**Xcode 클라우드. 출처: [Apple](https://developer.apple.com/xcode-cloud/)**

[SwiftUI](https://developer.apple.com/documentation/swiftui)는 앱의 사용자 인터페이스를 선언하기 위한 보기, 컨트롤 및 레이아웃 구조를 제공하는 사용자 인터페이스 툴킷입니다. SwiftUI 프레임워크는 탭, 제스처 및 기타 유형의 입력을 애플리케이션에 전달하기 위한 이벤트 핸들러를 제공합니다.

[UIKit](https://developer.apple.com/documentation/uikit)은 iOS 또는 tvOS 앱에 필요한 인프라를 제공하는 프레임워크입니다. 이는 인터페이스 구현을 위한 창 및 보기 아키텍처, 멀티 터치 및 기타 유형의 입력을 앱에 제공하기 위한 이벤트 처리 인프라, 사용자, 시스템 및 앱 간의 상호 작용을 관리하는 데 필요한 기본 실행 루프를 제공합니다.

[AppKit](https://developer.apple.com/documentation/appkit)은 창, 패널, 버튼, 메뉴, 스크롤러, 텍스트 필드 등 macOS 앱용 사용자 인터페이스를 구현하는 데 필요한 모든 개체가 포함된 그래픽 사용자 인터페이스 도구 키트로, 화면에 효율적으로 그리기, 하드웨어 장치 및 화면 버퍼와 통신하기, 그리기 전에 화면 영역 지우기, 보기 자르기 등 모든 세부 사항을 처리합니다.

[ARKit](https://developer.apple.com/augmented-reality/arkit/)은 개발자가 Apple에서 개발한 iOS용 증강 현실 앱을 구축할 수 있도록 지원하는 소프트웨어 개발 도구 세트입니다. 최신 버전 ARKit 3.5는 iPad Pro(2020)의 새로운 LiDAR 스캐너와 깊이 감지 시스템을 활용하여 향상된 장면 이해 및 객체 폐색을 위해 장면 기하학을 사용하는 차세대 AR 앱을 지원합니다.

[RealityKit](https://developer.apple.com/documentation/realitykit)은 ARKit 프레임워크에서 제공하는 정보를 사용하여 고성능 3D 시뮬레이션 및 렌더링을 구현하여 가상 객체를 현실 세계에 원활하게 통합하는 프레임워크입니다.

[SceneKit](https://developer.apple.com/scenekit/)은 iOS 앱에서 3D 애니메이션 장면과 효과를 만드는 데 도움이 되는 고급 3D 그래픽 프레임워크입니다.

[Mac Catalyst](https://developer.apple.com/mac-catalyst/)는 개발자가 iOS 앱을 [Apple Silicon M1 Chip](https://www.apple.com/mac/m1/)으로 빠르게 포팅하고 새로운 Apple 하드웨어의 새로운 기능을 최대한 활용하는 데 사용할 수 있는 Apple API 세트입니다.

[Instruments](https://help.apple.com/instruments/mac/current/#/dev7b09c84f5)는 Xcode 도구 세트의 일부인 강력하고 유연한 성능 분석 및 테스트 도구입니다. 이는 iOS, watchOS, tvOS 및 macOS 앱, 프로세스 및 장치의 동작과 성능을 더 잘 이해하고 최적화하기 위해 프로파일링하는 데 도움이 되도록 설계되었습니다.

[TestFlight](https://developer.apple.com/testflight/)는 App Store에 앱을 출시하기 전에 앱과 App Clip을 테스트하고 귀중한 피드백을 수집하도록 사용자를 쉽게 초대할 수 있는 도구입니다. 이메일 주소만 사용하거나 공개 링크를 공유하여 최대 10,000명의 테스터를 초대할 수 있습니다.

# 핵심 ML 개발
[맨 위로 돌아가기](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/132140794-0d4bf654-0884-4068-b5bb-eaee36c36797.png">
  <br />
</p>

## 핵심 ML 학습 리소스

[Core ML](https://developer.apple.com/documentation/coreml)은 기계 학습 모델을 Apple 기기(iOS, watchOS, macOS, tvOS 포함)에서 실행되는 앱에 통합하기 위한 Apple 프레임워크입니다. Core ML은 심층 신경망(컨벌루션 및 순환 모두), 부스팅이 포함된 트리 앙상블, 일반화된 선형 모델을 포함한 광범위한 ML 방법 세트를 위한 공개 파일 형식(.mlmodel)을 도입합니다. 이 형식의 모델은 Xcode를 통해 앱에 직접 통합될 수 있습니다.

[Core ML 소개](https://coremltools.readme.io/docs)

[앱에 Core ML 모델 통합](https://developer.apple.com/documentation/coreml/integrating_a_core_ml_model_into_your_app)

[핵심 ML 모델](https://developer.apple.com/machine-learning/models/)

[핵심 ML API 참조](https://apple.github.io/coremltools/index.html)

[핵심 ML 사양](https://apple.github.io/coremltools/mlmodel/index.html)

[Core ML을 위한 Apple 개발자 포럼](https://developer.apple.com/forums/tags/core-ml)

[최고의 핵심 ML 온라인 강좌 | Udemy](https://www.udemy.com/topic/Core-ML/)

[최고의 핵심 ML 온라인 강좌 | Coursera](https://www.coursera.org/courses?query=core%20ml)

[Core ML용 IBM Watson 서비스 | IBM](https://www.ibm.com/watson/stories/coreml)

[Apple Silicon에서의 Core ML을 통한 안정적인 확산](https://machinelearning.apple.com/research/stable-diffusion-coreml-apple-silicon)

[IBM Maximo Visual Inspection을 사용하여 Core ML 자산 생성 | IBM](https://developer.ibm.com/technologies/iot/tutorials/ibm-maximo-visual-inspection-apple-devices/)

## 핵심 ML 도구, 라이브러리 및 프레임워크

[Core ML 도구](https://github.com/apple/coremltools)는 타사 라이브러리의 기계 학습 모델을 Core ML 형식으로 변환하는 도구입니다. 이 Python 패키지에는 다음과 같은 학습 라이브러리의 모델을 변환하기 위한 지원 도구가 포함되어 있습니다.

   * [텐서플로우](https://www.tensorflow.org/versions/r1.15/api_docs/python/tf)
   * 텐서플로우 2](https://www.tensorflow.org/api_docs)
   * [파이토치](https://pytorch.org/)
    
**비신경망 프레임워크:**
   * [scikit-learn](https://scikit-learn.org/stable/)
   * [XGBoost](https://xgboost.readthedocs.io/en/latest/)
   * [LibSVM](https://www.csie.ntu.edu.tw/~cjlin/libsvm/)

[ML 생성](https://developer.apple.com/machine-learning/create-ml/)은 Mac에서 머신러닝 모델을 훈련하는 새로운 방법을 제공하는 도구입니다. 강력한 Core ML 모델을 생성하면서 모델 훈련의 복잡성을 제거합니다.

[Apple FaceLit](https://github.com/apple/ml-facelit/)은 Neural 3D Relightable Faces입니다.

[TensorFlow](https://www.tensorflow.org)는 머신러닝을 위한 엔드투엔드 오픈소스 플랫폼입니다. 연구자가 ML의 최첨단 기능을 활용하고 개발자가 ML 기반 애플리케이션을 쉽게 구축 및 배포할 수 있는 도구, 라이브러리, 커뮤니티 리소스로 구성된 포괄적이고 유연한 생태계를 갖추고 있습니다.

[Keras](https://keras.io)는 Python으로 작성되었으며 TensorFlow, CNTK 또는 Theano 위에서 실행될 수 있는 고급 신경망 API입니다. 빠른 실험을 가능하게 하는 데 중점을 두고 개발되었습니다. TensorFlow, Microsoft Cognitive Toolkit, R, Theano 또는 PlaidML 위에서 실행될 수 있습니다.

[PyTorch](https://pytorch.org)는 그래프, 포인트 클라우드, 매니폴드 등 불규칙한 입력 데이터에 대한 딥러닝을 위한 라이브러리입니다. 주로 Facebook의 AI 연구소에서 개발되었습니다.

[XGBoost](https://xgboost.readthedocs.io/)는 매우 효율적이고 유연하며 이식 가능하도록 설계된 최적화된 분산 그래디언트 부스팅 라이브러리입니다. Gradient Boosting 프레임워크에서 기계 학습 알고리즘을 구현합니다. XGBoost는 빠르고 정확한 방법으로 많은 데이터 과학 문제를 해결하는 병렬 트리 부스팅(GBDT, GBM이라고도 함)을 제공합니다. AWS, GCE, Azure 및 Yarn 클러스터를 포함한 여러 시스템에 대한 분산 교육을 지원합니다. 또한 Flink, Spark 및 기타 클라우드 데이터 흐름 시스템과 통합될 수 있습니다.

[LIBSVM](https://www.csie.ntu.edu.tw/~cjlin/libsvm/)은 지원 벡터 분류(C-SVC, nu-SVC), 회귀(epsilon-SVR, nu-SVR) 및 분포 추정(1클래스 SVM)을 위한 통합 소프트웨어입니다. 다중 클래스 분류를 지원합니다.

[Scikit-Learn](https://scikit-learn.org/stable/index.html)은 데이터 마이닝 및 데이터 분석을 위한 간단하고 효율적인 도구입니다. NumPy, SciPy 및 mathplotlib를 기반으로 구축되었습니다.

[Apple Vision](https://developer.apple.com/documentation/vision)은 얼굴 및 얼굴 랜드마크 감지, 텍스트 감지, 바코드 인식, 이미지 등록, 일반 특징 추적을 수행하는 프레임워크입니다. Vision을 사용하면 분류 또는 객체 감지와 같은 작업에 맞춤형 Core ML 모델을 사용할 수도 있습니다.

[Xcode](https://developer.apple.com/xcode/)에는 개발자가 Mac, iPhone, iPad, Apple TV 및 Apple Watch용 훌륭한 응용 프로그램을 만드는 데 필요한 모든 것이 포함되어 있습니다. Xcode는 개발자에게 사용자 인터페이스 디자인, 코딩, 테스트 및 디버깅을 위한 통합 워크플로를 제공합니다. Xcode 12는 Intel 기반 CPU 및 Apple Silicon에서 기본적으로 100% 실행되는 범용 앱으로 구축되었습니다. 여기에는 Apple Silicon 및 Intel x86_64 CPU에서 기본적으로 실행되는 앱을 구축하는 데 필요한 모든 프레임워크, 컴파일러, 디버거 및 기타 도구를 갖춘 통합 macOS SDK가 포함되어 있습니다.

[SwiftUI](https://developer.apple.com/documentation/swiftui)는 앱의 사용자 인터페이스를 선언하기 위한 보기, 컨트롤 및 레이아웃 구조를 제공하는 사용자 인터페이스 툴킷입니다. SwiftUI 프레임워크는 탭, 제스처 및 기타 유형의 입력을 애플리케이션에 전달하기 위한 이벤트 핸들러를 제공합니다.

[UIKit](https://developer.apple.com/documentation/uikit)은 iOS 또는 tvOS 앱에 필요한 인프라를 제공하는 프레임워크입니다. 이는 인터페이스 구현을 위한 창 및 보기 아키텍처, 멀티 터치 및 기타 유형의 입력을 앱에 제공하기 위한 이벤트 처리 인프라, 사용자, 시스템 및 앱 간의 상호 작용을 관리하는 데 필요한 기본 실행 루프를 제공합니다.

[AppKit](https://developer.apple.com/documentation/appkit)은 창, 패널, 버튼, 메뉴, 스크롤러, 텍스트 필드 등 macOS 앱용 사용자 인터페이스를 구현하는 데 필요한 모든 개체가 포함된 그래픽 사용자 인터페이스 도구 키트로, 화면에 효율적으로 그리기, 하드웨어 장치 및 화면 버퍼와 통신하기, 그리기 전에 화면 영역 지우기, 보기 자르기 등 모든 세부 사항을 처리합니다.

[ARKit](https://developer.apple.com/augmented-reality/arkit/)은 개발자가 Apple에서 개발한 iOS용 증강 현실 앱을 구축할 수 있도록 지원하는 소프트웨어 개발 도구 세트입니다.

[RealityKit](https://developer.apple.com/documentation/realitykit)은 ARKit 프레임워크에서 제공하는 정보를 사용하여 고성능 3D 시뮬레이션 및 렌더링을 구현하여 가상 객체를 현실 세계에 원활하게 통합하는 프레임워크입니다.

[SceneKit](https://developer.apple.com/scenekit/)은 iOS 앱에서 3D 애니메이션 장면과 효과를 만드는 데 도움이 되는 고급 3D 그래픽 프레임워크입니다.

[Instruments](https://help.apple.com/instruments/mac/current/#/dev7b09c84f5)는 Xcode 도구 세트의 일부인 강력하고 유연한 성능 분석 및 테스트 도구입니다. 이는 iOS, watchOS, tvOS 및 macOS 앱, 프로세스 및 장치의 동작과 성능을 더 잘 이해하고 최적화하기 위해 프로파일링하는 데 도움이 되도록 설계되었습니다.

[CocoaPods](https://cocoapods.org/)는 간단한 텍스트 파일에서 프로젝트에 대한 종속성을 지정하여 Xcode 프로젝트에서 사용되는 Swift 및 Objective-C용 종속성 관리자입니다. 그런 다음 CocoaPods는 라이브러리 간의 종속성을 반복적으로 해결하고, 모든 종속성에 대한 소스 코드를 가져오고, Xcode 작업공간을 생성 및 유지하여 프로젝트를 빌드합니다.

[AppCode](https://www.jetbrains.com/objc/)에서는 코드 품질을 지속적으로 모니터링하고 있습니다. 오류와 냄새에 대해 경고하고 자동으로 해결하기 위한 빠른 수정 사항을 제안합니다. AppCode는 Objective-C, Swift, C/C++에 대한 다양한 코드 검사와 기타 지원되는 언어에 대한 다양한 코드 검사를 제공합니다.

# 금속개발
[맨 위로 돌아가기](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/172255611-762a151f-6891-44b2-a0cf-657005e317ff.png">
  <br />
</p>

## 금속 학습 자료

[Metal](https://developer.apple.com/metal/)은 그래픽과 컴퓨팅 프로그램 간의 긴밀한 통합을 통해 풍부한 셰이딩 언어를 사용하여 최신 3D 프로 애플리케이션과 놀라운 게임을 개발하기 위해 플랫폼에 최적화되고 오버헤드가 낮은 API를 제공하는 하위 수준 API입니다. 점점 더 복잡한 셰이더 코드를 관리하면서 더 많은 작업을 수행할 수 있도록 Metal은 그래픽 코드의 잠재력을 최대한 실현할 수 있도록 돕는 비교할 수 없는 고급 GPU 디버깅 도구 모음을 추가합니다.

[Metal 3](https://developer.apple.com/metal/)은 고급 기능과 컴파일러 도구를 도입하여 리소스를 더 빠르게 로드하고, 빌드 시 셰이더 바이너리를 컴파일하고, 메시 셰이더로 복잡한 형상을 처리하고, 더 짧은 시간에 고해상도 그래픽을 렌더링하고, 기계 학습 네트워크를 더 빠르게 훈련시키는 등의 기능을 제공하는 Apple의 최신 그래픽 API입니다.

* [Apple 개발자 문서](https://developer.apple.com/documentation)

* [메탈킷](https://developer.apple.com/documentation/metalkit/)

* [메탈 셰이딩 언어 사양](https://developer.apple.com/metal/Metal-Shading-Language-Specification.pdf)

* [Metal 기능 세트 테이블 사용](https://developer.apple.com/documentation/metal/gpu_features/using_metal_feature_set_tables/)

* [메탈 퍼포먼스 셰이더](https://developer.apple.com/documentation/metalperformanceshaders/)

* [GPU 카운터 계측기로 성능 최적화](https://developer.apple.com/documentation/metal/optimizing_performance_with_the_gpu_counters_instrument?language=objc)

* [프레임 캡처 활성화](https://developer.apple.com/documentation/metal/frame_capture_debugging_tools/enabling_frame_capture?language=objc)

* [메탈 앱의 메모리 사용량 줄이기](https://developer.apple.com/documentation/metal/reducing_the_memory_footprint_of_metal_apps)

* [Windows용 Metal 개발자 도구](https://developer.apple.com/download/release/)

* [금속 샘플 코드](https://developer.apple.com/metal/sample-code/)

* [TensorFlow용 Metal 플러그인](https://developer.apple.com/metal/tensorflow-plugin/)

* [Metal 개발자 토론](https://developer.apple.com/forums/tags/metal/)


## 금속 도구, 라이브러리 및 프레임워크

[MTLDevice](https://developer.apple.com/documentation/metal/mtldevice)는 그래픽을 그리거나 병렬 계산을 수행하는 데 사용하는 GPU에 대한 Metal 인터페이스입니다.

[Metal-cpp](https://developer.apple.com/metal/cpp/)는 C++로 작성된 그래픽 앱, 게임 및 게임 엔진에 Metal 기능을 추가하는 데 도움이 되는 오버헤드가 낮은 Metal용 C++ 인터페이스입니다. [샘플 코드](https://developer.apple.com/metal/LearnMetalCPP.zip)

[TensorFlow용 Metal 플러그인](https://developer.apple.com/metal/tensorflow-plugin/)은 GPU에서 가속화된 새로운 작업, 사용자 정의 작업 및 분산 교육 지원을 통해 기계 학습 교육에 개선 사항을 추가하는 TensorFlow-Metal PluggableDevice입니다.

[MetalFX](https://developer.apple.com/videos/play/wwdc2022/10103/)는 Metal 애플리케이션을 위한 플랫폼 최적화 그래픽 효과를 제공하는 새로운 API입니다. MetalFX 업스케일링을 사용하면 이제 응용 프로그램에서 렌더링 품질 저하 없이 렌더링 시간을 단축하면서 더 낮은 해상도로 프레임을 렌더링할 수 있습니다. 또한 상당한 성능 향상을 제공하는 공간적 업스케일링과 최고 품질의 렌더링을 제공하는 시간적 AA 및 업스케일링이라는 두 가지 효과를 언제, 어떻게 사용하는지 보여드리겠습니다.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/172254747-9308be59-4d79-4677-a5ec-cf40f5762cf7.png">
  <br />
 MetalFX 렌더링. 크레딧: Apple
</p>

[MetalPetal](https://github.com/MetalPetal/MetalPetal)은 사용하기 쉬운 프로그래밍 인터페이스를 통해 정지 이미지 및 비디오에 대한 실시간 처리를 제공하도록 설계된 Metal 기반의 GPU 가속 이미지 및 비디오 처리 프레임워크입니다.

[Apple Foundation Framework](https://developer.apple.com/documentation/foundation)는 데이터 저장 및 지속성, 텍스트 처리, 날짜 및 시간 계산, 정렬 및 필터링, 네트워킹을 포함하여 앱과 프레임워크에 기본 기능 계층을 제공하는 프레임워크입니다. Foundation에서 정의한 클래스, 프로토콜 및 데이터 유형은 macOS, iOS, watchOS 및 tvOS SDK 전체에서 사용됩니다.

[Apple Core Animation Framework](https://developer.apple.com/documentation/quartzcore)는 CPU에 부담을 주거나 앱 속도를 저하시키지 않으면서 높은 프레임 속도와 부드러운 애니메이션을 제공하는 그래픽 렌더링 및 애니메이션 인프라입니다.

[Apple Core 그래픽 프레임워크](https://developer.apple.com/documentation/coregraphics)는 Quartz 고급 드로잉 엔진을 기반으로 한 프레임워크입니다. 비교할 수 없는 출력 충실도로 낮은 수준의 가벼운 2D 렌더링을 제공합니다.

[반가상화 그래픽 프레임워크](https://developer.apple.com/documentation/paravirtualizedgraphics)는 가상 머신(이하 게스트)에서 실행되는 macOS용 하드웨어 가속 그래픽을 구현하는 프레임워크입니다. macOS 운영 체제는 게스트 내부에서 실행되는 그래픽 드라이버를 제공하여 호스트 운영 체제의 프레임워크와 통신하여 Metal 가속 그래픽을 활용합니다.

[Xcode](https://developer.apple.com/xcode/)에는 개발자가 Mac, iPhone, iPad, Apple TV 및 Apple Watch용 훌륭한 응용 프로그램을 만드는 데 필요한 모든 것이 포함되어 있습니다. Xcode는 개발자에게 사용자 인터페이스 디자인, 코딩, 테스트 및 디버깅을 위한 통합 워크플로를 제공합니다. Xcode 12는 Intel 기반 CPU 및 Apple Silicon에서 기본적으로 100% 실행되는 범용 앱으로 구축되었습니다. 여기에는 Apple Silicon 및 Intel x86_64 CPU에서 기본적으로 실행되는 앱을 구축하는 데 필요한 모든 프레임워크, 컴파일러, 디버거 및 기타 도구를 갖춘 통합 macOS SDK가 포함되어 있습니다.

[SwiftUI](https://developer.apple.com/documentation/swiftui)는 앱의 사용자 인터페이스를 선언하기 위한 보기, 컨트롤 및 레이아웃 구조를 제공하는 사용자 인터페이스 툴킷입니다. SwiftUI 프레임워크는 탭, 제스처 및 기타 유형의 입력을 애플리케이션에 전달하기 위한 이벤트 핸들러를 제공합니다.

[UIKit](https://developer.apple.com/documentation/uikit)은 iOS 또는 tvOS 앱에 필요한 인프라를 제공하는 프레임워크입니다. 이는 인터페이스 구현을 위한 창 및 보기 아키텍처, 멀티 터치 및 기타 유형의 입력을 앱에 제공하기 위한 이벤트 처리 인프라, 사용자, 시스템 및 앱 간의 상호 작용을 관리하는 데 필요한 기본 실행 루프를 제공합니다.

[AppKit](https://developer.apple.com/documentation/appkit)은 창, 패널, 버튼, 메뉴, 스크롤러, 텍스트 필드 등 macOS 앱용 사용자 인터페이스를 구현하는 데 필요한 모든 개체가 포함된 그래픽 사용자 인터페이스 도구 키트로, 화면에 효율적으로 그리기, 하드웨어 장치 및 화면 버퍼와 통신하기, 그리기 전에 화면 영역 지우기, 보기 자르기 등 모든 세부 사항을 처리합니다.

[ARKit](https://developer.apple.com/augmented-reality/arkit/)은 개발자가 Apple에서 개발한 iOS용 증강 현실 앱을 구축할 수 있도록 지원하는 소프트웨어 개발 도구 세트입니다. 최신 버전 ARKit 3.5는 iPad Pro(2020)의 새로운 LiDAR 스캐너와 깊이 감지 시스템을 활용하여 향상된 장면 이해 및 객체 폐색을 위해 장면 기하학을 사용하는 차세대 AR 앱을 지원합니다.

[RealityKit](https://developer.apple.com/documentation/realitykit)은 ARKit 프레임워크에서 제공하는 정보를 사용하여 고성능 3D 시뮬레이션 및 렌더링을 구현하여 가상 객체를 현실 세계에 원활하게 통합하는 프레임워크입니다.

[SceneKit](https://developer.apple.com/scenekit/)은 iOS 앱에서 3D 애니메이션 장면과 효과를 만드는 데 도움이 되는 고급 3D 그래픽 프레임워크입니다.

[Instruments](https://help.apple.com/instruments/mac/current/#/dev7b09c84f5)는 Xcode 도구 세트의 일부인 강력하고 유연한 성능 분석 및 테스트 도구입니다. 이는 iOS, watchOS, tvOS 및 macOS 앱, 프로세스 및 장치의 동작과 성능을 더 잘 이해하고 최적화하기 위해 프로파일링하는 데 도움이 되도록 설계되었습니다.

[CocoaPods](https://cocoapods.org/)는 간단한 텍스트 파일에서 프로젝트에 대한 종속성을 지정하여 Xcode 프로젝트에서 사용되는 Swift 및 Objective-C용 종속성 관리자입니다. 그런 다음 CocoaPods는 라이브러리 간의 종속성을 반복적으로 해결하고, 모든 종속성에 대한 소스 코드를 가져오고, Xcode 작업공간을 생성 및 유지하여 프로젝트를 빌드합니다.

[AppCode](https://www.jetbrains.com/objc/)에서는 코드 품질을 지속적으로 모니터링하고 있습니다. 오류와 냄새에 대해 경고하고 자동으로 해결하기 위한 빠른 수정 사항을 제안합니다. AppCode는 Objective-C, Swift, C/C++에 대한 다양한 코드 검사와 기타 지원되는 언어에 대한 다양한 코드 검사를 제공합니다.

[MoltenVK](https://moltengl.com/moltenvk)는 Apple의 [Metal](https://developer.apple.com/metal/) 그래픽 프레임워크를 사용하여 iOS 및 macOS에서 실행되는 Vulkan의 구현입니다.

## VSCode 개발

[맨 위로 돌아가기](#목차)

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/140833078-77973dcf-d3a6-421f-b6a7-b6e63fb1e97c.png">
<br />
</p>

 * [VS 코드 문서](https://code.visualstudio.com/docs)

 * [VS Code에서 GitHub 작업](https://code.visualstudio.com/docs/editor/github)

[Visual Studio Code](https://code.visualstudio.com)는 데스크톱에서 실행되고 Windows, macOS 및 Linux에서 사용할 수 있는 가볍지만 강력한 소스 코드 편집기입니다. JavaScript, TypeScript 및 Node.js에 대한 기본 지원이 제공되며 다른 언어(예: C++, C#, Java, Python, PHP, Go) 및 런타임(예: .NET 및 Unity)에 대한 풍부한 확장 에코시스템을 갖추고 있습니다.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/140832435-49e53589-e9e1-47fe-a1bd-d9800cfc1274.png">
<br />
VS 코드
</p>

[Visual Studio Code Marketplace](https://marketplace.visualstudio.com/VSCode)는 Visual Studio, Azure DevOps Services, Azure DevOps Server 및 Visual Studio Code에 대한 모든 확장을 위한 마켓플레이스입니다.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/140832440-0247a088-4eeb-4c57-ae7d-90894d56d629.png">
<br />
VS 코드 마켓플레이스
</p>

[코드 서버](https://coder.com/)는 어디에서나 모든 컴퓨터에서 [VS 코드](https://code.visualstudio.com/)를 실행하고 브라우저에서 액세스할 수 있게 해주는 도구입니다.

[GitHub Codespaces](https://docs.github.com/en/free-pro-team@latest/github/developing-online-with-codespaces)는 GitHub의 통합 개발 환경(IDE)입니다. 이를 통해 개발자는 Visual Studio 및 Visual Studio Code를 사용하여 클라우드에서 완전히 개발할 수 있습니다. 또한 GitHub의 모든 리포지토리 또는 끌어오기 요청에서 간단히 키보드의 마침표(.) 키를 눌러 편집할 수 있는 소스 코드 파일이 있는 브라우저 기반 VS Code 환경을 불러올 수 있습니다. 점(.)을 눌러 웹 기반 VS Code 편집기를 불러오면 https://github.dev/.로 이동합니다.

[LSP(언어 서버 프로토콜)](https://microsoft.github.io/language-server-protocol/)는 자동 완성, 정의로 이동, 모든 참조 찾기와 같은 언어 기능을 제공하는 편집기 또는 IDE와 언어 서버 간에 사용되는 프로토콜을 정의하는 도구입니다.

### 개발자 생산성을 위한 VS 코드 확장

[맨 위로 돌아가기](#목차)

[Visual Studio Live Share](https://visualstudio.microsoft.com/services/live-share/)는 사용 중인 프로그래밍 언어나 빌드 중인 앱 유형에 관계없이 실시간으로 다른 사람들과 공동으로 편집하고 디버깅할 수 있는 서비스/확장입니다. 현재 프로젝트를 즉각적이고 안전하게 공유하고, 공동 디버깅 세션을 시작하고, 터미널 인스턴스를 공유하고, 로컬 호스트 웹 앱을 전달하고, 음성 통화 등을 할 수 있습니다.

[GistPad](https://marketplace.visualstudio.com/items?itemName=vsls-contrib.gistfs)는 즐겨 사용하는 편집기에서 편안하게 GitHub Gists 및 리포지토리를 편집할 수 있는 Visual Studio Code 확장입니다. 요점과 리포지토리를 열고, 생성하고, 삭제하고, 분기하고, 별표를 표시한 다음 아무것도 복제하거나 밀거나 당기지 않고도 마치 로컬에 있는 것처럼 파일 편집을 원활하게 시작할 수 있습니다.

[라이브 서버](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)는 정적 및 동적 페이지에 대한 라이브 다시 로드 기능을 사용하여 개발 로컬 서버를 시작하는 Visual Studio Code의 확장입니다.

[GitHub 끌어오기 요청 및 문제](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github)는 Visual Studio Code에서 GitHub 끌어오기 요청 및 문제를 검토하고 관리할 수 있는 Visual Studio Code용 확장입니다.

[터미널](https://marketplace.visualstudio.com/items?itemName=formulahendry.terminal)은 편집기에서 직접 터미널 명령을 실행할 수 있는 Visual Studio Code의 확장입니다.

[프로필 전환기](https://marketplace.visualstudio.com/items?itemName=aaronpowell.vscode-profile-switcher)는 생성한 다양한 프로필 간에 전환할 수 있는 Visual Studio Code용 확장입니다.

[머티리얼 아이콘 테마](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)는 머티리얼 디자인 아이콘을 VS Code로 가져오는 Visual Studio Code의 확장입니다.

[One Dark Pro](https://marketplace.visualstudio.com/items?itemName=zhuangtongfa.Material-theme)는 VS Code에 가장 많이 설치된 테마 중 하나인 Atom의 상징적인 One Dark 테마를 추가하는 Visual Studio Code의 확장입니다.

[VSCode 아이콘](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons)은 Visual Studio Code 설정에 아이콘을 제공하는 Visual Studio Code용 확장입니다.

[GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)는 Git 비난 주석 및 코드 렌즈를 통해 코드 작성자를 한눈에 시각화하고, Git 리포지토리를 원활하게 탐색 및 탐색하고, 강력한 비교 명령을 통해 귀중한 통찰력을 얻는 데 도움이 되는 Visual Studio Code의 확장입니다.

[가져오기 비용](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost)은 가져온/필수 패키지의 크기를 편집기에 인라인으로 표시하는 Visual Studio Code용 확장입니다. 확장은 가져온 크기를 감지하기 위해 babili-webpack-plugin과 함께 webpack을 활용합니다.

[Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)은 Markdown을 작성하는 데 필요한 모든 것(키보드 단축키, 목차, 자동 미리 보기 등)을 제공하는 Visual Studio Code의 확장입니다.

[자동 이름 바꾸기 태그](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)는 Visual Studio IDE 또는 Sublime Text와 마찬가지로 HTML/XML 닫기 태그를 자동으로 추가하는 Visual Studio Code용 확장입니다.

[자동 닫기 태그](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag)는 Visual Studio IDE 또는 Sublime Text와 마찬가지로 HTML/XML 닫기 태그를 자동으로 추가하는 Visual Studio Code용 확장입니다.

[설정 동기화](https://marketplace.visualstudio.com/items?itemName=Shan.code-settings-sync)는 GitHub Gist를 사용하여 여러 컴퓨터에서 설정, 조각, 테마, 파일 아이콘, 실행, 키 바인딩, 작업 영역 및 확장을 동기화하는 Visual Studio Code용 확장입니다.

[북마크](https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks)는 코드 줄을 표시하고 해당 줄로 이동할 수 있는 Visual Studio Code의 확장입니다.

[Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments)는 경고, 정보, TODO 등의 주석을 추가하여 코드 주석 처리를 개선하는 Visual Studio Code의 확장입니다.

[코드 맞춤법 검사기](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)는 소스 코드의 맞춤법 검사기로 작동하는 Visual Studio Code의 확장입니다.

[CSS Peak](https://marketplace.visualstudio.com/items?itemName=pranaygp.vscode-css-peek)는 HTML 파일에서 해당 CSS에 대한 정의로 CSS ID 및 클래스 문자열을 엿볼 수 있는 Visual Studio Code용 확장입니다. 또한 정의를 엿보고 고토할 수도 있습니다.

[Tailwind CSS IntelliSense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss)는 Visual Studio Code 사용자에게 자동 완성, 구문 강조 표시, Linting과 같은 고급 기능을 제공하여 Tailwind 개발 환경을 향상시키는 Visual Studio Code용 확장 프로그램입니다.

[Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)는 독창적인 코드 포맷터인 Visual Studio Code의 확장입니다. 코드를 구문 분석하고 최대 줄 길이를 고려하여 필요한 경우 코드를 래핑하는 자체 규칙으로 다시 인쇄하여 일관된 스타일을 적용합니다.

[NPM Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense)는 import 문에서 npm 모듈을 자동 완성하는 Visual Studio Code용 확장입니다.

[Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)는 파일 이름을 자동 완성하는 Visual Studio Code의 확장입니다.

[상대 경로](https://marketplace.visualstudio.com/items?itemName=jakob101.RelativePath)는 현재 작업 영역의 파일에서 상대 URL 경로를 가져오는 Visual Studio Code의 확장입니다.

[경로 자동 완성](https://marketplace.visualstudio.com/items?itemName=ionutvmi.path-autocomplete)은 Visual Studio 코드에 대한 경로 완성을 제공하는 Visual Studio Code의 확장입니다.

[Discord Presence](https://marketplace.visualstudio.com/items?itemName=icrawl.discord-vscode)는 풍부한 현재 상태로 불일치 상태를 업데이트하는 Visual Studio Code의 확장입니다.

[Code Runner](https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner)는 C/C++, Java, JavaScript, PHP, Python, Perl, Ruby, Go, Lua, Groovy, PowerShell, BASH/SH, C#, F#, .NET Core, TypeScript, CoffeeScript, Scala, Swift, Julia, OCaml, R, Elixir, Clojure, Haxe, Objective-C, Rust, Racket, Scheme, Kotlin, Dart, Haskell, Nim, D, CUDA 및 사용자 정의 명령.

[Kite](https://marketplace.visualstudio.com/items?itemName=kiteco.kite)는 Visual Studio Code 내에서 코드를 더 빠르게 작성하는 데 도움이 되는 AI 기반 프로그래밍 도우미를 제공하는 Visual Studio Code의 확장입니다. Kite는 Python, Java, Go, PHP, C/C#/C++, Javascript, HTML/CSS, Typescript, React, Ruby, Scala, Kotlin, Bash, Vue 및 React 등 모든 주요 프로그래밍 언어에서 작동합니다.

[Tabnine](https://marketplace.visualstudio.com/items?itemName=TabNine.tabnine-vscode)은 수백만 명의 개발자가 더 적은 오류로 더 빠르게 코딩할 수 있도록 신뢰하는 AI 코드 완성 도구를 제공하는 Visual Studio Code의 확장입니다. 새로운 개발자이든 노련한 전문가든, 혼자 일하든 팀의 일원이든 Tabnine은 즐겨 사용하는 IDE에서 QA 시간을 단축하는 동시에 생산성을 새로운 차원으로 끌어올리는 데 도움이 됩니다.


## 언리얼 엔진 5 개발

[맨 위로 돌아가기](#목차)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/162537763-308611ef-a619-4fcd-99bf-bfe328c50f27.png">
  <br />
</p>

**권장 하드웨어 요구 사항:**

* **OS:** MacOS 12 이상

* **CPU/GPU:** M1 Pro(10코어 CPU, 16코어 GPU)

* **RAM:** 32GB

* **스토리지:** 1TB

[Unreal Engine 5](https://www.unrealengine.com/unreal-engine-5)는 Epic Games가 세계에서 가장 개방적이고 진보된 실시간 3D 제작 도구를 사용하여 개발한 게임 엔진입니다. 최첨단 게임 엔진이라는 원래 목적을 달성하기 위해 지속적으로 발전하고 있는 이 엔진은 오늘날 업계 전반의 제작자에게 최첨단 콘텐츠, 대화형 경험 및 몰입형 가상 세계를 제공할 수 있는 자유와 제어권을 제공합니다.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/162538256-a3390573-88b8-4925-a92e-70a56da951b3.png">
  <br />
  Unreal Engine 5와 Big City 샘플 프로젝트
</p>

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/146693087-56cfbc91-3398-425c-90a1-6a2479ca3fce.png">
  <br />
</p>

 언리얼 엔진 트윈모션. 출처: [언리얼 엔진](https://www.unrealengine.com/en-US/blog/twinmotion-2021-1-is-here)
 
 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/180627376-15ab099e-f433-4e0b-bf29-3ebf48b95fe8.png">
  <br />
  언리얼 엔진 5 프로젝트 브라우저
</p>

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/180627379-afa5a3d7-c50a-4d9f-94c8-3b14d39cea36.png">
  <br />
  언리얼 엔진 5 차량 프로젝트 데모
</p>

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/172468555-e7f7b4d6-1ba0-4f37-b3dd-f6b17c90b0f1.png">
  <br />
  언리얼 엔진 마켓플레이스
</p>

### 언리얼 엔진 툴
[맨 위로 돌아가기](#목차)

[블루프린트 비주얼 스크립팅](https://docs.unrealengine.com/en-US/Engine/Blueprints/index.html)은 노드 기반 인터페이스를 사용하여 Unreal Editor 내에서 게임플레이 요소를 생성한다는 개념을 기반으로 하는 Unreal Engine의 완전한 게임플레이 스크립팅 시스템입니다. 많은 일반적인 스크립팅 언어와 마찬가지로 엔진에서 객체 지향(OO) 클래스나 객체를 정의하는 데 사용됩니다.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/180627381-f123e873-909c-410a-887e-51b2ba659439.png">
  <br />
 블루프린트 비주얼 스크립팅 UI
</p>

[Datasmith](https://www.unrealengine.com/en-US/datasmith)는 다양한 업계 표준 디자인 애플리케이션에서 생성된 사전 구성 전체 장면과 복잡한 자산을 Unreal Engine으로 가져오는 도구 및 플러그인 모음입니다.

[Chaos Physics](https://docs.unrealengine.com/5.0/en-US/InteractiveExperiences/Physics/ChaosPhysics/Overview/)는 포트나이트에서 사용되는 경량 물리 시뮬레이션 솔루션인 베타 기능으로, 다음과 같은 주요 기능을 포함하고 있습니다.

   * RBAN(강체 애니메이션 노드)
   * 파괴
   * 옷감
   * 래그돌
   * 차량

[나이아가라 VFX 시스템](https://docs.unrealengine.com/5.0/en-US/RenderingAndGraphics/Niagara/)은 Unreal Engine 5(UE5) 내에서 시각 효과(VFX)를 생성하고 조정하는 데 사용할 수 있는 두 가지 도구 중 하나입니다. 나이아가라 이전에는 UE4에서 시각 효과를 만들고 편집하는 주요 방법은 [캐스케이드](https://docs.unrealengine.com/4.27/en-US/RenderingAndGraphics/ParticleSystems)를 사용하는 것이었습니다. Cascade가 제공하는 것과 동일한 파티클 조작 방법이 많이 있지만 나이아가라와 상호 작용하고 시각적 효과를 구축하는 방식은 크게 다릅니다.

[MetaHuman Creator](https://www.unrealengine.com/en-US/metahuman-creator)는 누구나 몇 분 만에 머리카락과 옷까지 완성된 사실적인 디지털 휴먼을 만들 수 있는 무료 클라우드 기반 앱입니다. MetaHumans는 완벽하게 조작되어 Unreal Engine 프로젝트에 애니메이션을 적용할 준비가 되어 있습니다.

[Twinmotion](https://www.twinmotion.com/en-US)은 고품질 이미지, 파노라마, 표준 또는 360° VR 비디오를 몇 초 만에 생성하는 실시간 3D 몰입형 소프트웨어입니다. 건축, 건설, 도시 계획 및 조경 전문가를 위해 개발되었습니다.

[Bridgew by Quixel](https://www.unrealengine.com/en-US/bridge)은 Unreal Engine 내에서 바로 3D 콘텐츠의 세계를 만들 수 있는 관문입니다. 여기에는 실제 스캔 데이터를 기반으로 한 세계 최대 규모의 AAA, 영화 품질 자산 라이브러리인 Megascan이 포함되어 있습니다.

[루멘](https://docs.unrealengine.com/5.0/en-US/RenderingFeatures/Lumen/TechOverview/)은 전역 조명 및 반사를 해결하기 위해 여러 광선 추적 방법을 사용하는 Unreal Engine 5 기능입니다. 화면 추적이 먼저 수행된 후 보다 안정적인 방법이 수행됩니다. 기본적으로 Signed Distance Fields를 통해 소프트웨어 레이 트레이싱을 사용하지만, 하드웨어 레이 트레이싱이 활성화되면 지원 비디오 카드에서 더 높은 품질을 얻을 수 있습니다. **참고:** Lumen은 Unreal 5.2 릴리스의 Apple Silicon에서 작동합니다.

[Nanite](https://docs.unrealengine.com/5.0/en-US/RenderingFeatures/Nanite/)는 Unreal Engine 5의 새로운 가상화된 지오메트리 시스템으로, 새로운 내부 메시 형식과 렌더링 기술을 사용하여 픽셀 크기의 디테일과 많은 개체 수를 렌더링합니다. 그것은 인식될 수 있는 세부 사항에만 지능적으로 작동하며 그 이상은 작동하지 않습니다.

[절차적 콘텐츠 생성 프레임워크(PCG)](https://docs.unrealengine.com/5.2/en-US/procedural-content-generation--framework-in-unreal-engine/)는 Unreal Engine 내에서 자신만의 절차적 콘텐츠를 생성하기 위한 도구 세트입니다. 이는 아티스트와 디자이너에게 건물이나 생물군계 생성과 같은 자산 유틸리티부터 전체 세계에 이르기까지 모든 복잡성의 빠르고 반복적인 도구와 콘텐츠를 구축할 수 있는 기능을 제공합니다.

[Unreal Engine의 VCam 시스템](https://docs.unrealengine.com/5.2/en-US/virtual-cameras-in-unreal-engine/)은 모듈식 구성 요소 시스템을 사용하여 카메라 데이터를 조작하고 최종 결과를 다양한 외부 출력 장치로 출력하는 Unreal Engine의 시네 카메라입니다. 추가로, 가상 카메라 시스템은 에디터에 있을 때와 에디터에서 플레이(PIE) 또는 독립형 게임 모드 중에 그 기능을 제공합니다.

[nDisplay](https://docs.unrealengine.com/5.2/en-US/ndisplay-overview-for-unreal-engine/)는 nDisplay 렌더링 네트워크에서 여러 컴퓨터가 함께 작동하는 방식을 설명하는 Unreal Engine의 도구입니다.

[Unreal Engine Marketplace](https://unrealengine.com/marketplace/en-US/store)는 놀라운 3D 프로젝트와 게임을 만드는 데 필요한 텍스처, 모델, 애니메이션, 튜토리얼 등의 라이브러리를 갖춘 Unreal Engine의 스토어입니다.

[UnrealBuildTool (UBT)](https://docs.unrealengine.com/5.0/en-US/ProductionPipelines/BuildTools/UnrealBuildTool)은 다양한 빌드 구성에 걸쳐 UE4 소스 코드를 빌드하는 프로세스를 관리하는 도구입니다.

[UnrealHeaderTool (UHT)](https://docs.unrealengine.com/5.0/en-US/ProductionPipelines/BuildTools/UnrealHeaderTool)은 UObject 시스템을 지원하는 커스텀 구문 분석 및 코드 생성 도구입니다.

[AutomationTool](https://docs.unrealengine.com/4.27/en-US/ProductionPipelines/BuildTools/AutomationTool)은 게임 테스트 및 구축을 포함한 프로세스를 자동화하는 데 사용되는 일반 시스템입니다.

[프록시 지오메트리 도구](https://docs.unrealengine.com/5.0/en-US/TestingAndOptimization/ProxyGeoTool/)는 프로젝트의 시각적 품질을 그대로 유지하면서 Unreal Engine 4(UE4) 프로젝트의 성능을 높이기 위한 방법으로 개발된 도구 세트입니다.

[리플레이 시스템](https://docs.unrealengine.com/5.0/en-US/TestingAndOptimization/ReplaySystem/)은 나중에 볼 수 있도록 게임플레이를 녹화할 수 있는 도구입니다. 이 기능은 전용 서버에서 플레이되는 라이브 멀티플레이어 게임부터 싱글플레이어 게임, 심지어 Play-In-Editor 세션까지 모든 게임에서 사용할 수 있습니다. 높은 수준에서 Replay 시스템은 DemoNetDriver를 사용하여 내장 복제 시스템에서 가져온 데이터를 읽는 방식으로 작동합니다. 이는 NetDriver가 라이브 네트워크 게임 플레이 환경에서 작동하는 방식과 유사합니다.

### 언리얼 엔진 개발자 리소스

[맨 위로 돌아가기](#목차)

 * [Unreal Engine 4 프로젝트를 Unreal Engine 5 Early Access로 빠르고 원활하게 마이그레이션하는 방법](https://docs.unrealengine.com/5.0/en-US/MigrationGuide/)

 * [멀티 플랫폼 개발 - 언리얼 엔진](https://www.unrealengine.com/en-US/features/multi-platform-development)

 * [언리얼 엔진 5 문서](https://docs.unrealengine.com/5.0/)

 * [언리얼 엔진 포럼](https://forums.unrealengine.com/)

**참고:** Unreal Engine을 다운로드하려면 Epic Games 계정을 만들어야 합니다.

 * [에픽게임즈 계정 가입](https://www.epicgames.com/account/password)
 
 * [에픽게임즈 GitHub 가입](https://github.com/EpicGames/Signup)
 
 * [Unreal Engine용 macOS 개발 요구 사항](https://docs.unrealengine.com/5.0/en-US/hardware-and-software-specifications-for-unreal-engine/)
 
 * [Unreal Engine에서 iOS, iPadOS, tvOS 개발](https://docs.unrealengine.com/5.0/en-US/ios-ipados-and-tvos-support-for-unreal-engine/)
 
 * [Unreal Engine에서의 XR 개발](https://docs.unrealengine.com/5.0/en-US/developing-for-xr-experiences-in-unreal-engine)

 * [Unreal Engine용 Visual Studio 설정](https://docs.unrealengine.com/en-us/Programming/Development/VisualStudioSetup)

 * [언리얼 엔진 성능 및 프로파일링](https://docs.unrealengine.com/5.0/en-US/TestingAndOptimization/PerformanceAndProfiling/)

 * [언리얼 엔진 C++ API 레퍼런스](https://docs.unrealengine.com/5.0/en-US/API/index.html)

 * [언리얼 엔진 블루프린트 API 레퍼런스](https://docs.unrealengine.com/5.0/en-US/BlueprintAPI/index.html)

 * [언리얼 엔진 Python API 레퍼런스](https://docs.unrealengine.com/5.0/en-US/PythonAPI/index.html)
 
  * [Unreal Online Learning](https://www.unrealengine.com/en-US/onlinelearning-courses)은 실습 동영상 강좌와 안내식 학습 경로를 제공하는 무료 학습 플랫폼입니다.
 
 * [Unreal Engine 공인 교육 프로그램](https://www.unrealengine.com/en-US/training-partners)

 * [교육용 언리얼 엔진](https://www.unrealengine.com/en-US/education/)

 * [언리얼 엔진 트레이닝 및 시뮬레이션](https://www.unrealengine.com/en-US/industry/training-simulation)
 
 * [언리얼 엔진 | NVIDIA 개발자](https://developer.nvidia.com/unrealengine)

 * [게임용 Autodesk](https://www.autodesk.com/campaigns/autodesk-for-games)

 * [DirectX 12 Ultimate 시작하기](https://devblogs.microsoft.com/directx/directx-12-ultimate-getting-started-guide/)

 * [Vulkan 시작하기](https://www.khronos.org/vulkan/)

 * [Apple Metal 시작하기](https://developer.apple.com/metal/)
 
 ### 언리얼 엔진 5 개발 서적

 * [초보자를 위한 Unreal Engine 5: Unreal Engine 5로 게임 개발의 세계에 뛰어들어 Sargey Rose의 놀라운 3D 게임 구축](https://www.amazon.com/Unreal-Engine-Beginners-development-amazing/dp/1800568088)

 * [Unreal Engine 5용 블루프린트 비주얼 스크립팅: 블루프린트의 진정한 힘을 활용하여 UE5에서 인상적인 게임과 애플리케이션을 제작하세요. 제3판 작성자: Marcos Romero, Brenden Sewell, Luis Cataldi](https://www.amazon.com/Blueprints-Visual-Scripting-Unreal-Engine/dp/180181158X/)

 * [Unreal Engine 5 캐릭터 생성, 애니메이션 및 시네마틱스: Henk Venter, Wilhelm Ogterop의 MetaHuman, Lumen 및 Nanite를 사용하여 맞춤형 3D 자산을 생성하고 Unreal Engine 5에서 생생하게 구현](https://www.amazon.com/Unreal-Character-Creation-Animation-Cinematics/dp/1801812446/)

 * [Unreal Engine 5로 게임 경험 향상: Goncalo Marques, Devin Sherry, David Pereira, Hammad Fozi가 작성한 새로운 Unreal Engine 5 및 C++, 2판을 사용하여 게임 아이디어에 생명을 불어넣으세요](https://www.amazon.com/Elevating-Game-Experiences-Unreal-Engine/dp/1803239867/)

 * [C++ 및 블루프린트를 사용한 Unreal Engine 5 RPG 개발: Volume I: Chihming Chiu 박사의 기본, 전투 및 VFX](https://www.amazon.com/Unreal-Engine-RPG-Development-Blueprint/dp/B0BHC586PM/r)

 * [Unreal Engine 5로 놀라운 실시간 VFX 구축: Hrishikesh Andurlekar의 나이아가라를 사용하여 사실적인 시각 효과를 만들기 위해 Unreal 파티클 시스템으로의 여정을 시작하세요.](https://www.amazon.com/Build-Stunning-Real-time-Unreal-Engine/dp/1801072418/)

 * [Unreal Engine 5를 사용한 게임 개발 패턴: Stuart Butler, Tom Oliver의 C++ 및 Blueprint를 사용하여 유지 관리 및 확장 가능한 시스템 구축](https://www.amazon.com/Game-Development-Patterns-Unreal-Engine/dp/1803243252/)

 * [Unreal Engine 5 셰이더 및 효과 요리책: 머티리얼 및 고급 셰이딩 기술 제작을 위한 70가지 이상의 레시피, Brais Brenlla Ramos의 제2판](https://www.amazon.com/Unreal-Engine-Shaders-Effects-Cookbook/dp/1837633088/)

 * [Unreal Engine 5를 사용한 게임 개발: Unreal Engine 5에서 게임 개발의 기본 알아보기 - Mitchell Lynn, Cliff Sharif 저작](https://www.amazon.com/Game-Development-Unreal-Engine-English/dp/9355513445/)

 * [Unreal Engine C++ 최고의 개발자 핸드북: Stephen Seth Ulibarri의 완전한 액션 게임을 만들어 C++ 및 Unreal Engine 배우기](https://www.amazon.com/Unreal-Engine-Ultimate-Developers-Handbook/dp/B089M2H7J1/)

 * [Unreal Engine의 처음부터 숙련도까지(기초): Patrick Felicia의 Unreal Engine 첫 게임을 위한 단계별 가이드](https://www.amazon.com/Unreal-Engine-Proficiency-Foundations-Step/dp/B0B6XJDR3K/)

 * [Unreal Engine의 MetaHuman Creator로 캐릭터 재구성: Brian Rossney, Ciaran Kavanagh의 영화 수준의 캐릭터 디자인과 모션 캡처 애니메이션으로 영화의 수준을 높이세요](https://www.amazon.com/Reimagining-characters-Unreal-MetaHuman-Creator/dp/1801817723/)
 
 
## 유니티 개발
[맨 위로 돌아가기](#목차)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/147710942-5da4fef2-5525-4942-98bc-81421b2144e5.png">
  <br />
</p>

**권장 하드웨어 요구 사항:**

* **OS:** MacOS 12 이상

* **CPU/GPU:** M1 Pro(10코어 CPU, 16코어 GPU)

* **RAM:** 32GB

* **스토리지:** 1TB

[Unity](https://unity.com)는 크로스 플랫폼 게임 개발 플랫폼입니다. Unity를 사용하면 고품질 3D 및 2D 게임을 구축하고 이를 모바일, 데스크톱, VR/AR, 콘솔 또는 웹에 배포하고 충성도가 높고 열정적인 플레이어 및 고객과 연결할 수 있습니다. Unity 프로젝트를 시작하려면 [Unity 매뉴얼](https://docs.unity3d.com/Manual/UnityOverview.html)을 확인하세요.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/221379487-ea59279e-94f0-4caa-9cfb-cb8f48db13e4.png">
  <br />
</p>

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/146693059-97d5428c-cf3c-48f4-bb29-d35e4044d1d9.png">
  <br />
</p>

Unity 지형 프로젝트. 출처: [유니티](https://blog.unity.com/technology/evolving-the-unity-editor-ux)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/221379631-40782ba1-c5a2-4854-8cdd-2e4fa3bd63bf.png">
  <br />
  Unity Hub 설치
</p>

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/147710657-16a6e35a-c78e-408b-a836-45b21a342f11.png">
  <br />
  유니티 에셋 스토어
</p>

## 유니티 도구

[Unity Hub](https://unity.com/unity-hub)는 Unity 에디터의 여러 설치를 관리하고, 새 프로젝트를 만들고, 작업에 액세스하는 데 도움이 되는 도구입니다.

[Unity Asset Store](https://assetstore.unity.com)는 놀라운 3D 프로젝트와 게임을 만들기 위한 텍스처, 모델, 애니메이션, 튜토리얼 등의 라이브러리를 갖춘 Unity 스토어입니다.

[Unity Plus](https://store.unity.com/products/unity-plus)는 중소기업과 열정적인 애호가를 위한 Unity 버전으로, 프로젝트를 강화하는 데 필요한 더 많은 기능과 교육 리소스를 제공합니다.

[Unity Pro](https://store.unity.com/products/unity-pro)는 업계 전반의 전문가를 위한 완벽한 솔루션으로 놀라운 애플리케이션과 몰입형 경험을 만들고 운영하기 위한 Unity 버전입니다.

[Unity Enterprise](https://store.unity.com/products/unity-enterprise)는 대규모 팀을 위한 Unity 버전으로, Unity Enterprise는 혁신을 촉진하고 위험을 줄이며 성공을 지원하는 포괄적인 기술, 리소스 및 지원을 제공합니다.

[Unity XR](https://docs.unity3d.com/Manual/XR.html)은 XR 제공업체가 Unity 엔진과 통합하고 해당 기능을 최대한 활용할 수 있도록 지원하는 플러그인 프레임워크입니다.

[Unity MARS](https://unity.com/products/unity-mars)는 더 나은 워크플로와 특수 제작 도구를 사용하여 증강 현실(AR) 앱을 만드는 데 도움이 되는 도구입니다.

[Unity 빌드 서버](https://unity.com/products/unity-build-server)는 Unity 프로젝트 빌드를 네트워크 하드웨어로 오프로드하여 크리에이티브 팀이 더 많은 반복 작업을 수행하고 더 높은 품질의 제품을 생산하며 제 시간에 출시할 수 있도록 지원하는 도구입니다.

[Unity Teams](https://unity.com/products/unity-teams)는 귀하와 귀하의 팀이 더 빠르게 함께 창작할 수 있도록 도와주는 도구입니다. Unity 프로젝트를 간편하게 저장하고 누구와도 공유하고 동기화할 수 있습니다.

[Unity Automated QA](https://unity.com/products/automated-qa)는 팀 구성원 누구나 코드를 작성하지 않고도 만들고 실행할 수 있는 주문형 테스트를 통해 개발 피드백 루프를 단축하는 도구입니다.

[Unity Simulation Pro](https://unity.com/products/unity-simulation-pro)는 시뮬레이션에 최적화된 Unity 런타임 버전을 통해 확장 가능한 시뮬레이션의 진정한 힘을 활용하는 도구입니다.

[Unity Forma](https://unity.com/products/unity-forma)는 실시간 3D의 강력한 기능을 마케팅에 활용하는 도구입니다. 3D 제품 데이터를 대화형 3D 구성기, 놀라운 이미지 등으로 변환합니다.

[Unity Reflect](https://unity.com/products/unity-reflect)는 전체 프로젝트 수명주기에서 더 나은 의사결정을 내릴 수 있도록 AR 및 VR을 포함한 몰입형 협업 실시간 3D 환경을 만드는 데 도움이 되는 도구입니다.

[Unity Reflect 개발](https://unity.com/products/unity-reflect-develop)은 내부 또는 상업용 배포를 위한 전체 건물 및 인프라 수명주기 전반에 걸쳐 문제를 해결하기 위해 자체 커스텀 애플리케이션을 구축하는 도구입니다.

[Unity ArtEngine](https://unity.com/products/unity-artengine)은 Unity의 머티리얼 저작 도구입니다. 창작 지원 기능을 활용하는 이 도구는 창작자가 제작 파이프라인을 가속화하는 데 도움이 됩니다.

[Unity Machine Learning Agents](https://unity.com/products/machine-learning-agents)는 최첨단 딥 러닝 기술을 활용하여 지능형 에이전트를 훈련하고 내장하는 데 도움이 되는 도구입니다.

[Unity Essential Success ](https://unity.com/products/unity-essential-success)는 전담 지원 코디네이터 역할을 하는 도구이며 숙련된 Unity 엔지니어가 도와드릴 준비가 되어 있습니다.

[Bolt 시각적 스크립팅](https://unity.com/products/unity-visual-scripting)은 제작자가 전통적인 코드 줄을 작성하는 대신 시각적 그래프 기반 시스템을 사용하여 게임플레이 메커니즘이나 상호 작용 논리를 개발할 수 있도록 지원하는 Unity의 도구입니다.

[VisualLive](https://unity.com/products/visuallive)는 건설 전문가가 AR을 사용하여 대규모 BIM 및 CAD 파일을 작업 현장에 오버레이하여 설계를 시각화하고 실시간으로 협업할 수 있는 도구입니다.

[전문 서비스: Optimization Accelerator](https://unity.com/products/optimization-accelerator)는 Unity 엔지니어의 실무 지침을 통해 4일 간의 스프린트로 프로젝트와 생산성을 향상시키는 도구입니다. 성능 문제를 분석하고, 솔루션을 테스트하고, 개선 사항을 구현하는 데 도움이 됩니다.

[Odin Inspector Enterprise](https://unity.com/products/odin)는 프로젝트 작업 흐름을 최적화하고 수천 시간의 개발 시간을 절약해 주는 도구입니다.

[Multiplay](https://unity.com/products/multiplay)는 자체 인프라를 구축하고 유지 관리할 필요 없이 탄력적인 멀티클라우드 하이브리드 서버 호스팅 및 매치메이킹 플랫폼입니다. 세계 최대 규모의 게임에서 대규모로 입증되었습니다.

[Vivox](https://unity.com/products/vivox)는 구현하기 쉽고 기능이 풍부한 음성 및 문자 채팅 서비스를 활용하여 플레이어 참여도와 유지율을 높이고 몰입형 멀티플레이어 경험을 창출하는 음성 및 문자 통신 도구입니다.

[Relayᴮᴱᵀᴬ](https://unity.com/products/relay)는 현재 오픈 베타 버전인 Unity의 Relay 서비스를 통해 뛰어난 멀티플레이어 게임 경험을 제공하는 도구입니다.

[Lobbyᴮᴱᵀᴬ](https://unity.com/products/lobby)는 현재 오픈 베타 버전인 로비를 통해 훌륭한 멀티플레이어 게임 경험을 제공하기 위해 플레이어를 연결하는 도구입니다.

[Cloud Codeᴮᴱᵀᴬ](https://unity.com/products/cloud-code)는 클라우드에서 게임 로직을 서버리스 기능으로 실행하고 다른 백엔드 서비스와 상호작용하는 도구입니다.

[Cloud Saveᴮᴱᵀᴬ](https://unity.com/products/cloud-save)는 게임 데이터를 클라우드에 저장하여 더 나은 플레이어 경험을 구축하는 도구입니다.

[Furioos](https://unity.com/products/furioos)는 Unity, 기타 실시간 3D 플랫폼 및 Windows 애플리케이션에서 완전한 대화형 3D 경험을 모든 웹 브라우저에서 최고의 시각적 품질로 스트리밍하는 도구입니다.

[Unity용 OctaneRender®](https://unity.com/products/otoy-octanerender)는 물리적으로 정확한 렌더링을 Unity에서 직접 활용하고 OctaneRender 재질과 조명을 사용하여 멋진 영화 품질의 장면을 구성할 수 있게 해주는 도구입니다.

[Pacelab WEAVR](https://unity.com/products/weavr)은 모든 산업 분야의 모든 회사가 엔터프라이즈 규모의 몰입형 교육을 개발하고 관리할 수 있도록 지원하는 완전한 XR 플랫폼을 제공하는 도구입니다.

[Interact](https://unity.com/products/interact)는 교육, 시각화 및 안전을 위해 모든 VR 구성에서 고급 실시간 인간 중심 시뮬레이션을 생성하는 도구입니다.

[Prespective](https://unity.com/products/prespective)는 Unity 실시간 3D로 기계, 공장 또는 시스템을 설계하고 시뮬레이션하는 데 도움이 되는 도구입니다. 향상된 시각화 도구를 사용하여 이해관계자 간의 공통점을 만들고 의사결정 프로세스를 가속화합니다.

[Pixyz](https://unity.com/products/pixyz)는 Unity에서 실시간 시각화를 위해 대규모 CAD, 메시 및 포인트 클라우드 모델을 빠르게 가져오고, 준비하고, 최적화할 수 있는 도구입니다.

[Plastic SCM Cloud Edition](https://unity.com/products/plastic-scm)은 프로그래머, 아티스트 및 디자이너를 위해 제작된 성능이 뛰어나고 사용하기 쉬운 버전 제어 시스템(VCS)을 통해 협업을 더욱 효율적으로 만드는 도구입니다.

[Backtrace](https://unity.com/products/backtrace)는 오류에 대한 응답을 자동화하여 중단 없는 게임 경험을 제공하는 게임 충돌 관리 플랫폼입니다.

[SpeedTree®](https://store.speedtree.com/)는 Interactive Data Visualization, Inc.에서 개발 및 판매하는 식생 프로그래밍 및 모델링 소프트웨어 제품 그룹으로, 애니메이션, 건축을 위한 가상 나뭇잎을 생성하고 비디오 게임 및 까다로운 실시간 시뮬레이션을 위해 실시간으로 생성합니다. [Unity Technologies는 2021년 7월에 SpeedTree를 인수했습니다](https://investors.unity.com/news/news-details/2021/Unity-Acquires-Interactive-Data-Visualization-Inc.-IDV-Creators-of-SpeedTree-Environment-Creation-Suite/default.aspx).

[ParSec](https://parsec.app/)은 개발자, 디자이너, 건축가 및 엔지니어로 구성된 팀이 작업을 완료하고 어디에서나 함께 작업할 수 있을 만큼 강력한 최고의 원격 데스크톱입니다. [Unity Technologies는 2021년 8월에 Parsec을 인수했습니다](https://unity.com/our-company/newsroom/unity-enters-agreement-acquire-parsec).

[SyncSketch](https://syncsketch.com)는 팀이 서로의 작업을 보고, 검토하고, 피드백을 제공할 수 있는 시각 예술가를 위한 공동 작업 소프트웨어입니다. 여기에는 2D 및 3D 자산과 비디오에 대한 지원이 포함됩니다. [2021년 12월 SyncSketch가 Unity Technologies에 인수되었습니다](https://blog.syncsketch.com/news/sycncsketch-acquired-by-unity/).

[Weta Digital](https://www.wetafx.co.nz/)은 [Peter Jackson](https://www.imdb.com/name/nm0001392/)이 설립한 디지털 시각 효과 회사입니다. Heavenly Creatures와 Lord of the Rings의 디지털 특수 효과를 제작했습니다. [Unity Technologies는 2021년 11월 Weta Digital을 인수했습니다](https://unity.com/our-company/newsroom/unity-announces-intent-acquire-weta-digital).


## Unity 개발자 리소스

[Unity 기술 자료](https://support.unity.com/hc/en-us)는 계정 생성, 에셋 가져오기, 장면 베이킹 등 일반적인 문제를 해결하는 데 도움이 되는 문서 라이브러리입니다.

 * [유니티 포럼](https://forum.unity.com/)

 * [Unity 이슈 트래커](https://issuetracker.unity3d.com/)

 * [Unity 인증](https://unity.com/products/unity-certifications)

 * [Unity로 게임 개발 배우기](https://learn.unity.com/courses)
 
 * [Apple Metal 시작하기](https://developer.apple.com/metal/)
 
 * [게임용 Autodesk](https://www.autodesk.com/campaigns/autodesk-for-games)

 * [Udemy에 대한 Unity 강좌, 교육 및 강의](https://www.udemy.com/topic/unity/)

 * [edX의 온라인 강좌 및 강의를 통해 Unity 3D를 배우세요](https://www.edx.org/learn/unity-3d)

 * [Coursera에서 Unity 인증 프로그래머 시험 준비](https://www.coursera.org/specializations/unity-certified-programmer)
 
### Unity 개발 도서

 * [실습 Unity 2022 게임 개발: 최신 Unity 2022 기능을 사용하여 가능한 가장 간단한 방법으로 첫 번째 비디오 게임을 만드는 방법 알아보기, Nicolas Alejandro Borromeo의 제3판](https://www.amazon.com/Hands-Unity-2022-Game-Development/dp/1803236914/)
 
 * [Unity 게임 개발 설명서: 모든 게임을 위한 필수 요소 1판(Paris Buttfield-Addison, Jon Manning, Tim Nugent 저)](https://www.amazon.com/Unity-Game-Development-Cookbook-Virtual/dp/1491999152/)
 
 * [Unity 3D 게임 개발: 열정적인 게임 개발자를 위해 설계됨—Anthony Davis, Travis Baptiste, Russell Craig가 전문 게임을 구축하도록 설계](https://www.amazon.com/Unity-Game-Development-design-beautiful/dp/1801076146/)
 
 * [Unity와 C#을 사용한 게임 프로그래밍: 완전한 초보자 가이드 1판. Casey Hardman의 에디션](https://www.amazon.com/Game-Programming-Unity-Complete-Beginners/dp/1484256557/)
 
 * [Unity로 게임 개발을 통한 C# 학습: 처음부터 C#으로 코딩을 익히고 Unity 2022에서 간단한 3D 게임 빌드, Harrison Ferrone의 7판](https://www.amazon.com/Learning-Developing-Games-Unity-coding/dp/1837636877/)
 
 * [3D 게임 개발을 위한 마음을 녹이는 Unity 및 Blender: Unity와 Blender의 강력한 기능을 활용하여 놀라운 게임을 만드세요.
작성자: 스펜서 그레이](https://www.amazon.com/Mind-Melding-Unity-Blender-Game-Development/dp/1801071551/)
 
 * [Jeff W. Murray의 Unity 3D용 C# 게임 프로그래밍 요리책 2판](https://www.amazon.com/Game-Programming-Cookbook-Unity-3D-ebook/dp/B08VBMBGN2/)
 
 * [Unity in Action, 제3판: Joe Hocking의 C# 제3판을 사용한 다중 플랫폼 게임 개발](https://www.amazon.com/Unity-Action-Third-Joseph-Hocking/dp/1617299332/)
 
 * [Unity 3d 및 Mirror를 사용한 대규모 멀티플레이어 게임 프로그래밍: Chihming Chiu 박사가 작성한 MMOGS 구축 및 호스팅을 위한 최고의 가이드](https://www.amazon.com/Massively-Multiplayer-Programming-Unity-Mirror/dp/022884410X/)
 
 * [고급 Unity 게임 개발: Unity, C# 및 Visual Studio 1st ed.를 사용하여 전문 게임 빌드. Victor G Brusca 에디션](https://www.amazon.com/Advanced-Unity-Game-Development-Professional/dp/148427850X/)
 
 * [게임 프로그래밍 및 컴퓨터 그래픽을 위한 수학: Penny de Byl의 3D 가상 환경을 생성, 렌더링 및 조작하는 데 필수적인 수학 탐구](https://www.amazon.com/Mathematics-Game-Programming-Computer-Graphics/dp/1801077339/)


# 블렌더 개발
[맨 위로 돌아가기](#목차)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/125211848-53765800-e25e-11eb-872d-732aa2e74ad1.png">
  <br />
</p>

**권장 하드웨어 요구 사항:**

* **OS:** MacOS 12 이상

* **CPU/GPU:** M1 Pro(10코어 CPU, 16코어 GPU)

* **RAM:** 32GB

* **스토리지:** 1TB

[Blender](https://www.blender.org)는 애니메이션 영화, 시각 효과, 예술, 3D 인쇄 모델, 대화형 3D 애플리케이션 및 비디오 게임 제작에 사용되는 전문적인 무료 오픈 소스 3D 컴퓨터 그래픽 소프트웨어 도구 세트입니다.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/221347484-b09ef929-3cd2-4d41-9a31-e41dc7d9d6da.png">
  <br />
</p>


## 블렌더 개발자 리소스

 * [블렌더 문서](https://docs.blender.org/)

 * [블렌더 파운데이션](https://www.blender.org/foundation/)

 * [블렌더 커뮤니티 Fourm](https://devtalk.blender.org/)

 * [Blender Foundation 인증 교육](https://www.blender.org/certification/)

 * [Blender Cloud 강좌](https://cloud.blender.org/courses)

 * [블렌더 연구소](https://www.blender.org/institute/)

 * [블렌더 데모 프로젝트 파일](https://www.blender.org/download/demo-files/)

 * [블렌더 YouTube 튜토리얼 및 데모](https://www.youtube.com/user/BlenderFoundation)

 * [블렌더 기부 및 후원자](https://www.blender.org/foundation/donation-payment/)

 * [블렌더 교육](https://www.blender.org/get-involved/)

 * [블렌더 네트워크](https://www.blendernetwork.org/)

 * [BlenderNation](https://www.blendernation.com/category/blender/add-ons/)

 * [Blender Market(블렌더 창작자를 위한 인디 마켓)](https://www.blendermarket.com/categories/scripts-and-addons)

## 블렌더 도구 및 애드온

[Blender](https://www.blender.org)에는 다양한 프로그램에 대한 가져오기/내보내기 지원 기능이 포함되어 있습니다.

포함:

   - 이미지(Jpeg, Jpeg2000, PNG, TARGA, Openexr, DPX, Cineon, Radiance HDR, SGI Iris, Tiff)

   - 비디오(AVI, MPEG 및 Quicktime(MacOS)).

   - 3D(Alembic, 3D Studio(3DS), COLLADA(DAE), Filmbox(FBX), Autodesk(DXF), Wavefront(OBJ), DirectX(x), Lightwave(LWO), 모션 캡처(BVH), SVG, Stanford PLY, STL, VRML, VRML97, X3D).


[Eevee](https://docs.blender.org/manual/en/latest/render/eevee/introduction.html)는 PBR 자료 렌더링 목표를 달성하면서 속도와 상호 작용에 중점을 둔 Blender의 실시간 렌더링 엔진입니다. Eevee는 3D 뷰포트에서 대화식으로 사용할 수 있을 뿐만 아니라 고품질 최종 렌더링을 생성할 수도 있습니다. Eevee 재질은 Cycles와 동일한 셰이더 노드를 사용하여 생성되므로 기존 장면을 쉽게 렌더링할 수 있습니다. Cycles 사용자의 경우 Eevee는 실시간으로 자료를 미리 보는 데 적합합니다.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/125211855-5a04cf80-e25e-11eb-94cf-f55ecf273049.png">
  <br />
</p>

**Eevee 최종 렌더링 – "사원". 출처: [도미니크 그라프](https://docs.blender.org/manual/en/latest/render/eevee/introduction.html#id2)**

[Cycles](https://www.blender.org/features/rendering/)는 Blender의 광선 추적 기반 프로덕션 렌더 엔진입니다.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/118338215-6ec91f00-b4ca-11eb-9c9e-f5cf377ca3c4.png">
  <br />
</p>

 **블렌더의 사이클 렌더 엔진. 소스: [블렌더](https://www.blender.org)**

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/118338217-6ffa4c00-b4ca-11eb-92d0-9aa30230495d.png">
  <br />
</p>

 **블렌더 VFX(시각 효과). 소스: [블렌더](https://www.blender.org)**

[FreeStyle](https://docs.blender.org/manual/en/dev/render/freestyle/index.html)은 가장자리 및 선 기반 비사실적(NPR) 렌더링 엔진입니다. 메쉬 데이터와 z 깊이 정보를 사용하여 선택한 모서리 유형에 선을 그립니다. 다양한 선 스타일을 추가하여 예술적("손으로 그린", "페인트" 등) 또는 기술적(단단한 선) 모양을 생성할 수 있습니다.

[수정자](https://docs.blender.org/manual/en/dev/modeling/modifiers/introduction.html)는 비파괴적인 방식으로 객체에 영향을 미치는 자동 작업입니다. 수정자를 사용하면 수동으로 업데이트하기에는 너무 지루한 여러 효과(예: 세분화 표면)를 오브젝트의 기본 형상에 영향을 주지 않고 자동으로 수행할 수 있습니다.

[UV 언래핑](https://docs.blender.org/manual/en/latest/modeling/meshes/editing/uv/unwrapping/introduction.html)은 Blender 내에서 메쉬를 쉽게 언래핑하고, 이미지 텍스처를 사용하거나 모델에 직접 페인팅할 수 있는 도구입니다.

[UV Sculpt](https://docs.blender.org/manual/en/dev/modeling/meshes/editing/uv/uv_sculpt.html)는 Sculpt 모드와 마찬가지로 UV를 잡고, 모으고, 매끄럽게 만들 수 있는 Blender의 "모드"입니다.

[전용 작업 공간](https://www.blender.org/features/sculpting/#dedicated-workspace)은 블렌더에 내장된 조각 기능 세트를 사용하여 유기적인 대상을 조각하는 기능입니다.

[브러시](https://docs.blender.org/manual/en/latest/sculpt_paint/sculpting/introduction.html)는 주름, 클레이 스트립, 핀치, 잡기, 매끄럽게, 마스크 등과 같은 브러시가 내장되어 있는 Blender의 기능입니다.

[동적 토폴로지(dyntopo)](https://docs.blender.org/manual/en/dev/sculpt_paint/sculpting/adaptive.html)는 동적 테셀레이션 조각 방법으로 세부 사항을 즉시 추가하고 제거하는 반면 일반 조각은 메시 모양에만 영향을 미칩니다.

[마스킹](https://docs.blender.org/manual/en/dev/sculpt_paint/sculpting/hide_mask.html#mask)은 조각하는 동안 사용되는 기능으로, 영역이 메시 부분 뒤에 숨겨지거나 다른 부분과 너무 가까울 수 있습니다. 이를 해결하려면 조각할 메쉬 부분을 분리하는 것이 유용합니다. 이는 메시의 일부를 완전히 숨기거나 조각할 수 없는 영역을 마스킹하여 수행할 수 있습니다.

[그리스 연필](https://www.blender.org/features/grease-pencil/)은 3D 공간에서 그릴 수 있는 특정 유형의 블렌더 개체입니다. 전통적인 2D 애니메이션, 컷아웃 애니메이션, 모션 그래픽을 만드는 데 사용할 수 있으며 무엇보다도 스토리보드 도구로 사용할 수 있습니다.

[제약조건](https://docs.blender.org/manual/en/2.80/animation/constraints/index.html)은 일반 정적 값(예: "제한" 값) 또는 "대상"이라는 다른 개체(예: "복사" 값)를 사용하여 개체의 속성(예: 위치, 회전, 배율)을 제어하는 ​​방법입니다.

[도형 키](https://docs.blender.org/manual/en/2.80/animation/shape_keys/introduction.html)는 애니메이션을 위해 개체를 새로운 모양으로 변형하는 데 사용됩니다. 다른 용어로는 모양 키를 "모프 대상" 또는 "혼합 모양"이라고 부를 수 있습니다. 모양 키의 가장 인기 있는 사용 사례는 캐릭터 얼굴 애니메이션과 골격 리그 조정 및 개선입니다. 이는 회전과 크기를 조합하여 얻을 수 있는 것보다 결과 모양에 대해 더 많은 제어가 필요한 유기적 부드러운 부분과 근육을 모델링하는 데 특히 유용합니다.

[모션 경로](https://docs.blender.org/manual/en/2.80/animation/motion_paths.html)는 점의 모션을 일련의 프레임에 대한 경로로 시각화할 수 있는 도구입니다. 이러한 점은 객체 원점 및 뼈 관절일 수 있습니다.

[시뮬레이션](https://www.blender.org/features/simulation/)은 무너져가는 건물, 비, 불, 연기, 액체, 천 또는 전체 파괴와 같은 놀라운 시뮬레이션을 만들 수 있는 도구입니다.

[Blender Video Editor](https://www.blender.org/features/video-editing/)는 내장된 비디오 시퀀스 편집기와 함께 제공되는 비디오 편집기로, 비디오 자르기 및 접합과 같은 기본 작업은 물론 비디오 마스킹이나 컬러 그레이딩과 같은 보다 복잡한 작업을 수행할 수 있습니다.

[블렌더 합성](https://www.blender.org/features/vfx/#compositing)은 카메라 FX, 컬러 그레이딩, 비네팅 등을 생성하기 위한 인상적인 노드 라이브러리와 함께 제공되는 기능입니다.
렌더 레이어 지원. 다중 레이어 OpenEXR 파일로 렌더링하는 기능도 함께 제공됩니다.

[블렌더 모션 추적](https://www.blender.org/features/vfx/#motion-tracking)은 제작 준비가 완료된 카메라 및 객체 추적을 제공하는 기능으로, 원시 영상을 가져와 추적하고 영역을 마스크하고 3D 장면에서 실시간으로 카메라 움직임을 재구성할 수 있습니다.

### 블렌더 개발 서적

 * [Blender를 사용한 3D 환경 디자인: 모델링, 텍스처링 및 조명 기술을 향상하여 사실적인 3D 장면 만들기 - Abdelilah Hamdani, Carlos Barreto](https://www.amazon.com/Photorealistic-Nature-Environment-Creation-Blender/dp/1803235853/)
 
 * [Blender 3D Incredible Models: 단단한 표면 모델링, 절차적 텍스처링 및 렌더링에 대한 포괄적인 가이드
작성자: Arijan Belec](https://www.amazon.com/Blender-Incredible-Models-comprehensive-hard-surface/dp/1801817812/)

 * [Blender Pro 팁: 전문가가 3D 모델을 만드는 방법 - Arijan Belec](https://www.amazon.com/Blender-Pro-Tips-Professionals-Create-ebook/dp/B0BTKJVDGK/)
  
 * [예제를 통한 Blender 3D: 최신 Blender 3D, EEVEE 렌더링 엔진 및 Grease Pencil 학습을 위한 프로젝트 기반 가이드, Oscar Baechler, Xury Greer의 제2판](https://www.amazon.com/Blender-3D-Example-project-based-rendering/dp/178961256X/)
 
 * [Blender를 다음 단계로 끌어올리기: Ruan Lotter의 Blender 제작 파이프라인을 위한 지오메트리 노드, 시뮬레이션 및 모션 추적과 같은 고급 워크플로 구현](https://www.amazon.com/Taking-Blender-Next-Level-simulations/dp/1803233567/)
 
 * [Blender 그래픽 전체 가이드: 컴퓨터 모델링 및 애니메이션 7판(John M. Blain 저)](https://www.amazon.com/Complete-Guide-Blender-Graphics-Animation/dp/103212167X/)
  
 * [Blender EEVEE를 사용한 음영, 조명 및 렌더링: 실시간 렌더링 엔진을 사용하여 12배 더 빠르게 놀라운 컨셉 아트 제작
작성자: 새미 크라우더](https://www.amazon.com/Shading-Lighting-Rendering-Blender-EEVEE-ebook/dp/B09V1CR61X/)
 
 * [Blender 3.2: Allan Brito의 초보자 가이드](https://www.amazon.com/Blender-3-2-beginners-Allan-Brito/dp/B0B8RC4KL7/)
 
 * [Blender 방식으로 조각하기: Xury Greer의 면 세트, 메시 필터 및 천 브러시를 포함한 Blender의 3D 조각 작업 흐름과 최신 기능 살펴보기](https://www.amazon.com/Sculpting-Blender-Way-sculpting-workflows/dp/1801073872/)
  
 * [3D 게임 개발을 위한 마음을 녹이는 Unity 및 Blender: Unity와 Blender의 강력한 기능을 활용하여 놀라운 게임을 만드세요.
작성자: 스펜서 그레이](https://www.amazon.com/Mind-Melding-Unity-Blender-Game-Development/dp/1801071551/)

 * [Blender의 Squeaky Clean 토폴로지: Michael Steppig의 캐릭터 및 단단한 표면 모델에 대한 정확한 변형 및 최적화된 형상 생성](https://www.amazon.com/Squeaky-Clean-Topology-Blender-deformations/dp/1803244089/)
 
 * [올바른 방법으로 Blender 시뮬레이션 배우기: Stephen Pearson의 Mantaflow, 강체 및 연체, Dynamic Paint를 사용하여 매력적이고 사실적인 애니메이션 만들기](https://www.amazon.com/Learn-Blender-Simulations-Right-Way/dp/1803234156/)
 
 * [Blender 및 Godot를 사용한 게임 개발: Kumsal Obuz의 포인트 앤 클릭 어드벤처 게임을 구축하기 위해 Blender와 Godot의 결합된 기능을 활용](https://www.amazon.com/Development-Blender-Godot-point-click/dp/1801816026/)
  
 * [3dtotal Publishing의 Blender Paperback에서 캐릭터 생성을 위한 초보자 가이드](https://www.amazon.com/Beginners-Guide-Creating-Characters-Blender/dp/1912843137/)


# 가상화
[맨 위로 돌아가기](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/139736405-f98ea7e6-899c-4140-ba16-efd8caa1d856.png">
  <br />
</p>


### 개발자 빠른 링크

- [macOS용 Amazon Elastic Compute Cloud(EC2) M1 Mac 인스턴스](https://aws.amazon.com/about-aws/whats-new/2021/12/amazon-ec2-m1-mac-instances-macos/)

 - [Apple Silicon Mac의 가상 머신에서 macOS 실행](https://developer.apple.com/documentation/virtualization/running_macos_in_a_virtual_machine_on_apple_silicon_macs?language=objc) - 가상화 프레임워크를 사용하여 가상 머신에 macOS를 설치하고 실행합니다.

 - [Rosetta를 사용하여 Linux VM에서 Intel 바이너리 실행](https://developer.apple.com/documentation/virtualization/running_intel_binaries_in_linux_vms_with_rosetta?language=objc) - Apple Silicon의 ARM Linux에서 x86_64 Linux 바이너리를 실행합니다.

 - [Mac에서 macOS 가상화](https://developer.apple.com/documentation/virtualization/virtualize_macos_on_a_mac?language=objc) - Apple Silicon Mac 컴퓨터에서 macOS 게스트를 구성하고 실행합니다.

 - [Mac에서 Linux 가상화](https://developer.apple.com/documentation/virtualization/virtualize_linux_on_a_mac?language=objc) - Apple Silicon 및 Intel 기반 Mac 컴퓨터에서 Linux 게스트를 구성하고 실행합니다.

## 가상화 도구 및 프레임워크

[Apple Hypervisor](https://developer.apple.com/documentation/hypervisor)는 타사 커널 확장 없이 경량 하이퍼바이저 위에 가상화 솔루션을 구축하는 프레임워크입니다. 하이퍼바이저는 커널 확장(KEXT)을 작성하지 않고도 사용자 공간에서 가상화 기술과 상호 작용할 수 있도록 C API를 제공합니다. 결과적으로 이 프레임워크를 사용하여 만든 앱은 [Mac App Store](https://www.appstore.com/) 배포에 적합합니다.

[Apple Virtualization Framework](https://developer.apple.com/documentation/virtualization)는 Apple Silicon 및 Intel 기반 Mac 컴퓨터에서 가상 머신을 생성하고 관리하기 위한 고급 API를 제공하는 프레임워크입니다. 이 프레임워크는 사용자가 정의한 사용자 정의 환경에서 Linux 기반 운영 체제를 부팅하고 실행하는 데 사용됩니다. 또한 네트워크, 소켓, 직렬 포트, 스토리지, 엔트로피 및 메모리 풍선 장치를 포함한 다양한 장치 유형에 대한 표준 인터페이스를 정의하는 [Virtio 사양](https://www.redhat.com/en/virtio-networking-series)을 지원합니다.

[Apple 반가상화 그래픽 프레임워크](https://developer.apple.com/documentation/paravirtualizedgraphics)는 가상 머신(이하 게스트)에서 실행되는 macOS용 하드웨어 가속 그래픽을 구현하는 프레임워크입니다. 운영 체제는 게스트 내부에서 실행되는 그래픽 드라이버를 제공하여 호스트 운영 체제의 프레임워크와 통신하여 Metal 가속 그래픽을 활용합니다.

[Cilicon](https://github.com/traderepublic/Cilicon)은 Apple의 가상화 프레임워크를 활용하여 최소한의 설정 또는 유지 관리 노력으로 임시 가상 머신을 생성, 프로비저닝 및 실행하는 macOS 앱입니다. 한 시간 이내에 자체 호스팅 CI를 시작하고 실행할 수 있어야 합니다.

[Parallels Desktop](https://www.parallels.com)은 Mac(새로운 [Apple M1 칩](https://www.apple.com/newsroom/2020/11/apple-unleashes-m1/) 포함) 및 ChromeOS에서 Windows/Linux를 실행하기 위한 가장 빠르고, 쉽고, 강력한 응용프로그램을 제공하는 데스크톱 하이퍼바이저입니다.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/110880057-df697a80-8292-11eb-8484-9bbc02592377.jpg">
<br />
Mac용 패러렐즈 데스크톱
</p>

[UTM](https://getutm.app/)은 iOS 및 macOS용 모든 기능을 갖춘 시스템 에뮬레이터이자 가상 머신 호스트입니다. Mac, iPhone, iPad에서 Windows, Linux 등을 실행할 수 있는 [QEMU](https://www.qemu.org/)를 기반으로 합니다.

 - [iOS/iPadOS용 UTM(SE)](https://getutm.app/install/)
 
 - [macOS용 UTM](https://mac.getutm.app/)
 
 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/164793036-c84684fb-be06-4452-bfc9-32f77fb8059f.png">
  <br />
 UTM의 우분투
</p>

[VMware Fusion 22H2](https://blogs.vmware.com/teamfusion/2022/07/just-released-vmware-fusion-22h2-tech-preview.html)는 Mac 컴퓨터용으로 VMware에서 개발한 소프트웨어 하이퍼바이저입니다. 가상 머신을 생성하고 해당 가상 머신 내에 운영 체제(예: Windows 또는 Linux)를 설치합니다.

  * Intel 및 Apple Silicon 기반 Windows 11, 2D 그래픽 및 네트워킹 지원.
  * M1 기반 Mac에서 Windows 11 게스트 운영 체제에 대한 VMTools 설치를 지원합니다.
  * 빠른 암호화를 지원하는 가상 TPM 장치.
  * M1의 Linux 지원이 향상되었습니다.
  * Linux 가상 머신의 3D 그래픽 HW 가속 및 OpenGL 4.3(Linux 5.19+ 및 Mesa 22.1.3+ 필요).
  * Apple Silicon 및 Intel Mac용 범용 바이너리.
  
<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/182049352-b899b356-57c0-4ec0-8fb1-ff394a1f6403.png">
  <br />
 VMware Fusion의 Windows 11
</p>

[Tart](https://github.com/cirruslabs/tart)는 Apple Silicon에서 가상 머신을 구축, 실행 및 관리하기 위한 가상화 도구 세트입니다.

   * Tart는 [거의 기본 성능](https://browser.geekbench.com/v5/cpu/compare/14966395?baseline=14966339)을 위해 Apple 자체 Virtualization.Framework를 사용합니다.
   * OCI 호환 컨테이너 레지스트리에서 가상 머신을 푸시/풀합니다.
   * Tart Packer 플러그인을 사용하여 VM 생성을 자동화하세요.
   * 내장 CI 통합.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/184552497-4c820684-5217-452b-ae1e-0e764a9a14b5.png">
  <br />
타트
</p>

[Multipass](https://multipass.run/)는 Linux, macOS 및 Windows에서 클라우드 스타일 Ubuntu VM을 빠르게 생성하는 도구입니다. Linux에서는 [KVM](https://www.redhat.com/en/topics/virtualization/what-is-KVM), Windows에서는 [Hyper-V](https://docs.microsoft.com/en-us/virtualization/hyper-v-on-windows/about/), macOS에서는 [HyperKit](https://github.com/moby/hyperkit)을 사용합니다.

[VMware Horizon](https://www.vmware.com/products/horizon.html)은 언제 어디서나 모든 기기에서 작업자에게 필요한 기능을 제공하는 가상 데스크톱 및 애플리케이션을 효율적으로 제공하는 디지털 작업 공간입니다.

[VMware Carbon Black](https://www.vmware.com/products/whats-new/carbon-black.html)은 새로운 위협을 차단하는 데 필요한 지능형 시스템 강화와 행동 방지 기능을 결합한 클라우드 기반 엔드포인트 보호 플랫폼입니다.

[Proxmox Virtual Environment(VE)](https://www.proxmox.com/en/)는 엔터프라이즈 가상화를 위한 완전한 오픈 소스 플랫폼입니다. 여기에는 단일 솔루션에서 VM 및 컨테이너, 소프트웨어 정의 스토리지 및 네트워킹, 고가용성 클러스터링, 즉시 사용 가능한 여러 도구를 쉽게 관리할 수 있는 내장 웹 인터페이스가 포함되어 있습니다.

[VirtManager](https://github.com/virt-manager/virt-manager)는 libvirt를 통해 가상 머신을 관리하기 위한 그래픽 도구입니다. 대부분의 사용법은 QEMU/KVM 가상 머신에서 이루어지지만 Xen 및 libvirt LXC 컨테이너도 잘 지원됩니다. 모든 libvirt 드라이버에 대한 일반적인 작업이 작동해야 합니다.

[oVirt](https://www.ovirt.org)는 전체 엔터프라이즈 인프라를 관리하도록 설계된 오픈 소스 분산 가상화 솔루션입니다. oVirt는 신뢰할 수 있는 KVM 하이퍼바이저를 사용하며 libvirt, Gluster, PatternFly 및 Ansible을 포함한 여러 다른 커뮤니티 프로젝트를 기반으로 구축되었습니다. Red Hat Enterprise Virtualization의 기반이 되는 커뮤니티 프로젝트로 Red Hat에서 설립한 플랫폼 독립적인 액세스를 갖춘 사용하기 쉬운 웹 기반 프런트엔드에서 가상 머신, 컴퓨팅, 스토리지 및 네트워킹 리소스를 중앙 집중식으로 관리할 수 있습니다.

[KVM(커널 기반 가상 머신용)](https://www.linux-kvm.org/page/Main_Page)은 가상화 확장(Intel VT 또는 AMD-V)이 포함된 x86 하드웨어 기반 Linux용 전체 가상화 솔루션입니다. 이는 핵심 가상화 인프라를 제공하는 로드 가능한 커널 모듈 kvm.ko와 프로세서별 모듈로 구성됩니다.

[QEMU](https://www.qemu.org)는 휴대용 동적 변환기를 사용하는 빠른 프로세서 에뮬레이터입니다. QEMU는 프로세서와 다양한 주변 장치를 포함한 전체 시스템을 에뮬레이트합니다. PC를 재부팅하지 않고 다른 운영 체제를 시작하거나 시스템 코드를 디버깅하는 데 사용할 수 있습니다.

[macOS-Simple-KVM](https://github.com/foxlet/macOS-Simple-KVM)은 KVM으로 가속화되는 QEMU에서 빠른 macOS VM을 쉽게 설정할 수 있는 도구 세트입니다.

[Quickemu](https://github.com/wimpysworld/quickemu)는 최적화된 Windows, macOS, Linux 데스크톱 가상 머신을 빠르게 생성하고 실행하는 프로그램입니다.

[AWS ECS](https://aws.amazon.com/ecs/)는 Docker 컨테이너를 지원하고 AWS에서 컨테이너화된 애플리케이션을 쉽게 실행하고 확장할 수 있게 해주는 확장성이 뛰어난 고성능 컨테이너 오케스트레이션 서비스입니다. Amazon ECS를 사용하면 자체 컨테이너 오케스트레이션 소프트웨어를 설치 및 운영하거나, 가상 머신 클러스터를 관리 및 확장하거나, 해당 가상 머신에서 컨테이너를 예약할 필요가 없습니다.

[Cloud Hypervisor](https://github.com/cloud-hypervisor/cloud-hypervisor)는 [KVM](https://www.kernel.org/doc/Documentation/virtual/kvm/api.txt) 위에서 실행되는 오픈 소스 가상 머신 모니터(VMM)입니다. 이 프로젝트는 제한된 하드웨어 아키텍처 및 플랫폼 세트를 기반으로 최신 클라우드 워크로드를 독점적으로 실행하는 데 중점을 둡니다. 클라우드 워크로드는 일반적으로 클라우드 공급자 내부의 고객이 실행하는 워크로드를 의미합니다. Cloud Hypervisor는 [Rust](https://www.rust-lang.org/)로 구현되었으며 [rust-vmm](https://github.com/rust-vmm) 크레이트를 기반으로 합니다.

[Xen](https://github.com/xen-project/xen)은 서버 가상화, IaaS(Infrastructure as a Services), 데스크톱 가상화, 보안 애플리케이션, 임베디드 및 하드웨어 어플라이언스, 자동차/항공 등 다양한 상용 및 오픈 소스 애플리케이션에서 가상화를 발전시키는 데 주력하고 있습니다.

[Packer](https://www.packer.io/)는 단일 소스 구성에서 여러 플랫폼에 대해 동일한 머신 이미지를 생성하기 위한 오픈 소스 도구입니다. Packer는 가볍고 모든 주요 운영 체제에서 실행되며 성능이 뛰어나 여러 플랫폼용 머신 이미지를 병렬로 생성합니다. Packer는 Chef나 Puppet과 같은 구성 관리를 대체하지 않습니다. 실제로 이미지를 구축할 때 Packer는 Chef 또는 Puppet과 같은 도구를 사용하여 이미지에 소프트웨어를 설치할 수 있습니다.

[Vagrant](https://www.vagrantup.com/)는 단일 워크플로에서 가상 머신 환경을 구축하고 관리하기 위한 도구입니다. 사용하기 쉬운 작업 흐름과 자동화에 중점을 둔 Vagrant는 개발 환경 설정 시간을 줄이고 생산 패리티를 높이며 "내 컴퓨터에서 작업"을 과거의 유물로 변명하게 만듭니다. 업계 표준 기술을 기반으로 구축되고 일관된 단일 워크플로우로 제어되어 구성이 쉽고 재현 가능하며 이동 가능한 작업 환경을 제공하여 귀하와 팀의 생산성과 유연성을 극대화하는 데 도움을 줍니다.

## 가상화 개념 및 용어

[HVM(Hardware Virtual Machine)](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/virtualization_types.html)은 마치 베어메탈 하드웨어에서 실행되는 것처럼 아무런 수정 없이 가상 머신 위에서 직접 운영 체제를 실행할 수 있는 기능을 제공하는 가상화 유형입니다.

[PV(ParaVirtualization)](https://wiki.xenproject.org/wiki/Paravirtualization_(PV))는 Xen 프로젝트 팀에서 도입한 효율적이고 가벼운 가상화 기술로, 나중에 다른 가상화 솔루션에서도 채택됩니다. PV는 호스트 CPU의 가상화 확장이 필요하지 않으므로 하드웨어 지원 가상화를 지원하지 않는 하드웨어 아키텍처에서 가상화를 가능하게 합니다.

[NFV(네트워크 기능 가상화)](https://www.vmware.com/topics/glossary/content/network-functions-virtualization-nfv)는 네트워크 어플라이언스 하드웨어를 가상 머신으로 대체하는 것입니다. 가상 머신은 하이퍼바이저를 사용하여 라우팅 및 로드 밸런싱과 같은 네트워킹 소프트웨어 및 프로세스를 실행합니다. NFV를 사용하면 라우터 및 방화벽과 같은 전용 하드웨어에서 통신 서비스를 분리할 수 있습니다. 이러한 분리는 네트워크 운영이 새로운 하드웨어를 설치하지 않고도 새로운 서비스를 동적으로 제공할 수 있음을 의미합니다. 네트워크 기능 가상화를 통해 네트워크 구성 요소를 배포하는 데는 기존 네트워킹 솔루션처럼 몇 달이 걸리던 것과 비교하면 몇 시간 밖에 걸리지 않습니다.

[소프트웨어 정의 네트워킹(SDN)](https://www.vmware.com/topics/glossary/content/software-defined-networking)은 소프트웨어 기반 컨트롤러 또는 API(애플리케이션 프로그래밍 인터페이스)를 사용하여 기본 하드웨어 인프라와 통신하고 네트워크의 트래픽을 전달하는 네트워킹 접근 방식입니다. 이 모델은 전용 하드웨어 장치(라우터 및 스위치)를 사용하여 네트워크 트래픽을 제어하는 ​​기존 네트워크의 모델과 다릅니다.

[VIM(가상화 인프라 관리자)](https://www.cisco.com/c/en/us/td/docs/net_mgmt/network_function_virtualization_Infrastructure/3_2_2/install_guide/Cisco_VIM_Install_Guide_3_2_2/Cisco_VIM_Install_Guide_3_2_2_chapter_00.html)은 고성능 라이프사이클 관리를 통해 서비스를 제공하고 비용을 절감합니다. NFVI(NFV 인프라)를 구성하는 소프트웨어 및 하드웨어의 전체 라이프사이클을 관리하고 물리적 리소스와 가상 리소스 모두의 실시간 인벤토리 및 할당 계획을 유지관리합니다.

[관리 및 오케스트레이션(MANO)](https://www.etsi.org/technologies/open-source-mano)은 ETSI NFV에 맞춰 오픈 소스 NFV 관리 및 오케스트레이션(MANO) 소프트웨어 스택을 개발하기 위해 ETSI가 주최하는 이니셔티브입니다. ETSI NFV 아키텍처 프레임워크의 두 가지 주요 구성 요소는 NFV MANO로 알려진 NFV Orchestrator와 VNF Manager입니다.

[Magma](https://www.magmacore.org/)는 네트워크 사업자에게 개방적이고 유연하며 확장 가능한 모바일 코어 네트워크 솔루션을 제공하는 오픈 소스 소프트웨어 플랫폼입니다. 이들의 임무는 서비스 제공업체가 비용 효율적이고 확장 가능한 통신업체급 네트워크를 구축할 수 있도록 하여 세상을 더 빠른 네트워크에 연결하는 것입니다. Magma는 3GPP 세대(2G, 3G, 4G 또는 향후 5G 네트워크)이며 네트워크에 구애받지 않는 액세스(셀룰러 또는 WiFi)입니다. 최소한의 개발 및 배포 노력으로 무선 액세스 네트워크를 유연하게 지원할 수 있습니다.

[OpenRAN](https://open-ran.org/)은 소프트웨어 정의 기능 간의 개방형 인터페이스를 갖춘 범용 플랫폼에 통합된 지능형 무선 액세스 네트워크(RAN)입니다. 개방형 RANecosystem은 다중 공급업체 배포에 대한 완전한 개방성을 통해 엄청난 유연성과 상호 운용성을 제공합니다.

[Open vSwitch(OVS)](https://www.openvswitch.org/)는 오픈 소스 Apache 2.0 라이선스에 따라 라이선스가 부여된 오픈 소스 프로덕션 품질의 다중 계층 가상 스위치입니다. 이는 표준 관리 인터페이스 및 프로토콜(NetFlow, sFlow, IPFIX, RSPAN, CLI, LACP, 802.1ag)을 계속 지원하는 동시에 프로그래밍 방식 확장을 통해 대규모 네트워크 자동화를 가능하게 하도록 설계되었습니다.

[Edge](https://www.ibm.com/cloud/what-is-edge-computing)는 엔터프라이즈 애플리케이션을 IoT 장치 또는 로컬 에지 서버와 같은 데이터 소스에 더 가깝게 만드는 분산 컴퓨팅 프레임워크입니다. 소스의 데이터에 대한 이러한 근접성은 더 빠른 통찰력, 향상된 응답 시간 및 더 나은 대역폭 가용성을 포함하여 강력한 비즈니스 이점을 제공할 수 있습니다.

[다중 액세스 에지 컴퓨팅(MEC)](https://www.etsi.org/technologies/multi-access-edge-computing)은 ETSI 내의 산업 사양 그룹(ISG)으로, 다중 공급업체 다중 액세스 에지 컴퓨팅 플랫폼 전반에 걸쳐 공급업체, 서비스 제공업체 및 제3자의 애플리케이션을 효율적이고 원활하게 통합할 수 있는 표준화된 개방형 환경을 만듭니다.

[가상화된 네트워크 기능(VNF)](https://www.juniper.net/documentation/en_US/cso4.1/topics/concept/nsd-vnf-overview.html)은 인터페이스가 잘 정의되어 있고 정의된 방식으로 하나 이상의 구성 요소 네트워킹 기능을 제공하는 NFV(네트워크 기능 가상화) 구현에 사용되는 소프트웨어 애플리케이션입니다. 예를 들어 보안 VNF는 NAT(Network Address Translation) 및 방화벽 구성 요소 기능을 제공합니다.

[클라우드 네이티브 네트워크 기능(CNF)](https://www.cncf.io/announcements/2020/11/18/cloud-native-network-functions-conformance-launched-by-cncf/)은 컨테이너 내부에서 실행되도록 설계 및 구현된 네트워크 기능입니다. CNF는 Kubernetes(K8s) 수명주기 관리, 민첩성, 탄력성, 관찰 가능성을 포함한 모든 클라우드 네이티브 아키텍처 및 운영 원칙을 상속합니다.

[물리적 네트워크 기능(PNF)](https://www.mpirical.com/glossary/pnf-physical-network-function)은 가상화되지 않은 물리적 네트워크 노드입니다. PNF와 VNF(Virtualized Network Function) 모두 전체 네트워크 서비스를 구성하는 데 사용될 수 있습니다.

[네트워크 기능 가상화 인프라(NFVI)](https://docs.vmware.com/en/VMware-vCloud-NFV/2.0/vmware-vcloud-nfv-reference-architecture-20/GUID-FBEA6C6B-54D8-4A37-87B1-D825F9E0DBC7.html)는 전체 NFV 아키텍처의 기반입니다. VNF를 호스팅하는 물리적 컴퓨팅, 스토리지 및 네트워킹 하드웨어를 제공합니다. 각 NFVI 블록은 NFVI 노드로 간주할 수 있으며 많은 노드를 지리적으로 배포하고 제어할 수 있습니다.

[가상화 기반 보안(VBS)](https://docs.microsoft.com/en-us/windows-hardware/design/device-experiences/oem-vbs)은 일반 운영 체제에서 보안 메모리 영역을 생성하고 격리하는 하드웨어 가상화 기능입니다.

[HVCI(Hypervisor-Enforced Code Integrity)](https://docs.microsoft.com/en-us/windows-hardware/drivers/bringup/device-guard-and-credential-guard)는 Hyper-V와 같은 하이퍼바이저가 하드웨어 가상화를 사용하여 악성 또는 확인되지 않은 코드의 삽입 및 실행으로부터 커널 모드 프로세스를 보호하는 메커니즘입니다. 코드 무결성 검증은 악성 소프트웨어의 공격에 강한 안전한 환경에서 수행되며, 커널 모드에 대한 페이지 권한은 하이퍼바이저에 의해 설정 및 유지됩니다.

[NVIDIA 가상 GPU(vGPU)](https://www.nvidia.com/en-us/data-center/virtual-solutions/)는 그래픽이 풍부한 가상 워크스테이션부터 데이터 과학 및 AI에 이르는 워크로드에 대해 강력한 GPU 성능을 지원하는 소프트웨어로, IT 부서가 가상화의 관리 및 보안 이점은 물론 최신 워크로드에 필요한 NVIDIA GPU의 성능을 활용할 수 있도록 해줍니다.

[AMD MxGPU](https://www.amd.com/en/graphics/workstation-virtual-graphics)는 하드웨어 기반 가상화 GPU 솔루션으로, 업계 표준 SR-IOV(단일 루트 I/O 가상화) 기술을 기반으로 구축되었으며 물리적 GPU당 여러 명의 가상화된 사용자가 원격으로 작업할 수 있도록 해줍니다.

# 도커
[맨 위로 돌아가기](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/113521410-2e32c900-954e-11eb-8311-065fa0099546.png">
  <br />
</p>

### Apple Silicon(M1/M2)에서 Docker 실행

**[Apple Silicon용 Docker Desktop](https://docs.docker.com/desktop/mac/apple-silicon/)**

**[리마](https://github.com/lima-vm/lima)**는 자동 파일 공유 및 포트 전달(WSL2와 유사) 및 [containerd](https://containerd.io/)를 사용하여 Linux 가상 머신을 시작하는 도구입니다. [Docker Desktop](https://www.docker.com/products/docker-desktop)을 위한 훌륭한 무료 오픈 소스 대안입니다.

#### Homebrew를 사용하여 Lima 설치

```brew install lima docker docker-credential-helper```

**[Colima](https://github.com/abiosoft/colima)** is a container runtimes on macOS (and Linux) with minimal setup.

**Included Features:**

   * M1/M2 Macs and Intel support
    
   * Docker and Containerd support
    
   * Kubernetes
    
   * Port Forwarding
    
   * Volume mounts
    
#### Installing Colima

**Homebrew**

```brew install colima```

**맥포트**

```sudo port install colima```

**Nix**

```nix-env -iA nixpkgs.colima```

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/113521413-2ffc8c80-954e-11eb-9d19-b9c996bc524b.png">
  <br />
</p>

**컨테이너 아키텍처. 출처: [Containerd.io](https://containerd.io)**

## Docker 학습 리소스

[Docker 교육 프로그램](https://www.docker.com/dockercon/training)

[Docker Certified Associate(DCA) 인증](https://training.mirantis.com/dca-certification-exam/)

[도커 문서 | 도커 문서](https://docs.docker.com/)

[도커 워크샵](https://courses.packtpub.com/courses/docker)

[Udemy의 Docker 강좌](https://www.udemy.com/topic/docker/)

[Coursera의 Docker 과정](https://www.coursera.org/courses?query=docker)

[edX의 Docker 과정](https://www.edx.org/learn/docker)

[Linkedin Learning에 대한 Docker 과정](https://www.linkedin.com/learning/topics/docker)

## 도커 도구
 
[Lima](https://github.com/lima-vm/lima)는 자동 파일 공유 및 포트 전달(WSL2와 유사) 및 [containerd](https://containerd.io/)를 사용하여 Linux 가상 머신을 시작하는 도구입니다. [Docker Desktop](https://www.docker.com/products/docker-desktop)을 위한 훌륭한 무료 오픈 소스 대안입니다.

[Colima](https://github.com/abiosoft/colima)는 최소한의 설정으로 macOS(및 Linux)의 컨테이너 런타임입니다.

[Docker](https://www.docker.com/)는 애플리케이션을 개발, 제공, 실행하기 위한 개방형 플랫폼입니다. Docker를 사용하면 인프라에서 애플리케이션을 분리할 수 있으므로 Microsoft를 포함한 클라우드, Linux 및 Windows 공급업체와 협력하여 신속하게 소프트웨어를 제공할 수 있습니다.

[Docker Enterprise](https://www.mirantis.com/software/docker/docker-enterprise/)는 CentOS, Red Hat Enterprise Linux(RHEL), Ubuntu, SUSE Linux Enterprise Server(SLES), Oracle Linux, Windows Server 2016은 물론 클라우드 제공업체인 AWS 및 Azure에 대한 소프트웨어, 지원 및 인증된 컨테이너 플랫폼을 포함하는 구독입니다. [2019년 11월 Docker의 엔터프라이즈 플랫폼 사업이 Mirantis에 인수되었습니다](https://www.mirantis.com/company/press-center/company-news/mirantis-acquires-docker-enterprise/).

[Docker Desktop](https://www.docker.com/products/docker-desktop)은 컨테이너화된 애플리케이션과 마이크로서비스를 구축하고 공유하기 위한 MacOS 및 Windows 시스템용 애플리케이션입니다. Docker Desktop은 데스크탑에서 컨테이너화된 애플리케이션을 설계하고 제공하는 데 필요한 속도, 선택권 및 보안을 제공합니다. Docker Desktop에는 Docker 앱, 개발자 도구, Kubernetes 및 프로덕션 Docker 엔진에 대한 버전 동기화가 포함되어 있습니다.

[Docker Hub](https://hub.docker.com/)는 컨테이너 이미지를 위한 세계 최대 규모의 라이브러리이자 커뮤니티입니다. 소프트웨어 공급업체, 오픈 소스 프로젝트 및 커뮤니티에서 100,000개가 넘는 컨테이너 이미지를 찾아보세요.

[Docker Compose](https://docs.docker.com/compose/)는 다중 컨테이너 애플리케이션을 정의하고 공유하는 데 도움이 되도록 개발된 도구입니다. Docker Compose를 사용하면 YAML 파일을 생성하여 서비스를 정의하고 단일 명령으로 모든 것을 가동하거나 해체할 수 있습니다.

[Docker Swarm](https://docs.docker.com/engine/swarm/)은 Docker 기반 클러스터링 시스템입니다. Swarm은 Docker 호스트 클러스터를 제어하고 이를 단일 "가상" 호스트로 노출하는 간단한 도구입니다.

[Dockerfile](https://docs.docker.com/engine/reference/builder/)은 사용자가 이미지를 조합하기 위해 명령줄에서 호출할 수 있는 모든 명령이 포함된 텍스트 문서입니다. docker 빌드를 사용하면 사용자는 여러 명령줄 지침을 연속적으로 실행하는 자동화된 빌드를 만들 수 있습니다.

[Docker 컨테이너](https://www.docker.com/resources/what-container)는 애플리케이션이 한 컴퓨팅 환경에서 다른 컴퓨팅 환경으로 빠르고 안정적으로 실행될 수 있도록 코드와 모든 종속성을 패키지하는 소프트웨어의 표준 단위입니다.

[Docker 엔진](https://www.docker.com/products/container-runtime)은 다양한 Linux(CentOS, Debian, Fedora, Oracle Linux, RHEL, SUSE 및 Ubuntu) 및 Windows Server 운영 체제에서 실행되는 컨테이너 런타임입니다. Docker는 Docker 엔진에서 실행되는 컨테이너 내부에 모든 애플리케이션 종속성을 묶는 간단한 도구와 범용 패키징 접근 방식을 만듭니다.

[Docker 이미지](https://docs.docker.com/engine/reference/commandline/images/)는 코드, 런타임, 시스템 도구, 시스템 라이브러리 및 설정 등 애플리케이션을 실행하는 데 필요한 모든 것이 포함된 경량의 독립형 실행 가능 소프트웨어 패키지입니다. 이미지에는 재사용성을 높이고, 디스크 사용량을 줄이고, 각 단계를 캐시할 수 있도록 하여 Docker 빌드 속도를 높이는 중간 레이어가 있습니다. 이러한 중간 레이어는 기본적으로 표시되지 않습니다. SIZE는 이미지와 모든 상위 이미지가 차지하는 누적 공간입니다.

[Docker 네트워크](https://docs.docker.com/engine/reference/commandline/network/)는 하나 이상의 네트워크에 대한 자세한 정보를 표시하는 것입니다.

[Docker 데몬](https://docs.docker.com/config/daemon/)은 사용자가 수동으로 시작하는 서비스가 아닌 시스템 유틸리티에 의해 시작되는 서비스입니다. 이렇게 하면 머신이 재부팅될 때 Docker를 자동으로 시작하는 것이 더 쉬워집니다. Docker를 시작하는 명령은 운영 체제에 따라 다릅니다. 현재는 다양한 Linux 커널 기능에 의존하기 때문에 Linux에서만 실행되지만 운영 체제 유틸리티를 구성하여 MacOS 및 Windows에서도 Docker를 실행할 수 있는 몇 가지 방법이 있습니다.

[Docker Storage](https://docs.docker.com/storage/storagedriver/select-storage-driver/)는 Docker 호스트에서 이미지와 컨테이너가 저장되고 관리되는 방식을 제어하는 ​​드라이버입니다.

[Kitematic](https://kitematic.com/)은 Mac, Linux 및 Windows에서 Docker 컨테이너를 관리하기 위한 간단한 애플리케이션으로, 그래픽 사용자 인터페이스(GUI)에서 앱 컨테이너를 제어할 수 있습니다.

[개방형 컨테이너 이니셔티브](https://opencontainers.org/about/overview/)는 컨테이너 형식 및 런타임에 대한 개방형 업계 표준을 만들려는 명확한 목적을 위한 개방형 거버넌스 구조입니다.

[Buildah](https://buildah.io/)는 OCI(Open Container Initiative) 이미지를 빌드하기 위한 명령줄 도구입니다. Docker, Podman, Kubernetes와 함께 사용할 수 있습니다.

[Podman](https://podman.io/)은 OCI(Open Containers Initiative) 컨테이너 및 컨테이너 이미지를 사용하여 애플리케이션을 쉽게 검색, 실행, 빌드, 공유 및 배포할 수 있도록 설계된 데몬이 없는 오픈 소스 Linux 기본 도구입니다. Podman은 Docker 컨테이너 엔진을 사용해 본 사람이라면 누구에게나 친숙한 명령줄 인터페이스(CLI)를 제공합니다.

[Containerd](https://containerd.io)는 이미지 전송 및 저장부터 컨테이너 실행 및 감독, 하위 수준 저장, 네트워크 연결 등에 이르기까지 호스트 시스템의 전체 컨테이너 수명주기를 관리하는 데몬입니다. Linux와 Windows에서 사용할 수 있습니다.


# 쿠버네티스
[맨 위로 돌아가기](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/95383873-a884d800-08a0-11eb-8eaf-57af5b119f56.png">
  <br />
</p>

**Apple Silicon(M1/M2)에서 로컬로 Kubernetes 실행**

**[kind](https://kind.sigs.k8s.io/)**는 Docker 컨테이너 "노드"를 사용하여 로컬 Kubernetes 클러스터를 실행하기 위한 도구입니다. 주로 Kubernetes 자체를 테스트하기 위해 설계되었지만 로컬 개발이나 CI에 사용될 수도 있습니다.

**macOS 홈브루 명령**

 ```brew install kind```


**[Okra (Orchestration with Kubernetes on Apple)](https://www.macstadium.com/orka)** is a virtualization layer created for Mac build infrastructure, Orka allows you to orchestrate macOS in a cloud environment using Kubernetes on genuine Apple hardware.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/145732013-d0b9a6d3-d135-49df-bf2b-cc1f4e8970b4.png">
  <br />
  OKRA CLI
</p>

**[Colima](https://github.com/abiosoft/colima)** is a container runtimes on macOS (and Linux) with minimal setup.

**Included Features:**

   * M1/M2 Macs and Intel support
    
   * Docker and Containerd support
    
   * Kubernetes
    
   * Port Forwarding
    
   * Volume mounts
    
#### Installing Colima

**Homebrew**

```brew install colima```

**맥포트**

```sudo port install colima```

**Nix**

```nix-env -iA nixpkgs.colima```


## Kubernetes 학습 리소스

[Kubernetes(K8s)](https://kubernetes.io/)는 컨테이너화된 애플리케이션의 배포, 확장, 관리를 자동화하기 위한 오픈 소스 시스템입니다.

[Kubernetes 인증 받기](https://training.linuxfoundation.org/certification/catalog/?_sft_technology=kubernetes)

[AWS에서 Kubernetes 시작하기](https://aws.amazon.com/kubernetes/)

[Microsoft Azure의 Kubernetes](https://azure.microsoft.com/en-us/topic/what-is-kubernetes/)

[Azure Kubernetes Service 소개](https://docs.microsoft.com/en-us/azure/aks/kubernetes-dashboard)

[Azure Red Hat OpenShift](https://azure.microsoft.com/en-us/services/openshift/)

[Google Cloud 시작하기](https://cloud.google.com/learn/what-is-kubernetes)

[Red Hat에서 Kubernetes 시작하기](https://www.redhat.com/en/topics/containers/what-is-kubernetes)

[IBM에서 Kubernetes 시작하기](https://www.ibm.com/cloud/learn/kubernetes)

[IBM Cloud의 Red Hat OpenShift](https://www.ibm.com/cloud/openshift)

[Red Hat OpenShift에서 OpenShift 가상화 활성화](https://developers.redhat.com/blog/2020/08/28/enable-openshift-virtualization-on-red-hat-openshift/)

[Kubernetes의 YAML 기본 사항](https://developer.ibm.com/technologies/containers/tutorials/yaml-basics-and-usage-in-kubernetes/)

[Kubernetes의 Elastic Cloud](https://www.elastic.co/elastic-cloud-kubernetes)

[Docker 및 Kubernetes](https://www.docker.com/products/kubernetes)

[Kubernetes에서 Apache Spark 실행](http://spark.apache.org/docs/latest/running-on-kubernetes.html)

[VMware vRealize Automation 전반의 Kubernetes](https://blogs.vmware.com/management/2019/06/kubernetes-across-vmware-cloud-automation-services.html)

[VMware Tanzu Kubernetes 그리드](https://tanzu.vmware.com/kubernetes-grid)

[VMware Tanzu가 AWS와 협력하는 모든 방식](https://tanzu.vmware.com/content/blog/all-the-ways-vmware-tanzutm-works-with-aws)

[VMware Tanzu 교육](https://tanzu.vmware.com/education)

[클라우드 네이티브 Kubernetes 환경에서 Ansible 사용](https://www.ansible.com/blog/how-useful-is-ansible-in-a-cloud-native-kubernetes-environment)

[Ansible을 사용하여 Kubernetes(K8s) 객체 관리](https://docs.ansible.com/ansible/latest/collections/community/kubernetes/k8s_module.html)

[Vagrant 및 Ansible을 사용하여 Kubernetes 클러스터 설정](https://kubernetes.io/blog/2019/03/15/kubernetes-setup-using-ansible-and-vagrant/)

[Kubernetes로 MongoDB 실행](https://www.mongodb.com/kubernetes)

[Kubernetes Fluentd](https://docs.fluentd.org/v/0.12/articles/kubernetes-fluentd)

[새로운 GitLab Kubernetes 에이전트 이해](https://about.gitlab.com/blog/2020/09/22/introducing-the-gitlab-kubernetes-agent/)

[Visual Studio2019용 Kubernetes를 사용한 로컬 프로세스 소개](https://devblogs.microsoft.com/visualstudio/introducing-local-process-with-kubernetes-for-visual-studio%E2%80%AF2019/)

[Kubernetes 기여자](https://www.kubernetes.dev/)

[VMware의 KubeAcademy](https://kube.academy/)

[Pulumi의 Kubernetes 튜토리얼](https://www.pulumi.com/docs/tutorials/kubernetes/)

[Kubernetes 플레이그라운드 - Katacoda](https://www.katacoda.com/courses/kubernetes/playground)

[Udacity의 Kubernetes 과정을 사용한 확장 가능한 마이크로서비스](https://www.udacity.com/course/scalable-microservices-with-kubernetes--ud615)

## Kubernetes 도구, 프레임워크 및 프로젝트

[개방형 컨테이너 이니셔티브](https://opencontainers.org/about/overview/)는 컨테이너 형식 및 런타임에 대한 개방형 업계 표준을 만들려는 명확한 목적을 위한 개방형 거버넌스 구조입니다.

[Buildah](https://buildah.io/)는 OCI(Open Container Initiative) 이미지를 빌드하기 위한 명령줄 도구입니다. Docker, Podman, Kubernetes와 함께 사용할 수 있습니다.

[Podman](https://podman.io/)은 OCI(Open Containers Initiative) 컨테이너 및 컨테이너 이미지를 사용하여 애플리케이션을 쉽게 검색, 실행, 빌드, 공유 및 배포할 수 있도록 설계된 데몬이 없는 오픈 소스 Linux 기본 도구입니다. Podman은 Docker 컨테이너 엔진을 사용해 본 사람이라면 누구에게나 친숙한 명령줄 인터페이스(CLI)를 제공합니다.

[Containerd](https://containerd.io)는 이미지 전송 및 저장부터 컨테이너 실행 및 감독, 하위 수준 저장, 네트워크 연결 등에 이르기까지 호스트 시스템의 전체 컨테이너 수명주기를 관리하는 데몬입니다. Linux와 Windows에서 사용할 수 있습니다.

[Google Kubernetes Engine(GKE)](https://cloud.google.com/kubernetes-engine/)은 컨테이너화된 애플리케이션을 실행하기 위해 프로덕션에 즉시 사용 가능한 관리형 환경입니다.

[Azure Kubernetes Service(AKS)](https://azure.microsoft.com/en-us/services/kubernetes-service/)는 통합 CI/CD(지속적인 통합 및 지속적 전달) 환경과 엔터프라이즈급 보안 및 거버넌스를 갖춘 서버리스 Kubernetes입니다. 개발팀과 운영팀을 단일 플랫폼에 통합하여 자신 있게 애플리케이션을 신속하게 구축, 제공, 확장하세요.

[Amazon EKS](https://docs.aws.amazon.com/eks/latest/userguide/what-is-eks.html)는 고가용성을 보장하기 위해 여러 가용 영역에서 Kubernetes 제어 플레인 인스턴스를 실행하는 도구입니다.

[Kubernetes용 AWS 컨트롤러(ACK)](https://aws.amazon.com/blogs/containers/aws-controllers-for-kubernetes-ack/)는 Kubernetes에서 AWS 서비스를 직접 관리할 수 있는 새로운 도구입니다. ACK를 사용하면 AWS 서비스를 활용하는 확장 가능하고 가용성이 높은 Kubernetes 애플리케이션을 간단하게 구축할 수 있습니다.

[OKE(Container Engine for Kubernetes)](https://www.oracle.com/cloud-native/container-engine-kubernetes/)는 최신 클라우드 네이티브 애플리케이션을 구축하는 데 드는 시간과 비용을 줄일 수 있는 Oracle 관리형 컨테이너 오케스트레이션 서비스입니다. 대부분의 다른 공급업체와 달리 Oracle Cloud Infrastructure는 더 높은 성능, 더 저렴한 컴퓨팅에서 실행되는 무료 서비스로 Kubernetes용 Container Engine을 제공합니다.

[Anthos](https://cloud.google.com/anthos/docs/concepts/overview)는 클라우드 및 온프레미스 환경에 일관된 개발 및 운영 환경을 제공하는 최신 애플리케이션 관리 플랫폼입니다.

[Red Hat Openshift](https://www.openshift.com/)는 온프레미스, 하이브리드, 멀티클라우드 배포를 위한 기반을 제공하는 완전 관리형 Kubernetes 플랫폼입니다.

[OKD](https://okd.io/)는 지속적인 애플리케이션 개발 및 다중 테넌트 배포에 최적화된 Kubernetes의 커뮤니티 배포판입니다. OKD는 Kubernetes 위에 개발자 및 운영 중심 도구를 추가하여 소규모 및 대규모 팀을 위한 신속한 애플리케이션 개발, 손쉬운 배포 및 확장, 장기적인 수명 주기 유지 관리를 지원합니다.

[Odo](https://odo.dev/)는 Kubernetes 및 OpenShift에서 애플리케이션을 작성, 구축 및 배포하는 개발자를 위한 빠르고 반복적이며 간단한 CLI 도구입니다.

[Kata Operator](https://github.com/openshift/kata-operator)는 Openshift 및 Kubernetes 클러스터에서 [Kata Runtime](https://katacontainers.io/)의 수명주기 관리(설치/업그레이드/제거)를 수행하는 연산자입니다.

[Thanos](https://thanos.io/)는 무제한 저장 용량을 갖춘 고가용성 측정 시스템으로 구성할 수 있는 구성 요소 집합으로, 기존 Prometheus 배포 위에 원활하게 추가할 수 있습니다.

[OpenShift Hive](https://github.com/openshift/hive)는 Kubernetes/OpenShift 위에서 서비스로 실행되는 연산자입니다. Hive 서비스를 사용하여 OpenShift 4 클러스터의 초기 구성을 프로비저닝하고 수행할 수 있습니다.

[Rook](https://rook.io/)은 분산 스토리지 시스템을 자가 관리, 자가 확장, 자가 치유 스토리지 서비스로 전환하는 도구입니다. 배포, 부트스트래핑, 구성, 프로비저닝, 확장, 업그레이드, 마이그레이션, 재해 복구, 모니터링, 리소스 관리 등 스토리지 관리자의 작업을 자동화합니다.

[VMware Tanzu](https://tanzu.vmware.com/tanzu)는 여러 팀과 프라이빗/퍼블릭 클라우드 전반에서 Kubernetes 인프라와 최신 애플리케이션을 일관되게 운영하고 보호하기 위한 중앙 집중식 관리 플랫폼입니다.

[Kubespray](https://kubespray.io/)는 Kubernetes와 Ansible을 결합하여 [AWS](https://github.com/kubernetes-sigs/kubespray/blob/master/docs/aws.md), GCE, [Azure](https://github.com/kubernetes-sigs/kubespray/blob/master/docs/azure.md), [OpenStack](https://github.com/kubernetes-sigs/kubespray/blob/master/docs/openstack.md), [vSphere](https://github.com/kubernetes-sigs/kubespray/blob/master/docs/vsphere.md), [패킷](https://github.com/kubernetes-sigs/kubespray/blob/master/docs/packet.md)(베어메탈), Oracle Cloud Infrastructure(실험적) 또는 베어메탈에 배포할 수 있는 Kubernetes 클러스터를 쉽게 설치하는 도구입니다.

[KubeInit](https://github.com/kubeinit/kubeinit)은 여러 Kubernetes 배포판의 배포 및 구성을 위한 Ansible 플레이북과 역할을 제공합니다.

[Rancher](https://rancher.com/)는 컨테이너를 채택하는 팀을 위한 완전한 소프트웨어 스택입니다. 여러 Kubernetes 클러스터를 관리하는 데 따른 운영 및 보안 문제를 해결하는 동시에 DevOps 팀에 컨테이너화된 워크로드를 실행하기 위한 통합 도구를 제공합니다.

[K3s](https://github.com/rancher/k3s)는 리소스가 제한된 무인 원격 위치 또는 IoT 어플라이언스 내부의 프로덕션 워크로드를 위해 설계된 고가용성 인증 Kubernetes 배포판입니다.

[Helm](https://helm.sh/)은 Kubernetes 애플리케이션을 더 쉽게 설치하고 관리할 수 있게 해주는 Kubernetes 패키지 관리자 도구입니다.

[Knative](https://knative.dev/)는 최신 서버리스 워크로드를 구축, 배포, 관리하기 위한 Kubernetes 기반 플랫폼입니다. Knative는 네트워킹, 자동 스케일링(0까지) 및 개정 추적의 운영 오버헤드 세부사항을 처리합니다.

[KubeFlow](https://www.kubeflow.org/)는 Kubernetes에서 기계 학습(ML) 워크플로를 간단하고 이식 가능하며 확장 가능하게 배포하기 위한 전용 도구입니다.

[Etcd](https://etcd.io/)는 분산 시스템이나 머신 클러스터에서 액세스해야 하는 데이터를 저장하는 안정적인 방법을 제공하는 분산 키-값 저장소입니다. Etcd는 서비스 검색을 위한 백엔드로 사용되며 Kubernetes의 클러스터 상태 및 구성을 저장합니다.

[OpenEBS](https://openebs.io/)는 컨테이너 연결 스토리지를 사용하여 상태 저장 애플리케이션을 생성하기 위한 Kubernetes 기반 도구입니다.

[컨테이너 스토리지 인터페이스(CSI)](https://www.architecting.it/blog/container-storage-interface/)는 Kubernetes와 같은 컨테이너 오케스트레이션 플랫폼이 플러그인을 통해 저장된 데이터와 원활하게 통신할 수 있게 해주는 API입니다.

[MicroK8s](https://microk8s.io/)는 전체 Kubernetes 경험을 제공하는 도구입니다. 매우 안정적인 운영을 위해 압축된 무선 업데이트를 갖춘 완전히 컨테이너화된 배포입니다. Linux, Windows 및 MacOS에서 지원됩니다.

[Charmed Kubernetes](https://ubuntu.com/kubernetes/features)는 Canonical에서 개발한 멀티 클라우드 환경에 최적화된 잘 통합된 턴키 방식의 준수 Kubernetes 플랫폼입니다.

[Grafana Kubernetes App](https://grafana.com/grafana/plugins/grafana-kubernetes-app)은 Kubernetes 클러스터의 성능을 모니터링할 수 있는 유료 서비스입니다. 여기에는 4개의 대시보드, 클러스터, 노드, 포드/컨테이너 및 배포가 포함됩니다. 이를 통해 필수 Prometheus 내보내기 도구의 자동 배포와 클러스터 내 Prometheus 배포와 함께 사용할 기본 스크레이프 구성이 가능합니다.

[KubeEdge](https://kubeedge.io/en/)는 기본 컨테이너화된 애플리케이션 오케스트레이션 기능을 Edge의 호스트로 확장하기 위한 오픈 소스 시스템입니다. kubernetes를 기반으로 구축되었으며 네트워크, 앱에 대한 기본 인프라 지원을 제공합니다. 클라우드와 엣지 간의 배포 및 메타데이터 동기화.

[Lens](https://k8slens.dev/)는 매일 Kubernetes 클러스터를 처리해야 하는 사람들을 위한 가장 강력한 IDE입니다. MacOS, Windows 및 Linux 운영 체제를 지원합니다.

[Flux CD](https://fluxcd.io/)는 Kubernetes 클러스터의 상태가 Git에 제공한 구성과 일치하는지 자동으로 확인하는 도구입니다. 클러스터의 연산자를 사용하여 Kubernetes 내부 배포를 트리거합니다. 즉, 별도의 지속적인 배포 도구가 필요하지 않습니다.

[Platform9 Managed Kubernetes(PMK)](https://platform9.com/managed-kubernetes/)는 데이터 센터, 퍼블릭 클라우드 또는 엣지 등 모든 환경에서 99.9% SLA로 완전히 자동화된 2일 차 운영을 보장하는 서비스형 Kubernetes입니다.

# 앤서블
[맨 위로 돌아가기](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/113448802-62bd4e00-93b1-11eb-9114-419e758af23b.png">
  <br />
</p>

**[Jeff Geerling의 Mac 개발 Ansible 플레이북](https://github.com/geerlingguy/mac-dev-playbook)**

## Ansible 학습 리소스

[Ansible](https://www.ansible.com/)은 클라우드 프로비저닝, 구성 관리, 애플리케이션 배포, 서비스 내 조정 및 기타 여러 IT 요구 사항을 자동화하는 간단한 IT 자동화 엔진입니다. 이는 일반 영어에 접근하는 방식으로 자동화 작업을 설명할 수 있는 매우 간단한 언어(YAML, Ansible Playbooks 형식)를 사용합니다. Ansible은 Linux(RHEL(Red Hat EnterPrise Linux) 및 Ubuntu) 및 Microsoft Windows에서 작동합니다.

[Ansible을 위한 Red Hat 교육](https://www.ansible.com/products/training-certification)

[Udemy의 인기 Ansible 온라인 강좌](https://www.udemy.com/topic/ansible/)

[Ansible 소개: Coursera의 기초](https://www.coursera.org/projects/ansible-fundamentals)

[Pluralsight에 대한 Ansible 기초 학습](https://www.pluralsight.com/courses/ansible-fundamentals)

[Red Hat Ansible Automation Platform 2.1 소개](https://www.ansible.com/blog/introducing-red-hat-ansible-automation-platform-2.1)

[앤서블 문서](https://docs.ansible.com/ansible/latest/index.html)

[Ansible Galaxy 사용자 가이드](https://docs.ansible.com/ansible/latest/galaxy/user_guide.html)

[가능한 사용 사례](https://www.ansible.com/use-cases?hsLang=en-us)

[Ansible 통합](https://www.ansible.com/integrations?hsLang=en-us)

[Ansible 컬렉션 개요](https://github.com/ansible-collections/overview/blob/main/README.rst)

[플레이북 작업](https://docs.ansible.com/ansible/latest/user_guide/playbooks.html)

[Jeff Geerling의 DevOps용 Ansible 예제](https://github.com/geerlingguy/ansible-for-devops)

[시작하기: 첫 번째 플레이북 작성 - Ansible](https://www.ansible.com/blog/getting-started-writing-your-first-playbook)

[Ansible의 모듈 작업](https://docs.ansible.com/ansible/latest/user_guide/modules.html)

[Ansible 모범 사례: 역할 및 모듈](https://www.ansible.com/resources/webinars-training/ansible-best-practices-roles-modules)

[Ansible용 명령줄 도구 작업](https://docs.ansible.com/ansible/latest/user_guide/command_line_tools.html)

[Ansible Vault로 콘텐츠 암호화](https://docs.ansible.com/ansible/latest/user_guide/vault.html)

[Ansible로 플레이북에서 Vault 사용](https://docs.ansible.com/ansible/latest/user_guide/playbooks_vault.html)

[Azure와 함께 Ansible 사용](https://docs.microsoft.com/en-us/azure/developer/ansible/overview)

[Azure VM에서 Ansible 구성](https://docs.microsoft.com/en-us/azure/developer/ansible/install-on-linux-vm)

[Ansible 사용 방법: DigitalOcean의 Ansible 치트 시트 가이드](https://www.digitalocean.com/community/cheatsheets/how-to-use-ansible-cheat-sheet-guide)

[Linode의 Ansible 소개 | 공간 연구소](https://spatial-labs.dev/posts/202101072328-intro-to-ansible-on-linode/)

## Ansible DevOps 도구 통합

[Ansible Automation Hub](https://www.ansible.com/products/automation-hub)는 Ansible Automation Platform 구독의 일부로 포함된 지원되는 [컬렉션](https://docs.ansible.com/ansible/latest/user_guide/collections_using.html#collections)을 검색하고 다운로드할 수 있는 공식 위치입니다. 이러한 콘텐츠 컬렉션에는 다운로드 가능한 패키지에 모듈, 플러그인, 역할 및 플레이북이 포함되어 있습니다.

[컬렉션](https://docs.ansible.com/ansible/latest/user_guide/collections_using.html#collections)은 플레이북, 역할, 모듈 및 플러그인을 포함할 수 있는 Ansible 콘텐츠의 배포 형식입니다. 모듈이 핵심 Ansible 리포지토리에서 컬렉션으로 이동함에 따라 모듈 문서도 [컬렉션 페이지](https://docs.ansible.com/ansible/latest/collections/index.html#list-of-collections)로 이동됩니다.

[Ansible Lint](https://ansible-lint.readthedocs.io/en/latest/)는 Ansible 사용자를 대상으로 플레이북, 역할 및 컬렉션을 Linting하기 위한 명령줄 도구입니다. 주요 목표는 쉽게 버그가 발생하거나 코드를 유지 관리하기 어렵게 만드는 일반적인 함정을 피하면서 입증된 사례, 패턴 및 동작을 장려하는 것입니다.

[Ansible cmdb](https://github.com/fboender/ansible-cmdb)는 Ansible의 사실 수집 결과를 가져와 시스템 구성 정보가 포함된 정적 HTML 개요 페이지로 변환하는 도구입니다.

[Ansible Inventory Grapher](https://github.com/willthames/ansible-inventory-grapher)는 인벤토리 상속 계층 구조와 변수가 인벤토리에 정의된 수준을 시각적으로 표시합니다.

[Ansible 플레이북 그래퍼](https://github.com/haidaraM/ansible-playbook-grapher)는 Ansible 플레이북 작업 및 역할을 나타내는 그래프를 생성하는 명령줄 도구입니다.

[Ansible Shell](https://github.com/dominis/ansible-shell)은 모든 모듈에 대한 탭 완성 기능이 내장된 Ansible용 대화형 셸입니다.

[Ansible Silo](https://github.com/groupon/ansible-silo)는 [Docker](https://www.docker.com/)에 의한 독립형 Ansible 환경입니다.

[Ansigenome](https://github.com/nickjj/ansigenome)은 Ansible 역할을 관리하는 데 도움이 되도록 설계된 명령줄 도구입니다.

[ARA](https://github.com/openstack/ara)는 Ansible 플레이북이 실행되는 기록이며 콜백 플러그인으로 Ansible과 통합되어 사용자와 시스템이 기록된 데이터를 사용하고 직관적으로 만들 수 있습니다.

[Capistrano](https://capistranorb.com/documentation/overview/what-is-capistrano/)는 원격 서버 자동화 도구입니다. 임의 작업의 스크립팅 및 실행을 지원하고 정상적인 기본 배포 워크플로 세트를 포함합니다.

[Fabric](https://www.fabfile.org)은 SSH를 통해 원격으로 셸 명령을 실행하여 유용한 Python 개체를 생성하도록 설계된 고급 Python(2.7, 3.4+) 라이브러리입니다. 이는 [Invoke](https://www.pyinvoke.org)(하위 프로세스 명령 실행 및 명령줄 기능) 및 [Paramiko](https://paramiko.org/)(SSH 프로토콜 구현) 위에 구축되어 API를 확장하여 서로를 보완하고 추가 기능을 제공합니다.

[ansible-role-wireguard](https://galaxy.ansible.com/githubixx/ansible_role_wireguard)는 WireGuard VPN 설치를 위한 Ansible 역할입니다. Ubuntu, Debian, Archlinx, Fedora 및 CentOS Stream을 지원합니다.

[wireguard_cloud_gateway](https://galaxy.ansible.com/consensus/wireguard_cloud_gateway)는 Wireguard를 클라우드 네트워크용 게이트웨이 VPN 서버로 설정하기 위한 Ansible 역할입니다.

[Red Hat OpenShift](https://www.openshift.com/)는 컨테이너 스택의 모든 수준과 애플리케이션 라이프사이클 전반에 걸쳐 보안에 중점을 두고 있습니다. 여기에는 선도적인 Kubernetes 기여자 중 하나와 오픈 소스 소프트웨어 회사의 장기적인 엔터프라이즈 지원이 포함됩니다.

[OpenShift Hive](https://github.com/openshift/hive)는 Kubernetes/OpenShift 위에서 서비스로 실행되는 연산자입니다. Hive 서비스를 사용하여 OpenShift 4 클러스터의 초기 구성을 프로비저닝하고 수행할 수 있습니다.

# Apple Silicon에서 Linux 실행
[맨 위로 돌아가기](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

### Apple Silicon에서의 Linux 가상화

 - [Rosetta를 사용하여 Linux VM에서 Intel 바이너리 실행](https://developer.apple.com/documentation/virtualization/running_intel_binaries_in_linux_vms_with_rosetta?language=objc) - Apple Silicon의 ARM Linux에서 x86_64 Linux 바이너리를 실행합니다.

 - [Mac에서 Linux 가상화](https://developer.apple.com/documentation/virtualization/virtualize_linux_on_a_mac?language=objc) - Apple Silicon 및 Intel 기반 Mac 컴퓨터에서 Linux 게스트를 구성하고 실행합니다.
 

[Parallels Desktop for Mac](https://www.parallels.com/products/desktop/)은 MacBook, MacBook Pro, iMac, iMac Pro, Mac mini 또는 Mac Pro에서 Windows를 macOS와 함께(다시 시작할 필요 없이) 실행할 수 있게 해주는 프로그램입니다. 파일과 폴더를 공유하고, 이미지와 텍스트를 복사하여 붙여넣고, Mac과 Windows 응용 프로그램 간에 파일을 끌어서 놓으세요.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/110880057-df697a80-8292-11eb-8484-9bbc02592377.jpg">
<br />
Mac용 패러렐즈 데스크톱
</p>


[UTM](https://getutm.app/)은 iOS 및 macOS용 모든 기능을 갖춘 시스템 에뮬레이터이자 가상 머신 호스트입니다. Mac, iPhone, iPad에서 Windows, Linux 등을 실행할 수 있는 [QEMU](https://www.qemu.org/)를 기반으로 합니다.

 - [iOS/iPadOS용 UTM(SE)](https://getutm.app/install/)
 
 - [macOS용 UTM](https://mac.getutm.app/)
 
 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/164793036-c84684fb-be06-4452-bfc9-32f77fb8059f.png">
  <br />
 UTM의 우분투
</p>

[VMware Fusion](https://blogs.vmware.com/teamfusion/2022/07/just-released-vmware-fusion-22h2-tech-preview.html)은 Mac 컴퓨터용으로 VMware에서 개발한 소프트웨어 하이퍼바이저입니다. 가상 머신을 생성하고 해당 가상 머신 내에 운영 체제(예: Windows 또는 Linux)를 설치합니다.

  * Intel 및 Apple Silicon 기반 Windows 11, 2D 그래픽 및 네트워킹 지원.
  * M1 기반 Mac에서 Windows 11 게스트 운영 체제에 대한 VMTools 설치를 지원합니다.
  * 빠른 암호화를 지원하는 가상 TPM 장치.
  * M1의 Linux 지원이 향상되었습니다.
  * Linux 가상 머신의 3D 그래픽 HW 가속 및 OpenGL 4.3(Linux 5.19+ 및 Mesa 22.1.3+ 필요).
  * Apple Silicon 및 Intel Mac용 범용 바이너리.
 
[Multipass](https://multipass.run/)는 Linux, macOS 및 Windows에서 클라우드 스타일 Ubuntu VM을 빠르게 생성하는 도구입니다. Linux에서는 [KVM](https://www.redhat.com/en/topics/virtualization/what-is-KVM), Windows에서는 [Hyper-V](https://docs.microsoft.com/en-us/virtualization/hyper-v-on-windows/about/), macOS에서는 [HyperKit](https://github.com/moby/hyperkit)을 사용합니다.

### 아사히 리눅스 개발

[Hector Martin](https://github.com/marcan)은 Apple M1 하드웨어에 대한 초기 지원을 [Linux Kernel 5.13](https://git.kernel.org/pub/scm/linux/kernel/git/soc/soc.git/commit/?h=for-next&id=0d5fe4b31785b732b71e764b55cda5c8d6e3bbbf)용 Linux SOC(System On a Chip) 트리에 병합했습니다. 또한 개발자 [Sven Peter](https://github.com/svenpeter42) 및 [Alyssa Rosenzweig](https://github.com/alyssarosenzweig)에게도 감사드립니다.

Linux 커널 6.2는 Asahi Linux 개발자의 작업이 업스트림되면서 Apple M1 Pro, Max 및 Ultra 칩에 대한 메인라인 지원을 제공합니다. 하지만 그렇다고 해서 6.2 커널을 사용하여 Fedora, Ubuntu 또는 Debian과 같은 Linux 배포판을 간단히 설치할 수 있다는 의미는 아닙니다.

 * [Linux 커널 6.2 릴리스 노트](https://lkml.org/lkml/2023/2/19/309).

[Asahi Linux](https://asahilinux.org/)는 2020년 M1 Mac Mini, MacBook Air, MacBook Pro를 시작으로 Linux를 Apple Silicon Mac에 포팅하는 것을 목표로 하는 프로젝트이자 커뮤니티입니다. 이들의 목표는 단순히 이러한 시스템에서 Linux를 실행하는 것이 아니라 일상적인 OS로 사용할 수 있을 정도로 다듬는 것입니다.

  - [Asahi Linux Alpha 릴리스 출시!](https://asahilinux.org/2022/03/asahi-linux-alpha-release/)

  - [GitHub의 Asahi Linux 설치 프로그램](https://github.com/AsahiLinux/asahi-installer)
  
  - [Asahi Linux 기능 지원](https://github.com/AsahiLinux/docs/wiki/Feature-Support)
  
  - [아사히 리눅스 위키](https://github.com/AsahiLinux/docs/wiki)
  
  - [이제 M1/+M2 계열 GPU에 적합한 OpenGL® ES 3.1 드라이버를 사용할 수 있습니다.](https://rosenzweig.io/blog/first-conformant-m1-gpu-driver.html)

[M1N1](https://github.com/AsahiLinux/m1n1)은 Apple Silicon의 부트로더이자 실험 놀이터입니다.

[Apple Silicon to Apple Silicon VDM 유틸리티](https://github.com/AsahiLinux/macvdmtool)는 macOS를 실행하는 다른 Apple Silicon 장치와 표준 Type C 케이블만 사용하여 Apple Silicon 장치에서 직렬 콘솔을 가져와 원격으로 재부팅할 수 있게 해주는 도구입니다.

[Asahi GPU](https://github.com/AsahiLinux/gpu)는 Apple M1 칩용 오픈 소스 그래픽 스택(3D 가속)에 대한 연구를 제공하는 저장소입니다.

<h3 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/110054441-f4349400-7d0f-11eb-8889-743009b33994.png">
  <br />
</h3>

[AsahiLinux Apple GPU 드라이버](https://asahilinux.org/2022/12/gpu-drivers-now-in-asahi-linux/) 기능은 현재 모든 Apple M 시리즈 시스템에 대해 진행 중인 OpenGL 2.1 및 OpenGL ES 2.0 지원입니다. GNOME 및 KDE와 같은 데스크탑 환경의 하드웨어 가속에는 충분합니다. Quake3나 Neverball과 같은 오래된 3D 게임에도 충분합니다.

아사히 리눅스 그래픽 팀:

   * [Alyssa Rosenzweig](https://social.treehouse.systems/@alyssa)는 OpenGL 드라이버와 컴파일러를 작성하고 있습니다.
   * [Asahi Lina](https://vt.social/@lina)는 커널 드라이버를 작성하고 OpenGL을 돕고 있습니다.
   * [Dougall Johnson](https://mastodon.social/@dougall)은 Alyssa와 함께 명령어 세트를 리버스 엔지니어링하고 있습니다.
   * [Ella Stanforth](https://tech.lgbt/@ella)는 커널 드라이버, 컴파일러 및 OpenGL 드라이버와 공유되는 일부 코드를 재사용하여 Vulkan 드라이버를 작업하고 있습니다.

**Apple GPU 드라이버 설치:**

새 드라이버를 얻으려면 linux-asahi-edge 커널을 실행하고 mesa-asahi-edge Mesa 패키지도 설치해야 합니다.

```
$ sudo pacman -Syu
$ sudo pacman -S linux-asahi-edge mesa-asahi-edge
$ sudo update-grub
```

한 번에 하나의 Mesa 버전만 설치할 수 있으므로 pacman에서는 mesa를 mesa-asahi-edge로 바꾸라는 메시지를 표시합니다. 이것은 정상입니다!

**권장 사항:** 이 시점에서 Xorg 대신 Wayland를 실행하십시오. 따라서 KDE Plasma 환경을 사용하는 경우 Wayland 세션을 설치하십시오.

```$ sudo pacman -S plasma-wayland-session```

Then reboot, pick the Wayland session at the top of the login screen (SDDM), and enjoy! You might want to adjust the screen scale factor in System Settings → Display and Monitor (Plasma Wayland defaults to 100% or 200%, while 150% is often nicer). If you have “Force font DPI” enabled under Appearance → Fonts, you should disable that (it is saved separately for Wayland and Xorg, and shouldn’t be necessary on Wayland sessions). Log out and back in for these changes to fully apply.

### Fedora Linux Development

**Most of the hard work, including the kernel and boot software, was done by the [Asahi Linux project](https://asahilinux.org/) and their development team.**

While you will end up with a fairly usable computer, the exact hardware features you want [may not be ready yet](https://github.com/AsahiLinux/docs/wiki/%22When-will-Asahi-Linux-be-done%3F%22). Please look at the [Asahi Linux Feature Support page](https://github.com/AsahiLinux/docs/wiki/Feature-Support) for information. 

For more general information about Linux on Apple Silicon Macs, refer to the [Asahi Linux project](https://asahilinux.org/) and [alpha installer release](https://asahilinux.org/2022/03/asahi-linux-alpha-release/). 

* [Our new flagship distro: Fedora Asahi Remix - Asahi Linux](https://asahilinux.org/2023/08/fedora-asahi-remix/)
* [Fedora Asahi Remix project](https://fedora-asahi-remix.org/)
* [Fedora Asahi Remix packages for Apple Silicon](https://packages.fedoraproject.org/pkgs/asahi-scripts/asahi-scripts/)
* [Fedora COPR Pacakges for Asahi](https://copr.fedorainfracloud.org/groups/g/asahi/coprs/)
* [Fedora Asahi Special Interest Group](https://fedoraproject.org/wiki/SIGs/Asahi)

[Asahi-Fedora-Builder](https://github.com/leifliddy/asahi-fedora-builder) is a script that builds a minimal Fedora image to run on Apple M1/M2 systems.

**Installing a Prebuilt Image**

Make sure to update your macOS to version 12.3 or later, then just pull up a Terminal in macOS and paste in this command:

```curl https://leifliddy.com/fedora.sh | sh```

**Fedora 패키지 설치**

```dnf install mkosi arch-install-scripts systemd-container zip```

<h3 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/220301314-23dbffb5-5c08-4d6f-ae22-f5f6c9ab46d3.png">
  <br />
  Fedora Linux 
</h3>

### NixOS Linux Development 

* **[NixOS on Apple Silicon](https://github.com/tpwrules/nixos-m1)**

## UEFI Boot Standalone NixOS (February 2023)

**This build was tested with the following software:**

* **Asahi Linux kernel version 6.1.0-asahi2**
* **Asahi Linux's Mesa version 23.0.0_pre20221219-1**
* **m1n1 version v1.2.3**
* **Asahi Linux's U-Boot version 2022.10.asahi1-1**
* **Nixpkgs, as of 2023-02-21**
* **macOS stub 12.3 or later**

**NOTE:** For more general information about Linux on Apple Silicon Macs, refer to the [Asahi Linux project](https://asahilinux.org/) and [Asahi Linux Alpha installer release](https://asahilinux.org/2022/03/asahi-linux-alpha-release/).

## Intro

This section will explain how to install NixOS on the internal NVMe drive of an Apple Silicon Mac using a customized version of the official NixOS install ISO, then boot it without the help of another computer. Aside from the Apple Silicon support module and AArch64 CPU, the resulting installation can be configured and operated like any other NixOS system. Your macOS install will still work normally, and you can easily switch between booting both macOS and NixOS.

**Most of the hard work, including the kernel and boot software, was done by the [Asahi Linux project](https://asahilinux.org/) and their development team.**

**Quick NixOS Intro:**

 * [NixOS](https://nixos.org/) is a Linux distribution built on top of the [Nix package manager](https://nixos.wiki/wiki/Nix). It has tools dedicated to DevOps and deployment tasks.

 * [Nix Tour](https://nixcloud.io/tour/) is an interactive tour that uses the actual package manager to learn you the language by example, in the browser

* [Nix](https://nixos.wiki/wiki/Nix) is a package manager and build system that parses reproducible build instructions specified in the [Nix Expression Language](https://nixos.wiki/wiki/Nix_Expression_Language), is a pure functional language with lazy evaluation. Nix expressions are pure functions taking dependencies as arguments and producing derivation specifying a reproducible build environment for the package. Nix stores the results of the build in unique addresses specified by a hash of the complete dependency tree, creating an immutable package store that allows for atomic upgrades, rollbacks and concurrent installation of different versions of a package, essentially eliminating [dependency hell](https://en.wikipedia.org/wiki/Dependency_hell).

* [Nix Expression Language](https://nixos.wiki/wiki/Nix_Expression_Language) is a pure, lazy, functional language. Purity means that operations in the language don't have side-effects (for instance, there is no variable assignment). The language is not a full-featured, general purpose language. Its main job is to describe packages, compositions of packages, and the variability within packages.

* [Nixpkgs](https://nixos.wiki/wiki/Nixpkgs) is the largest repository of [Nix](https://nixos.wiki/wiki/Nix) packages(over 60,000 packages) and [NixOS](https://nixos.wiki/wiki/NixOS) modules. The repository is [hosted on GitHub](https://github.com/nixos/nixpkgs) and maintained by the community, with official backing from the [NixOS Foundation](https://nixos.org/). Additionally, checkout [Language-specific package helpers](https://nixos.wiki/wiki/Language-specific_package_helpers) and [Alternative Package Sets](https://nixos.wiki/wiki/Alternative_Package_Sets).

 * [NixOS Packages Search](https://search.nixos.org/packages) is a tool for searching through NixOS packages.

### Warning

Damage to the macOS recovery partitions or the partition table could result in the Mac becoming unbootable and loss of all data on the internal NVMe drive. In this circumstance, a suitable USB cable and another computer which can run [idevicerestore](https://github.com/libimobiledevice/idevicerestore) will be required to perform a DFU upgrade and restore normal operation. Backups are always wise.

While you will end up with a fairly usable computer, the exact hardware features you want [may not be ready yet](https://github.com/AsahiLinux/docs/wiki/%22When-will-Asahi-Linux-be-done%3F%22). Please look at the [Asahi Linux Feature Support page](https://github.com/AsahiLinux/docs/wiki/Feature-Support) for information. Any features marked with a kernel version or **`linux-asahi`** should be supported by NixOS too.

### Prerequisites

**The following items are required to get started:**

* Apple Silicon Mac [supported by Asahi Linux](https://github.com/AsahiLinux/docs/wiki/Feature-Support#table-of-contents) with macOS 12.3 or later and an admin account.
* For Mac mini users: tested and working HDMI monitor. Many do not work properly; if it shows the Asahi Linux logo and console when m1n1 is running, it's fine.
* USB flash drive which is at least 512MB and can be fully erased, and USB A to C adapter.
* Familiarity with the command line and installers without GUIs.
* **Optional:** x86_64 or aarch64 Linux PC or VM (any distro is fine).

### Overview

* [Software Preparation](#software-preparation): build the customized NixOS installer ISO and Asahi Linux components
* [UEFI Preparation](#uefi-preparation): use the Asahi Linux installer to set up a standard UEFI boot environment
* [Installation](#installation): boot the NixOS installer and use it to set up and install NixOS
* [Maintenance](#maintenance): repair and upgrade NixOS and the Asahi Linux components
* [Removal](#removal): restore the system to the stock state


## Software Preparation

#### Nix

This setup takes advantage of the Nix package manager, which handles downloading and compiling everything. You must first install it on your Linux host PC if it doesn't run NixOS. Most distros are compatible, and installation (and uninstallation) is simple. Instructions are available on the [NixOS website](https://nixos.org/download.html#nix-quick-install).

If you can't or do not wish to install Nix and/or build these components yourself, installation ISOs are automatically built and made available from the [GitHub Releases page](https://github.com/tpwrules/nixos-apple-silicon/releases). Download the latest one, use `dd` or similar to transfer it to your USB flash drive, then skip down to the section on [UEFI Preparation](#uefi-preparation). Programs like `unetbootin` are not supported. These ISOs are fully reproducible; that is, the ISO you download will be (or should be...) bit-identical to the one you will get by following these preparation instructions.

#### NixOS Apple Silicon

Clone this repository to a suitable location on the host PC. In the future, you can update this repository using `git pull` and re-run the `nix build` commands to update things.

```
$ 자식 클론 https://github.com/tpwrules/nixos-apple-silicon/
$ CD nixos-애플-실리콘
```

#### m1n1

The Asahi Linux project has developed **m1n1** as a bridge between Apple's boot firmware and the Linux world. m1n1 is installed as a faux macOS kernel into a stub macOS installation. In addition to booting Linux (or U-Boot), m1n1 also sets up the hardware and allows remote control and debugging over USB.

**Change directories to the repository, then use Nix to build m1n1 and symlink the result to `m1n1`:**

```
nixos-apple-silicon$ nix build --extra-experimental-features 'nix-command flakes' .#m1n1 -o m1n1
```

m1n1 has been built and the build products are now in `m1n1/build/`. You can also run m1n1's scripts such as `chainload.py` using a command like `m1n1/bin/m1n1-chainload`.

#### U-Boot

In the default installation, m1n1 loads U-Boot and U-Boot is used to set up a standard UEFI environment from which GRUB or systemd-boot or whatever can be booted. Due to the limitations of the Apple boot picker, there must be one EFI system partition per installed OS.

**Use Nix to build U-Boot along with m1n1 and the device trees:**

```
nixos-apple-silicon$ nix build --extra-experimental-features 'nix-command flakes' .#uboot-asahi -o u-boot
```

The `.bin` file with m1n1, the device trees, and U-Boot joined together is now in `u-boot/`.

#### Kernel and Bootstrap Installer

The bootstrap NixOS installer ISO contains UEFI-compatible GRUB, the Asahi Linux kernel, its initrd, and enough packages and drivers to allow connection to the Internet in order to download and install a full NixOS system.

```
nixos-apple-silicon$ nix build --extra-experimental-features 'nix-command flakes' .#installer-bootstrap -o installer -j4 -L
```

The installer ISO is now available as `installer/iso/nixos-*.iso`. Use `dd` or similar to transfer it to your USB flash drive. Programs like `unetbootin` are not supported.

## UEFI Preparation

This setup uses the alpha Asahi Linux installer to install a stub macOS and standard UEFI boot environment from which the NixOS installer and installed OS will run. These steps must be run from Terminal.app in macOS. You must also be logged into an administrator account.

#### Asahi Linux Installation

**Download and run the alpha installer with the following command:**
```
% 컬 https://alx.sh | 쉿
```

**Choose the following options to get started:**
* Enter your administrator password
* Do not enable expert mode

**Resize your existing macOS install:**
* Resize an existing partition to make space for a new OS (`r`)
* Enter the new size of the macOS install. It should be at least 20GB less than its current size to make room for NixOS with a GUI (note that here 1GB = 1,000,000,000 bytes)
* Confirm the resize operation
* Wait patiently while the partition is resized; it will take several minutes. Do not attempt to use the machine while this is in progress.
* Press enter when finished

**Install UEFI environment:**
* Install an OS into free space (`f`)
* UEFI environment only
* Name it NixOS (this is what shows up in the firmware boot picker)
* Wait while the installation proceeds and enter your password when prompted
* Wait for the default boot volume to be set (this may take several seconds)
* Read the final advice, then press enter to shut down the machine

Boot into recovery mode by holding the power button down as directed and select the new NixOS option in the boot picker. Follow the prompts and enter your administrator password. The local policy update will take several seconds to complete. Once complete, select that you want to set a custom boot object and put your system to permissive security mode, enter your administrator username (the same one you put in the password for earlier) and password, then reboot when prompted.

If everything went well, you will restart into U-Boot with the Asahi Linux and U-Boot logos on-screen. Shut the system down by holding the power button, then proceed to the next step.

## Installation

#### Booting the Installer

Shut down the machine fully. Connect the flash drive with the installer ISO to a USB-C port through the USB A to C adapter. If on a Mac mini, you must use the USB-C ports as U-Boot does not support the USB-A ports at this time. If not using Wi-Fi, connect the Ethernet cable to the network port or adapter as well.

Start the Mac, and U-Boot should start booting from the USB drive automatically. If you've already installed something to the internal NVMe drive, U-Boot will try to boot it first. To instead boot from USB, hit a key to stop autoboot when prompted, then run the command `run bootcmd_usb0`.

GRUB will start, then the NixOS installer after a short delay (the default GRUB option is fine). You will get a console prompt once booting completes. Run the command `sudo su` to get a root prompt in the installer. If the console font is too small, run the command `setfont ter-v32n` to increase the size.


#### Partitioning and Formatting

**DANGER:** Damage to the GPT partition table, first partition (`iBootSystemContainer`), or the last partition (`RecoveryOSContainer`) could result in the loss of all data and render the Mac unbootable and unrecoverable without assistance from another computer! Do not use your distro's automated partitioner or partitioning instructions!

We will add a root partition to the remaining free space and format it as ext4. Alternative partition layouts and filesystems, including LUKS encryption, are possible, but not covered currently.

**Create the root partition to fill up the free space:**
```
nixos# sgdisk /dev/nvme0n1 -n 0:0 -s
[...]
작업이 성공적으로 완료되었습니다.
```

**Identify the number of the new root partition (type code 8300, typically second to last):**
```
nixos# sgdisk /dev/nvme0n1 -p
디스크 /dev/nvme0n1: 244276265 섹터, 931.8 GiB
모델: 애플 SSD AP1024Q
섹터 크기(논리적/물리적): 4096/4096바이트
디스크 식별자(GUID): 27054D2E-307A-41AA-9A8C-3864D56FAF6B
파티션 테이블은 최대 128개의 항목을 보유합니다.
메인 파티션 테이블은 섹터 2에서 시작하여 섹터 5에서 끝납니다.
첫 번째 사용 가능한 섹터는 6이고 마지막 사용 가능한 섹터는 244276259입니다.
파티션은 1 섹터 경계에 정렬됩니다.
총 여유 공간은 0섹터(0바이트)입니다.

번호 시작(섹터) 끝(섹터) 크기 코드 이름
   1 6 128005 500.0MiB FFFF iBootSystemContainer
   2 128006 219854567 838.2 GiB AF0A 컨테이너
   3 219854568 220465127 2.3GiB AF0A
   4 220465128 220590311 489.0MiB EF00
   5 220590312 242965550 85.4GiB 8300
   6 242965551 244276259 5.0GiB FFFF RecoveryOSContainer
```

**Format the new root partition:**
```
nixos# mkfs.ext4 -L nixos /dev/nvme0n1p5
```

#### NixOS Configuration

The subsequent steps in this section will help you install NixOS onto your new partitions. More information is available in the Installing section of the [NixOS manual](https://nixos.org/manual/nixos/stable/index.html#sec-installation-installing). Some changes to the configuration procedure as described in that manual are needed for NixOS on Apple Silicon to work properly.

**Mount the root partition, then the EFI system partition that was created by the Asahi Linux installer specifically for NixOS:**
```
nixos# 마운트 /dev/disk/by-label/nixos /mnt
nixos# mkdir -p /mnt/boot
nixos# 마운트 /dev/disk/by-partuuid/`cat /proc/device-tree/chosen/asahi,efi-system-partition` /mnt/boot
```

**Create a default configuration for the new system, then copy the Apple Silicon support module into it:**
```
nixos# nixos-generate-config --root /mnt
nixos# cp -r /etc/nixos/apple-silicon-support /mnt/etc/nixos/
nixos# chmod -R +w /mnt/etc/nixos/
```

Use vim (or any editor of your choice) to edit the configuration of the new system to include the Apple Silicon support module. Be aware that other editors and most documentation has been left out of the bootstrap installer to save space and time.
```
nixos # vim /mnt/etc/nixos/configuration.nix
```

Add the `./apple-silicon-support` directory to the imports list and switch off the `canTouchEfiVariables` option. That portion of the file should look like this:
```
  수입 =
    [ # 하드웨어 스캔 결과를 포함합니다.
      ./hardware-configuration.nix
      # Apple Silicon 지원에 필요한 패키지와 구성을 포함합니다.
      ./apple-silicon-support
    ];

  # systemd-boot EFI 부트로더를 사용합니다.
  boot.loader.systemd-boot.enable = true;
  boot.loader.efi.canTouchEfiVariables = false;
```

If you used the cross-compiled installer image, i.e. **you downloaded the ISO from GitHub or built it on an `x86_64-linux` machine, you may add the following line to re-use the cross-compiled Asahi packages**. If you don't, they will be rebuilt in the installer, which wastes time. When you update the system and they need to be rebuilt on the Mac itself, remove this line or you will get an error that an `x86_64-linux` builder is required.
```
  # x86_64-linux 빌더가 필요하다는 오류가 발생하면 제거합니다.
  hardware.asahi.pkgsSystem = "x86_64-linux";
```

The configuration above is the minimum required to produce a bootable system, but you can further edit the file as desired to perform additional configuration. Uncomment the relevant options and change their values as explained in the file. Note that some advertised features may not work properly at this time. Refer to the [NixOS installation manual](https://nixos.org/manual/nixos/stable/index.html#ch-configuration) for further guidance.

Various non-free non-redistributable peripheral firmware files are required to use system hardware like Wi-Fi. The Asahi Linux installer grabs these from macOS and stores them on the EFI system partition when it is created. The NixOS installer loads them from there while booting so that all hardware is available during installation. By default, the Apple Silicon support module will automatically reference the files in the EFI system partition and incorporate them into your configuration to be managed by the normal NixOS mechanisms.

Currently, the only supported way to update the peripheral firmware files is to destroy and re-create the EFI system partition, so they will not change unexpectedly. If you do not want the impurity of referencing them (or are using flakes where this is prohibited), copy them off the EFI system partition (e.g. on the installation ISO `mkdir -p /mnt/etc/nixos/firmware && cp /mnt/boot/asahi/{all_firmware.tar.gz,kernelcache*} /mnt/etc/nixos/firmware`) and specify this path in your configuration:
```
  # 주변 펌웨어 파일의 경로를 지정합니다.
  hardware.asahi.peripheralFirmwareDirectory = ./firmware;
  # 또는 추출 및 관리를 완전히 비활성화합니다.
  # hardware.asahi.extractPeripheralFirmware = false;
```

You can choose to build the Asahi kernel with a 4K page size by enabling the appropriate option. This results in a reduction in raw compilation speed of 10-25%, but improves software compatibility in some cases (such as with Chromium/Electron and x86 emulation).
```
  # 4K 페이지로 커널을 구축하여 소프트웨어 호환성을 향상시킵니다.
  # 어떤 경우에는 성능 비용.
  hardware.asahi.use4KPages = true;
```

If you want to install a desktop environment, you will have to uncomment the option to enable X11 and NetworkManager, then add an option to include your favorite desktop environment. You may also wish to include graphical packages such as `firefox` in `environment.systemPackages`. For example, to install Xfce:
```
  # X11 윈도우 시스템을 활성화합니다.
  services.xserver.enable = true;
  services.xserver.desktopManager.xfce.enable = true;
```

Some keyboard layouts are not detected correctly. On some devices, the \` key is swapped with `<`, and `~` with `>`. The layout can be fixed by setting options in `boot.extraModprobeConfig`. Which option needs to be set depends on your hardware keyboard's layout (see: [Arch Wiki - Apple Keyboard](https://wiki.archlinux.org/title/Apple_Keyboard)).
 ```
 # `에서 < 및 ~에서 >(미국 키보드를 사용하는 경우)
 boot.extraModprobeConfig = ''
   옵션 hid_apple iso_layout=0
 '';
 ```

#### NixOS Installation

Once you are happy with your initial configuration, you may install the system. This will have to download a large amount of data.

You can configure wireless networking in the installer using `wpa_supplicant` by following [the minimal installer directions](https://nixos.org/manual/nixos/stable/index.html#sec-installation-booting-networking) in the NixOS manual.

Once the network is set up, ensure the time is set correctly, then install the system. You will be asked to set a root password as the final step:
```
nixos# systemctl 재시작 systemd-timesyncd
nixos# nixos-설치
[...]
루트 비밀번호 설정 중...
새 비밀번호: ******
새 비밀번호를 다시 입력하세요: ******
passwd: 비밀번호가 성공적으로 업데이트되었습니다.
설치 완료!
```

If there are any errors, or you mess up entering the root password, you can edit the configuration and safely re-run the command.

**Once complete, reboot the system:**
```
nixos # 재부팅
```

When the system reboots, the bootloader will come up and boot the default configuration after a short delay. Once NixOS boots, log in with the root password, and create your account, or set your user account password if you created your account in the configuration. To learn more about NixOS's configuration system, read the section in the manual on [changing the configuration](https://nixos.org/manual/nixos/stable/index.html#sec-changing-config).

#### Dual Booting

The machine is now set up to boot NixOS by default when turned on. To access the boot picker, turn off the machine, then hold the power button to turn the machine on instead of just pressing it. Let go once the options come up. To boot a particular OS once, click on it, then click Continue underneath it. To switch the default OS, click on the desired default, hold Option (Alt), then click Always Use underneath it.

#### Hypervisor Boot

By selecting the appropriate menu option in the Asahi Linux installer, you can also choose to install m1n1 without U-Boot and run U-Boot, the bootloader, and the OS under m1n1's hypervisor.

To run U-Boot under the hypervisor, start m1n1 and attach the Mac to the host PC using an appropriate USB cable, change directories to the repo, then run:

```
nixos-apple-silicon$ m1n1/bin/m1n1-run_guest --raw u-boot/m1n1-u-boot.bin
```

To access the serial console, in a separate terminal run:

```
$ nix-shell -p picocom --run 'picocom /dev/ttyACM1'
```

Downloading the kernel over USB using m1n1 is not supported.

## Maintenance

#### System Rescue

If something goes wrong and NixOS doesn't boot or is otherwise unusable, you can first try rolling back to a previous generation. Instead of selecting the default bootloader option, choose another configuration that worked previously.

If something is seriously wrong and the bootloader does not work (or you don't have any other generations), you will want to get back into the installer. To start the installer with a system installed on the internal disk, shut down the computer, re-insert the USB drive with the installer, start it up again, hit a key in U-Boot when prompted to stop autoboot, then run the command `run bootcmd_usb0`.

Once in the installer, you can re-mount your root partition and EFI system partition without reformatting them. Depending on what exactly went wrong, you might need to edit your configuration, copy over the latest Apple Silicon support module, or update U-Boot using the latest installer.

Rerunning the installer will create a new generation but not touch any user data. This means you can "undo" the installation by selecting a previous generation in the bootloader. To redo the installation without changing your root password or changing the version of Nixpkgs, run:
```
# nixos-install --no-root-password --no-channel-copy
```

In the extreme case, you can delete the EFI system partition and stub macOS install and rerun the Asahi Linux installer, then follow the steps above to reinstall NixOS's bootloader menu. You will need to regenerate the hardware configuration using `nixos-generate-config --root /mnt` because the EFI system partition's ID will change. This shouldn't modify your root partition or other NixOS configuration, but of course it's always smart to have a backup. You might also wish to re-copy the peripheral firmware files.

#### NixOS Updates

NixOS itself can be updated like any other NixOS system. In brief, this is as follows:
```
$ sudo nix-channel --update
$ sudo nixos-rebuild 스위치
```

You may have to reboot after updating in some cases. If something goes wrong, you can boot a previous generation and roll back the channel update. For more details, consult the [Upgrading section](https://nixos.org/manual/nixos/stable/index.html#sec-upgrading) of the NixOS manual.

#### Apple Silicon Support Updates

To update the Apple Silicon support module, including the Asahi kernel, U-Boot, and m1n1, you can simply download newer files from this repo under `apple-silicon-support` and place them under `/etc/nixos/apple-silicon-support`. Any changes will require a configuration rebuild and reboot to take effect. If you wish to customize your kernel, you can edit the kernel config in `/etc/nixos/apple-silicon-support/kernel/config`. Consult the comments in `/etc/nixos/apple-silicon-support/kernel/default.nix` and `/etc/nixos/apple-silicon-support/kernel/package.nix` for more details. **Note that if the kernel device trees change, U-Boot will need to be updated too.**

U-Boot and m1n1 are automatically managed by NixOS' bootloader system. If you roll back to a previous generation and things do not work properly due to a device tree incompatibility, you can run `/run/current-system/bin/switch-to-configuration switch` then reboot to force the bootloader and the correct version of U-Boot/m1n1 to be reinstalled and loaded.

If you want the Apple Silicon support module to be upgraded in tandem with NixOS instead of manually downloading new files, you can add it as a channel with the following command:
```
$ sudo nix-channel --add https://github.com/tpwrules/nixos-apple-silicon/archive/main.tar.gz apple-silicon-support
```

Modify your `/etc/nixos/configuration.nix` to reference the channel instead of the local files:
```
  수입 =
    [ # 하드웨어 스캔 결과를 포함합니다.
      ./hardware-configuration.nix
      # Apple Silicon 지원에 필요한 패키지와 구성을 포함합니다.
      <apple-silicon-support/apple-silicon-support>
    ];
```

**You can now update NixOS as normal. Note that Apple Silicon support module updates will generally require reboots to load new kernels and other boot components:**
```
$ sudo nix-channel --update
$ sudo nixos-rebuild 스위치
$ sudo 재부팅
```

#### Recovering from Boot Failure with `idevicerestore`

In extremely extreme circumstances (i.e. something messed up the firmware partition, recovery partition, or partition table), your Mac may fail to boot. On the Mac mini (and presumably Mac Studio), this state is identifiable by a flashing orange power light indicating the Morse code for SOS. On a Mac laptop, this state is identifiable by an illustration of an exclamation point in a circle on the screen with a link to Apple's website.

To make the Mac bootable again, you can use [idevicerestore](https://github.com/libimobiledevice/idevicerestore) from another Mac or Linux x86_64 or aarch64 VM or computer that has an Internet connection. You will need a USB cable with at least one USB-C end. This procedure has been tested with Mac and Linux hosts restoring a Mac mini with macOS 12.4.

Please note that this procedure may require you to unrecoverably destroy all data on the Mac's internal drive. If erasing is necessary, you will be clearly warned and asked to confirm before it happens. The drive will end up zeroed and its encryption keys (probably) regenerated, so not even the NSA will be able to save you. If you haven't made backups, make peace with yourself now.

You'll need to build `idevicerestore` from source to get a version capable of restoring Apple Silicon Macs. If Nix is already installed on your second computer, an appropriate version is already packaged in recent `nixpkgs-unstable`. **Check out and build both `idevicerestore` and `usbmuxd` (if on Linux):**

```
# 자식 클론 https://github.com/NixOS/nixpkgs/
# CD nixpkgs
# nix-build -A pkgs.idevicerestore -o idevicerestore
# nix-build -A pkgs.usbmuxd -o usbmuxd # Linux의 경우
```

To start the procedure, hook up the appropriate port on your unbootable Mac to the second computer and invoke DFU mode. This process is covered by Steps 1 and 2 of [Apple's documentation](https://support.apple.com/guide/apple-configurator-mac/revive-or-restore-a-mac-with-apple-silicon-apdd5f3c75ad/mac). We will first try what Apple calls a "revive" where the disk is not erased, although both we and `idevicerestore` still call it a "restore".

If DFU mode was started correctly, the unbootable Mac will show up on your second computer as an `Apple, Inc. Mobile Device (DFU Mode)` in `lsusb` on Linux or System Information on macOS. If you see `Apple, Inc. Apple Mobile Device [Recovery Mode]` instead (or nothing), the procedure was not followed correctly and you need to try again.

Open a terminal on your second computer and, if you are on Linux and didn't install the udev rules (which Nix did not), start `usbmuxd` in the background by running it without any arguments. Then, ask `idevicerestore` to restore the firmware by using the `--latest` flag. If you wish to erase the disk either because the revive didn't work or because you want to start with a clean slate, use the `--erase` flag also.

```
# sudo usbmuxd/bin/usbmuxd # 리눅스 전용
# sudo idevicerestore/bin/idevicerestore --latest
idevicerestore 1.0.0-불안정-2022-05-22
DFU 모드에서 장치 발견
식별된 장치는 j274ap, Macmini9,1
현재 Macmini9,1에 대해 다음 펌웨어가 서명되고 있습니다.
[...]
복원하려는 펌웨어를 선택하십시오:
```

Once `idevicerestore` detects the unbootable Mac, select the desired firmware (usually number `1`) and wait patiently while the firmware is downloaded; it's about 13GiB. If `idevicerestore` doesn't detect the unbootable Mac, make sure that your cables are hooked up correctly, that you used `sudo`, and that you are using a suitably recent version.

The restore process will automatically start once the firmware is downloaded and verified. If `idevicerestore` fails with the message `ERROR: Device did not disconnect. Possibly invalid iBEC. Reset device and try again.`, the unbootable Mac is likely not in DFU mode, or there is something wrong with your system's udev related to hotplug events. Check that you followed Apple's procedure correctly and that the appropriate USB device is detected.

After 30 seconds of messages and status updates, you should see the Apple logo on the unbootable Mac's screen with a progress bar and `idevicerestore` will tell you that it is `Waiting for device to enter restore mode...`. If the unbootable Mac resets after a couple minutes and you get the message `ERROR: Device failed to enter restore mode. Please make sure that usbmuxd is running.`, then `usbmuxd` is likely not running. Start it and try again.

Once the restore process starts, the progress bar will start moving and `idevicerestore` will spam lots of information about the process. If it fails with `ERROR: Unable to restore device`, your only choice may be to restart the process, but this time pass the `--erase` flag to `idevicerestore` and destroy all data on the unbootable Mac's internal drive.

Otherwise, wait patiently while the restore proceeds. Expect it to take 20 or 30 minutes at least. Eventually `idevicerestore` will say `DONE` and the formerly-unbootable Mac will reboot and start recovery mode (if erasing was not necessary) or the out-of-the-box wizard (if the disk was erased) and you can use it again.

Finally, shut down `usbmuxd` if on Linux and you started it manually. To clean up your second computer, remove the downloaded firmware, the `idevicerestore` and `usbmuxd` GC roots, and run the Nix garbage collector:
```
# sudo killall usbmuxd # Linux인 경우
# sudo rm -rf *.ipsw* 유니버설맥*
# rm -f 결과* usbmuxd idevicerestore
# nix-수집-쓰레기
```

## Removal

#### Host PC Cleanup

To recover the space on the host PC, change directories into the repo, remove the built symlinks (removing just the installer will recover almost all the space), then run the garbage collector:

```
nixos-apple-silicon$ rm m1n1 u-boot 설치 프로그램 결과
nixos-apple-silicon$ nix-수집-쓰레기
```

#### NixOS Uninstallation

NixOS can be completely uninstalled by deleting the stub partition, EFI system partition, and root partition off the disk.

Boot back into macOS by shutting down the machine fully, then pressing and holding the power button until the boot picker comes up. Select the macOS installation, then click Continue to boot it. Log into an administrator account and open Terminal.app.

Identify the partitions to remove. In this example, `disk0s3` is the stub because of its small size. `disk0s4` is the EFI system partition and `disk0s5` is the root partition:
```
% diskutil 목록 disk0
/dev/disk0(내부):
   #: 유형 이름 크기 식별자
   0: GUID_partition_scheme 1.0TB 디스크0
   1: Apple_APFS_ISC 524.3MB disk0s1
   2: Apple_APFS 컨테이너 disk4 900.0GB disk0s2
   3: Apple_APFS 컨테이너 disk3 2.5GB disk0s3
   4: EFI EFI - NIXOS 512.8MB disk0s4
   5: Linux 파일 시스템 91.6GB disk0s5
   6: Apple_APFS_Recovery 5.4GB disk0s6
```

**WARNING:** Unlike Linux, on macOS each partition's identifier does not necessarily equal its partition index. Double check the identifiers of your own system!

**Remove the EFI system partition and root partition:**
```
% diskutil erasureVolume free free disk0s4
disk0s4에서 삭제가 시작되었습니다(EFI - NIXOS).
디스크 마운트 해제
disk0에서 삭제가 완료되었습니다.
% diskutil erasureVolume free free disk0s5
disk0s5에서 지우기가 시작되었습니다.
디스크 마운트 해제
disk0에서 삭제가 완료되었습니다.
```

**Remove the stub partition:**
```
% diskutil apfs deleteContainer disk0s3
disk3에서 APFS 작업이 시작되었습니다.
모든 APFS 볼륨이 포함된 APFS 컨테이너 삭제
[...]
파티션 맵에서 disk0s3 제거
```

**Expand the main macOS partition to use the resulting free space. This command will take a few minutes to run; do not attempt to use the machine while it is in progress:**
```
% diskutil apfs resizeContainer disk0s2 0
APFS 작업 시작
델타 증가를 94,662,586,368바이트로 조정하고 새로운 물리적 저장소 크기를 994,662,584,320바이트로 목표로 삼았습니다.
[...]
APFS 작업 완료
```
To complete the uninstallation, open the Startup Disk pane of System Preferences and select your macOS installation as the startup disk. If this is not done, the next boot will fail, and you will be asked to select another OS to boot from.

<h3 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/128645111-b2a92dd2-f246-4df0-b05c-5b0ffce05448.png">
  <br />
  NixOS with the Plasma Desktop
</h3>

### Debian Linux Development

**Most of the hard work, including the kernel and boot software, was done by the [Asahi Linux project](https://asahilinux.org/) and their development team.**

While you will end up with a fairly usable computer, the exact hardware features you want [may not be ready yet](https://github.com/AsahiLinux/docs/wiki/%22When-will-Asahi-Linux-be-done%3F%22). Please look at the [Asahi Linux Feature Support page](https://github.com/AsahiLinux/docs/wiki/Feature-Support) for information. 

For more general information about Linux on Apple Silicon Macs, refer to the [Asahi Linux project](https://asahilinux.org/) and [alpha installer release](https://asahilinux.org/2022/03/asahi-linux-alpha-release/). 

**Important Note:** Starting from mid-2022, the best advice for getting Debian installed is to be found here: **https://git.zerfleddert.de/cgi-bin/gitweb.cgi/m1-debian/.**

#### Artefacts

**If you don't want to use the prebuild artefacts, you can build them yourself using the following scripts:**

   - **prepare_rust.sh** - Prepares a rust installation suitable for kernel compilation
   - **m1n1_uboot_kernel.sh** - Builds m1n1, u-boot and the kernel including gpu support.
   - **mesa.sh** - Creates mesa packages
   - **bootstrap.sh** - Creates Debian root and live filesystem
   - **meta.sh** - Meta package which makes sure that we always get latest and gratest kernel.
    
    
#### Asahi installer

**[Video Recording](https://tg.st/u/debian_asahi_installer.mp4)**

   Poweroff your Mac. Hold and press the power button until you see a wheel chain and Options written below. **Approx 20 seconds**.

   In the boot picker, choose Options. Once loaded, open a Terminal under Utilities > Terminal

   **Run the asahi installer and select Debian:**

   ```curl -sL https://tg.st/d | sh```

  **설치 프로그램 지침을 따르세요.**

  **데비안이 부팅되면 비밀번호 없이 루트로 로그인하고 루트 비밀번호를 설정하세요.**

   ```passwd```
   
   ```pwconv```

  **wpa_supplicant.conf를 편집하여 Wi-Fi를 구성하고, 인터페이스를 활성화하고, 부팅 중에 활성화하려면 Allow-hotplug 전에 #을 제거하세요.**

   ```vi /etc/wpa_supplicant/wpa_supplicant.conf```
   
   ```ifup wlan0```
   
   ```vi /etc/network/interfaces```

   **Reboot to see if grub was correctly installed**

   ```reboot```

   **블랙박스 등 데스크톱 환경 설치**

   ```apt-get update```
   
   ```apt-get install -y xinit blackbox xterm firefox-esr lightdm```

  **권한 없는 사용자를 생성하세요**

   ```useradd -m -c 'Firstname Lastname' -s /bin/bash <username>```
   
   ```passwd <username>```

   **선택적으로 SSHD를 설치합니다. 루트로 로그인할 수 없으며 권한이 없는 사용자로만 로그인할 수 있습니다**

   ```apt update```
   
   ```apt install -y openssh-server```

   다른 흥미로운 작업을 수행하는 방법을 알아보려면 **[/root/quickstart.txt](https://git.zerfleddert.de/cgi-bin/gitweb.cgi/m1-debian/blob_plain/refs/heads/master:/files/quickstart.txt)** 파일을 참조하세요.
    
   <h3 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/222395704-be1d4f1b-498e-484e-9035-e7758f784aef.png">
  <br />
  데비안
</h3>

이미지 출처: [Alyssa Rosenzweig](https://social.treehouse.systems/@alyssa)

### 우분투 개발

* **[Ubuntu Apple Silicon 이미지](https://github.com/tobhe/ubuntu-asahi)**

**커널 및 부팅 소프트웨어를 포함한 대부분의 노력은 [Asahi Linux 프로젝트](https://asahilinux.org/) 및 해당 개발팀에서 수행했습니다.**

상당히 유용한 컴퓨터를 갖게 되겠지만 원하는 정확한 하드웨어 기능은 [아직 준비되지 않았을 수 있습니다](https://github.com/AsahiLinux/docs/wiki/%22When-will-Asahi-Linux-be-done%3F%22). 자세한 내용은 [Asahi Linux 기능 지원 페이지](https://github.com/AsahiLinux/docs/wiki/Feature-Support)를 참조하세요.

Apple Silicon Mac의 Linux에 대한 일반적인 정보는 [Asahi Linux 프로젝트](https://asahilinux.org/) 및 [알파 설치 프로그램 릴리스](https://asahilinux.org/2022/03/asahi-linux-alpha-release/)를 참조하세요.

#### 설치 프로그램

**사전 빌드된 이미지를 설치하려면 다음을 실행하세요.**

```
curl -sL https://tobhe.de/ubuntu/install > install.sh	# Download
less install.sh						# Review
sh install.sh						# Run
```

설치 프로그램은 다양한 Ubuntu 릴리스 및 빌드 구성을 선택할 수 있도록 제공합니다.

**현재 지원되는 항목은 다음과 같습니다.**

  * 우분투 22.10 데스크탑
  * 우분투 22.10 서버
  * 우분투 22.04 데스크탑
  * 우분투 22.04 서버

기본 **사용자 이름과 비밀번호는 모두 ```ubuntu```입니다.** 루트 액세스는 ```sudo```를 통해 달성할 수 있습니다.


### macOS 및 Linux 듀얼 부팅

예, 설치 프로그램은 원하는 대로 macos 파티션의 크기를 자동으로 조정하고 여유 공간에 Ubuntu를 설치할 수 있습니다. macOS 제거는 시스템 펌웨어를 업데이트해야 하기 때문에 현재 지원되지 않습니다.

### 건물

사전 구축된 디스크 이미지를 사용하지 않으려면 아래 지침에 따라 직접 구축할 수 있습니다.

```
# Install dependencies
sudo apt-get install arch-install-scripts debootstrap mtools parted gnupg eatmydata rsync git squashfs-tools zip

# Install dependencies, if your builder system is NOT arm64
sudo apt-get install binfmt-support qemu qemu-user-static
````
#### 짓다

```
cd ubuntu-asahi
# Build the entire live image
sudo ./build-generic.sh
```
라이브 GPT 이미지 파일은 ```build/ubuntu.live.img```로 출력되고, Asahi Linux 설치 프로그램의 zip 아카이브는 ```build/ubuntu.live.img.zip```로 출력됩니다.

#### 깨끗한

clean.sh 스크립트는 debootstrap이 debs를 캐시하는 데 사용하는 캐시 폴더를 제외한 빌드 폴더를 정리합니다.

```
cd ubuntu-asahi
# Clean the build folder
./clean.sh
```


# Apple Silicon에서 Windows 10/11 실행
[맨 위로 돌아가기](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

[![Mac의 Windows 11 ARM? Parallels 대 VMware 대 UTM](https://ytcards.demolab.com/?id=lsik-eGJIog&lang=en&background_color=%230d1117&title_color=%23ffffff&stats_color=%23dedede&width=240 "Mac의 Windows 11 ARM? Parallels 대 VMware 대 UTM")](https://www.youtube.com/watch?v=lsik-eGJIog)
[![VMware가 마침내 Mac에서 게임을 할 수 있게 됐습니다. 그리고.. 무료인가요?](https://ytcards.demolab.com/?id=Mqn1yoV_OW4&lang=en&background_color=%230d1117&title_color=%23ffffff&stats_color=%23dedede&width=240 "VMware가 마침내 Mac에서 게임을 할 수 있게 됐습니다. 그리고.. 무료인가요?")](https://www.youtube.com/watch?v=Mqn1yoV_OW4)
[![Mac의 Windows가 더욱 좋아졌습니다.](https://ytcards.demolab.com/?id=Ar4kx13TxBo&lang=en&background_color=%230d1117&title_color=%23ffffff&stats_color=%23dedede&width=240 "Mac의 Windows가 더욱 좋아졌습니다.")](https://www.youtube.com/watch?v=Ar4kx13TxBo)
[![UTM VM 앱을 사용하여 Mac에 Windows 11을 무료로 설치하는 방법](https://ytcards.demolab.com/?id=5Z_G6QG7xxg&lang=en&background_color=%230d1117&title_color=%23ffffff&stats_color=%23dedede&width=240 "UTM VM 앱을 사용하여 Mac에 Windows 11을 무료로 설치하는 방법")](https://www.youtube.com/watch?v=5Z_G6QG7xxg)
[![Mac M1/M2 Pro세서에 Windows 11을 무료로 설치하는 방법(UTM)](https://ytcards.demolab.com/?id=b_hGkl9CSbM&lang=en&background_color=%230d1117&title_color=%23ffffff&stats_color=%23dedede&width=240 "Mac M1/M2 Pro세서에 무료로 Windows 11을 설치하는 방법(UTM)")](https://www.youtube.com/watch?v=b_hGkl9CSbM)

[Parallels Desktop for Mac](https://www.parallels.com/products/desktop/)은 MacBook, MacBook Pro, iMac, iMac Pro, Mac mini 또는 Mac Pro에서 Windows를 macOS와 함께(다시 시작할 필요 없이) 실행할 수 있게 해주는 프로그램입니다. 파일과 폴더를 공유하고, 이미지와 텍스트를 복사하여 붙여넣고, Mac과 Windows 응용 프로그램 간에 파일을 끌어서 놓으세요.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/110880057-df697a80-8292-11eb-8484-9bbc02592377.jpg">
<br />
Mac용 패러렐즈 데스크톱
</p>

[UTM](https://getutm.app/)은 iOS 및 macOS용 모든 기능을 갖춘 시스템 에뮬레이터이자 가상 머신 호스트입니다. Mac, iPhone, iPad에서 Windows, Linux 등을 실행할 수 있는 [QEMU](https://www.qemu.org/)를 기반으로 합니다.

 - [iOS/iPadOS용 UTM(SE)](https://getutm.app/install/)
 
 - [macOS용 UTM](https://mac.getutm.app/)
 
 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/164793030-07cba054-33e2-4251-9be6-1f1c71851df6.png">
  <br />
 UTM의 Windows 11
</p>
 
[VMware Fusion](https://blogs.vmware.com/teamfusion/2022/07/just-released-vmware-fusion-22h2-tech-preview.html)은 Mac 컴퓨터용으로 VMware에서 개발한 소프트웨어 하이퍼바이저입니다. 가상 머신을 생성하고 해당 가상 머신 내에 운영 체제(예: Windows 또는 Linux)를 설치합니다.

  * Intel 및 Apple Silicon 기반 Windows 11, 2D 그래픽 및 네트워킹 지원.
  * M1 기반 Mac에서 Windows 11 게스트 운영 체제에 대한 VMTools 설치를 지원합니다.
  * 빠른 암호화를 지원하는 가상 TPM 장치.
  * M1의 Linux 지원이 향상되었습니다.
  * Linux 가상 머신의 3D 그래픽 HW 가속 및 OpenGL 4.3(Linux 5.19+ 및 Mesa 22.1.3+ 필요).
  * Apple Silicon 및 Intel Mac용 범용 바이너리.
  
<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/182049352-b899b356-57c0-4ec0-8fb1-ff394a1f6403.png">
  <br />
 VMware Fusion의 Windows 11
</p>

[ARM64EC(“에뮬레이션 호환”)](https://docs.microsoft.com/en-us/windows/uwp/porting/arm64ec)은 기본 속도로 실행되고 x64 아키텍처와 상호 운용 가능한 ARM 기반 Windows 11용 새로운 ABI(애플리케이션 바이너리 인터페이스)입니다. 앱, 프로세스 또는 모듈도 필요에 따라 ARM64EC 및 x64와 자유롭게 혼합하고 일치시킬 수 있습니다. 앱의 ARM64EC 코드는 기본적으로 실행되지만 모든 x64 코드는 ARM의 내장 에뮬레이션에서 Windows 11을 사용하여 실행됩니다. ARM64EC ABI는 x64 코드와 바이너리 호환되도록 만드는 방식에서 현재 [ARM64 ABI](https://docs.microsoft.com/en-us/cpp/build/arm64-windows-abi-conventions?view=msvc-160)와 약간 다릅니다. 특히 ARM64EC ABI는 호출 규칙, 스택 사용 및 데이터 정렬을 포함한 x64 소프트웨어 규칙을 따르므로 ARM64EC와 x64가 상호 운용 가능합니다. ARM64EC로 빌드된 앱에는 x64 코드가 포함될 수 있지만 반드시 그럴 필요는 없습니다. ARM64EC는 자체적으로 완벽한 Windows용 일류 ABI이기 때문입니다.

<h3 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124997795-20cf2400-e000-11eb-8954-4944286b8ea8.png">
  윈도우 11 데스크탑
</h3>

<h3 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/120387363-a9aabf80-c2de-11eb-84a5-8e4b422e7546.png">
  윈도우 10 데스크탑
</h3>

# 게임 개발
[맨 위로 돌아가기](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/97361059-45151700-185c-11eb-9d12-dae51c79eb8a.png">
  <br />
</p>

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/119279021-ea6b5000-bbdd-11eb-9f59-5251fc3ac751.png">
  <br />
</p>

## 게임 엔진

**[Unity 엔진 확인](https://unity.com/)**

<img src="https://user-images.githubusercontent.com/45159366/104788113-3432be00-5746-11eb-99b1-49360669f327.png">

**[Unreal Engine 확인](https://www.unrealengine.com/)**

<img src="https://user-images.githubusercontent.com/45159366/104788122-37c64500-5746-11eb-8f61-48a69b94582d.png">


**[Godot 엔진 확인](https://godotengine.org/)**

[Godot 프로젝트에 기부하고 싶다면](https://www.patreon.com/godotengine)

<img src="https://user-images.githubusercontent.com/45159366/104788134-3f85e980-5746-11eb-94c4-d97165ee888b.jpeg">


**[체크아웃 블렌더](https://www.blender.org/)**

[블렌더 프로젝트에 기부하고 싶다면](https://fund.blender.org/)

<img src="https://user-images.githubusercontent.com/45159366/104788139-401e8000-5746-11eb-9647-058dee01a00e.png">


**[Game Maker Studio 2 확인](https://www.yoyogames.com/gamemaker)**

<img src="https://user-images.githubusercontent.com/45159366/104788147-44e33400-5746-11eb-879a-bc6239c98ce4.jpg">


## 게임 개발 학습 리소스

[Unreal Online Learning](https://www.unrealengine.com/en-US/onlinelearning-courses)은 실습 동영상 강좌와 안내식 학습 경로를 제공하는 무료 학습 플랫폼입니다.

[Unreal Engine 공인 교육 프로그램](https://www.unrealengine.com/en-US/training-partners)

[교육용 언리얼 엔진](https://www.unrealengine.com/en-US/education/)

[언리얼 엔진 교육 및 시뮬레이션](https://www.unrealengine.com/en-US/industry/training-simulation)

[Unity 인증](https://unity.com/products/unity-certifications)

[게임용 Autodesk](https://www.autodesk.com/campaigns/autodesk-for-games)

[DirectX 12 Ultimate 시작하기](https://devblogs.microsoft.com/directx/directx-12-ultimate-getting-started-guide/)

[Vulkan 시작하기](https://www.khronos.org/vulkan/)

[Apple Metal 시작하기](https://developer.apple.com/metal/)

[Udemy의 게임 디자인 온라인 강좌](https://www.udemy.com/courses/Design/Game-Design/)

[Skillshare의 게임 디자인 온라인 강좌](https://www.skillshare.com/browse/game-design)

[edX의 온라인 강좌 및 수업으로 게임 디자인 배우기](https://www.edx.org/learn/game-design)

[Coursera의 게임 디자인 과정](https://www.coursera.org/courses?query=game%20design)

[Coursera의 게임 디자인 및 개발 전문 과정](https://www.coursera.org/specializations/game-development)

## 게임 개발 도구

[Unreal Engine](https://www.unrealengine.com)은 Epic Games가 세계에서 가장 개방적이고 진보된 실시간 3D 제작 도구를 사용하여 개발한 게임 엔진입니다. 최첨단 게임 엔진이라는 원래 목적을 달성하기 위해 지속적으로 발전하고 있는 이 엔진은 오늘날 업계 전반의 제작자에게 최첨단 콘텐츠, 대화형 경험 및 몰입형 가상 세계를 제공할 수 있는 자유와 제어권을 제공합니다.

[Unity](https://unity.com)는 크로스 플랫폼 게임 개발 플랫폼입니다. Unity를 사용하여 고품질 3D 및 2D 게임을 구축하고 모바일, 데스크톱, VR/AR, 콘솔 또는 웹에 배포하고 충성도가 높고 열정적인 플레이어 및 고객과 소통하세요.

[Unigine](https://unigine.com)은 대화형 3D 앱을 작업하는 개발팀(C++/C# 프로그래머, 3D 아티스트)을 위해 설계된 크로스 플랫폼 게임 엔진입니다.

[Panda3D](https://www.panda3d.org/)는 Disney와 CMU가 개발한 Python 및 C++ 프로그램용 3D 렌더링 및 게임 개발을 위한 프레임워크인 게임 엔진입니다. Panda3D는 오픈 소스이며 상업적인 벤처를 포함하여 어떤 목적으로도 무료입니다.

[Havok](https://www.havok.com/)은 현실적인 물리 엔진 구성요소와 비디오 게임 관련 기능을 제공하는 미들웨어 소프트웨어 제품군입니다. Nintendo Switch, PlayStation®, Stadia 및 Xbox를 포함한 모든 주요 플랫폼에서 지원되고 최적화되었습니다. Unity 및 Unreal Engine에 대한 통합과 함께 수많은 독점 게임 엔진에 사용됩니다.

[AutoDesk 3ds Max](https://www.autodesk.com/products/3ds-max/overview)는 3D 모델링, 애니메이션, 렌더링 및 시각화를 위한 전문 소프트웨어 프로그램입니다. 3ds Max를 사용하면 놀라운 게임 환경, 디자인 시각화 및 가상 현실 경험을 만들 수 있습니다.

[Houdini](https://www.sidefx.com/)는 영화, TV, 광고 및 비디오 게임 파이프라인의 모델링, 리깅, 애니메이션, VFX, 룩 개발, 조명 및 렌더링을 위한 3D 절차적 소프트웨어입니다.

[A-Frame](https://aframe.io)은 HTML 및 Entity-Component를 사용하여 WebVR에서 가상 현실 경험을 구축하기 위한 웹 프레임워크입니다. A-Frame은 Vive, Rift, 데스크톱, 모바일 플랫폼에서 작동합니다.

[AppGameKit](https://www.appgamekit.com)은 애호가 및 인디 개발자에게 이상적인 강력한 게임 개발 엔진입니다. 배우기 쉬운 AppGameKit BASIC에서 코딩을 시작하거나 C++ 및 Xcode의 라이브러리를 사용할 수 있습니다.

[Blender](https://www.blender.org)는 무료 오픈 소스 3D 제작 제품군입니다. 모델링, 리깅, 애니메이션, 시뮬레이션, 렌더링, 합성 및 모션 추적, 비디오 편집, 2D 애니메이션 파이프라인 등 3D 파이프라인 전체를 지원합니다.

[GameMaker Studio 2](https://www.yoyogames.com/gamemaker)는 GameMaker의 최신이자 최고의 화신입니다. 여기에는 아이디어를 개념부터 완성된 게임까지 가져오는 데 필요한 모든 것이 포함되어 있습니다. 진입 장벽이 없고 강력한 기능을 갖춘 GameMaker Studio 2는 최고의 2D 개발 환경입니다.

[Godot](https://godotengine.org)은 통합 인터페이스에서 2D 및 3D 게임을 만들 수 있는 기능이 가득한 크로스 플랫폼 게임 엔진입니다. 포괄적인 공통 도구 세트를 제공하므로 사용자는 바퀴를 다시 만들 필요 없이 게임 제작에 집중할 수 있습니다. 한 번의 클릭으로 주요 데스크톱 플랫폼(Linux, macOS, Windows)은 물론 모바일(Android, iOS) 및 웹 기반(HTML5) 플랫폼을 포함한 다양한 플랫폼으로 게임을 내보낼 수 있습니다.

[개방형 컴퓨팅 언어(OpenCL)](https://www.khronos.org/opencl/)는 슈퍼컴퓨터, 클라우드 서버, 개인용 컴퓨터, 모바일 장치 및 임베디드 플랫폼에 사용되는 CPU, GPU 및 기타 하드웨어 가속기로 구성된 이기종 플랫폼의 [병렬 프로그래밍](https://www.coursera.org/lecture/parprog1/introduction-to-parallel-computing-zNrIS)에 대한 개방형 표준입니다.

[OpenGL Shading Language(GLSL)](https://www.khronos.org/opengl/wiki/Core_Language_(GLSL))은 C 스타일 언어를 기반으로 하는 고급 셰이딩 언어이므로 사용자가 해당 언어에서 기대하는 대부분의 기능을 다룹니다.  GLSL에는 스위치 문을 포함하여 제어 구조(for-loop, if-else 문 등)가 존재합니다.

[HLSL(High Level Shading Language)](https://docs.microsoft.com/en-us/windows/win32/direct3dhlsl/dx-graphics-hlsl)은 DirectX용 고급 셰이딩 언어입니다. HLSL을 사용하면 사용자는 Direct3D 파이프라인을 위한 C와 유사한 프로그래밍 가능 셰이더를 만들 수 있습니다. HLSL은 프로그래밍 가능한 3D 파이프라인을 설정하기 위해 DirectX 9로 처음 만들어졌습니다.

[Vulkan](https://www.khronos.org/vulkan/)은 PC 및 콘솔부터 휴대폰 및 임베디드 플랫폼에 이르기까지 다양한 장치에 사용되는 최신 GPU에 대한 고효율의 크로스 플랫폼 액세스를 제공하는 최신 크로스 플랫폼 그래픽 및 컴퓨팅 API입니다. Vulkan은 현재 Khronos 컨소시엄에서 개발 중입니다.

[Metal](https://developer.apple.com/metal/)은 iOS, iPadOS, macOS, watchOS 및 tvOS와 같은 Apple 플랫폼에서 2D 및 3D 그래픽을 렌더링하는 데 사용되는 하위 수준 GPU 프로그래밍 프레임워크입니다.

[MoltenVK](https://moltengl.com/moltenvk)는 Apple의 [Metal](https://developer.apple.com/metal/) 그래픽 프레임워크를 사용하여 iOS 및 macOS에서 실행되는 Vulkan의 구현입니다.

[MoltenGL](https://moltengl.com)은 Apple의 [Metal](https://developer.apple.com/metal/) 그래픽 프레임워크에서 실행되는 OpenGL ES 2.0 API의 구현입니다.

[Mesa 3D 그래픽 라이브러리](https://docs.mesa3d.org/index.html)는 OpenGL 사양의 오픈 소스 구현으로 시작된 프로젝트입니다. 대화형 3D 그래픽을 렌더링하기 위한 시스템입니다. Mesa는 [직접 렌더링 인프라](https://dri.freedesktop.org/), [X.org](https://x.org/) 및 [Wayland](https://wayland.freedesktop.org/)와 같은 여러 다른 오픈 소스 프로젝트와 연결되어 Linux, FreeBSD 및 기타 운영 체제에서 OpenGL 지원을 제공합니다.

[OpenCL](https://www.khronos.org/opencl/)은 CPU, GPU, DSP, FPGA 및 기타 프로세서나 하드웨어 가속기로 구성된 이기종 플랫폼에서 실행되는 프로그램을 작성하기 위한 프레임워크입니다.

[VDPAU](https://www.freedesktop.org/wiki/Software/VDPAU/)는 UNIX용 비디오 디코드 및 프레젠테이션 API입니다. 이는 최신 GPU에 있는 비디오 디코드 가속 및 프레젠테이션 하드웨어에 대한 인터페이스를 제공합니다.

[VA API](https://freedesktop.org/wiki/Software/vaapi/)는 비디오 처리를 위한 그래픽 하드웨어 가속 기능에 대한 액세스를 제공하는 오픈 소스 라이브러리 및 API 사양입니다.

[XvMC](https://en.wikipedia.org/wiki/X-Video_Motion_Compensation)는 X 윈도우 시스템용 X 비디오 확장(Xv)의 확장입니다. XvMC API를 사용하면 비디오 프로그램이 비디오 디코딩 프로세스의 일부를 GPU 하드웨어로 오프로드할 수 있습니다.

[AMD Radeon ProRender](https://www.amd.com/en/technologies/radeon-prorender)는 창의적인 전문가가 12개 이상의 주요 디지털 콘텐츠 제작 및 CAD 애플리케이션에서 거의 모든 GPU, CPU 및 OS에서 놀랍도록 사실적인 이미지를 생성할 수 있도록 지원하는 강력한 물리 기반 렌더링 엔진입니다.

[NVIDIA Omniverse](https://developer.nvidia.com/nvidia-omniverse-platform)는 Pixar의 Universal Scene Description 및 NVIDIA RTX를 기반으로 하는 3D 제작 파이프라인을 위한 강력한 다중 GPU, 실시간 시뮬레이션 및 협업 플랫폼입니다.

[LibGDX](https://github.com/libgdx/libgdx)는 Windows, Linux, Mac OS X, Android, WebGL 지원 브라우저 및 iOS에서 작동하는 OpenGL(ES) 기반의 크로스 플랫폼 Java 게임 개발 프레임워크입니다.

[cocos2d-x](https://github.com/cocos2d/cocos2d-x)는 2D 게임, 대화형 책, 데모 및 기타 그래픽 애플리케이션을 구축하기 위한 다중 플랫폼 프레임워크입니다. cocos2d-iphone을 기반으로 하지만 Objective-C 대신 C++를 사용합니다. iOS, Android, macOS, Windows 및 Linux에서 작동합니다.

[MonoGame](https://github.com/MonoGame/MonoGame)은 강력한 크로스 플랫폼 게임을 만들기 위한 프레임워크입니다. 데스크탑, 모바일, 콘솔 플랫폼 전반에 걸쳐 수천 개의 타이틀이 출시된 XNA의 정신적 후속작입니다. MonoGame은 블랙박스가 없는 완전 관리형 .NET 오픈 소스 게임 프레임워크입니다.

[Three.js](https://threejs.org)는 WebGL을 사용하여 웹 브라우저에서 애니메이션 3D 컴퓨터 그래픽을 생성하고 표시하는 데 사용되는 크로스 브라우저 JavaScript 라이브러리 및 애플리케이션 프로그래밍 인터페이스입니다.

[Superpowers](http://superpowers-html5.com/)는 실시간 공동 프로젝트를 위한 다운로드 가능한 HTML5 앱입니다. 일반 오프라인 게임 제작자처럼 단독으로 사용할 수도 있고, 비밀번호를 설정하고 친구들이 웹 브라우저를 통해 프로젝트에 참여하도록 할 수도 있습니다.

[URHO3D](https://urho3d.github.io/)는 C++로 구현되고 MIT 라이센스에 따라 출시된 무료 경량 크로스 플랫폼 2D 및 3D 게임 엔진입니다. OGRE와 Horde3D에서 큰 영감을 받았습니다.

[Vivox](https://www.vivox.com/)는 Fortnite, PUBG, League of Legends, Rainbow Six Siege 등 세계 최대 게임 브랜드와 타이틀이 신뢰하는 음성 및 텍스트 채팅 플랫폼입니다.

[HGIG](https://www.hgig.org/)는 HDR에서 소비자 게임 경험을 개선하기 위한 공개 지침을 지정하고 제공하기 위해 모이는 게임 및 TV 디스플레이 업계 기업의 자원 봉사 그룹입니다.

[GameBlocks](https://www.gameblocks.com/)는 서버측 치트 방지 및 미들웨어 소프트웨어입니다.

## 증강 현실(AR) 및 가상 현실(VR)

[ARKit](https://developer.apple.com/augmented-reality/arkit/)은 개발자가 Apple에서 개발한 iOS용 증강 현실 앱을 구축할 수 있도록 지원하는 소프트웨어 개발 도구 세트입니다. 최신 버전 ARKit 3.5는 iPad Pro(2020)의 새로운 LiDAR 스캐너와 깊이 감지 시스템을 활용하여 향상된 장면 이해 및 객체 폐색을 위해 장면 기하학을 사용하는 차세대 AR 앱을 지원합니다.

[RealityKit](https://developer.apple.com/documentation/realitykit)은 ARKit 프레임워크에서 제공하는 정보를 사용하여 고성능 3D 시뮬레이션 및 렌더링을 구현하여 가상 객체를 현실 세계에 원활하게 통합하는 프레임워크입니다.

[SceneKit](https://developer.apple.com/scenekit/)은 iOS 앱에서 3D 애니메이션 장면과 효과를 만드는 데 도움이 되는 고급 3D 그래픽 프레임워크입니다.

[ARCore](https://developers.google.com/ar/)는 현실 세계에서 증강 현실 애플리케이션을 허용하기 위해 Google에서 개발한 소프트웨어 개발 키트입니다. 이러한 도구에는 장치가 수평 및 수직 표면과 평면을 감지할 수 있도록 하는 환경 이해가 포함됩니다. 또한 휴대폰이 세계를 기준으로 자신의 위치를 ​​이해하고 추적할 수 있게 해주는 모션 추적도 포함되어 있습니다. 또한 ARCore의 Light Estimation API를 사용하면 디지털 객체가 실제로 물리적 세계의 일부인 것처럼 현실적으로 나타날 수 있습니다.

[OpenVR](https://github.com/ValveSoftware/openvr)은 애플리케이션이 대상 하드웨어에 대한 특정 지식을 갖고 있지 않아도 여러 공급업체의 VR 하드웨어(Steam Index, HTC Vive 및 Oculus Rift)에 액세스할 수 있게 해주는 API 및 런타임입니다.

[Steam의 OpenVR 벤치마크](https://store.steampowered.com/app/955610/OpenVR_Benchmark/)는 VR 헤드셋 내부에서 렌더링하여 실제 VR 성능을 재현 가능하게 테스트하기 위한 최초의 벤치마크 도구입니다.

[OpenHMD](http://www.openhmd.net/)는 Oculus Rift, HTC Vive, Sony PSVR 등과 같은 다양한 HMD(헤드 마운트 디스플레이) 장치를 지원하는 오픈 소스 API 및 드라이버입니다.

[openXR](https://www.khronos.org/OpenXR/)은 AR(증강 현실) 및 VR(가상 현실), 통칭 XR(플랫폼 및 장치)에 대한 고성능 액세스를 제공하는 무료 개방형 표준입니다.

[Monado](https://monado.dev/)는 GNU/Linux용 최초의 OpenXR™ 런타임입니다. Monado는 오픈 소스 XR 생태계의 개발을 시작하고 장치 공급업체가 GNU/Linux 플랫폼을 대상으로 하는 기본 구성 요소를 제공하는 것을 목표로 합니다.

[Libsurvive](https://github.com/cntools/libsurvive)는 완전한 오픈 소스이며 모든 장치에서 실행할 수 있는 Lighthouse 및 Vive 기반 시스템에서 6 자유도 추적을 가능하게 하는 도구 및 라이브러리 세트입니다. 현재 SteamVR 1.0 및 SteamVR 2.0 세대 장치를 모두 지원하며 상업적으로 사용 가능한 모든 추적 개체를 지원해야 합니다.

[Simula](https://github.com/SimulaVR/Simula)는 Godot 위에서 실행되는 Linux용 VR 창 관리자입니다. 설치하는데 1분도 채 걸리지 않습니다. Simula는 Linux 드라이버(예: HTC Vive, HTC Vive Pro, Valve Index)가 장착된 SteamVR 헤드셋과 공식적으로 호환됩니다. 또한 Monado 드라이버(예: North Star, OSVR HDK 및 PSVR)가 있는 OpenXR 헤드셋에 실험적인 지원을 추가했습니다. 어떤 사람들은 OpenHMD를 통해 Simula를 실행하기 위해 Oculus Rift S를 구입했습니다([여기 참조](https://github.com/OpenHMD/OpenHMD/issues/225#issuecomment-638454156)).

# 전문 오디오/비디오 개발
[맨 위로 돌아가기](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/100922475-caf73400-3492-11eb-88ac-d0976f3057d3.png">
  <br />
</p>

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/119560582-f62f5180-bd58-11eb-842b-fcf4330f3e2f.png">
  <br />
</p>

## 오디오/비디오 학습 리소스

[좋은 비디오와 나쁜 비디오의 차이를 만드는 10가지 비디오 제작 도구 - Dann Albright ](https://www.uscreen.tv/blog/video-production-equipment/)

[Skillshare의 온라인 오디오 편집 수업](https://www.skillshare.com/browse/audio-editing)

[온라인 영상 편집 수업 Skillshare](https://www.skillshare.com/search?query=Video-Editing)

[Udemy의 동영상 편집 강좌](https://www.udemy.com/topic/video-editing/)

[udemy의 오디오 편집 강좌](https://www.udemy.com/topic/audio-editing/)

[Coursera의 비디오 편집 강좌](https://www.coursera.org/courses?query=video%20editing)

[Coursera의 오디오 편집 기본 사항](https://www.coursera.org/lecture/vocal-production/basic-audio-editing-6JLBJ)

[Audacity 팟캐스트 제작 과정: 팟캐스터를 위한 오디오 편집](https://www.thepodcasthost.com/academy/course-library/audacity-course/)

[LinkedIn Learning의 동영상 편집 온라인 교육 과정](https://www.linkedin.com/learning/topics/video-editing)

[LinkedIn Learning의 오디오 편집 온라인 교육 과정](https://www.linkedin.com/learning/topics/audio-editing)

## 오디오/비디오 도구 및 장비

[H.264(AVC)](https://en.wikipedia.org/wiki/H.264/MPEG-4_AVC)은 최대 8K를 지원하는 여러 프로필(도구) 및 수준(최대 비트 전송률 및 해상도)을 정의하는 블록 지향 및 동작 보상 정수 DCT 코딩을 기반으로 하는 비디오 압축 표준입니다.

[H.265(HEVC)](https://en.wikipedia.org/wiki/High_Efficiency_Video_Coding)은 H.264(AVC)의 후속 비디오 압축 표준입니다. 동일한 비디오 품질 수준에서 25%~50% 더 나은 데이터 압축을 제공하거나 동일한 비트 전송률에서 향상된 비디오 품질을 제공합니다.

[FFmpeg](https://ffmpeg.org)는 인간과 기계가 만든 거의 모든 것을 디코딩, 인코딩, 트랜스코딩, 다중화, 역다중화, 스트리밍, 필터링 및 재생할 수 있는 선도적인 멀티미디어 프레임워크입니다. Windows, macOS 및 Linux와 같은 여러 플랫폼에서 최첨단 형식까지 가장 모호한 고대 형식을 지원합니다.

[HandBrake](https://handbrake.fr/)는 널리 지원되는 코덱을 선택하여 거의 모든 형식의 비디오를 트랜스코딩하는 도구입니다. Window, macOS, Linux에서 지원됩니다.

[HTTP 라이브 스트리밍(HLS)](https://developer.apple.com/streaming/)은 라이브 및 주문형 오디오 및 비디오를 iPhone, iPad, Mac, Apple Watch, Apple TV 및 PC로 보내는 Apple에서 개발한 통신 프로토콜입니다.

[DASH(Dynamic Adaptive Streaming over HTTP)](https://developer.mozilla.org/en-US/docs/Web/HTML/DASH_Adaptive_Streaming_for_HTML_5_Video)는 비디오 재생을 유지하기 위해 네트워크 성능에 따라 비디오 스트림이 비트 전송률 간에 전환할 수 있도록 하는 적응형 스트리밍 프로토콜입니다.

[OpenMAX™](https://www.khronos.org/openmax/)은 가속 멀티미디어 구성 요소를 여러 운영 체제와 실리콘 플랫폼에서 개발, 통합 및 프로그래밍할 수 있도록 하여 포괄적인 스트리밍 미디어 코덱과 애플리케이션 이식성을 제공하는 크로스 플랫폼 API입니다.

[GStreamer](https://gstreamer.freedesktop.org/)는 미디어 처리 구성 요소의 그래프를 구성하기 위한 라이브러리입니다. 지원하는 애플리케이션은 단순한 Ogg/Vorbis 재생, 오디오/비디오 스트리밍부터 복잡한 오디오(믹싱) 및 비디오(비선형 편집) 처리까지 다양합니다. 애플리케이션은 코덱 및 필터 기술의 발전을 투명하게 활용할 수 있습니다.

[미디어 소스 확장(MSE)](https://www.w3.org/TR/media-source/)은 JavaScript가 HTML5 비디오 및 오디오를 지원하는 웹 브라우저 내의 미디어 코덱에 바이트 스트림을 보낼 수 있도록 하는 [W3C 사양](https://github.com/w3c/media-source)입니다. 또한 이를 통해 완전히 JavaScript로 미디어 스트리밍을 위한 클라이언트측 프리패치 및 버퍼링 코드를 구현할 수 있습니다.

[WebRTC](https://webrtc.org/)는 개방형 표준을 기반으로 작동하는 애플리케이션에 실시간 통신 기능을 추가하는 오픈 소스 프로젝트입니다. 피어 간에 전송되는 비디오, 음성 및 일반 데이터를 지원하므로 개발자는 강력한 음성 및 비디오 통신 솔루션을 구축할 수 있습니다.

[Apple ProRes](https://support.apple.com/en-us/HT200321)는 Final Cut Pro의 고품질, 고성능 편집을 위해 Apple이 개발한 코덱 기술로, 최대 8K를 지원합니다.

[Premiere Pro](https://www.adobe.com/products/premiere.html)는 영화, TV, 웹을 위한 업계 최고의 비디오 편집 소프트웨어입니다. 창의적인 도구, 다른 앱 및 서비스와의 통합, Adobe Sensei의 강력한 기능을 통해 영상을 세련된 영화와 비디오로 제작할 수 있습니다. [Premiere Rush](https://www.adobe.com/products/premiere-rush.html)를 사용하면 모든 기기에서 새 프로젝트를 만들고 편집할 수 있습니다.

[Final Cut Pro](https://www.apple.com/final-cut-pro/)는 Apple의 전문가급 동영상 편집 소프트웨어입니다.

[Kdenlive](https://kdenlive.org/en/)는 무제한 멀티미디어 파일을 지원하는 오픈 소스 비디오 편집 도구입니다. MLT 프레임워크, KDE 및 Qt를 기반으로 합니다. 다양한 기능을 갖춘 매우 다재다능한 비디오 편집 도구를 찾는 사람들. 최신 20.08 릴리스에는 인터페이스 레이아웃, 다중 오디오 스트림 지원, 캐시된 데이터 관리, 클립 모니터 및 효과 패널의 줌바와 같은 멋진 기능이 포함되어 있지만 이 릴리스의 하이라이트는 안정성과 인터페이스 개선이라고 주장할 수도 있습니다.

[OpenShot](https://www.openshot.org/)은 편집 환경을 처음 접하는 사용자를 위해 설계된 오픈 소스 비디오 편집 도구입니다. 간단한 드래그 앤 드롭 기능과 같은 간단한 기능을 갖추고 있어 사용하기 쉽고 빠르게 배울 수 있는 사용자 인터페이스를 제공합니다. 강력한 비디오 편집기는 비디오를 자르고 다듬는 효율적인 방법을 다양하게 제공합니다. 무제한 트랙, 비디오 효과 엔진, 타이틀 편집기, 3D 애니메이션, 슬로우 모션, 시간 효과를 자유롭게 활용할 수 있습니다. WebM(VP9), AVCHD(libx264), HEVC(libx265)와 같은 FFmpeg에서 지원하는 일반적으로 사용되는 비디오 코덱과 mp3(libmp3lame) 및 aac(libfaac)와 같은 오디오 코덱을 지원합니다. 이 프로그램은 YouTube와 같은 인터넷 비디오 웹사이트에 업로드하기 위해 MPEG4, ogv, Blu-ray 및 DVD 비디오와 Full HD 비디오를 렌더링할 수 있습니다.

[DaVinci Resolve](https://www.blackmagicdesign.com/products/davinciresolve/)는 전문적인 8K 편집, 색보정, 시각 효과, 오디오 후반 제작을 모두 하나의 소프트웨어 도구에 결합한 세계 유일의 솔루션입니다! 한 번의 클릭으로 편집, 색상, 효과 및 오디오 사이를 즉시 이동할 수 있습니다. DaVinci Resolve Studio는 편집자, 어시스턴트, 컬러리스트, VFX 아티스트, 사운드 디자이너가 모두 동시에 동일한 프로젝트에서 실시간으로 작업할 수 있도록 다중 사용자 공동 작업을 위해 설계된 유일한 솔루션이기도 합니다.

[Blender](https://www.blender.org/features/video-editing/)에는 비디오 시퀀스 편집기가 내장되어 있어 비디오 자르기, 연결 등의 기본 작업은 물론 비디오 마스킹이나 컬러 그레이딩과 같은 보다 복잡한 작업도 수행할 수 있습니다. Video Editor에는 실시간 미리보기, 루마 파형, 크로마 벡터스코프 및 히스토그램 표시가 포함되어 있습니다. 오디오 믹싱, 동기화, 스크러빙 및 파형 시각화.

[Lightworks](https://www.lwks.com/)는 영화 산업에서 사용되는 디지털 비디오를 편집하고 마스터링하기 위한 비선형 비디오 편집 애플리케이션입니다. 프로페셔널 에디션은 Shutter Island, Pulp Fiction 및 Mission Impossible과 같은 흥행작에 사용되었습니다. 위협적인 사용자 인터페이스. Adobe Premiere Pro와 같은 전문 비디오 편집자와 마찬가지로 Lightworks는 신규 사용자가 사용하기에는 다소 복잡합니다.

[Shotcut](https://www.shotcut.org/)은 오픈소스 멀티 플랫폼 동영상 편집기입니다. 비디오 편집(4K 비디오 품질 포함), 효과 추가, 새 영화 만들기, 대부분의 이미지 파일 형식 가져오기, 거의 모든 파일 형식으로 내보내기 등 다양한 작업을 수행할 수 있습니다.

[Olive](https://www.olivevideoeditor.org)는 고급 전문 비디오 편집 소프트웨어에 대한 모든 기능을 갖춘 대안을 제공하는 것을 목표로 하는 무료 비선형 비디오 편집기입니다.

[OBS(오픈 브로드캐스터 소프트웨어)](https://obsproject.com/)는 동영상 녹화 및 라이브 스트리밍을 위한 무료 오픈 소스 소프트웨어입니다. Twitch, YouTube 및 기타 여러 제공업체로 스트리밍하거나 고품질 H264/AAC 인코딩으로 자신만의 비디오를 녹화하세요.

[REAPER](https://www.reaper.fm/)은 완전한 멀티트랙 오디오 및 MIDI 녹음, 편집, 처리, 믹싱 및 마스터링 도구 세트를 제공하는 컴퓨터용 완전한 디지털 오디오 제작 애플리케이션입니다. REAPER는 광범위한 하드웨어, 디지털 형식 및 플러그인을 지원하며 포괄적으로 확장, 스크립팅 및 수정이 가능합니다.

[Logic Pro](https://www.apple.com/logic-pro/)는 macOS용 DAW(디지털 오디오 워크스테이션) 및 MIDI 시퀀서 소프트웨어 애플리케이션입니다.

[Ableton Live](https://www.ableton.com/live)는 디지털 오디오 워크스테이션 애플리케이션입니다. 라이브 공연을 위한 악기이자 작곡, 녹음, 편곡, 믹싱, 마스터링을 위한 도구로 설계되었습니다.

[Bitwig Studio](https://www.bitwig.com)는 사운드 디자인, 녹음, 라이브 공연 등을 위한 선형 및 비선형 워크플로우를 갖춘 디지털 오디오 워크스테이션입니다. 90개 이상의 악기, 효과 및 기타 창의적인 도구가 함께 제공됩니다. Windows, macOS, Linux를 지원합니다.

[SonoBus](https://sonobus.net)는 인터넷이나 로컬 네트워크를 통해 장치 간에 고품질, 낮은 지연 시간의 P2P 오디오를 스트리밍하기 위한 사용하기 쉬운 애플리케이션입니다.

[Avid Pro Tools](https://www.avid.com/pro-tools)는 Dolby Atmos 또는 영화나 TV용 기타 3D 오디오를 믹싱하기 위한 디지털 오디오 워크스테이션으로, 대규모 믹싱 스테이지나 소규모 편집실에서 작업합니다.

[Adobe Audition](https://www.adobe.com/products/audition.html)은 색상, 오디오 및 그래픽용 도구를 갖춘 디지털 오디오 워크스테이션이며, Premiere Pro는 After Effects, Adobe Audition, Adobe Stock을 비롯한 다른 앱 및 서비스와 원활하게 작동합니다.

[JACK 오디오 연결 키트 AKA JACK](https://jackaudio.org/)은 API를 구현하는 애플리케이션 간의 오디오 및 MIDI 데이터 모두에 대해 실시간, 짧은 지연 시간 연결을 제공하는 전문 사운드 서버 데몬입니다. JACK은 네트워크를 통해 오디오 데이터를 기본 시스템으로 전송한 후 오디오를 물리적 장치로 출력하도록 구성할 수 있습니다. 이는 추가 케이블이나 하드웨어 믹서 없이 연결된 여러 컴퓨터의 오디오를 믹싱하고 오디오 경로를 가능한 한 오랫동안 디지털로 유지하는 데 유용할 수 있습니다.

[JACK2](https://github.com/jackaudio/jack2)는 다중 프로세서 시스템용 JACK 저지연 오디오 서버의 C++ 버전입니다. 이는 JACK1 설계의 일부 제한 사항을 제거하는 것을 목표로 하는 JACK 서버 핵심 기능의 새로운 구현입니다. 데이터 흐름 모델에 맞게 활성화 시스템을 변경했으며 그래프 액세스를 위한 잠금 없는 프로그래밍 기술을 사용하여 보다 역동적이고 견고한 시스템을 갖췄습니다.

[Image-Line FL Studio](https://www.image-line.com/fl-studio/)는 Image-Line이 개발한 오디오와 음악 시퀀싱을 믹싱하기 위한 디지털 오디오 워크스테이션입니다.

[Propellerhead Reason](https://www.reasonstudios.com/)은 창의적인 음악 제작, 녹음, 시퀀싱 및 믹싱에 필요한 도구를 갖춘 디지털 오디오 워크스테이션입니다.

[Cockos Reaper](https://www.cockos.com/reaper/)는 상업/홈 스튜디오, 방송, 장소 녹음, 교육, 과학/연구, 사운드 디자인, 게임 개발 등에 사용되는 도구를 갖춘 완전하고 유연한 기능 세트의 디지털 오디오 워크스테이션입니다.

[PreSonus Studio One](https://www.presonus.com/products/studio-one)은 음악 및 기타 오디오를 생성, 녹음, 믹싱 및 마스터링하는 데 사용되는 디지털 오디오 워크스테이션 애플리케이션입니다.

[Steinberg Cubase](https://new.steinberg.net/cubase/)는 음악/MIDI 녹음 및 오디오 편곡/편집을 위해 Steinberg가 개발한 디지털 오디오 워크스테이션입니다.

[Digital Performer](https://motu.com/products/software/dp/)는 디지털 오디오 워크스테이션 및 음악 시퀀서 소프트웨어 패키지입니다. 녹음, 편집, 편곡, 믹싱, 마스터링, MIDI 등이 가능합니다. Digital Performer는 Stretch Audio(Zynaptiq의 ZTX PRO 기술 기반), 라이브 트리거링 및 루핑과 같은 정교한 기능 덕분에 음악을 최고 수준으로 끌어올립니다.

[Sonic Visualiser](https://www.sonicvisualiser.org)는 Windows, Linux 및 Mac용 무료 오픈 소스 애플리케이션으로, 음악 녹음을 면밀히 연구할 때 가장 먼저 접할 수 있는 프로그램으로 설계되었습니다.

[PipeWire](https://pipewire.org)는 멀티미디어 파이프라인을 처리하기 위한 서버 및 사용자 공간 API입니다. 현재 pulseaudio와 JACK에서 모두 처리하는 사용 사례를 지원하는 데 사용할 수 있는 오디오 및 비디오 장치 위에 지연 시간이 짧은 그래프 기반 처리 엔진을 제공합니다. PipeWire는 컨테이너화된 애플리케이션의 오디오 및 비디오 장치와 쉽게 상호 작용할 수 있게 해주는 강력한 보안 모델로 설계되었습니다. 그래프의 노드는 별도의 프로세스로 구현되어 소켓과 통신하고 fd 전달을 사용하여 멀티미디어 콘텐츠를 교환할 수 있습니다.

[LMMS](https://lmms.io/)는 오픈 소스 디지털 오디오 워크스테이션 응용 프로그램입니다. LMMS가 적절한 컴퓨터 하드웨어와 결합되면 샘플 정렬, 사운드 합성, MIDI 키보드 연주, 트래커와 시퀀서 기능 결합을 통해 음악을 생성할 수 있습니다. Paul Giblock과 Tobias Junghans가 개발한 이 프로그램은 "Linux MultiMedia Studio"의 약자이며 다양한 운영 체제에서 작동할 수 있는 편리한 플러그인을 지원합니다.

[Ardour](http://ardour.org/)는 음악가, 프로그래머, 전문 녹음 엔지니어로 구성된 전 세계 팀의 공동 작업인 오픈 소스입니다. 개발은 투명합니다. 누구나 우리 작업을 실시간으로 볼 수 있습니다. 마치 좋은 빈티지 철물처럼 상자를 열고 안을 들여다볼 수 있습니다.

[Audacity](https://www.audacityteam.org/)는 Windows, Mac OS X, GNU/Linux 및 기타 운영 체제를 위한 사용하기 쉬운 멀티 트랙 오디오 편집기 및 녹음기입니다. 자원봉사자 그룹에 의해 오픈 소스로 개발되었으며 무료로 제공됩니다. 놀라운 지원 커뮤니티.

# 3D 그래픽 및 디자인
[맨 위로 돌아가기](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/97116104-27a74800-16b8-11eb-9556-bdb90ba45ce7.png">
  <br />
</p>

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/126396094-16e1b14c-e1a2-4086-803d-5a8d99edeade.png">
  <br />
</p>

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/118338215-6ec91f00-b4ca-11eb-9c9e-f5cf377ca3c4.png">
  <br />
</p>

 **블렌더의 사이클 렌더 엔진. 소스: [블렌더](https://www.blender.org)**

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/118338217-6ffa4c00-b4ca-11eb-92d0-9aa30230495d.png">
  <br />
</p>

 **블렌더 VFX(시각 효과). 소스: [블렌더](https://www.blender.org)**

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/118338223-72f53c80-b4ca-11eb-8100-2e2abd98c910.png">
  <br />
</p>

**Adobe XD에서 애플리케이션을 위한 간단한 UI/UX를 디자인합니다. 출처: [Adobe](https://www.adobe.com/products/xd.html)**

## 3D 그래픽 및 디자인 학습 리소스

[픽사의 유니버설 장면 설명(USD) 소개](https://graphics.pixar.com/usd/docs/index.html)

[NVIDIA의 Universal Scene Description 사용 소개](https://developer.nvidia.com/usd)

[Blender에서 범용 장면 설명을 사용한 첫 번째 단계](https://code.blender.org/2019/07/first-steps-with-universal-scene-description/)

[AMD Radeon ProRender 개발자 제품군](https://gpuopen.com/radeon-prorender-suite/)

[블렌더 파운데이션](https://www.blender.org/foundation/)

[Blender Foundation 인증 교육](https://www.blender.org/certification/)

[Blender Cloud 강좌](https://cloud.blender.org/courses)

[블렌더 연구소](https://www.blender.org/institute/)

[블렌더 교육](https://www.blender.org/get-involved/)

[블렌더 네트워크](https://www.blendernetwork.org/)

[Udemy의 블렌더 강좌](https://www.udemy.com/topic/blender/)

[AutoDesk 학습, 교육 및 인증](https://www.autodesk.com/training)

[AutoDesk 디자인 아카데미](https://academy.autodesk.com)

[Coursera의 AutoDesk 강좌 및 전문 분야](https://www.coursera.org/autodesk)

[Cinema 4D 빠른 팁](https://www.cineversity.com/vidplaylist/cinema_4d_quick_tips)

[Cinema 4D 시작하기](https://www.cineversity.com/vidplaylist/getting_started_with_cinema_4d_r20)

[Udemy의 그래픽 디자인 마스터클래스(Photoshop, Illustrator, InDesign)](https://www.udemy.com/course/graphic-design-masterclass-everything-you-need-to-know/)

[Vectr: udemy의 그래픽 디자인 초보자 가이드](https://www.udemy.com/course/vectr-beginners-guide-to-graphic-design/)

[Canva MasterClass: Udemy가 제공하는 일상적인 디자인](https://www.udemy.com/course/canva-masterclass-design-for-everyday-use/)


## 3D 그래픽 및 디자인 도구

[Adobe Creative Cloud](https://www.adobe.com/creativecloud.html)는 20개 이상의 데스크탑 및 모바일 앱(Lightroom, Photoshop, Illustrator, InDesign, Rush 등)과 사진, 디자인, 비디오, 웹, UX 등을 위한 서비스 모음입니다.

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/126396097-921982e9-5b6b-4f1e-90f3-9b7033eeb9ca.png">
  <br />
</p>

[Autodesk®](https://www.autodesk.com/)은 3D 디자인, 건축, 엔지니어링, 제조 및 대량 생산 엔터테인먼트 회사에서 사용되는 전문 소프트웨어 제품 및 서비스 모음입니다.

[Maya®](https://www.autodesk.com/products/maya/overview)는 폭발부터 의상 시뮬레이션까지 사실적인 효과를 만들 수 있는 3D 컴퓨터 애니메이션, 모델링, 시뮬레이션 및 렌더링 소프트웨어입니다.

[Maya LT™](https://www.autodesk.com/products/maya-lt/overview)은 정교한 3D 모델링 및 애니메이션 도구를 사용하여 사실적으로 보이는 캐릭터, 소품 및 환경을 만들고 애니메이션할 수 있는 인디 게임 제작자를 위한 게임 디자인 소프트웨어입니다.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/122687226-2a682780-d1ca-11eb-9408-4b32ddc7d493.png">
  <br />
</p>

**Autodesk® Maya. 출처:[Autodesk](https://www.autodesk.com/products/maya/overview)**

[3DS Max®](https://www.autodesk.com/products/3ds-max/overview)는 디자인 시각화, 게임 및 애니메이션을 위한 3D 모델링 및 렌더링 소프트웨어입니다.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/122687233-3358f900-d1ca-11eb-8e9c-0cb68b16db0e.png">
  <br />
</p>

**Autodesk® 3DS Max. 출처:[Autodesk](https://www.autodesk.com/products/3ds-max/overview)**

[Arnold](https://www.autodesk.com/products/arnold/overview)는 보다 효율적으로 작업할 수 있도록 도와주는 고급 Monte Carlo 광선 추적(전역 조명) 렌더러입니다.

[ReCap™](https://www.autodesk.com/products/recap/overview)은 물리적 세계를 디지털 자산으로 변환하는 Pro 3D 스캐닝 소프트웨어입니다. 현실 캡처 데이터를 사용하면 기존 및 준공 조건을 더 잘 이해하고 검증하여 통찰력을 얻고 더 나은 결정을 내릴 수 있습니다.

[Flame®](https://www.autodesk.com/products/flame/overview)은 3D VFX이며 마무리 소프트웨어는 3D 합성, 시각 효과 및 편집 마무리를 위한 강력한 도구를 제공합니다. 통합된 창의적인 환경은 더 빠른 합성, 고급 그래픽, 색상 교정 등을 의미합니다.

[Mudbox®](https://www.autodesk.com/products/mudbox/overview)는 매우 상세한 3D 형상 및 텍스처를 조각하고 페인팅할 수 있는 3D 디지털 페인팅 및 조각 소프트웨어입니다.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/122687228-2e944500-d1ca-11eb-894e-b55e15c35620.png">
  <br />
</p>

**Autodesk® Mudbox. 출처:[Autodesk](https://www.autodesk.com/products/mudbox/overview)**

[Blender](https://www.blender.org)는 애니메이션 영화, 시각 효과, 예술, 3D 인쇄 모델, 대화형 3D 애플리케이션 및 비디오 게임 제작에 사용되는 전문적인 무료 오픈 소스 3D 컴퓨터 그래픽 소프트웨어 도구 세트입니다.

[Cinema 4D](https://www.maxon.net/en-us/products/cinema-4d/overview/)는 절차적 및 다각형 모델링, 애니메이션, 조명, 텍스처링, 모션 그래픽 및 렌더링을 수행할 수 있는 전문 3D 및 VFX 소프트웨어 제품군입니다.

[Houdini](https://www.sidefx.com/)는 영화, TV, 광고 및 비디오 게임 파이프라인의 모델링, 리깅, 애니메이션, VFX, 룩 개발, 조명 및 렌더링을 위한 3D 절차적 소프트웨어입니다.

[오픈 그래픽 라이브러리(OpenGL)](https://www.opengl.org/)는 현재 [Khronos Group](https://www.khronos.org/)에서 개발한 2D/3D 벡터 그래픽의 하드웨어 가속 렌더링을 위해 여러 프로그래밍 언어 및 플랫폼에서 사용되는 API입니다.

[개방형 컴퓨팅 언어(OpenCL)](https://www.khronos.org/opencl/)는 슈퍼컴퓨터, 클라우드 서버, 개인용 컴퓨터, 모바일 장치 및 임베디드 플랫폼에 사용되는 CPU, GPU 및 기타 하드웨어 가속기로 구성된 이기종 플랫폼의 [병렬 프로그래밍](https://www.coursera.org/lecture/parprog1/introduction-to-parallel-computing-zNrIS)에 대한 개방형 표준입니다.

[Vulkan](https://www.khronos.org/vulkan/)은 PC 및 콘솔부터 휴대폰 및 임베디드 플랫폼에 이르기까지 다양한 장치에 사용되는 최신 GPU에 대한 고효율의 크로스 플랫폼 액세스를 제공하는 최신 크로스 플랫폼 그래픽 및 컴퓨팅 API입니다. Vulkan은 현재 Khronos 컨소시엄에서 개발 중입니다.

[Metal](https://developer.apple.com/metal/)은 iOS, iPadOS, macOS, watchOS 및 tvOS와 같은 Apple 플랫폼에서 2D 및 3D 그래픽을 렌더링하는 데 사용되는 하위 수준 GPU 프로그래밍 프레임워크입니다.

[MoltenVK](https://moltengl.com/moltenvk)는 Apple의 [Metal](https://developer.apple.com/metal/) 그래픽 프레임워크를 사용하여 iOS 및 macOS에서 실행되는 Vulkan의 구현입니다.

[MoltenGL](https://moltengl.com)은 Apple의 [Metal](https://developer.apple.com/metal/) 그래픽 프레임워크에서 실행되는 OpenGL ES 2.0 API의 구현입니다.

[Mesa 3D 그래픽 라이브러리](https://docs.mesa3d.org/index.html)는 OpenGL 사양의 오픈 소스 구현으로 시작된 프로젝트입니다. 대화형 3D 그래픽을 렌더링하기 위한 시스템입니다. Mesa는 [직접 렌더링 인프라](https://dri.freedesktop.org/), [X.org](https://x.org/) 및 [Wayland](https://wayland.freedesktop.org/)와 같은 여러 다른 오픈 소스 프로젝트와 연결되어 Linux, FreeBSD 및 기타 운영 체제에서 OpenGL 지원을 제공합니다.

[OpenGL ES](https://www.khronos.org/opengles/)는 OpenGL의 모바일 하위 집합입니다. 이는 모든 주요 모바일 플랫폼에서 지원되며 WebGL의 기반이기도 합니다.

[OpenCL](https://www.khronos.org/opencl/)은 CPU, GPU, DSP, FPGA 및 기타 프로세서나 하드웨어 가속기로 구성된 이기종 플랫폼에서 실행되는 프로그램을 작성하기 위한 프레임워크입니다.

[Vuforia](https://developer.vuforia.com/)는 포괄적이고 확장 가능한 엔터프라이즈 AR 플랫폼입니다. 당사의 광범위한 솔루션 제품군은 비즈니스 요구 사항에 따라 모든 고객에게 적합한 AR 기술을 제공할 수 있도록 보장합니다.

[Vuforia Studio](https://www.ptc.com/en/products/vuforia/vuforia-studio)는 누구나 코딩 없이 아름다운 3D 증강 현실(AR) 경험을 단 몇 분 만에 만들 수 있는 도구입니다.

[OpenVX™](https://www.khronos.org/openvx/)은 컴퓨터 비전 애플리케이션의 크로스 플랫폼 가속을 위한 로열티 없는 오픈 소스 표준입니다. OpenVX는 성능과 전력 최적화된 컴퓨터 비전 처리를 가능하게 하며, 특히 얼굴, 신체 및 동작 추적, 스마트 비디오 감시, 고급 운전자 지원 시스템(ADAS), 객체 및 장면 재구성, 증강 현실, 시각 검사, 로봇 공학 등과 같은 임베디드 및 실시간 사용 사례에서 중요합니다.

[openXR](https://www.khronos.org/OpenXR/)은 AR(증강 현실) 및 VR(가상 현실), 통칭 XR(플랫폼 및 장치)에 대한 고성능 액세스를 제공하는 무료 개방형 표준입니다.

[GPUImage 프레임워크](https://github.com/BradLarson/GPUImage)는 이미지, 라이브 카메라 비디오 및 영화에 GPU 가속 필터 및 기타 효과를 적용할 수 있는 BSD 라이선스 iOS 라이브러리입니다. Core Image(iOS 5.0의 일부)와 비교하여 GPUImage를 사용하면 사용자 정의 필터를 직접 작성할 수 있고 iOS 4.0에 대한 배포를 지원하며 인터페이스가 더 간단합니다. 그러나 현재 얼굴 감지와 같은 Core Image의 고급 기능 중 일부가 부족합니다.

[GPUImage3](https://github.com/BradLarson/GPUImage3)은 Mac 및 iOS에서 GPU 가속 이미지 및 비디오 처리를 수행하기 위한 오픈 소스 프로젝트인 [GPUImage 프레임워크](https://github.com/BradLarson/GPUImage)의 3세대입니다. 원래 GPUImage 프레임워크는 Objective-C로 작성되었으며 Mac 및 iOS를 대상으로 했습니다. 두 번째 반복은 Mac, iOS 및 Linux를 대상으로 OpenGL을 사용하여 Swift로 재작성되었으며 이제 이 3세대는 OpenGL 대신 Metal을 사용하도록 재설계되었습니다.

[EGL](https://www.khronos.org/egl/)은 OpenGL 또는 OpenVG와 같은 Khronos 렌더링 API와 기본 네이티브 플랫폼 윈도우 시스템 간의 인터페이스입니다.

[VDPAU](https://www.freedesktop.org/wiki/Software/VDPAU/)는 UNIX용 비디오 디코드 및 프레젠테이션 API입니다. 이는 최신 GPU에 있는 비디오 디코드 가속 및 프레젠테이션 하드웨어에 대한 인터페이스를 제공합니다.

[VA API](https://freedesktop.org/wiki/Software/vaapi/)는 비디오 처리를 위한 그래픽 하드웨어 가속 기능에 대한 액세스를 제공하는 오픈 소스 라이브러리 및 API 사양입니다.

[XvMC](https://en.wikipedia.org/wiki/X-Video_Motion_Compensation)는 X 윈도우 시스템용 X 비디오 확장(Xv)의 확장입니다. XvMC API를 사용하면 비디오 프로그램이 비디오 디코딩 프로세스의 일부를 GPU 하드웨어로 오프로드할 수 있습니다.

[AMD Radeon ProRender](https://www.amd.com/en/technologies/radeon-prorender)는 창의적인 전문가가 12개 이상의 주요 디지털 콘텐츠 제작 및 CAD 애플리케이션에서 거의 모든 GPU, CPU 및 OS에서 놀랍도록 사실적인 이미지를 생성할 수 있도록 지원하는 강력한 물리 기반 렌더링 엔진입니다.

[NVIDIA Omniverse](https://developer.nvidia.com/nvidia-omniverse-platform)는 Pixar의 Universal Scene Description 및 NVIDIA RTX를 기반으로 하는 3D 제작 파이프라인을 위한 강력한 다중 GPU, 실시간 시뮬레이션 및 협업 플랫폼입니다.

[Universal Scene Description](https://github.com/PixarAnimationStudios/USD)은 그래픽 애플리케이션 간의 교환을 위해 시간 샘플링된 장면 설명을 작성, 읽기 및 스트리밍하기 위한 효율적이고 확장 가능한 시스템입니다.

[OpenTimelineIO](https://github.com/PixarAnimationStudios/OpenTimelineIO)는 편집컷 정보를 위한 교환 형식이자 API입니다. OTIO는 미디어의 컨테이너 형식이 아니라 컷의 순서와 길이, 외부 미디어에 대한 참조에 대한 정보를 포함합니다. OTIO에는 파일 형식과 해당 형식을 조작하기 위한 API가 모두 포함되어 있습니다. 또한 기존 편집 타임라인 형식 간 변환을 위한 어댑터 작성을 위한 플러그인 아키텍처도 포함되어 있습니다. 또한 시간, 오픈타임을 엄격하게 처리하기 위해 종속성이 없는 라이브러리를 구현합니다.

[OpenSubdiv](https://github.com/PixarAnimationStudios/OpenSubdiv)는 대규모 병렬 CPU 및 GPU 아키텍처에서 고성능 세분화 표면(subdiv) 평가를 구현하는 오픈 소스 라이브러리 세트입니다. 이 코드 경로는 대화형 프레임 속도에서 정적 토폴로지를 사용하여 변형 하위 분할을 그리는 데 최적화되어 있습니다. 결과적인 한계 표면은 Pixar의 Renderman과 수치 정밀도를 일치시킵니다.

[Affinity Designer](https://affinity.serif.com/en-gb/designer/)는 고품질 컨셉 아트를 제작하려는 업계 최고의 일러스트레이터, 디자이너 및 기타 창작자들이 사용하는 전문 벡터 그래픽 편집기입니다.

[Sketch](https://www.sketch.com)는 아름다운 UI와 강력한 도구 세트를 갖춘 전문 벡터 그래픽 앱입니다.

[Krita](https://krita.org/)는 디지털 페인팅 및 2D 애니메이션을 위한 오픈 소스 전문 페인팅 프로그램입니다.

[Vectr](https://vectr.com/)은 벡터 그래픽을 쉽고 직관적으로 만드는 데 사용되는 무료 그래픽 소프트웨어입니다.

[Glimpse](https://glimpse-editor.github.io/)는 Linux, macOS 및 Windows에서 사용할 수 있는 GNU 이미지 조작 프로그램을 기반으로 하는 크로스 플랫폼 래스터 그래픽 편집기입니다. YouTube 비디오 썸네일을 만들기 위한 훌륭한 도구입니다.

[GNU 이미지 조작 프로그램(GIMP)](https://www.gimp.org/)은 Linux, macOS 및 Windows에서 사용할 수 있는 GNU 이미지 조작 프로그램(GIMP)을 기반으로 하는 크로스 플랫폼 래스터 그래픽 편집기입니다. Photoshop을 위한 훌륭한 무료 대안입니다.

[PhotoGIMP](https://github.com/Diolinux/PhotoGIMP)는 모든 Adobe Photoshop 사용자가 편안함을 느낄 수 있도록 돕는 [GIMP 2.10+](https://www.gimp.org/)용 간단한 패치입니다.

[Photopea](https://www.photopea.com/)는 Adobe Photoshop(PSD), GIMP(XCF), Sketch App(Sketch), Adobe XD(XD) 및 CorelDRAW(CDR) 형식을 지원하는 고급 온라인 사진 편집기입니다.

[Inkscape](https://inkscape.org/)는 오픈 소스 벡터 그래픽 편집기입니다. 일러스트레이션, 다이어그램, 라인 아트, 차트, 로고 및 복잡한 그림과 같은 벡터 그래픽을 생성하거나 편집하는 데 사용할 수 있습니다.

[G three](https://github.com/alexlarsson/gthree)는 three.js의 GObject/Gtk+ 포트입니다.

[FreeCAD](https://www.freecadweb.org/)는 무료 오픈 소스 범용 파라메트릭 3D CAD 모델러이자 유한 요소법을 지원하는 건축 정보 모델링 소프트웨어입니다.

[Ultimaker Cura](https://ultimaker.com/software/ultimaker-cura)는 세계에서 가장 인기 있는 3D 프린팅 소프트웨어입니다. 몇 번의 클릭만으로 인쇄물을 준비하고, 더 쉬운 작업 흐름을 위해 CAD 소프트웨어와 통합하거나, 심층적인 제어를 위해 사용자 정의 설정을 살펴보세요.

[Dust3D](https://dust3d.org/)는 크로스 플랫폼 오픈 소스 모델링 소프트웨어입니다. 몇 초 만에 3D 방수 모델을 생성하는 데 도움이 됩니다. 게임 제작, 3D 프린팅 등에서 캐릭터 모델링 속도를 높이는 데 사용하세요.

[Goxel](https://github.com/guillaumechereau/goxel)은 무료 오픈 소스 3D 복셀 편집기입니다.

[Sketchfab](https://sketchfab.com/tags/open-source)에서는 무료로 보고, 구매하고, 다운로드할 수 있는 오픈 소스 3D 모델을 제공합니다.

# 신속한 개발
[맨 위로 돌아가기](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/93719675-03949c00-fb39-11ea-8f81-bf4cd544c17f.png">
</p>

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/110880054-dd9fb700-8292-11eb-9478-a5d62dc76f9d.png">
<br />
Xcode 12에서 SwiftUI를 사용하여 개발
</p>

## Swift 학습 리소스

[Swift](https://developer.apple.com/swift/)는 iOS, macOS, watchOS 및 tvOS 앱 개발을 위한 Apple의 주요 프로그래밍 언어입니다. 하지만 Swift의 많은 부분은 C 및 Objective-C 개발 경험을 통해 개발자에게 친숙할 것입니다.

[Swift Evolution](https://github.com/apple/swift-evolution)은 Swift 프로그래밍 언어에 대한 변경 사항 및 사용자에게 표시되는 개선 사항에 대한 제안을 유지 관리합니다.

[Xcode + Swift](https://developer.apple.com/swift/resources/)를 사용하면 MacOS 및 iOS용 애플리케이션을 빠르고 재미있게 개발할 수 있습니다.

[Swift 5.3 기본](https://docs.swift.org/swift-book/LanguageGuide/TheBasics.html)

[Swift로 iOS 앱 개발 시작](https://developer.apple.com/library/archive/referencelibrary/GettingStarted/DevelopiOSAppsSwift/)

[Apple 개발자 문서](https://developer.apple.com/documentation)

[Apple 재단 프레임워크](https://developer.apple.com/documentation/foundation)

[Apple 핵심 애니메이션 프레임워크](https://developer.apple.com/documentation/quartzcore)

[Apple 핵심 그래픽 프레임워크](https://developer.apple.com/documentation/coregraphics)

[가상화 프레임워크](https://developer.apple.com/documentation/virtualization)

[반가상화 그래픽 프레임워크](https://developer.apple.com/documentation/paravirtualizedgraphics)

[LLDB 시작하기](https://developer.apple.com/library/archive/documentation/IDEs/Conceptual/gdb_to_lldb_transition_guide/document/lldb-basics.html)

[Mac Catalyst - iOS - 휴먼 인터페이스 지침](https://developer.apple.com/design/human-interface-guidelines/ios/overview/mac-catalyst/)

[Amazon EC2 Mac 인스턴스](https://aws.amazon.com/ec2/instance-types/mac/)

[스위프트 GitHub](https://github.com/apple/swift)

[Apple 개발자 포럼](https://developer.apple.com/forums/)

[스위프트 포럼](https://forums.swift.org/)

[Google의 Swift 스타일 가이드](https://google.github.io/swift/)

[Coursera의 신속한 온라인 강좌](https://www.coursera.org/courses?query=swift)

[Udemy의 신속한 온라인 강좌](https://www.udemy.com/topic/swift/)

[Codecademy의 Swift 학습 과정](https://www.codecademy.com/learn/learn-swift)

## Swift 도구, 라이브러리 및 프레임워크

[Xcode](https://developer.apple.com/xcode/)에는 개발자가 Mac, iPhone, iPad, Apple TV 및 Apple Watch용 훌륭한 응용 프로그램을 만드는 데 필요한 모든 것이 포함되어 있습니다. Xcode는 개발자에게 사용자 인터페이스 디자인, 코딩, 테스트 및 디버깅을 위한 통합 워크플로를 제공합니다. Xcode 12는 Intel 기반 CPU 및 Apple Silicon에서 기본적으로 100% 실행되는 범용 앱으로 구축되었습니다. 여기에는 Apple Silicon 및 Intel x86_64 CPU에서 기본적으로 실행되는 앱을 구축하는 데 필요한 모든 프레임워크, 컴파일러, 디버거 및 기타 도구를 갖춘 통합 macOS SDK가 포함되어 있습니다.

[SwiftUI](https://developer.apple.com/documentation/swiftui)는 앱의 사용자 인터페이스를 선언하기 위한 보기, 컨트롤 및 레이아웃 구조를 제공하는 사용자 인터페이스 툴킷입니다. SwiftUI 프레임워크는 탭, 제스처 및 기타 유형의 입력을 애플리케이션에 전달하기 위한 이벤트 핸들러를 제공합니다.

[UIKit](https://developer.apple.com/documentation/uikit)은 iOS 또는 tvOS 앱에 필요한 인프라를 제공하는 프레임워크입니다. 이는 인터페이스 구현을 위한 창 및 보기 아키텍처, 멀티 터치 및 기타 유형의 입력을 앱에 제공하기 위한 이벤트 처리 인프라, 사용자, 시스템 및 앱 간의 상호 작용을 관리하는 데 필요한 기본 실행 루프를 제공합니다.

[AppKit](https://developer.apple.com/documentation/appkit)은 창, 패널, 버튼, 메뉴, 스크롤러, 텍스트 필드 등 macOS 앱용 사용자 인터페이스를 구현하는 데 필요한 모든 개체가 포함된 그래픽 사용자 인터페이스 도구 키트로, 화면에 효율적으로 그리기, 하드웨어 장치 및 화면 버퍼와 통신하기, 그리기 전에 화면 영역 지우기, 보기 자르기 등 모든 세부 사항을 처리합니다.

[ARKit](https://developer.apple.com/augmented-reality/arkit/)은 개발자가 Apple에서 개발한 iOS용 증강 현실 앱을 구축할 수 있도록 지원하는 소프트웨어 개발 도구 세트입니다. 최신 버전 ARKit 3.5는 iPad Pro(2020)의 새로운 LiDAR 스캐너와 깊이 감지 시스템을 활용하여 향상된 장면 이해 및 객체 폐색을 위해 장면 기하학을 사용하는 차세대 AR 앱을 지원합니다.

[RealityKit](https://developer.apple.com/documentation/realitykit)은 ARKit 프레임워크에서 제공하는 정보를 사용하여 고성능 3D 시뮬레이션 및 렌더링을 구현하여 가상 객체를 현실 세계에 원활하게 통합하는 프레임워크입니다.

[SceneKit](https://developer.apple.com/scenekit/)은 iOS 앱에서 3D 애니메이션 장면과 효과를 만드는 데 도움이 되는 고급 3D 그래픽 프레임워크입니다.

[Mac Catalyst](https://developer.apple.com/mac-catalyst/)는 개발자가 iOS 앱을 [Apple Silicon M1 Chip](https://www.apple.com/mac/m1/)으로 빠르게 포팅하고 새로운 Apple 하드웨어의 새로운 기능을 최대한 활용하는 데 사용할 수 있는 Apple API 세트입니다.

[Instruments](https://help.apple.com/instruments/mac/current/#/dev7b09c84f5)는 Xcode 도구 세트의 일부인 강력하고 유연한 성능 분석 및 테스트 도구입니다. 이는 iOS, watchOS, tvOS 및 macOS 앱, 프로세스 및 장치의 동작과 성능을 더 잘 이해하고 최적화하기 위해 프로파일링하는 데 도움이 되도록 설계되었습니다.

[CocoaPods](https://cocoapods.org/)는 간단한 텍스트 파일에서 프로젝트에 대한 종속성을 지정하여 Xcode 프로젝트에서 사용되는 Swift 및 Objective-C용 종속성 관리자입니다. 그런 다음 CocoaPods는 라이브러리 간의 종속성을 반복적으로 해결하고, 모든 종속성에 대한 소스 코드를 가져오고, Xcode 작업공간을 생성 및 유지하여 프로젝트를 빌드합니다.

[AppCode](https://www.jetbrains.com/objc/)에서는 코드 품질을 지속적으로 모니터링하고 있습니다. 오류와 냄새에 대해 경고하고 자동으로 해결하기 위한 빠른 수정 사항을 제안합니다. AppCode는 Objective-C, Swift, C/C++에 대한 다양한 코드 검사와 기타 지원되는 언어에 대한 다양한 코드 검사를 제공합니다.

[Vapor](https://github.com/vapor/vapor)는 Swift용 웹 프레임워크입니다. 다음 웹 사이트, API 또는 클라우드 프로젝트를 위한 아름답게 표현되고 사용하기 쉬운 기반을 제공합니다.

[Hero](https://github.com/HeroTransitions/Hero)는 iOS 뷰 컨트롤러 전환을 빌드하기 위한 라이브러리입니다. 이는 UIKit의 번거로운 전환 API 위에 선언적 레이어를 제공하여 개발자가 사용자 정의 전환을 쉽게 수행할 수 있도록 해줍니다.

[Kingfisher](https://github.com/onevcat/Kingfisher)는 웹에서 이미지를 다운로드하고 캐싱하기 위한 강력한 순수 Swift 라이브러리입니다. 다음 앱에서 원격 이미지 작업을 위해 순수 Swift 방식을 사용할 수 있는 기회를 제공합니다.

[Realm](https://github.com/realm/realm-cocoa)은 휴대폰, 태블릿 또는 웨어러블 기기 내에서 직접 실행되는 모바일 데이터베이스입니다. 이 저장소에는 Realm Swift 및 Realm Objective-C의 iOS, macOS, tvOS 및 watchOS 버전에 대한 소스 코드가 보관되어 있습니다.

[Perfect](https://github.com/PerfectlySoft/Perfect)는 Linux, iOS 및 macOS(OS X)를 위한 완벽하고 강력한 도구 상자, 프레임워크 및 애플리케이션 서버입니다. 이는 Swift 엔지니어가 클라이언트 측 애플리케이션과 서버 측 애플리케이션 모두를 위해 Swift 프로그래밍 언어로 가볍고 유지 관리 가능하며 확장 가능한 앱과 기타 REST 서비스를 개발하는 데 필요한 모든 것을 제공합니다.

[Alamofire](https://github.com/Alamofire/Alamofire)는 Swift로 작성된 HTTP 네트워킹 라이브러리입니다.

[Eureka](https://github.com/xmartlabs/Eureka)는 Swift의 우아한 iOS 양식 작성 도구입니다.

[Carthage](https://github.com/Carthage/Carthage)는 Cocoa 애플리케이션에 프레임워크를 추가하는 가장 간단한 방법으로 만들어졌습니다. Carthage는 종속성을 구축하고 바이너리 프레임워크를 제공하지만 프로젝트 구조와 설정에 대한 모든 권한은 사용자가 유지합니다. 카르타고는 프로젝트 파일이나 빌드 설정을 자동으로 수정하지 않습니다.

[ReactiveCocoa](https://github.com/ReactiveCocoa/ReactiveCocoa)는 ReactiveSwift 위에 구축된 Cocoa 프레임워크에 대한 반응형 확장입니다.

# 오브젝티브-C 개발
[맨 위로 돌아가기](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/121821278-e6ff3d80-cc4c-11eb-9a57-c7aa13b88b30.png">
</p>


## Objective-C 학습 리소스

[Objective-C](https://developer.apple.com/library/archive/documentation/Cocoa/Conceptual/ProgrammingWithObjectiveC/Introduction/Introduction.html)는 2014년 [Swift](https://developer.apple.com/swift/)가 도입될 때까지 macOS 및 iOS용 소프트웨어 작성에 사용된 기본 프로그래밍 언어였습니다. 이는 C 프로그래밍 언어의 상위 집합이며 객체 지향 기능과 동적 런타임을 제공합니다.

[Apple 개발자 포럼](https://developer.apple.com/forums/)

[Google의 Objective-C 스타일 가이드](https://google.github.io/styleguide/objcguide.html)

[Coursera의 Objective C 과정](https://www.coursera.org/courses?query=objective%20c)

[Udemy의 Objective-C 온라인 강좌](https://www.udemy.com/topic/objective-c/)

[David Nutter의 Swift 개발자를 위한 Objective-C 과정](https://www.pluralsight.com/courses/objective-c-swift-developers)

[LinkedIn 학습에 대한 Objective-C 필수 교육](https://www.linkedin.com/learning/objective-c-essential-training/)

[Udacity의 Swift 개발자를 위한 Objective-C](https://www.udacity.com/course/objective-c-for-swift-developers--ud1009)

## Objective-C 도구, 라이브러리 및 프레임워크

[Xcode](https://developer.apple.com/xcode/)에는 개발자가 Mac, iPhone, iPad, Apple TV 및 Apple Watch용 훌륭한 응용 프로그램을 만드는 데 필요한 모든 것이 포함되어 있습니다. Xcode는 개발자에게 사용자 인터페이스 디자인, 코딩, 테스트 및 디버깅을 위한 통합 워크플로를 제공합니다.

[AppKit](https://developer.apple.com/documentation/appkit)은 창, 패널, 버튼, 메뉴, 스크롤러, 텍스트 필드 등 macOS 앱용 사용자 인터페이스를 구현하는 데 필요한 모든 개체가 포함된 그래픽 사용자 인터페이스 도구 키트로, 화면에 효율적으로 그리기, 하드웨어 장치 및 화면 버퍼와 통신하기, 그리기 전에 화면 영역 지우기, 보기 자르기 등 모든 세부 사항을 처리합니다.

[Instruments](https://help.apple.com/instruments/mac/current/#/dev7b09c84f5)는 Xcode 도구 세트의 일부인 강력하고 유연한 성능 분석 및 테스트 도구입니다. 이는 iOS, watchOS, tvOS 및 macOS 앱, 프로세스 및 장치의 동작과 성능을 더 잘 이해하고 최적화하기 위해 프로파일링하는 데 도움이 되도록 설계되었습니다.

[CocoaPods](https://cocoapods.org/)는 간단한 텍스트 파일에서 프로젝트에 대한 종속성을 지정하여 Xcode 프로젝트의 Swift 및 Objective-C용 종속성 관리자입니다. 그런 다음 CocoaPods는 라이브러리 간의 종속성을 반복적으로 해결하고, 모든 종속성에 대한 소스 코드를 가져오고, Xcode 작업공간을 생성 및 유지하여 프로젝트를 빌드합니다.

[AppCode](https://www.jetbrains.com/objc/)에서는 코드 품질을 지속적으로 모니터링하고 있습니다. 오류와 냄새에 대해 경고하고 자동으로 해결하기 위한 빠른 수정 사항을 제안합니다. AppCode는 Objective-C, Swift, C/C++에 대한 다양한 코드 검사와 기타 지원되는 언어에 대한 다양한 코드 검사를 제공합니다.

[Realm](https://github.com/realm/realm-cocoa)은 휴대폰, 태블릿 또는 웨어러블 기기 내에서 직접 실행되는 모바일 데이터베이스(Core Data 및 SQLite 대체)입니다.

[Infer](https://github.com/facebook/infer)는 Java, C++, Objective-C, C용 정적 분석 도구입니다.

[Mantle](https://github.com/Mantle/Mantle)은 Cocoa 또는 Cocoa Touch 애플리케이션을 위한 간단한 모델 레이어를 쉽게 작성할 수 있게 해주는 모델 프레임워크입니다.

[Quick](https://github.com/Quick/Quick)은 Swift 및 Objective-C용 동작 중심 개발 프레임워크입니다.

[Aspects](https://github.com/steipete/Aspects)는 Objective-C 및 Swift의 관점 ​​지향 프로그래밍을 위한 간단한 라이브러리입니다.

[Hammerspoon](https://github.com/Hammerspoon/hammerspoon)은 운영 체제와 Lua 스크립팅 엔진 사이의 가교 역할을 하는 macOS용 강력한 자동화 도구입니다.

[Nimbus](https://github.com/jverkoey/nimbus)는 문서화만큼 빠르게 기능 세트가 성장하는 iOS 프레임워크입니다.

# C/C++ 개발
[맨 위로 돌아가기](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/115297894-961e0d80-a111-11eb-81c3-e2bd2ac9a7cd.png">
  <br />
</p>

## C/C++ 학습 리소스

[C++](https://www.cplusplus.com/doc/tutorial/)은 Bjarne Stroustrup이 C 언어의 확장으로 개발한 고성능 애플리케이션을 구축하는 데 사용할 수 있는 크로스 플랫폼 언어입니다.

[C](https://www.iso.org/standard/74528.html)는 원래 Dennis M. Ritchie가 Bell Labs에서 UNIX 운영 체제를 개발하기 위해 개발한 범용 고급 언어입니다. 정적 유형 시스템을 통해 구조적 프로그래밍, 어휘 변수 범위 및 재귀를 지원합니다. C는 또한 일반적인 기계 명령어에 효율적으로 매핑되는 구성을 제공하므로 오늘날 가장 널리 사용되는 프로그래밍 언어 중 하나입니다.

[임베디드 C](https://en.wikipedia.org/wiki/Embedded_C)는 다양한 [임베디드 시스템](https://en.wikipedia.org/wiki/Embedded_system)에 대한 C 확장 간에 존재하는 문제를 해결하기 위해 [C 표준 위원회](https://isocpp.org/std/the-committee)에서 만든 C 프로그래밍 언어용 언어 확장 세트입니다. 확장은 고정 소수점 산술, 다중 개별 메모리 뱅크 및 기본 I/O 작업과 같은 마이크로프로세서 기능을 향상시킵니다. 이로 인해 Embedded C는 세계에서 가장 인기 있는 임베디드 소프트웨어 언어가 되었습니다.

[JetBrains의 C 및 C++ 개발자 도구](https://www.jetbrains.com/cpp/)

[cppreference.com의 오픈 소스 C++ 라이브러리](https://en.cppreference.com/w/cpp/links/libs)

[C++ 그래픽 라이브러리](https://cpp.libhunt.com/libs/graphics)

[MATLAB의 C++ 라이브러리](https://www.mathworks.com/help/matlab/call-cpp-library-functions.html)

[C++ 도구 및 라이브러리 문서](https://www.cplusplus.com/articles/tools/)

[Google C++ 스타일 가이드](https://google.github.io/styleguide/cppguide.html)

[Google Developers의 C++ 교육 입문 과정](https://developers.google.com/edu/c++/)

[Fuchsia용 C++ 스타일 가이드](https://fuchsia.dev/fuchsia-src/development/languages/c-cpp/cpp-style)

[OpenTitan의 C 및 C++ 코딩 스타일 가이드](https://docs.opentitan.org/doc/rm/c_cpp_coding_style/)

[Chromium C++ 스타일 가이드](https://chromium.googlesource.com/chromium/src/+/master/styleguide/c++/c++.md)

[C++ 핵심 지침](https://github.com/isocpp/CppCoreGuidelines/blob/master/CppCoreGuidelines.md)

[ROS용 C++ 스타일 가이드](http://wiki.ros.org/CppStyleGuide)

[C++ 배우기](https://www.learncpp.com/)

[C 배우기: 대화형 C 튜토리얼](https://www.learn-c.org/)

[C++ 연구소](https://cppinstitute.org/free-c-and-c-courses)

[LinkedIn Learning의 C++ 온라인 교육 과정](https://www.linkedin.com/learning/topics/c-plus-plus)

[W3Schools에 대한 C++ 튜토리얼](https://www.w3schools.com/cpp/default.asp)

[edX에서 C 프로그래밍 온라인 강좌 배우기](https://www.edx.org/learn/c-programming)

[edX 온라인 강좌로 C++ 배우기](https://www.edx.org/learn/c-plus-plus)

[Codecademy에서 C++ 배우기](https://www.codecademy.com/learn/learn-c-plus-plus)

[모두를 위한 코딩: Coursera의 C 및 C++ 과정](https://www.coursera.org/specializations/coding-for-everyone)

[C 프로그래머를 위한 Coursera의 C++](https://www.coursera.org/learn/c-plus-plus-a)

[Coursera의 인기 C 강좌](https://www.coursera.org/courses?query=c%20programming)

[Udemy의 C++ 온라인 강좌](https://www.udemy.com/topic/c-plus-plus/)

[Udemy의 인기 C 강좌](https://www.udemy.com/topic/c-programming/)

[Udemy 초보자를 위한 임베디드 C 프로그래밍의 기초](https://www.udemy.com/course/embedded-c-programming-for-embedded-systems/)

[Udacity 프로그래머를 위한 C++ 과정](https://www.udacity.com/course/c-for-programmers--ud210)

[Pluralsight에 대한 C++ 기초 과정](https://www.pluralsight.com/courses/learn-program-cplusplus)

[MIT 무료 온라인 강좌 자료의 C++ 소개](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-096-introduction-to-c-january-iap-2011/)

[프로그래머를 위한 C++ 소개 | 하버드](https://online-learning.harvard.edu/course/introduction-c-programmers)

[온라인 C 강좌 | 하버드 대학교](https://online-learning.harvard.edu/subject/c)


## C/C++ 도구 및 프레임워크

[Visual Studio](https://visualstudio.microsoft.com/)는 Microsoft의 IDE(통합 개발 환경)입니다. 이는 소프트웨어 개발의 다양한 측면에 사용할 수 있는 기능이 풍부한 응용 프로그램입니다. Visual Studio를 사용하면 앱을 쉽게 편집, 디버그, 빌드 및 게시할 수 있습니다. Windows API, Windows Forms, Windows Presentation Foundation 및 Windows Store와 같은 Microsoft 소프트웨어 개발 플랫폼을 사용합니다.

[Visual Studio Code](https://code.visualstudio.com/)는 최신 웹 및 클라우드 애플리케이션을 구축하고 디버깅하기 위해 재정의되고 최적화된 코드 편집기입니다.

[Vcpkg](https://github.com/microsoft/vcpkg)은 Windows, Linux 및 MacOS용 C++ 라이브러리 관리자입니다.

[ReSharper C++](https://www.jetbrains.com/resharper-cpp/features/)는 JetBrains에서 개발한 C++ 개발자를 위한 Visual Studio 확장 프로그램입니다.

[AppCode](https://www.jetbrains.com/objc/)에서는 코드 품질을 지속적으로 모니터링하고 있습니다. 오류와 냄새에 대해 경고하고 자동으로 해결하기 위한 빠른 수정 사항을 제안합니다. AppCode는 Objective-C, Swift, C/C++에 대한 다양한 코드 검사와 기타 지원되는 언어에 대한 다양한 코드 검사를 제공합니다. 모든 코드 검사는 즉시 실행됩니다.

[CLion](https://www.jetbrains.com/clion/features/)은 JetBrains에서 개발한 C 및 C++ 개발자를 위한 크로스 플랫폼 IDE입니다.

[Code::Blocks](https://www.codeblocks.org/)는 사용자의 가장 까다로운 요구 사항을 충족하기 위해 구축된 무료 C/C++ 및 Fortran IDE입니다. 확장성이 뛰어나고 완전히 구성 가능하도록 설계되었습니다. 플러그인 프레임워크를 기반으로 구축된 Code::Blocks는 플러그인을 통해 확장될 수 있습니다.

[CppSharp](https://github.com/mono/CppSharp)는 .NET 생태계에서 네이티브 C/C++ 코드의 사용을 용이하게 하는 도구이자 라이브러리 세트입니다. C/C++ 헤더 및 라이브러리 파일을 사용하고 네이티브 API를 관리형 API로 표시하는 데 필요한 글루 코드를 생성합니다. 이러한 API를 사용하면 관리 코드에서 기존 네이티브 라이브러리를 사용하거나 네이티브 코드베이스에 관리 스크립팅 지원을 추가할 수 있습니다.

[Conan](https://conan.io/)은 다른 개발 생태계와 동등한 21세기 C++ 개발 및 종속성 관리를 위한 오픈 소스 패키지 관리자입니다.

[고성능 컴퓨팅(HPC) SDK](https://developer.nvidia.com/hpc)는 GPU 가속 HPC 모델링 및 시뮬레이션 애플리케이션을 위한 포괄적인 도구 상자입니다. 여기에는 NVIDIA 플랫폼에서 HPC 애플리케이션을 개발하는 데 필요한 C, C++ 및 Fortran 컴파일러, 라이브러리 및 분석 도구가 포함되어 있습니다.

[Thrust](https://github.com/NVIDIA/thrust)는 C++ 표준 라이브러리와 유사한 C++ 병렬 프로그래밍 라이브러리입니다. Thrust의 고급 인터페이스는 프로그래머 생산성을 크게 향상시키는 동시에 GPU와 멀티코어 CPU 간의 성능 이식성을 가능하게 합니다. CUDA, TBB, OpenMP 등 확립된 기술과의 상호 운용성은 기존 소프트웨어와 통합됩니다.

[Boost](https://www.boost.org/)는 최첨단 C++에 초점을 맞춘 교육 기회입니다. Boost는 2007년부터 연례 Google Summer of Code에 참여해 왔습니다. 이 행사에서 학생들은 Boost 라이브러리 개발 작업을 통해 기술을 개발합니다.

[Automake](https://www.gnu.org/software/automake/)는 GNU 코딩 표준을 준수하는 Makefile.in 파일을 자동으로 생성하는 도구입니다. Automake에는 GNU Autoconf를 사용해야 합니다.

[Cmake](https://cmake.org/)는 소프트웨어를 빌드, 테스트 및 패키징하도록 설계된 오픈 소스 크로스 플랫폼 도구 제품군입니다. CMake는 간단한 플랫폼 및 컴파일러 독립적 구성 파일을 사용하여 소프트웨어 컴파일 프로세스를 제어하고 선택한 컴파일러 환경에서 사용할 수 있는 기본 makefile 및 작업 공간을 생성하는 데 사용됩니다.

[GDB](http://www.gnu.org/software/gdb/)는 다른 프로그램이 실행되는 동안 다른 프로그램 '내부'에서 무슨 일이 일어나고 있는지 또는 충돌 순간에 다른 프로그램이 무엇을 하고 있었는지 볼 수 있게 해주는 디버거입니다.

[GCC](https://gcc.gnu.org/)는 C, C++, Objective-C, Fortran, Ada, Go 및 D용 프런트 엔드와 이러한 언어용 라이브러리를 포함하는 컴파일러 컬렉션입니다.

[GSL](https://www.gnu.org/software/gsl/)은 C 및 C++ 프로그래머를 위한 숫자 라이브러리입니다. GNU General Public License에 따른 무료 소프트웨어입니다. 라이브러리는 난수 생성기, 특수 함수 및 최소 제곱 피팅과 같은 광범위한 수학 루틴을 제공합니다. 광범위한 테스트 스위트를 포함해 총 1000개 이상의 기능이 있습니다.

[OpenGL 확장 Wrangler 라이브러리(GLEW)](https://www.opengl.org/sdk/libs/GLEW/)는 크로스 플랫폼 오픈 소스 C/C++ 확장 로딩 라이브러리입니다. GLEW는 대상 플랫폼에서 지원되는 OpenGL 확장을 결정하기 위한 효율적인 런타임 메커니즘을 제공합니다.

[Libtool](https://www.gnu.org/software/libtool/)은 일관되고 이식 가능한 인터페이스 뒤에 공유 라이브러리 사용의 복잡성을 숨기는 일반 라이브러리 지원 스크립트입니다. Libtool을 사용하려면 Makefile, Makefile.in 또는 Makefile.am에 새로운 일반 라이브러리 구축 명령을 추가하세요.

[Maven](https://maven.apache.org/)은 소프트웨어 프로젝트 관리 및 이해 도구입니다. POM(프로젝트 개체 모델) 개념을 기반으로 Maven은 중앙 정보에서 프로젝트의 빌드, 보고 및 문서화를 관리할 수 있습니다.

[TAU(Tuning And Analysis Utilities)](http://www.cs.uoregon.edu/research/tau/home.php)는 이벤트 기반 샘플링은 물론 함수, 메서드, 기본 블록 및 명령문의 계측을 통해 성능 정보를 수집할 수 있습니다. 템플릿과 네임스페이스를 포함하여 모든 C++ 언어 기능이 지원됩니다.

[Clang](https://clang.llvm.org/)은 X86-32, X86-64 및 ARM을 대상으로 하는 프로덕션 품질의 C, Objective-C, C++ 및 Objective-C++ 컴파일러입니다(다른 대상에는 주의 사항이 있을 수 있지만 일반적으로 수정하기 쉽습니다). Clang은 프로덕션 환경에서 Google Chrome 또는 Firefox와 같이 성능이 중요한 소프트웨어를 구축하는 데 사용됩니다.

[OpenCV](https://opencv.org/)는 실시간 애플리케이션에 초점을 맞춘 고도로 최적화된 라이브러리입니다. 크로스 플랫폼 C++, Python 및 Java 인터페이스는 Linux, MacOS, Windows, iOS 및 Android를 지원합니다.

[Libcu++](https://nvidia.github.io/libcudacxx)은 전체 시스템을 위한 NVIDIA C++ 표준 라이브러리입니다. 이는 CPU와 GPU 코드 사이에서 사용할 수 있는 C++ 표준 라이브러리의 이기종 구현을 제공합니다.

[ANTLR(언어 인식을 위한 또 다른 도구)](https://www.antlr.org/)은 구조화된 텍스트 또는 바이너리 파일을 읽고, 처리하고, 실행하거나 번역하기 위한 강력한 파서 생성기입니다. 언어, 도구 및 프레임워크를 구축하는 데 널리 사용됩니다. 문법에서 ANTLR은 구문 분석 트리를 구축할 수 있는 구문 분석기를 생성하고 관심 있는 구문 인식에 쉽게 응답할 수 있는 청취자 인터페이스도 생성합니다.

[Oat++](https://oatpp.io/)은 확장성이 뛰어나고 리소스 효율성이 뛰어난 웹 애플리케이션을 위한 가볍고 강력한 C++ 웹 프레임워크입니다. 종속성이 없으며 휴대가 간편합니다.

[JavaCPP](https://github.com/bytedeco/javacpp)는 일부 C/C++ 컴파일러가 어셈블리 언어와 상호 작용하는 방식과 다르지 않게 Java 내부의 기본 C++에 대한 효율적인 액세스를 제공하는 프로그램입니다.

[Cython](https://cython.org/)은 Python 자체만큼 쉽게 Python용 C 확장을 작성할 수 있게 해주는 언어입니다. Cython은 Pyrex를 기반으로 하지만 C 함수 호출, 변수 및 클래스 속성에 대한 C 유형 선언과 같은 더욱 최첨단 기능과 최적화를 지원합니다.

[Spdlog](https://github.com/gabime/spdlog)는 매우 빠른 헤더 전용/컴파일된 C++ 로깅 라이브러리입니다.

[Infer](https://fbinfer.com/)는 Java, C++, Objective-C, C용 정적 분석 도구입니다. Infer는 [OCaml](https://ocaml.org/)로 작성되었습니다.

## 기여하다

- [x] 이 가이드에 기여하고 싶으시면 [Pull Request](https://github.com/mikeroyal/Apple-Silicon-Guide/pulls)를 보내시면 됩니다.


## 라이센스
[맨 위로 돌아가기](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

[Creative Commons Attribution 4.0 International(CC BY 4.0) 공중 라이선스](https://creativecommons.org/licenses/by/4.0/)에 따라 배포됩니다.
