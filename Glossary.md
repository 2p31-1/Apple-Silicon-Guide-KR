# 용어집

<p align="center">
<img src="https://github.com/mikeroyal/Apple-Silicon-Guide/assets/45159366/ccbb8f68-f857-43bf-a762-db23dda7b8f1">
<br />
Apple Silicon 기기
</p>

A

   **AGX:** Apple GPU 시리즈의 내부 명칭.

   **AIC:** Apple Interrupt Controller. Apple의 커스텀 ARM 인터럽트 컨트롤러로, 표준 GIC가 Apple에게는 너무 표준적이었기 때문에 만들어졌다.

   **ANS:** NVME/스토리지 보조 프로세서.

   **AP: Application Processor**. 대부분의 OS를 실행하는 메인 CPU. SEP와 대조됨.

   **Apple File System (APFS):** macOS 10.13 이상을 사용하는 Mac 컴퓨터의 기본 파일 시스템으로, 강력한 암호화, 공간 공유, 스냅샷, 빠른 디렉토리 크기 계산, 개선된 파일 시스템 기반 기능을 제공한다.

   **APFS Container:** 디스크의 물리적 파티션으로, 여러 파일 시스템(볼륨)을 포함할 수 있으며 모두 동적으로 공간을 공유한다.
   APFS Snapshot: APFS 볼륨의 읽기 전용 copy-on-write 스냅샷.

   **APFS Volume:** APFS 컨테이너 내의 논리적 파일 시스템으로, 디렉토리에 마운트할 수 있다.

   **ASC:** 보조 프로세서의 일반적인 명칭으로 추정됨.

   **ARM64(AKA AArch64):** **Armv8-A** 아키텍처와 함께 처음 도입된 ARM 아키텍처 계열의 64비트 확장.

B

   **BootROM:** M1과 같은 칩에 내장된 읽기 전용 메모리로, 부팅 시 가장 먼저 실행되는 코드이다. SecureROM 참조.

C

   **Chicken Bits:** "kill bits"라고도 불리며, 특정 기능을 비활성화/활성화하는 데 사용되는 설정 비트.

   **countryd**는 현재 GPS 위치, Wi-Fi 라우터의 국가 코드, SIM 카드에서 얻은 정보 등 여러 데이터를 결합하여 사용자가 있는 국가를 판단하는 iOS 시스템이다. iOS 16.2에서 조용히 추가되었지만, 아직 활발히 사용되지 않고 있다. iOS 17에서 **EU 지역 전용** 사이드로딩 앱에 사용될 가능성이 높다.

D

   **DART:** Device Address Resolution Table. Apple의 커스텀 IOMMU.

   **DCP:** Display Control Processor(추정). 티어링 없이 새 프레임을 표시하고, 마우스 커서와 같은 하드웨어 스프라이트, 해상도 전환, 다중 출력 구성 등을 지원한다.

   **DFR:** Dynamic Function Row. Touch Bar의 Apple 내부 명칭.

   **DFU:** Device Firmware Update. USB를 통해 기기의 펌웨어를 플래싱할 수 있는 USB 모드. Apple 기기는 SecureROM에서 이를 지원하여 사용자가 벽돌이 된 기기를 복원할 수 있게 한다.

E

   **EEPROM:** Electrically Erasable Programmable Read Only Memory. 재기록 가능한 메모리 유형으로, 일반적으로 최대 수 킬로바이트 크기로 제공되며 NOR Flash보다 견고하다. 설정 및 매우 초기 부팅 코드에 자주 사용된다.

F

   **fuOS:** 커스텀 OS로, "fully untrusted OS(완전히 신뢰할 수 없는 OS)"를 의미하는 것으로 추정됨.

   **Fallback Recovery OS:** 전원 버튼을 두 번 클릭하고 길게 눌러 부팅하는 2차 복구 OS. 1TR과 달리 보안 상태(설정)를 변경할 수 없다. 유틸리티 아래에 "보안 유틸리티 시작" 옵션이 없어 Recovery OS 1TR과 구별할 수 있다.

