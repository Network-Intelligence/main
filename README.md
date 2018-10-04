### Network-Intelligence (Private Github)

<sub> Network Intelligence는 인공지능 기술을 이용한 NFV (Network Function Virtualization) 환경에서의 물리/가상 자원 관리기술 개발을 목적으로 하는 연구 프로젝트입니다. 본 연구는 NFV 환경의 가상 네트워크 및 물리/가상 자원을 실시간으로 감시하고 효과적으로 제어하기 위해 NFV 운용 전반에 걸친 라이프사이클 관리에 필수적인 기능들을 다양한 인공지능 기반의 알고리즘으로 개발하고 이를 검증하는 것을 목표로 합니다. </sub>
      
![alt tag](https://github.com/Network-Intelligence/private/blob/master/Images/Architecture.png)

### Network-Intelligence 프로젝트 연구 개발내용
**1. NFV 모니터링 기술 개발**
* <sub> NFV를 구성하는 가상 네트워크 및 물리/가상 자원의 상태 감시 기술 개발. </sub>
* <sub> NFV는 기본적으로 클라우드 컴퓨팅 환경에서 구축되므로 물리적 서버와 네트워크의 상태감시뿐 아니라 하이퍼바이저와 가상 서버(VM: Virtual Machine)의 상태 및 가상 서버들 간의 트래픽 정보, 실제 네트워크 기능을 수행하는 VNF(Virtual Network Function: 응용기능)의 상태를 실시간으로 감시하는 기능의 개발이 필요함. NFV 모니터링 기능은 이러한 정보의 수집 및 수집한 데이터를 머신러닝에 적합한 형태로 변환하는 기능을 제공함. </sub>

**2. VNF Deployment 기능 개발**
* <sub> 다양한 가상 서버와 가상 네트워크로 구성되는 NFV 환경에서 다양한 요구조건을 갖는 VNF(응용기능)들을 배치하는 기능. VNF 특성에 따라 최적의 자원을 할당하고, 적합한 위치의 물리 노드 위에 VNF를 자동 배치하는 기능을 머신러닝(딥러닝 포함) 기술로 개발함. </sub>

**3. Service Function Chaining (SFC) 기능 개발**
* <sub> 네트워크 사용자의 서비스 요구사항에 따라 여러 개의 VNF를 순서에 따라 연결하는 기능. VNF를 구성하는 가상서버 노드의 부하와 링크 대역폭 및 지연을 최소화하고, 장애에 동적으로 대응하는 Service Function Chaining 기능을 머신러닝 기술로 개발함. </sub>

**4. VNF Resource Demand Prediction 기능 개발**
* <sub> VNF가 요구할 자원의 수요를 미리 예측하는 기능. VNF와 이에 연결된 다른 VNF 정보를 이용하여 머신러닝 기술로 개발함. </sub>

**5. VNF Auto-scaling 기능 개발**
* <sub> VNF 자원 사용량 및 트래픽 부하에 따라 VNF에 할당된 자원(가상 서버)을 동적으로 증감시키는 기능. Scaling 작업 중 성능저하 없이 사용자의 QoS/QoE를 보장하고, NFV 자원 사용량을 최적화하는 Auto-scaling 기능을 머신러닝 기술로 개발함. </sub>

**. Anomaly Detection & Attack and Intrusion Detection 기능 개발**
* <sub> NFV의 성능 저하를 막기 위해, VNF 또는 가상 및 물리 서버의 비정상 행위를 미리 검출하여 통보하는 기능과  NFV 플랫폼을 공격하거나 침입하는 등의 이상 징후를 탐지하고 보호하는 기능을 머신러닝 기술을 이용하여 개발함. </sub>

**7. VNF Live Migration 기능 개발**
* <sub> 전반적인 장애발생 가능성을 사전에 예측하여 VNF가 배치된 가상머신을 실시간으로 이동시키는 VNF Live Migration 기능. 본 기능을 머신러닝 기술을 기반으로 개발하여 VNF의 down time을 최소화하고, WAN 환경에서 가상머신을 이동시킬 경우 발생할 수 있는 IP 주소 변경 문제를 LISP 프로토콜 기반으로 해결함. </sub>

**8. VNF Electricity Power Management 기능 개발**
* <sub> NFV 환경에서 구동되는 모든 VNF의 SLA(Service Level Agreement)를 충족시키는 범위 내에서 최소한의 물리 노드에서 VNF를 구동하게 하여 전력비용을 절감하는 Electricity Power Management 기능을 머신러닝 기술을 기반으로 개발함. </sub>

**9. 인공지능 기반 NFV 관리 플랫폼 연구 개발**
* <sub> 상기와 같은 NFV 라이프사이클 관리 필수기능들을 통합 운용하는 NFV 관리 플랫폼을 개발하여 기능과 성능의 시험 및 검증(PoC)을 수행하고자 함. </sub>
