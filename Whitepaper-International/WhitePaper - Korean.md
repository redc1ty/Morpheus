![Morpheuslogo](https://github.com/MorpheusAIs/Morpheus/assets/1563345/235b9c04-f3b1-4520-a328-2070c9c890ab)

# Morpheus
## 스마트 에이전트를 구동하기 위한 네트워크
### Morpheus팀 Trinity, & Neo 작성
작성 - 2023년 9월 2일

기술 세부정보에 대한 Yello Paper 링크: https://github.com/MorpheusAIs/Morpheus/blob/main/YellowPaper.md

## 소개
Morpheus는 스마트 에이전트(Smart Agent)로 알려진 최초의 개인 AI로 이루어진 P2P 네트워크를 장려하도록 설계되었습니다. 사용자에게 지갑, Dapp 및 스마트 컨트랙트에 연결할 수 있는 오픈 소스 스마트 에이전트를 제공하게 되면 모든 사람들에게 Web3의 세계를 개방할 수 있게 됩니다.

마침내, 일반 사용자는 스마트 에이전트와 평이한 언어로 대화하여 질문을 이해하고 의도/승인에 따라서 특정 행동을 수행할 수 있습니다. 이는 Google의 검색 엔진이 1990년대 후반 초기 인터넷을 사용하기 쉬운 웹 인터페이스를 통해 대중에게 개방하였던 방식과 유사합니다.

모두가 스마트 에이전트에 접근할 수 있도록 하고 인프라의 분산화를 높이기 위해 우리는 Morpheus 네트워크 개발을 제안합니다. Morpheus 네트워크에는 네트워크의 주요 기여자 4개의 그룹 모두에게 보상을 제공하기 위해 상당히 출시된 토큰("MOR" 토큰)이 존재합니다. 4개의 주요 기여자 그룹은 1. 인터페이스를 구축하는 빌더, 2. Morpheus 소프트웨어/에이전트에 기여하는 코더, 3. 유동성을 추가하는 자본 제공자, 4. 연산, 스토리지 및 대역폭을 제공하는 커뮤니티 집합입니다. 한정된 가상자산에 대한 자유롭고 공개적인 경쟁이 장기간에 걸쳐 퍼블릭 블록체인을 위한 확장 가능한 인프라를 제공할 수 있다는 것은 비트코인과 이더리움의 역사를 통해 잘 입증되었습니다.

![MorpheusNetworkDiagram](https://github.com/MorpheusAIs/Morpheus/assets/1563345/f0960e25-80e3-42ed-aa1f-ad9792eb672d)

## 배경 & 역사
OpenAI, Microsoft, Google과 같은 기존 업체는 소스코드가 공개되지 않은(클로즈드 소스의) 대규모 언어 모델을 실행하고 고객에게 라이선스 비용을 청구하며 고객 데이터로 수익을 창출하고 있습니다. 이 모델은 검열이 존재하고 취약하며 벽으로 둘러싸인 정원처럼 폐쇄된 환경에서 작동합니다. 무료로 제공되는 오픈 소스 대규모 언어 모델에 대한 수요가 높습니다. Llama, Falcon 및 기타 오픈 소스 LLM이 최근 출시되었으며 클로즈드 소스 기반 경쟁업체의 성능에 빠르게 도달해나가고 있습니다.

이러한 오픈 소스 LLM에는 현재 사용자가 채팅할 수 있는 표준 그래픽 인터페이스(GUI), 개발자를 위한 API, 장치 간 이동을 위한 클라우드 솔루션, 사용자 데이터 및 복구 프로세스를 관리하는 방법이 부족합니다. 스마트 에이전트 프로토콜은 바로 여기서 등장하는데, 이를 통해 로컬로 실행되는 오픈 소스 LLM을 제공하고 사용자의 Web3 지갑에 의해 관리할 수 있게 됩니다.

그러나 로컬 접근 방식에는 개발자가 구축할 수 있는 API, 사용자 네트워크가 고성능 하드웨어에서 라이트 클라이언트(풀노드를 다운로드하거나 스마트 에이전트를 로컬 환경에 다운로드할 필요가 없음)와 같은 사용 사례들을 가능하게 하는 소프트웨어를 실행할 수 있는 클라우드 솔루션이 여전히 부족합니다.

## Morpheus 시작
Morpheus는 스마트 에이전트 커뮤니티에 퍼블릭 블록체인 인프라를 제공하는 사람들에게 보상하기 위해 네트워크와 토큰을 출시하여 이러한 API와 분산형 클라우드 기능을 제공할 것입니다. 스마트 에이전트 프로토콜의 구현을 통해 Morpheus는 오픈 소스 기반 개인 AI가 오늘날 폐쇄형 GPT 모델을 제공하는 기술 회사 제품의 성능에 도달하고 능가하는 데 필요한 리소스를 수집하려고 합니다.

Morpheus는 당장 장점이 많습니다. Web3 기반이기 때문에 사용자는 암호화폐를 구매 또는 판매하고, 스테이블코인을 전송하고, 스마트 컨트랙트에 액세스하고, 현재 LLM이 연결되어 있지 않은 Dapp 및 DeFi 서비스를 사용할 수 있습니다. 중앙화된 회사들의 규제 장벽에 부딪혀 이러한 도구를 사용자에게 제공할 수 없으므로 그들의 모델은 작업에 대해 대화할 수 있지만 Web3 환경에서 사용자를 대신하여 행동할 수는 없습니다. 분산형 공용 인프라에서 실행하는 것은 모든 신규 사용자에게 있어 Chat GPT에 라이센스 비용을 지불하는 것보다 저렴합니다.

Morpheus는 새로운 에이전트/LLM을 무료로 신속하게 가동할 수 있기를 원하는 개발자를 위한 Linux 유형의 새로운 대안입니다. 사용자는 자신의 비즈니스 또는 개인 데이터에 대한 소유권을 유지할 수 있습니다. 이를 통해 경쟁업체의 유출, 해킹, 공격을 방지할 수 있습니다. Morpheus에 코드를 기여한 것뿐만 아니라 보다 전문화된 에이전트를 구축한 개발자에게 보상함으로써 사용자를 위한 App Store/Agent Store 유형의 경험이 개발될 것입니다. 사용자가 소유한 데이터, 프롬프트 및 기록의 지속성을 통해 스마트 에이전트 프로토콜은 LLM 및 에이전트 세계에서 상호 운용성을 위한 최고의 솔루션이 됩니다.

마지막으로, 그래픽 사용자 인터페이스(GUI)를 갖추고, Electron을 활용하여 원클릭 설치로 패키징함으로써 Morpheus는 유명한 "Friedl 테스트"를 통과한 최초의 오픈 소스 AI가 되었습니다. Friedl Test는 소프트웨어의 사용에 대해 처음으로 기술과 관련없는 일반 대중까지도 소프트웨어에 액세스할 수 있게 만드는 시점을 벤치마킹하는 최소요구값입니다.

## 토큰 보상 & 경제
우리는 위의 내용을 위해 Morpheus 토큰(기호 "MOR")을 제안합니다.
MOR은 매일 커뮤니티에 24%, 자본에 24%, 컴퓨팅에 24%, 코더에 24%의 보상을 제공하며 4%의 자금은 보호기금으로 할당됩니다.

이는 Morpheus가 성장하기 위해 다음이 필요하다는 사실을 반영합니다:

커뮤니티 - 빌더는 프런트엔드/도구를 만들고 사용자를 Morpheus 생태계로 안내합니다.

자본 - 컴퓨팅 및 코드에 대한 자금을 조달합니다.

컴퓨팅 - 장비와 전력을 제공합니다.

코더 - 프런트엔드, 자본 및 컴퓨팅을 사용할 수 있는 인텔리전스를 제공합니다.

MOR 토큰 공급은 최대 42,000,000개의 토큰으로 제한됩니다. 분배는 네트워크에 작업 증명(노동) 및 지분 증명(자본) 형식을 제공하여 4개 그룹 모두 토큰을 획득하는 것으로 시작됩니다. 사전 채굴 및 조기 토큰 판매 없이 공정하게 출시(Fair Launch)됩니다.

![MOREmissionsCurve2](https://github.com/MorpheusAIs/Morpheus/assets/1563345/3514217c-50ed-4639-8c5d-87ca5cfb5d1b)

블록 보상은 하루 14,400 MOR부터 시작하여 5,833일째에 보상이 0에 도달할 때까지 매일 2.468994701 MOR씩 감소합니다. 그 때(지금으로부터 약 16년 후)쯤에는 Morpheus가 널리 사용되고, 수수료가 주요 인센티브로 자리잡게 될 것입니다. 수수료는 데이터에 대해 사용자에게 지불되는 수수료, 연산 제공자에 대한 수수료, 자본 제공자에 대한 수수료 및 코더에 대한 수수료로 구분됩니다.

**MOR 토큰의 최대 공급량은 4200만개입니다.** 
하루 14,400개의 토큰이 커뮤니티 사용자, 자본, 코드, 컴퓨팅 간에 균등하게 분배됩니다.
- 컴퓨팅용 토큰 3,456개. API 호출 처리에 대한 거래 증명.
- 코드용 토큰 3,456개. Morpheus 코드저장소에 대한 코드 Commit 및 Merge 증명.
- 자본금은 3,456개.  기여한 stETH 증명 및 수익에 대해 50%는 MOR로 교환되었으며 나머지는 유동성 공급자로서 AMM에 고정.
- 커뮤니티용 토큰 3,456개. 사용자 참여를 유도하는 프런트엔드 애플리케이션 및 도구를 통해 증명.
나머지(하루 576개의 토큰)는 보호 자원을 위해 따로 보관됩니다.

![5050version3](https://github.com/MorpheusAIs/Morpheus/assets/1563345/c9fe763f-d4e4-4069-b9c9-75e0a777c3ad)

## MOR 토큰 유틸리티
MOR의 목표는 Morpheus 네트워크의 많은 기능을 통해 광범위한 유틸리티를 제공하는 것입니다. 결과적으로, MOR 토큰의 사용은 소프트웨어의 실제 사용을 기반으로 보상을 계산하는 온체인 회계 메커니즘을 제공합니다.

개발자는 로컬 하드웨어가 실행할 수 있는 것 이상의 기능을 제공하기 위해 컴퓨팅 공급자에게 MOR를 지불합니다. MOR 토큰은 스마트 에이전트 프로토콜을 사용하는 분산형 애플리케이션에 대한 Morpheus API 호출 비용으로 지불됩니다. 사용자는 개발자가 출시한 전문화된 에이전트에게 MOR를 지불할 수 있습니다. 결과적으로 개발자는 새로운 LLM/에이전트를 학습할 데이터에 대해 사용자에게 MOR 토큰을 지불할 수 있습니다.

모든 프로젝트는 개발 단계를 거칩니다. 초기에는 ETH와 같은 유동성 자산을 개발자 및 장비 비용으로 사용하는 것이 중요합니다. 이더리움은 동일한 방식으로 커뮤니티의 BTC를 활용하여 블록체인의 초기 코딩 비용을 지불하였습니다. 여기서 차이점은 스마트 에이전트 프로토콜이 이미 개발되었고 Morpheus가 보다 범용화된 버전을 구현하고 있으므로 프로젝트 시작 전에 대중에게 따로 판매가 필요하지 않다는 것입니다. 소프트웨어가 런칭한 이후에만 MOR 토큰 보상을 받습니다.

## 단기: 출시시점
자본 - 수익률을 생성하는 스마트 컨트랙트에 ETH가 잠겨 있습니다(예시: stETH Lido 스테이킹 컨트랙트의 ETH). stETH 수익률의 50%는 AMM을 통해 정기적으로 MOR로 교환되고 stETH 수익률의 나머지 50%는 유동성 공급을 위해 풀에 stETH로 유지됩니다. 즉 자본 기여자는 시간이 지남에 따라 AMM MOR/stETH 풀의 유동성을 높이기 위해 약 50%의 $MOR 및 50%의 $stETH를 추가하는 것입니다.

- 자본, ETH 수익률의 가치는 기여된 모든 ETH 수익률과 비례하여 보상되는 MOR 수익률을 기준으로 계산됩니다.
- 컴퓨팅, 컴퓨팅 제공업체는 유저 프롬프트가 응답시 MOR을 받습니다.
- 코더, 코더는 Merge된 Morpheus 소프트웨어에 대해 기여한 대가로 MOR을 받습니다.
- 커뮤니티, 커뮤니티 빌더는 Morpheus 네트워크로 가져오는 프런트 엔드, 도구, 사용 및 가치에 대해 MOR을 받습니다.

## 중기: MOR 토큰의 폭넓은 순환
- 자본, 블록 보상과 획득 수수료 사이의 균형이 발전합니다.
- 컴퓨팅, 블록 보상과 획득 수수료 간의 균형이 발전합니다.
- 코더, 블록 보상과 획득 수수료 사이의 균형이 발전합니다.
- 커뮤니티, 블록 보상과 획득 수수료 사이의 균형이 발전합니다.

## 장기적: MOR의 깊은 유동성, 높은 유기적 수요
- 자본, MOR 토큰에 ETH 유동성을 제공하기 위한 수수료가 대부분의 보상을 제공합니다.
- 컴퓨팅, 컴퓨팅 제공자에게 지불되는 수수료가 보상의 대부분을 차지합니다.
- 코더, 코더에게 전달되는 수수료가 보상의 대부분을 차지합니다.
- 커뮤니티, 사용자가 지불한 수수료가 대부분의 보상을 제공합니다.

참고로 이는 타임라인이 아닙니다. 수명주기의 일부에 대한 설명에 가깝습니다. 커뮤니티가 각 단계를 통해 성장하고 성숙하는 데 수년이 걸릴 수 있으며 블록 보상은 약 16년 후에 종료됩니다. 이 긴 배포 일정은 토큰이 전 세계적으로 매우 광범위하게 보상받을 수 있는 시간을 제공하기 위한 것입니다. 또한 수년에 걸쳐 매일 블록 보상이 완만하게 감소함으로써 모든 참가자는 일정 수준의 규모를 달성하고 초기 보조금을 통한 보상에서 자신이 얻은 수수료만으로 운영할 수 있도록 전환하는 시간을 제공합니다.

![MOREmissionSchedule](https://github.com/MorpheusAIs/Morpheus/assets/1563345/94c96cb0-b6e4-4c63-be46-39088c91e168)

## MOR 토큰의 꼬리 방출
비트코인이 출시된 이후로 사람들은 "블록 보상이 마침내 중단되면 어떻게 될까요?"에 대해 논쟁을 벌였습니다. Morpheus는 이러한 도움이 되지 않는 논쟁을 피하고 오랫동안 새로운 코더, 커뮤니티, 컴퓨팅 및 자본 제공자를 계속해서 유지하기 위해 우리는 MOR 토큰의 "꼬리 방출"을 제안합니다. 꼬리 방출은 배포 일정의 5,833일째 마지막 MOR 토큰이 방출된 후에 시작됩니다.

꼬리 배출량은 지난 5,833일 동안 소각된 MOR 토큰 수를 검토하고 꼬리 배출량을 소각량의 50%로 설정하여 계산됩니다. 이 꼬리 배출은 다음 5,833일 동안 방출됩니다. 그러나 어떤 경우에도 꼬리 배출은 당시 시점 기준으로 MOR 유통량의 16%를 초과하지 않습니다.

예를 들어, 처음 5,833일 동안 평균 25%의 MOR 토큰이 소각되었다면 첫 번째 배출 일정 동안 10,500,000 MOR이 소각되었을 것입니다. 그런 다음 50% 꼬리 배출 값을 적용하여 두 번째 5,833일 기간 동안 5,250,000 MOR을 보상받을 수 있다고 계산합니다. 이는 현재 유통 중인 31,500,000 MOR의 약 16.6%에 해당합니다. 이에 따라 이 금액은 5,040,000MOR(유통량의 16%)로 한번 더 감소되어 두 번째 5,833일 기간동안 하루 약 864MOR의 보상을 받게 됩니다.

두 번째 5,833일 기간이 완료되면 이 프로세스가 반복됩니다. 지난 5,833일 동안 소각된 MOR 토큰 수를 검토하고 꼬리 배출 값을 소각량의 50%로 설정하여 꼬리 배출을 다시 계산합니다. 이 꼬리 배출 값은 다음 5,833일 동안 진행됩니다. 그러나 어떤 경우에도 꼬리 배출은 당시 시점 기준 MOR 유통량의 16%를 초과하지 않습니다.

예를 들어, 두 번째 기간 동안 MOR 토큰의 25%가 소각된 경우, 이는 두 번째 배출 일정 동안 9,135,000 MOR이 소각된 것과 같습니다. 그런 다음 세 번째 5,833일 기간 동안 4,567,500 MOR을 보상받을 수 있습니다. 그러나 이 숫자는 당시 유통 중인 27,405,000 MOR의 16%를 초과하므로 (유통 중인 토큰 대비) 연간 보상인 1%에 맞춰 4,384,800 MOR로 감소됩니다.
 
이 과정은 영원히 반복됩니다.

장기적인 결과로, 연간 MOR 보상의 약 1%(당시 유통되는 MOR 수에 비례)는 향후 코더, 컴퓨팅, 커뮤니티 및 자본에 사용할 수 있습니다.

![MaxMORScenario25](https://github.com/SmartAgentProtocol/SmartAgents/assets/1563345/81c7794a-b5bc-4a9e-bb2d-1f28b98ea079)

**중요 참고사항:** 이 경우에도 절대 MOR 토큰의 4,200만개 최대 공급을 초과할 수 없습니다.
꼬리 배출 일정은 정의로 보았을 때 소각된 MOR 토큰의 일부일 뿐이므로 MOR 토큰은 5,833일마다 점점 더 부족해질 수 있습니다.

![MOR25ScenarioV9](https://github.com/SmartAgentProtocol/SmartAgents/assets/1563345/4813cd02-b104-4a0c-893b-a7fd329fe2a3)

아래에 처음 5,833일 기간을 보여주고 17년차부터 256년차까지의 긴 꼬리 배출량을 추가한 통합된 MOR 공급 곡선이 나와 있습니다. 해당 배출 주기에 걸쳐 MOR의 평균 소각율이 25%인 것으로 가정합니다.

![MORSupplyCurve20231019](https://github.com/SmartAgentProtocol/SmartAgents/assets/1563345/8994c389-dad1-4e46-9b63-e048da8ef172)

## 커뮤니티, 코드 및 연산 & 자본에 대한 증명:
Morpheus 풀노드에는 지갑이 함께 제공되거나 사용자가 기존 지갑을 연결할 수 있습니다. 이를 통해 사용자는 스마트 에이전트가 권장하는 트랜잭션에 서명하거나 전송할 수 있습니다. 즉 사용자는 Morpheus 소프트웨어를 통해 증명에 참여할 수 있습니다. 그러나 예를 들어 자본 공급자는 풀 노드를 가지고 있을 필요가 없습니다. stETH를 사용하여 Ethereum/Arbitrum의 스마트 컨트랙트와 직접 상호 작용할 수 있습니다.

## 자본 증명 & 보상:
자본 제공자는 "프로토콜 소유 유동성(PoL)이 되는 Morpheus 네트워크에 stETH 수익을 제공하는 자"라는 뜻입니다. 이 자본 제공자 스마트 컨트랙트는 Morpheus 스왑 기능에 stETH 산출 수익의 50%를 제공합니다. 스왑은 AMM(Automated Market Maker)을 통해 MOR 토큰을 구매한 다음 stETH 수익률의 50%와 페어로 맞춰짐으로써 AMM 유동성 풀에 PoL로 고정됩니다. 이는 모든 코더, 커뮤니티 구성원 및 컴퓨팅 제공자에게 유동성을 제공할 것입니다. 유동성 포지션으로 얻은 수수료는 풀에 재투자되어 꾸준한 유동성 성장을 보장합니다.

이러한 방식으로 예치를 통해 얻은 모든 stETH 수익은 프로토콜 소유 유동성(PoL)으로 변환됩니다. 수익률은 PoL로 무기한 유지되지만 언제든지 stETH를 인출할 수 있습니다.

결과적으로, 자본 제공자는 기여한 총 stETH 수익률에 비례하여 매일 MOR 토큰을 받게 됩니다. 예를 들어, 네트워크 출시 1일차에 수익에 각각 1 stETH만큼 기여한 100명의 자본 제공자가 있는 경우, 각각은 매일 3,456 MOR 토큰의 1% = 34.56 MOR을 얻습니다.

이러한 수익 기여, 스왑 및 유동성 추가 프로세스를 "TCM"이라고 부르는 것이 제안되었습니다. TCM은 e/acc 철학자 Beff Jezos를 기리기 위한 "techno-capital machine"의 약자입니다.

## 코드 증명, 등록 & 보상:
여기서 코더는 Morpheus 풀 노드를 다운로드 및 실행하고, 지갑을 연결하고, 에이전트, 스마트 계약 또는 기타 소프트웨어에 기여함으로써 Morpheus 네트워크에 기여한 사람입니다.

코더는 에이전트/스마트 계약 또는 소프트웨어를 등록하기 위해 코더 스마트 컨트랙트에 MOR 트랜잭션을 전송합니다.
코더는 트랜잭션 메모에 다음 메타데이터를 포함합니다.
- A. 등록 시 MOR 트랜잭션의 메모 필드에 있는 소프트웨어 엔드포인트에 대한 IPFS 링크.
- B. 개발자가 앱 배포본에 서명/인증하는 방법과 유사한 암호화 서명.
- C. 소프트웨어의 버전 번호.
- D. 사용자가 프로그램이 유효하고 변경되지 않은 복사본인지 확인할 수 있도록 하는 프로그램 상태의 해시값.

Morpheus 코드에 기여한 사람은 기여한 FTE(Full Time Equivalent) 작업을 기준으로 저장소에서 수행된 모든 누적 개발진행에 비례하여 보상을 받습니다. 예를 들어, 네트워크가 시작될 때 각각 FTE 시간(시간(h)으로 표시)의 10%를 기여한 10명의 코더가 있는 경우 각 코더는 매일 3,456 MOR 토큰의 10% = 345.6 MOR을 얻습니다. 이 계산은 현재 Morpheus 소프트웨어 메인넷 버전의 누적 FTE 시간(시간(h) 단위) 기여도를 기준으로 매달 업데이트됩니다.

여기서의 개념은 노동의 가치 이론에 기초한 것이 아닙니다. 중요한 것은 몇 시간을 일했는지가 아니라 그 일이 만들어낸 가치입니다. 그렇기 때문에 저장소 소유자는 실제로 보상을 받기 위해 코드(작업 산출물)를 병합(Merge)해야 합니다. 저장소 소유자는 시장에서 "고객" 역할을 합니다.

코드 기여자가 기여에 너무 많은 시간을 요청하거나 기여의 품질이 적합하지 않거나 불충분한 경우 저장소 소유자가 병합을 거부할 가능성이 높습니다. 누구나 저장소를 "만들 수" 있지만 유지 관리하고 다른 사람들보다 저장소에 기여할 사람들을 유치하는 데 많은 작업이 필요하므로 시장은 가장 많은 기여자와 최고의 코드 결과를 제공하는 최고의 저장소에 집중할 가능성이 높습니다.

승리를 위한 오픈 소스 및 자유 시장 경제를 선택했습니다.

Morpheus와 상호 운용 가능한 전문 에이전트나 도구 또는 체인(LLM에 대한 프롬프트/호출 순서)이 있으면 보상의 절반(50%)이 해당 개발자에게 전달됩니다. 보상은 해당 에이전트의 사용량에 비례하여 계산됩니다. 예를 들어, Morpheus 네트워크에서 각각 에이전트 사용량의 10%를 생성하는 10개의 에이전트를 구축한 10명의 개발자가 있다고 가정합니다. Morpheus 스마트 계약은 MOR 트랜잭션을 통해 이러한 사용 통계를 계산합니다. 그런 다음 Morpheus 소프트웨어 코더는 MOR 보상의 50%를 획득하고 전문 에이전트의 각 개발자는 토큰의 5%(이 예시에서는 개발자당 172.8 MOR)를 획득합니다.

"기여의 증명" 분야에서 수행된 많은 주요 연구는 TEA 프로토콜의 훌륭한 사람들에 의해 이루어졌습니다. HomeBrew의 개발자인 Max Howell 역시 연구에 참여했습니다. 자세한 내용이 담긴 문서와 연결됩니다. Morpheus는 2024년 출시 이후 TEA 활용을 고려할 수도 있습니다.

## 연산 증명, 등록 & 보상:
Yellowstone 연산 모델에서 Morpheus 네트워크는 경쟁 입찰 프로세스를 통해 실제로 제공된 연산력(computing)에 대해서만 공급자에게 비용을 지불하고 부족한 토큰 생산량을 지불이 아닌 잔액을 기준으로 MOR 토큰 보유자에게 분배합니다. 이는 시빌에 대한 취약점을 최소화하면서 UX를 대폭 향상시킵니다. Yellowstone은 또한 공급자가 적절, 신속, 정확한지 확인하기 위해 중요한 시간 측정 기준과 합격/불합격 여부에 대해 테스트를 제공합니다. Yellowstone은 라우터를 통해 절대 메시지나 결과를 전송하지 않음으로써 개인 정보를 보호하고, 대규모 작업을 위해 블록체인 트랜잭션을 최소 수준으로 줄입니다. 이 모델을 통해 MOR은 추론당 트랜잭션을 요구하지 않고 무허가 컴퓨팅에 대한 반영구적인(무제한은 아니지만) 액세스를 가능하게 함으로써 근본적인 추종가치를 달성할 수 있습니다.

요청에 대한 연산을 수용할 수 있는 자격을 갖추기 위해서는 연산력 공급자의 주소에 MOR 토큰이 있어야 합니다. 요청은 등록된 다른 모든 연산력 공급자들의 보유한 MOR에 비례하여 연산력 공급자 API로 라우팅됩니다.

자세한 사항은 Yellowstone 연산 모델 문서에 설명되어있습니다: https://github.com/MorpheusAIs/Morpheus/blob/main/Yellowstone%20Compute%20Model.md 

## 커뮤니티 빌더 증명, 등록 & 보상:
커뮤니티 빌더는 "Morpheus 전체 노드를 다운로드하여 실행하고 지갑을 연결하며 Morpheus API를 사용하여 사용자 프런트 엔드 및 개발자 도구를 제공하는 자"입니다. 제공된 기여도는 스마트 에이전트가 생성한 서명된 트랜잭션을 MOR 트랜잭션의 결과 반환과 함께 포함하여 계산할 수 있습니다.

커뮤니티 빌더는 MOR 트랜잭션을 커뮤니티 빌더 스마트 컨트랙트로 전송하여 요청 수신을 위한 API 엔드포인트를 등록합니다.
커뮤니티 빌더는 트랜잭션 메모에 다음 메타데이터를 포함합니다.
- A. 등록 시 MOR 트랜잭션의 메모 필드에 있는 엔드포인트를 통해 프런트엔드 또는 도구에 대한 IPFS 링크.
- B. 개발자가 앱 배포본에 서명/인증하는 방법과 유사한 암호화 서명.
- C. 사용 중인 Morpheus 소프트웨어의 버전 번호.
- D. 사용자가 유효하고 변경되지 않은 복사본인지 확인할 수 있도록 하는 프런트 엔드/도구 상태의 해시값.

각 커뮤니티 빌더가 소각한 MOR 거래 수수료는 커뮤니티 빌더의 상태를 증명하는 역할을 하며 이에 비례하여 매일 MOR 토큰의 일부를 얻습니다.

예를 들어, 네트워크가 출시된 첫날에 100명의 커뮤니티 빌더가 있었다면 각 커뮤니티 빌더는 수수료를 통해 소각한 MOR 양에 따라 비례 보상을 받습니다. 이 경우, 100명의 커뮤니티 빌더가 각각 100 MOR을 소각했다고 가정하면 매일 3,456 MOR 토큰의 1% = 34.56 MOR이 됩니다.

## Morpheus 유저 다이어그램
![UpdatedDiagram2UserFlow](https://github.com/MorpheusAIs/Morpheus/assets/1563345/a02468a7-9284-4ce5-b7e3-f32f476ff9f1)

## 이더리움 Layer 2 상의 스마트 컨트랙트 의해 제공되는 Morpheus 보상
보상을 위한 stETH 예치는 지불 및 기타 MOR 유틸리티 관련 작업을 위해 이더리움 Layer 2인 Arbitrum에서 Morpheus 토큰(MOR) 보상이 지급될 때 Ethereum 메인넷에서 이루어집니다.

Morpheus는 이더리움 및 Layer 2인 Arbitrum을 기반으로 구축되었기 때문에 분산 원장에서 블록체인 합의 또는 트랜잭션 실행에 대한 MOR 보상을 별도로 설정할 필요가 없습니다.

MOR 보유자는 언제든지 MOR 스마트 컨트랙트로 트랜잭션을 전송하고 MOR 보상을 청구할 수 있습니다. 또한 언제든지 stETH를 인출할 수도 있습니다.

## 자유 시장은 Morpheus에 수수료를 설정합니다.
최고의 시스템은 최소한의 매직 넘버를 선택하고 대신 자유 시장이 가능한 한 많은 변수를 결정하도록 합니다. 수수료가 이에 대한 좋은 예입니다. Morpheus는 임의로 수수료를 선택하는 대신 이러한 수치를 사용자, 개발자, 자본 및 컴퓨팅 제공업체에 맡깁니다. 예를 들어, 컴퓨팅 제공업체가 LLM에 대해 언어 토큰 1,000개당 0.02달러의 가격을 제공할 수 있고 사용자가 이를 지불하기로 결정한 경우 시장은 해당 금액을 지불할 의사가 있습니다. 컴퓨팅 속도가 빨라지면 가격이 변할 가능성이 높으므로 이러한 변수와 기타 변수를 Morpheus 소프트웨어를 사용하는 사용자에게 맡기는 것이 좋습니다.

컴퓨팅 수수료
사용자와 연산력 제공자가 설정한 수수료 금액입니다. 각 수수료로 컴퓨팅 비용을 지불하고 MOR 토큰을 소각할 수 있는 옵션. 시간이 지나면서 발전할 오픈마켓. 합의 또는 특권 노드 대신 컴퓨팅을 위한 무료/자유 시장입니다.

코드/에이전트 인텔리전스에 대한 수수료
코더가 설정하고 사용자가 응하는 수수료 금액입니다. 수수료를 지불하고 각 수수료로 MOR 토큰을 소각할 수 있는 옵션. 시간이 지나면서 발전할 오픈 마켓. 작업에 대한 합의 대신 코드를 위한 무료/자유 시장입니다.

자본 수수료
유동성 제공자가 설정하고 사용자가 응하는 수수료 금액입니다. 수수료를 지불하고 각 수수료로 MOR 토큰을 소각할 수 있는 옵션. 시간이 지나면서 발전할 오픈마켓. 재무에 대한 합의 대신 자본을 위한 무료/자유 시장.

## 사용자 커뮤니티를 위한 수수료
사용자가 설정하고 데이터 구매자가 수락하는 수수료 금액입니다. 수수료를 지불하고 각 수수료로 MOR 토큰을 소각할 수 있는 옵션. 시간이 지나면서 발전할 오픈 마켓. 데이터를 위한 무료/자유 시장.

모든 수수료는 사용량이 증가함에 따라 시스템에 자연스러운 수요를 창출하는 기본 MOR 토큰으로 지불됩니다.

## 정직한 에이전트에게 보상을 제공 & 오류 발생시 손실을 복구하기 위한 수수료 사용
Morpheus 네트워크에서 MOR 및 ETH의 또 다른 중요한 용도는 스마트 에이전트/스마트 컨트랙트 실패 시 사용자에게 보상하는 것입니다. 우리는 경제적 자원으로 뒷받침되는 큐레이팅과 평판 구축이 스마트 에이전트에 대한 신뢰를 높이고 발생하는 오류, 버그 및 기타 문제를 해결하기 위한 자금원을 확보하는 데 핵심이 될 것이라고 믿습니다. 2010년 심각한 버그와 그에 따른 비트코인 ​​하드포크 이후 초기 핵심 개발자 Gavin Andresen은 하드포크로 인해 보상을 잃은 채굴자에게 비트코인을 지불하기 위해 발벗고 나섰습니다. 이 조치는 주요했고 하드포크를 신속하게 해결했지만 결국 임시적인 조치였습니다.

소프트웨어는 완벽하지 않다는 점을 미리 인지하고 코드 버그로 인해 영향을 받은 사람들에게 상환하기 위해 MOR 자원의 4%를 따로 확보합니다. Morpheus 개발자 커뮤니티는 버그나 오류가 사용자, 컴퓨팅 제공자 또는 자본 제공자에게 경제적 영향을 미쳤을 때 이를 인식하는 오라클 역할을 합니다. 사전에 정의된 오류 집합은 Morpheus 스마트 컨트랙트 또는 로컬 설치의 버그를 포함하여 이러한 리소스로 처리됩니다.

보다 광범위한 보호를 위해 Nexus Mutual 또는 유사한 스마트 컨트랙트/분산형 보안 네트워크와의 통합을 고려하여, Morpheus Agent Store에 포함되거나 SmartContractRank 알고리즘에 의해서 더 나은 순위를 원하는 에이전트 / 스마트 컨트랙트 등의 극단적인 사례를 다루는 것을 고려할 수 있습니다.

## 영속성을 위한 저장소 & 복구를 위한 지갑
비용이 많이 들고 중앙화 압력이 존재할 수 있는 Morpheus 네트워크 자체에 개인 데이터를 저장하는 대신 개인은 자신의 데이터, 프롬프트 및 지갑에 대한 접근을 제어하는 ​​개인 키를 보유하게 됩니다. 데이터 자체는 장기간에 걸쳐 분산형 저장을 위해 IPFS 표준과 Filecoin 네트워크를 사용하여 저장됩니다. Filecoin EVM 및 DeFi를 활용하여 영구히 반복되는 스토리지를 마련할 수 있습니다. 또는 사용자는 ENS 처럼 연간 스토리지 비용을 지불할 수 있습니다. 사용자가 컴퓨터나 전화를 변경할 때 이 데이터를 다른 장치로 이동/복구하기 위한 핵심으로 개인 Web3 지갑에 접근하고 유지하는 것입니다.

## Morpheus 기술스택, 스마트 컨트랙트 & 개발
스마트 에이전트 프로토콜의 Morpheus 구현은 기존 로컬 실행 저장소의 직접적인 folk(복제)가 될 것입니다. 가장 중요한 변화는 스마트 에이전트 네트워크에 전력을 공급하는 MOR 토큰 및 기능에 대한 지식을 포함하도록 SmartContractRank를 업데이트하는 것입니다.

Morpheus MOR 토큰은 대체 가능한 토큰에 대한 ERC20 표준을 통해 Ethereum의 스마트 컨트랙트로 개발되고 있습니다. 대부분의 스마트 계약은 Ethereum에 있으며 Ethereum Virtual Machine은 Web3 공간의 공용어가 되었습니다. 일일 보상 전송에 대한 가스 비용을 줄이기 위해 우리는 이더리움의 레이어 2인 Arbitrum을 활용할 것입니다.

우리는 이더리움 블록체인의 선택이 ETH 스테이킹과 같은 체인 활동에 대한 최고의 출발점이라고 믿습니다. 이는 동일한 체인에서 실행되는 스마트 계약에 의해서만 검증될 수 있습니다. ENS 도메인 또는 Ethereum 공개 주소를 통한 코딩의 체인 검증 외에도 코드를 제공한 코더의 지갑에 기여된 코드를 연결하는 또 다른 수단을 추가합니다. 또한 이는 Morpheus 스마트 컨트랙트가 매일 접근할 수 있는 기록이기도 합니다.

또한 확장성과 개인 정보 보호를 위한 영지식 증명은 많은 사용 사례의 핵심입니다. 따라서 처음부터 이러한 기능을 제공하면 Smart Agent 커뮤니티가 미래를 위한 최고의 위치에 놓이게 될 것입니다. Arbitrum은 ZK 기술을 추가하는 과정에 있으며 대부분은 이미 활성화되어 있습니다.

단기적으로 이 기술 스택 선택은 레이어 2의 가스 비용을 절감하고 이더리움의 레이어 1 보안을 통해 Morpheus를 직접 보호합니다. 중기적으로 이 선택은 Morpheus를 다른 이더리움 레이어 2 및 EVM 호환 블록체인으로 확장할 수 있는 길도 제공합니다.

퍼블릭 블록체인 간의 상호 운용성이 향상됨에 따라 Morpheus는 다양한 EVM/솔리디티 호환 개발자 커뮤니티에서 모든 Web3 AI 에이전트 빌더에게 서비스를 제공하려고 노력할 것입니다. 우리는 유사한 비전과 가치를 공유하는 Arbitrum, Polygon, OP Stack, Base, Arbitrum, Avalanche, Polkadot, Solana, Filecoin 및 Cosmos의 강력한 빌더 커뮤니티를 수용합니다. Morpheus의 존재는 오늘날 이러한 여러 체인의 개발자가 구축한 도구 덕분에 가능합니다.

## 사용자 데이터 보안
컴퓨팅 공급자의 Morpheus P2P 네트워크에 메시지를 보낼 때 개인 데이터 유출을 방지하려면 소프트웨어는 출시된 대규모 언어 모델의 FHE(완전 동형 암호화) 버전을 활용해야 합니다. 2024/2025년에 FHE를 위한 하드웨어 가속화 기술이 등장하면서 이 계산 비용이 일반 텍스트 처리와 동등한 수준이 될 것으로 예상됩니다.
 
- LLM 예시 https://huggingface.co/blog/encrypted-llm 
- EVM 예시 https://www.fhenix.io/

## 네트워크 출시 및 90일간의 부트스트래핑 기간
Morpheus Network는 로컬 설치 버전 0.0.1로 시작한 다음 MOR 토큰 스마트 컨트랙트와 풀 노드 소프트웨어로 계속해서 진행됩니다.

MOR의 보상을 계산하는 스마트 컨트랙트는 메인넷에 배포하기 전에 테스트넷을 통해 광범위하게 테스트되어야 합니다.

또한 메인넷이 보상 계산을 시작하는 시점과 사용자가 해당 MOR 토큰을 청구/전송할 수 있는 시점 사이에 90일의 지연(부트스트래핑 기간이라고도 함)이 한 번 발생합니다. 이 부트스트래핑 기간은 네트워크의 유틸리티 기능을 수행하기 위해 충분한 MOR 토큰이 유통될 수 있도록 보장합니다.

AMM을 부트스트랩하기 위해 보호 자금 전용으로 할당된 MOR 토큰의 4%(90일 기준 51,444 MOR)가 이 목적으로 활용됩니다.

이러한 단계를 통해 메인넷에서 91일차 초에 1,286,111 MOR을 청구할 수 있으므로 채굴 1일차부터 처음으로 소수의 토큰만 사용할 수 있었던 Zcash 출시 당시의 극심한 토큰 부족을 피할 수 있습니다. 이 상황은 시장이 균형에 도달하고 합리적인 가격 발견을 확립하는 데 수 주가 걸리는 문제를 야기했습니다. Morpheus는 90일의 부트스트래핑 기간을 통해 이 문제를 방지함으로써 유틸리티를 충족하고 합리적인 가격 발견을 확립하기에 충분한 토큰 공급을 준비합니다.

MOR 토큰이 청구 가능하고 전송 가능해지면 Morpheus 네트워크는 MOR 트랜잭션을 활성화하여 API 호출, 커스텀 에이전트에 대한 비용을 지불하고 네트워크 참가자의 지분을 검증할 수 있게 됩니다.

## 결론
우리는 역사적으로 중요한 순간에 가까워졌습니다. Morpheus를 통해 모든 사람은 자신과 함께 생각하고 자신에게 이익이 되는 행동을 취할 수 있는 강력한 개인 AI를 갖게 됩니다. 개인용 컴퓨터와 검색 엔진이 개인에게 권한을 부여한 것과 마찬가지로 오늘날 개인용 AI에도 같은 기회가 있습니다. 스마트 에이전트 프로토콜은 LLM, 에이전트 및 Web3와 함께 적절한 기능의 조합을 제공합니다. Morpheus는 이러한 가용성을 스마트 에이전트의 대중화 및 사용을 가속화할 수 있는 퍼블릭 네트워크로 확장합니다.

우리는 인센티브의 경제적 배치가 궁극적으로 AGI의 도래로부터 최상의 결과를 확보하는 방법이라고 믿습니다. 모든 사람을 위한 오픈 소스의, 무허가인, 자유로운 미래를 확보할 수 있도록 도와주세요.

_______________________
## 제안 배경:

2023년 9월 2일 개발자 Morpheus에게 위 제안이 포함된 이메일을 받았습니다.

_______________________
David,

아래에서 "Morpheus - 스마트 에이전트 구동을 위한 네트워크" 출시에 대한 제안을 찾아보세요.

이 백서는 커뮤니티, 코더, 자본 및 컴퓨팅 제공자에게 토큰을 공정하게 보상하기 위한 토큰 경제학, 기술 스택 및 증명 계산 수단을 제시합니다.

이 문서는 Smart Agent 커뮤니티에 무료로 제공되며 공개 도메인에서 사용할 수 있습니다.

마음을 편하게 가지세요.

Morpheus

--------------------------------------------------------------------