G

  **Game Mode**는 **macOS 14**에서 활성화된 도구로, 실행 중인 타이틀에 CPU 및 GPU 성능을 우선 할당하여 전반적인 게임 하드웨어 성능을 향상시킨다.

   **GPT: GUID Partition Table**: EFI/UEFI용으로 만들어진 파티션 테이블 형식으로, 현재 대부분의 최신 시스템에서 사용된다.

   **GXF:** Guarded Execution Function(추정). XNU 자체로부터 페이지 테이블 및 동등하게 중요한 구조를 보호하기 위해 저오버헤드 하이퍼바이저를 생성하는 데 사용되는 측면 예외 수준.

H

   **HFS+: Hierarchical Filesystem+**: Apple의 이전 파일 시스템으로, 외부 스토리지에 사용된다. M1 Mac의 내부 스토리지에는 사용되지 않는다.

I

   **I²C: Inter-Integrated Circuit**. 보드 내 칩 간 저속 통신을 위한 2선 표준.

   **iBoot**: Apple의 부트로더. iBoot1, iBoot2, 또는 iBSS, iBEC, 심지어 SecureROM 자체(모두 다른 기능을 가진 iBoot의 다른 빌드)를 지칭할 수 있다.

   **iBoot1**: NOR에 위치한 1단계 iBoot로, SecureROM에 의해 로드된다. 초기 초기화 및 OS 독립적 펌웨어 로딩 후 OS Preboot 파티션의 2단계 iBoot(iBoot2)를 체인로드한다. LLB는 iBoot1의 이전 명칭이다.

   **iBoot2**: OS Preboot 파티션에 위치한 2단계 iBoot. 이 버전의 iBoot는 설치된 각 OS에 특화되어 있으며, OS 실행에 필요한 런타임 펌웨어 번들과 함께 패키징된다.

   **iBSS: iBoot Single Stage**. NOR이 손상되었을 때 DFU 부팅 과정에서 로드되는 1단계 iBoot(iBoot1/LLB)의 대체품.

   **iBEC: iBoot Epoch Change**. DFU 부팅 과정에서 로드되는 2단계 iBoot의 대체품.

  **IOMMU: I/O Memory Management Unit**, Apple의 DART에 대한 보다 일반적인 용어.

   **IOKit**: I/O Kit은 XNU(Apple의 운영 체제 커널)용 Apple의 장치 드라이버 프레임워크이다.

   **IPI: Inter-processor interrupt**. 한 프로세서가 다른 프로세서를 인터럽트하는 데 사용되는 인터럽트.

   **iSC: iBoot System Container**. 시스템 전체 부팅 데이터를 포함하는 디스크 파티션(일반적으로 내부 SSD의 첫 번째). (SW:Storage 참조)

J

   **JTAG: Joint Test Action Group**. 실제로는 해당 그룹에서 발표한 디버깅 인터페이스를 지칭하며, 하드웨어 수준에서 칩과 CPU를 디버깅하기 위한 4/5선 인터페이스이다.

K

  **kASLR: kernel Address Space Location Randomization**: 커널 코드가 부팅 시 메모리에 배치되는 위치를 무작위화하는 Linux 커널 기능. nokaslr 부팅 플래그를 지정하면 비활성화된다.

   **kcOS**: 커스텀 커널 캐시를 가진 OS.

   **Kernel cache**: 커널과 그 확장의 번들로, 선택적으로 암호화된다.

  **kmutil** 커널 확장(kext)을 관리하기 위한 macOS 커널 관리 유틸리티.
L

   **LLB: Low Level Bootloader**, iOS 플랫폼에서 물려받은 iBoot1의 이전 명칭.

M

  **Mux: Multiplexer**, USB, UART, SWD 모드 간에 한 세트의 핀을 전환하는 것처럼 여러 장치 중 하나를 단일 연결에 연결할 수 있는 장치.

   **Mini** - 내부 조사를 위한 커스텀 부트로더. SSD 부팅을 지원할 수도 있고 지원하지 않을 수도 있다.

