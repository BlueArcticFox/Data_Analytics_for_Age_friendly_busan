# Data Analytics for Age-friendly Busan
"고령친화 도시 부산" 을 위한 데이터 분석 프로젝트.

## 개요
국제보건기구 WHO는 [Age-Friendly World](https://extranet.who.int/agefriendlyworld/age-friendly-cities-framework/) 프레임워크 내 8개의 상호연결된 도메인을 제안하였습니다. 도메인은 노인들의 건강과 참여에 대한 경계를 식별 및 언급하는데 도움을 줄 수 있습니다. 우리는 오픈 데이터 기반 로케이션 인텔리젼스 프레임워크를 제안함으로서 고령친화 도시 부산에 관련된 정책의 투명성과 정책품질의 향상을 추구합니다. 고령친화도시 부산의 정책적 방향은 5대 전략과 20대 과제, 110개의 세부사업으로 구성됩니다 [관련링크](http://afc.bswdi.re.kr/Main.do). 우리의 목표는 진행중/실시될 정책에 대하여 오픈 데이터와 함께 분석사례를 만들어 재사용 및 재생산이 가능하면서도 확장가능한 오픈소스 기반 분석 프레임워크와 그에 대한 사례를 개발하는 것입니다.

## 현재단계
현재 프레임워크는 오픈소스 기반 GIS도구를 이용하여 시니어 센터의 입지 분석 기능을 지원합니다. 
1. 최적화된 입지분석을 위한 데이터 분석 과정 ( 접근성(도보 이동시간), 시니어 센터 이용율, 고령인구 변화 )

## 향후 진행방향
우리의 목표는 상업적 프레임워크를 사용하는 것이 아닌, 오픈소스 기반 분석 프레임워크를 향상 개발하고 이에 대한 분석사례 개발을 목표합니다.
1. 입지분석을 위해 고려해야할 요인를 추가
2. 현재 도로 네트워크의 교차점별로 데이터가 집계되어 있음. 집계데이터에, 통계학 방법/기계학습/딥러닝/그래프 방법론 등을 적용
3. 입지분석을 위해 다양한 시각적인 지도, 차트 구현.

## 특징


## 기술적 요구사항
- 코드 간결화
- 부동산 이론을 활용해 최적 입지의 수학적 근거 확립.
  - ex) 베버의 최소 생산비 이론: ax + by + cz >= cm (페르마-토리첼리 지점을 응용. 최소운송비 = 재화의 무게 * 단위거리)
- 인구 예측 수식 고도화
  - ex) 재정학 참고.
- 주석 필수

## 국내 참고자료
- 서울시 빅데이터분석 사례 
- 노인복지시설 현황 분석
- 국내외 논문

## 관련 용어
[로케이션 인텔리젼스](https://www.esri.com/en-us/location-intelligence)(LI: Location Intelligence): 공간 정보 데이터의 시각화 및 분석하여 제공하며 인구 통계, 교통, 날씨와 같은 데이터 레이어를 스마트 맵 또는 대시보드에 추가하여, 이벤트 발생 위치를 식별하고 이벤트 발생 이유를 이해하며 원인에 대한 통찰력을 확보할 수 있는 도구.
