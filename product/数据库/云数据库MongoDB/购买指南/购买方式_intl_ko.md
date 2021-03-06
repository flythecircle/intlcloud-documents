사용자는 [Tencent Cloud 공식 웹사이트](https://cloud.tencent.com/)에 로그인하여, 아래 그림에 나온 메뉴를 클릭하여 [MongoDB 제품 소개 페이지](https://cloud.tencent.com/product/mongodb)로 이동하십시오.
![](https://main.qcloudimg.com/raw/0ca36011c0ea72c457079c869a3149d7.png)
바로 구매 버튼을 클릭하여 [제품 구매 페이지](https://buy.cloud.tencent.com/mongodb)로 이동하십시오.
![](https://main.qcloudimg.com/raw/db8d147eeb15b9716516cf40271d4b04.png)
제품 구매 페이지는 다음과 같은 몇 가지 설정을 포함하고 있습니다. 자세한 설명은 다음과 같습니다.
### 요금제와 지역 ###
### 요금제 ###
현재 선택 가능한 요금제는 연/월정액 요금제와 사용량 기반 요금제입니다. 사용량 기반 요금제는 비즈니스 요구량이 순간적으로 크게 변동하는 시나리오에 적합합니다. 비즈니스 확장에 큰 변동성이 있고 예측할 수 없는 경우나 리소스를 사용할 때 임시적이거나 돌발적인 사항이 있는 경우에는, 사용량 기반 요금제를 권장합니다. 사용량 기반 요금제는 후불식이고 사용자가 문서 데이터베이스를 생성할 때 계정 내 한 시간만큼의 하드웨어 비용을 동결하고 세분화 단위는 초입니다. 요금은 미리 지불할 필요 없이 TencentDB for MongoDB의 실제 사용량에 따라 청구하면 됩니다. 연/월정액 요금제는 비즈니스 양이 비교적 안정적인 장기 비즈니스에 적합합니다. 사용량 기반 요금제보다 비용이 더 저렴합니다. 연/월정액 요금제는 선불식이고 사용자가 구매할 때, 자신의 비즈니스 요구에 따라 1개월 또는 몇 개월/년의 TencentDB for MongoDB 비용을 선불로 지급합니다.
#### 지역 ####
Tencent Cloud 호스팅 데이터 센터는 전세계 여러 곳에 분포되어 있습니다. 중국 국내에는 화남, 화동, 화북, 서남 네 지역을 포함하고 있으며 중국 대륙 이외는 동남아, 아시아 태평양 지역, 미국 서부, 미국 동부, 북미, 유럽 등 여러 지역을 포함하고 있습니다. 또한, 당사는 더 많은 노드를 충족시키기 위해 점점 지역을 넓혀가고 있습니다. 현재 인스턴스 생성을 지원하는 지역은 광저우, 상하이, 베이징, 청두, 충칭, 홍콩, 싱가포르, 서울, 뭄바이, 방콕, 실리콘 밸리, 토론토, 버지니아, 프랑크푸르트, 모스크바입니다. 금융 전용 지역을 지원하는 지역은 선전 금융, 및 상하이 금융입니다.<br>
설명: <br>
- 동일 지역의 클라우드 서비스 제품은 사설망으로 서로 연결할 수 있습니다. 그러나 다른 계정의 리소스 사설망은 완전히 격리되어 있습니다.
- 다른 지역의 클라우드 서비스 제품은 사설망으로 서로 연결할 수 없습니다.
- Tencent Cloud의 리소스는 지역 간의 사설망 액세스를 지원하지 않습니다.
- 클라우드 서비스 구매 시, 액세스 지연을 줄이기 위해 가장 가까운 지역을 선택하는 것을 권장합니다.

#### 가용 영역 #### 
가용 영역은 Tencent Cloud가 동일 지역에서 구축한 전력과 네트워크가 서로 독립된 물리적인 IDC를 말합니다. 가용 영역 간에 고장을 서로 격리시키고(대형 재해 또는 대형 전력 고장 제외) 고장의 확산을 방지하여 고객의 비즈니스가 온라인 서비스를 지속적으로 제공할 수 있게 합니다. 또한, 동일 지역 내에 가용 영역 간에 사설망이 서로 연결되어 동일 가용 영역 내에 제품의 네트워크 지연이 더 줄어듭니다.
#### 기본 구성 ####
기본 구성은 서버 유형, 데이터베이스 버전, 스토리지 엔진, 인스턴스 유형, 샤딩 노드 수, 컴퓨팅 리소스 사양, 스토리지 용량 등을 포함합니다. 자세한 설명은 다음과 같습니다.
#### 구성 유형 ####
현재는 다음 두 종류의 서버 유형이 있습니다. 높은 IO 형과 높은 IO 10 기가비트형.
#### 버전 ####
현재 선택 가능한 데이터베이스 버전은 3.2입니다. 3.6 버전은 곧 출시할 예정입니다.
#### 엔진 ####
TencentDB for MongoDB는 WiredTiger와 Rocks 스토리지 엔진을 지원합니다.
#### 인스턴스 유형과 노드 수 ####
인스턴스는 복제본 세트와 샤딩을 포함합니다. 복제본 세트 인스턴스를 선택하면 시스템이 기본적으로 마스터 한 개와 슬레이브 두 개의 아키텍처로 설정합니다. 샤딩 클러스터를 선택하면 샤딩의 수량과 샤딩당 노드 수를 자유롭게 선택할 수 있습니다. 샤딩은 마스터 한 개와 슬레이브 구 개의 구성이 기본적입니다. 데이터의 가용성을 높이기 위해 샤딩당의 노드 수를 늘릴 수 있고 클러스터의 저장 가능한 용량을 증가하기 위해 샤딩 수를 늘릴 수 있습니다.
#### 사양 ####
선택 가능한 컴퓨팅 규격은 다음 표와 같습니다.<br>

| CPU/노드 | 메모리/노드| 
| ------- |-------|
| 1코어 | 2GB |
| 2코어 | 4GB |
| 4코어 | 8GB |
| 6코어 | 16GB |
| 12코어 | 32GB |
| 24코어 | 64GB |
| 24코어 | 128GB |
| 32코어 | 240GB |

#### 용량 ####
사용자는 컴퓨팅 사양에 따라 이에 맞는 스토리지 규격을 선택할 수 있습니다. 시스템에서는 기본적으로 oplog 저장 공간이 선택한 스토리지 용량의 10%로 설정되며 oplog의 크기는 사용자가 공식 웹사이트 콘솔에서 자유롭게 조정할 수 있습니다.
### 네트워크와 프로젝트 ###
#### 네트워크 유형 ####
네트워크 유형은 VPC와 기본 네트워크를 지원합니다. 기본 네트워크를 선택하면 기본 네트워크 장치만 생성한 데이터베이스 인스턴스를 액세스할 수 있습니다. VPC를 선택하면 서브넷의 장치만 생성한 데이터베이스 인스턴스를 액세스할 수 있습니다.
#### 프로젝트 ####
사용자의 비즈니스 요구에 적합한 프로젝트를 선택합니다.
### 구매 수량과 시간 ###
#### 구매 수량 ####
사용자가 선택할 수 있는 연/월정액 요금제 인스턴스 수량은 10입니다. 모든 지역에서 사용량 기반 요금제 인스턴스 수량은 30입니다.
#### 구매 시간 ####
연/월정액 요금제를 선택할 경우, 구매 가능한 최장 시간은 3년입니다. 또한 사용자는 할인 혜택으로 6개월 이상 12% 할인, 2년 60% 할인, 3년 70% 할인을 받을 수 있습니다.