N

   **NAND: Not-AND**는 논리 게이트의 한 유형이지만, 일반적으로 Flash 메모리의 한 유형을 지칭한다. SD 카드, SSD와 같은 모든 최신 대용량 Flash 기반 스토리지에 사용되며, 베어 칩으로도 제공된다.

   **NOR: Not-OR**는 논리 게이트의 한 유형이지만, 일반적으로 저용량 애플리케이션(최대 수 메가바이트)에만 사용되는 Flash 메모리의 한 유형을 지칭한다. NAND보다 견고하다. 요즘은 일반적으로 8핀 베어 칩으로 제공된다.

   **NVRAM: Non-Volatile RAM**. 이름은 구식이지만, 부팅 구성을 위해 Mac에 저장된 key=value 매개변수 목록을 의미한다. UEFI 변수와 유사하다.

O

   **1TR: One True RecoveryOS**. 전원 버튼을 길게 눌러 부팅할 때의 RecoveryOS 명칭이다. 이는 물리적 존재를 확인했으며 완전히 Apple이 신뢰하는 복구 환경을 실행하고 있음을 의미하고, 커스텀 OS 설치 권한과 같은 특별한 권한을 부여한다. 루트 접근 권한을 얻지만, Apple이 서명한 소프트웨어만 실행할 수 있으며, FileVault가 활성화된 경우 먼저 인증이 필요하다.

   **OpticID**는 Vision Pro 헤드셋에서 복잡한 알고리즘을 사용하여 홍채 데이터를 처리하는 Apple의 FaceID 생체 인식 및 인증 기술의 Apple AR 버전이다.

P

   **PMGR**: Power manager(전원 관리자).

R

   **RecoveryOS**: 복구 환경으로, OS 설치와 페어링된 복구 이미지(APFS 하위 볼륨 내에 위치) 또는 디스크의 마지막 APFS 컨테이너에 설치된 전역 복구 이미지가 될 수 있다. macOS 11.x는 기본적으로 전역 이미지를 사용하고, macOS 12.0 이상은 페어링된 recoveryOS를 사용한다.

   **RestoreOS**: Apple Configurator를 통해 DFU 모드로 기기를 "부활"시킬 때 기기에 로드되는 복원 환경.

   **ROM:** Read-Only Memory의 약자. 영구적 또는 반영구적 데이터를 포함하는 컴퓨터 메모리 칩을 지칭한다.

   **RTKit**: Apple의 독점 실시간 운영 체제. 대부분의 가속기(AGX, ANE, AOP, DCP, AVE, PMP)는 내부 프로세서에서 RTKit을 실행한다. "RTKSTACKRTKSTACK" 문자열은 RTKit을 포함하는 펌웨어의 특징이다.

   **RTOS**: Real-time operating system(실시간 운영 체제).

