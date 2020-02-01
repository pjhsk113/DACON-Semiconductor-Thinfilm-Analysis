# 대회 개요
최근 고사양 반도체 수요가 많아지면서 반도체를 수직으로 적층하는 3차원 공정이 많이 연구되고 있습니다. 반도체 박막을 수십 ~ 수백 층 쌓아 올리는 공정에서는 박막의 결함으로 인한 두께와 균일도가 저하되는 문제가 있습니다. 이는 소자 구조의 변형을 야기하며 성능 하락의 주요 요인이 됩니다. 이를 사전에 방지하기 위해서는 박막의 두께를 빠르면서도 정확히 측정하는 것이 중요합니다.
박막의 두께를 측정하기 위해 광스펙트럼 분석이 널리 사용되고 있습니다. 하지만 광 스펙트럼을 분석하기 위해서는 관련 지식을 많이 가진 전문가가 필요하며 분석과정에 많은 컴퓨팅자원이 필요합니다. 빅데이터 분석을 통해 이를 해결하고자 반도체 소자의 두께 분석 알고리즘 경진대회를 개최합니다.

# 데이터 설명
### 배경 자료

_반도체 박막은 얇은 반도체 막으로 박막의 종류와 두께는 반도체 소자의 특성을 결정짓는 중요한 요소 중 하나입니다._ **박막의 두께를 측정하는 방법으로 반사율 측정**이 널리 사용되며 **반사율은 입사광 세기에 대한 반사광 세기의 비율**로 정해집니다. **(반사율 = 반사광/입사광)** 반사율은 빛의 파장에 따라 변하며 **파장에 따른 반사율의 분포를 반사율 스펙트럼**이라고 합니다. 

### 구조 설명

이번 대회에서 분석할 소자는 **질화규소(layer_1)/이산화규소(layer_2)/질화규소(layer_3)/이산화규소(layer_4)/규소(기판) 총 5층 구조**로 되어 있습니다. **대회의 목적**은 기판인 규소를 제외한 **layer_1 ~ layer_4의 두께를 예측하는 것**으로 train.csv 파일에는 각 층의 두께와 반사율 스펙트럼이 포함되어 있습니다. 

