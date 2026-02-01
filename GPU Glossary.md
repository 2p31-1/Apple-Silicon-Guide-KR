# GPU 용어집

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/138614121-28110c11-cc0b-4115-8335-8cb30a6bfe32.png">
<br />
애플리케이션 코드를 실행할 때 CPU와 GPU가 함께 작동하는 방식
</p>

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/138614114-a0fdd83a-b885-42b8-849f-f45691091454.png">
<br />
통합 메모리 아키텍처
</p>


A

  [ASIC (Application Specific Integrated Circuits)](https://en.wikipedia.org/wiki/Application-specific_integrated_circuit)은 임베디드 시스템, 휴대폰, 개인용 컴퓨터, 전문 워크스테이션 등에서 범용 목적이 아닌 특정 용도에 맞게 설계된 집적 회로(IC) 칩입니다.

  [Apple Hypervisor](https://developer.apple.com/documentation/hypervisor)는 타사 커널 확장 없이 경량 하이퍼바이저 위에 가상화 솔루션을 구축하는 프레임워크입니다. Hypervisor는 C API를 제공하여 커널 확장(KEXT)을 작성하지 않고도 사용자 공간에서 가상화 기술과 상호 작용할 수 있습니다. 따라서 이 프레임워크를 사용하여 만든 앱은 [Mac App Store](https://www.appstore.com/)에서 배포하기에 적합합니다.

   [Apple Virtualization Framework](https://developer.apple.com/documentation/virtualization)는 Apple Silicon 및 Intel 기반 Mac 컴퓨터에서 가상 머신을 생성하고 관리하기 위한 고수준 API를 제공하는 프레임워크입니다. 이 프레임워크는 사용자가 정의한 사용자 정의 환경에서 Linux 기반 운영 체제를 부팅하고 실행하는 데 사용됩니다. 또한 네트워크, 소켓, 직렬 포트, 스토리지, 엔트로피 및 메모리 벌룬 장치를 포함한 많은 장치 유형에 대한 표준 인터페이스를 정의하는 [Virtio 사양](https://www.redhat.com/en/virtio-networking-series)을 지원합니다.

   [Apple Paravirtualized Graphics Framework](https://developer.apple.com/documentation/paravirtualizedgraphics)는 가상 머신에서 실행되는 macOS(이하 게스트)를 위한 하드웨어 가속 그래픽을 구현하는 프레임워크입니다. 운영 체제는 게스트 내부에서 실행되는 그래픽 드라이버를 제공하며, 이 드라이버는 호스트 운영 체제의 프레임워크와 통신하여 Metal 가속 그래픽을 활용합니다.

B


C

   [CPU (Central Processing Unit)](https://en.wikipedia.org/wiki/Central_processing_unit)는 컴퓨터 프로그램을 구성하는 명령어를 실행하는 여러 코어로 구성된 회로입니다. CPU는 프로그램의 명령어로 지정된 기본 산술, 논리, 제어 및 입출력(I/O) 연산을 수행합니다. 이는 주 메모리, I/O 회로 및 그래픽 처리 장치(GPU)와 같은 다른 외부 구성 요소와 다릅니다.

   [CMOS (Complementary Metal-Oxide Semiconductor)](https://www.computerhope.com/jargon/c/cmos.htm)는 BIOS 설정을 저장하는 컴퓨터 마더보드의 소량의 메모리입니다. 이러한 BIOS 설정에는 시스템 시간과 날짜, 하드웨어 설정이 포함됩니다.

D

**[Dynamic Caching](https://patents.google.com/patent/US20210271606A1/)**은 M3 시리즈 칩에서 실시간으로 로컬 메모리 사용을 할당하는 Apple의 새로운 GPU 프로세스입니다. 이를 통해 게임, 비디오 렌더링, 3D 그래픽과 같은 특정 작업에 필요한 정확한 양의 메모리가 사용됩니다.

E

 [ECC (Error Correction Code) 메모리](https://www.crucial.com/products/memory/server/ecc)는 단일 비트 메모리 오류를 감지하고 수정하는 방법입니다. 단일 비트 메모리 오류는 서버 출력 또는 생산에서의 데이터 오류이며, 오류의 존재는 서버 성능에 큰 영향을 미칠 수 있습니다. 단일 비트 메모리 오류에는 **하드 오류와 소프트 오류** 두 가지 유형이 있습니다. **하드 오류**는 과도한 온도 변화, 전압 스트레스 또는 메모리 비트에 가해지는 물리적 스트레스와 같은 물리적 요인으로 인해 발생합니다. **소프트 오류**는 마더보드의 전압 변화, 우주선 또는 방사성 붕괴로 인해 메모리의 비트가 뒤집힐 수 있어 데이터가 원래 의도와 다르게 쓰이거나 읽힐 때 발생합니다.

  [EEPROM (Electrically Erasable Programmable Read-Only Memory)](https://www.futureelectronics.com/c/semiconductors/memory--RAM--eeprom)은 스마트 카드/원격 무선 시스템용 마이크로컨트롤러와 기타 전자 장치에 통합되어 애플리케이션에서 필요에 따라 개별 바이트를 지우고 다시 프로그래밍할 수 있도록 하여 비교적 적은 양의 데이터를 저장하는 데 사용되는 비휘발성 메모리 유형입니다.

  [EPROM](https://www.minitool.com/lib/eprom.html)은 전원이 꺼져도 데이터가 손실되지 않는 메모리 칩입니다. 이것은 비휘발성 메모리 유형이므로 전원이 꺼져도 데이터를 유지합니다. 각 EPROM은 전자 장치에 의해 개별적으로 프로그래밍됩니다.

F

G

   [GPU (Graphics Processing Unit)](https://en.wikipedia.org/wiki/Graphics_processing_unit)는 수천 개의 스레드를 동시에 처리할 수 있는 수백 개의 코어로 구성된 회로입니다. GPU는 디스플레이 장치로 출력하기 위한 프레임 버퍼에서 이미지 생성을 가속화하기 위해 메모리를 빠르게 조작하고 변경할 수 있습니다. 임베디드 시스템, 휴대폰, 개인용 컴퓨터, 전문 워크스테이션 및 게임 콘솔에서 사용됩니다.


   [GDDR (Graphics Double Data Rate) SDRAM](https://en.wikipedia.org/wiki/GDDR6_SDRAM#GDDR6X)은 그래픽 카드, 게임 콘솔 및 고성능 컴퓨팅에 사용하도록 설계된 고대역폭("더블 데이터 레이트") 인터페이스를 갖춘 동기식 그래픽 랜덤 액세스 메모리(SGRAM)의 한 유형입니다.

H

  [HVM (Hardware Virtual Machine)](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/virtualization_types.html)은 베어메탈 하드웨어에서 실행되는 것처럼 수정 없이 가상 머신 위에서 직접 운영 체제를 실행할 수 있는 기능을 제공하는 가상화 유형입니다.

I

  [ISP (Image Signal Processing)](https://en.wikipedia.org/wiki/Image_processor)는 특수한 유형의 미디어 프로세서를 사용하여 노이즈 감소, 자동 노출, 자동 초점, 자동 화이트 밸런스, HDR 보정 및 이미지 선명화와 같은 작업을 수행하여 이미지를 디지털 형식으로 변환하는 프로세스입니다.

J

K

  [KVM (Kernel-based Virtual Machine)](https://www.linux-kvm.org/page/Main_Page)은 가상화 확장(Intel VT 또는 AMD-V)을 포함하는 x86 하드웨어의 Linux용 전체 가상화 솔루션입니다. 핵심 가상화 인프라를 제공하는 로드 가능한 커널 모듈 kvm.ko와 프로세서별 모듈 kvm-intel.ko 또는 kvm-amd.ko로 구성됩니다.

L

M

   [메모리 모듈](https://en.wikipedia.org/wiki/Memory_module)은 메모리 집적 회로가 장착된 인쇄 회로 기판입니다. 메모리 모듈은 개인용 컴퓨터, 워크스테이션 및 서버와 같은 전자 시스템에서 쉬운 설치 및 교체를 가능하게 합니다.

N

  [NIC (Network Interface Card)](https://www.ni.com/en-us/support/documentation/supplemental/11/best-practices-for-using-multiple-network-interfaces--nics--with.html)는 네트워크 인터페이스 컨트롤러, 네트워크 어댑터 또는 LAN(Local Area Network) 어댑터입니다. 컴퓨터 및 서버와 같은 장치에 네트워크 연결을 제공합니다.

  [NTB (Non-Transparent Bridging)](https://docs.nvidia.com/drive/drive_os_5.1.6.1L/nvvib_docs/index.html#page/DRIVE_OS_Linux_SDK_Development_Guide/System%20Programming/sys_components_non_transparent_bridging.html#)는 도메인 간 통신을 가능하게 하여 서로 다른 스위치 파티션의 장치 간 통신을 용이하게 하는 프로세스입니다. 이 기능을 통해 호스트와 EP 모두 다른 스위치 파티션의 호스트 및/또는 EP에 트랜잭션을 시작할 수 있습니다. NTB 또는 NT 상호 연결은 브리징 기능으로 상호 연결된 Type 0 PCI 헤더로 정의된 두 개 이상의 PCI 기능으로 구성됩니다. Type 0 PCI 기능은 Non-Transparent EP(NT EP)라고 합니다. 각 파티션에는 최대 하나의 NT EP가 있을 수 있습니다.

O


   [oVirt](https://www.ovirt.org)는 전체 엔터프라이즈 인프라를 관리하도록 설계된 오픈 소스 분산 가상화 솔루션입니다. oVirt는 신뢰할 수 있는 KVM 하이퍼바이저를 사용하며 libvirt, Gluster, PatternFly 및 Ansible을 포함한 여러 다른 커뮤니티 프로젝트를 기반으로 구축되었습니다. Red Hat이 커뮤니티 프로젝트로 설립했으며 Red Hat Enterprise Virtualization의 기반이 되어 사용하기 쉬운 웹 기반 프론트엔드에서 플랫폼에 독립적인 액세스로 가상 머신, 컴퓨팅, 스토리지 및 네트워킹 리소스의 중앙 집중식 관리를 가능하게 합니다.

  [Open vSwitch(OVS)](https://www.openvswitch.org/)는 오픈 소스 Apache 2.0 라이선스로 라이선스된 오픈 소스 프로덕션 품질의 다중 계층 가상 스위치입니다. 표준 관리 인터페이스 및 프로토콜(NetFlow, sFlow, IPFIX, RSPAN, CLI, LACP, 802.1ag)을 지원하면서도 프로그래밍 방식 확장을 통해 대규모 네트워크 자동화를 가능하게 하도록 설계되었습니다.

P

  [PV (ParaVirtualization)](https://wiki.xenproject.org/wiki/Paravirtualization_(PV))는 Xen Project 팀이 도입하고 나중에 다른 가상화 솔루션에서 채택한 효율적이고 경량의 가상화 기술입니다. PV는 호스트 CPU의 가상화 확장이 필요하지 않으므로 하드웨어 지원 가상화를 지원하지 않는 하드웨어 아키텍처에서도 가상화가 가능합니다.

Q

  [QEMU](https://www.qemu.org)는 휴대용 동적 변환기를 사용하는 빠른 프로세서 에뮬레이터입니다. QEMU는 프로세서와 다양한 주변 장치를 포함한 전체 시스템을 에뮬레이트합니다. PC를 재부팅하지 않고 다른 운영 체제를 시작하거나 시스템 코드를 디버그하는 데 사용할 수 있습니다.

R

  [RAM (Random Access Memory)](https://en.wikipedia.org/wiki/Random-access_memory)은 일반적으로 작업 데이터와 기계 코드를 저장하는 데 사용되며 어떤 순서로든 읽고 변경할 수 있는 컴퓨터 메모리의 한 형태입니다. 랜덤 액세스 메모리 장치는 다른 직접 액세스 데이터 저장 매체와 달리 메모리 내 데이터의 물리적 위치와 관계없이 거의 동일한 시간 내에 데이터 항목을 읽거나 쓸 수 있습니다.

  [RDMA (Remote Direct Memory Access) fabrics](https://core.vmware.com/resource/basics-remote-direct-memory-access-rdma-vsphere)는 CPU 개입 없이 호스트 메모리에 직접 액세스하는 기능인 DMA(Direct Memory Access) 기술의 확장입니다. RDMA는 한 호스트에서 다른 호스트로 메모리 데이터에 액세스할 수 있게 합니다. RDMA의 핵심 특성은 네트워크 패킷을 처리하는 데 필요한 CPU 사이클이 줄어들기 때문에 처리량과 성능이 크게 향상된다는 것입니다.

  [RT (Real-time ray tracing) Core](https://developer.nvidia.com/blog/nvidia-turing-architecture-in-depth/)는 BVH(Bounding Volume Hierarchy) 순회 및 레이/삼각형 교차 테스트(레이 캐스팅) 기능을 가속화하는 하드웨어 기반 레이 트레이싱 가속기입니다. RT Core는 SM에서 실행되는 스레드를 대신하여 가시성 테스트를 수행하여 다른 버텍스, 픽셀 및 컴퓨트 셰이딩 작업을 처리할 수 있게 합니다.

S

  [SIMD (Single Instruction, Multiple Data)](https://en.wikipedia.org/wiki/SIMD)는 여러 데이터 포인트에서 동시에 동일한 작업을 수행하는 여러 처리 요소가 있는 컴퓨터를 설명하는 병렬 처리 유형입니다.

  [보안 가상 메모리](https://support.apple.com/guide/mac-help/what-is-secure-virtual-memory-on-mac-mh11852/mac)는 가상 메모리의 데이터를 암호화하는 macOS에서 사용되는 기술입니다. 보안 가상 메모리는 항상 켜져 있으므로 하드 디스크와 RAM 간에 데이터가 교환되는 동안 데이터가 안전하게 유지됩니다. Mac의 RAM은 전원이 꺼져 있을 때 정보를 포함하지 않습니다.

T

   [TLP (Transaction Layer Packets)](https://www.oreilly.com/library/view/pci-express-system/0321156307/0321156307_ch04lev1sec5.html)는 아웃바운드 TLP(Transaction Layer Packets) 조립의 시작점이자 수신기에서 인바운드 TLP 분해의 끝점입니다. 그 과정에서 각 장치의 데이터 링크 계층과 물리 계층이 패킷 조립 및 분해에 기여합니다.

U

   [UFS (Universal Flash Storage)](https://www.jedec.org/standards-documents/focus/flash/universal-flash-storage-ufs)는 스마트폰 및 태블릿과 같은 모바일 시스템뿐만 아니라 자동차 애플리케이션을 포함하여 전력 소비를 최소화해야 하는 애플리케이션에서 사용하도록 설계된 개방형 표준 고성능 인터페이스입니다. 고속 직렬 인터페이스와 최적화된 프로토콜을 통해 처리량과 시스템 성능을 크게 향상시킬 수 있습니다.

  **uMCP (UFS 기반 멀티칩 패키지)**는 슬림한 디자인을 위해 작은 폼팩터에서 큰 성능과 전력 절감을 제공하기 위해 초고속 UFS(Universal Flash Storage) 컨트롤러를 활용하는 프로세스입니다. 10GB 또는 12GB 메모리 모듈로 제공됩니다.

V

  [VRAM (Video Random Access Memory)](https://en.wikipedia.org/wiki/VRAM)은 이미지 또는 그래픽 관련 데이터를 저장하기 위해 할당된 RAM입니다. RAM과 동일한 방식으로 작동하며 더 쉬운 액세스와 성능을 위해 특정 데이터를 저장합니다. 이미지 데이터는 먼저 프로세서에 의해 읽히고 VRAM에 쓰입니다. 그런 다음 [RAMDAC](https://en.wikipedia.org/wiki/RAMDAC) 또는 RAM 디지털-아날로그 변환기에 의해 변환되어 그래픽 출력으로 표시됩니다.

  [벡터 프로세서](https://en.wikipedia.org/wiki/Vector_processor)는 벡터라고 하는 대규모 1차원 데이터 배열에서 효율적이고 효과적으로 작동하도록 설계된 명령어 세트를 구현하는 중앙 처리 장치(CPU)입니다.

  [가상 메모리](https://en.wikipedia.org/wiki/Virtual_memory)는 하드웨어(중앙 처리 장치(CPU))와 소프트웨어를 모두 사용하여 구현되는 메모리 관리 기술입니다. 이는 프로그램이 사용 가능한 저장 공간 또는 주소 공간이 있다고 생각하게 만듭니다. 실제로 가상 메모리는 일반적으로 여러 물리적 메모리 조각으로 나뉘어 필요할 때 데이터를 교환하는 데 사용할 수 있는 디스크 저장소(SSD 또는 HDD)에 저장됩니다. Windows에서는 이를 [페이지 파일](https://docs.microsoft.com/en-us/windows/client-management/introduction-page-file)이라고 하고 Linux에서는 [스왑 공간](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/7/html/storage_administration_guide/ch-swapspace)이라고 합니다.

W

X

Y

Z