S

   **SBU: Sideband Use**. Type C 커넥터에서 Type C 표준 자체에 정의되지 않은 임의 용도로 자유롭게 사용할 수 있는 두 개의 핀.

   **SecureROM**: M1의 BootROM. NOR에서 iBoot1을 읽고 제어권을 넘기거나, DFU 모드로 폴백하는 역할을 담당한다.

   **SEP: Secure Enclave Processor**. M1에 내장된 HSM/TPM 등의 장치. Touch ID와 대부분의 암호화, 부팅 정책 결정을 처리한다. Linux에 무해하지만, 원한다면 그 기능을 사용할 수 있다. AP와 대조됨.

   **SFR: System Firmware and Recovery**, NOR의 구성 요소(iBoot1 등), iBoot System Container, System Recovery 파티션, 외부 Flash 메모리 및 기타 위치를 포함하여 시스템에 설치된 모든 OS가 공유하는 펌웨어 및 복구 이미지 모음. SFR은 항상 버전이 앞으로만 진행되며 뒤로 가지 않는다(전체 삭제를 통한 경우 제외).

   **SIP: System Integrity Protection**. "rootless"라고도 불리며, macOS 커널이 루트 사용자조차 일부 작업을 수행하지 못하게 차단한다.

   **SMC: System Management Controller**: 온도 센서, 전압/전력 측정기, 배터리 상태, 팬 상태, LCD 백라이트 및 덮개 스위치 등의 접근을 처리하는 하드웨어.

   **SOP: Start Of Packet**. USB-PD에서 패킷 유형을 구별하는 데 사용된다. SOP는 일반 통신용, SOP' 및 SOP"는 케이블의 내장 칩과 통신용, SOP'DEBUG 및 SOP"DEBUG는 Apple VDM과 같은 커스텀 벤더 전용 용도로 사용된다.

   **SPI: Serial Peripheral Interface**. 보드 내 칩 간 저속 통신을 위한 4선 표준.

   **SPMI: MIPI Alliance의 System Power Management Interface**: 2선 양방향 인터페이스, 다중 마스터(최대 4개), 다중 슬레이브(최대 16개), 32KHz~26MHz. [System Power Management Interface](https://en.wikipedia.org/wiki/System_Power_Management_Interface)를 참조.

   **SPRR: Shadow Permission Remap Registers(추정)**. 일반 페이지 권한 속성(AP, PXN, UXN)을 별도 테이블의 인덱스로 변환한다. 이 새 테이블이 실제 페이지 권한을 결정한다. 또한 동시에 쓰기 가능하고 실행 가능한 페이지를 허용하지 않는다.

   **SWD: Serial Wire Debug**. ARM 코어를 디버깅하는 데 사용되는 2핀 인터페이스로, 더 적은 핀으로 JTAG와 유사하다. Apple 기기에서 사용되지만, 보안 제한으로 인해 양산 기기에서는 메인 CPU/SoC에 접근할 수 없다.

T

   **TBT**: Thunderbolt Technology.

U

   **UART: Universal Asynchronous Receiver Transmitter**. 직렬 포트 뒤의 하드웨어.

   **USC: Unified shader core**. 모든 셰이더 유형(버텍스, 프래그먼트, 컴퓨트)을 지원하는 셰이더 코어. AGX는 통합 아키텍처이므로 이는 단순히 셰이더 코어를 지칭한다.

   **USB-PD: USB Power Delivery**. USB Type C를 통한 사이드밴드 통신 표준(정신 건강을 위해 이전 표준에 대해서는 다루지 않겠다). 사용 중인 케이블 종류 감지, 커넥터 방향, 공급 전압 구성, 비USB 모드 전환 등에 사용된다.

   **UFS-based multichip packages (uMCPs)**는 초고속 Universal Flash Storage (UFS) 컨트롤러를 활용하여 슬림한 디자인에 작은 풋프린트로 뛰어난 성능과 전력 절감을 제공하는 프로세스이다. 10GB 또는 12GB 메모리 모듈로 제공된다.

V

   **VBUS: 전원을 공급하는 USB 핀**. 기본값은 5V이며, USB-PD로 최대 20V까지 올라갈 수 있다.

   **VDM: Vendor Defined Message**. USB Alternate Mode(실제로는 독점적이지 않음)와 USB-PD를 통한 벤더 독점 명령 모두에 사용된다. Apple은 Type C 포트의 특수 모드를 구성하는 데 이를 사용한다.

   **VHE: Virtual Host Extensions**. OS/VM/사용자 공간 간의 보다 효율적인 전환을 위한 추가 레지스터. [ARM VHE explanation](https://developer.arm.com/documentation/102142/0100/Virtualization-Host-Extensions)을 참조.

   **visionOS**는 Vision Pro 헤드셋을 위한 Apple의 iPadOS/iOS와 유사한 운영 체제이다.

X

   **XNU**: macOS, iOS, iPadOS, watchOS, tvOS 등을 위한 Apple의 운영 체제 커널. "XNU"는 "X is not Unix"의 약자이다.
