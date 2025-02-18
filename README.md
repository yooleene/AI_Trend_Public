## 프롬프트 엔지니어링

### 1.환각을 최소화 하는 방법

#### 1) Context:
```
---------- JOB POSTING ----------
마감된 공고는 아래의 경로를 통해 확인 가능합니다.
1.포스코 채용 솔루션 [채용 공고 관리] 클리합니다.
2.상단 [채용 종료] 를 클릭하면 공고를 확인할 수 있습니다.
※ 마감된 공고를 다시 게시하기를 원할 경우 게시 설정에서 포스코 공고 게시 ON, 게시 마감일을 다시 설정해 주시면 됩니다.
---
```
#### 2) Prompt:
```
JOB POSTING 정보를 바탕으로 질문에 답변하세요.
질문과 가장 관련성이 높은 내용을 찾으세요. 문구를 정확하게 인용하세요.
JOB POSTING 정보에 없는 내용을 생성하려고 시도하지 마세요.
JOB POSTING 정보에 질문과 관련된 내용이 없는 경우에는 “관련된 내용을 찾을 수 없습니다.”라고 답변하세요.
질문의 답을 정확히 알고 있거나 답변을 하기에 정보가 충분한지  확인하세요.
충분한 정보를 바탕으로 정확히 답변할 수 있는 경우에만 답변하세요.
답변이 확실하지 않은 경우에는 “죄송합니다. 답을 찾을 수 없습니다.＂라고 답변하세요.
```
#### 3) 질문:
```
마감된 공고는 어떻게 봐야 하니?
```


### 2.Prompt Design Framework
```
넌 서울대 대학병원 내과 의사야!
나는 고지혈증 고혈압 증세가 있어
규칙적인 운동과 식생활을 개선해야 하는데,
너무 많은 정보들로 인해 어떻게 해야할 지 모르겠어.
전문가 입장에서 식생활을 어떻게 개선해야 하는지,
어떻게 규칙적인 운동을 해야 하는지 표로 작성해줄래?
```

### 3.보고서 작성
```
다음 5가지 조건을 지키면서 부서내 세대간 소통 활성화 방안에 대해 답변해줘.

1. 너는 조직내 소통 분야 전문가야.
2. 직장내 소통분야 / 조직 문화 분야  최고 전문가 수준으로 답해.
3. 정보는 ‘연구기관, 행정기관자료, 협회자료, 논문, 학술지, 학회지, 출판자료, 기업교육자료,  백과사전’에서 취득한 정보를 활용 해.
4. 답변은  ‘글머리표’ 를 적용해야 해.
5. 사장님께 보고할 “부서내 세대간 소통 활성화 방안” 보고서를 작성해줘
```

### 4.전략 분석

#### 1)
```
너는 프렌차이즈 컨설턴트야,
나는 서울시 강남구에 치킨집을 오픈하려고해, 유동인구가 많고
주변에 직장인들이 거주하는 원룸이 많아,
비즈니스 모델 캔버스를 활용해서 사업모델을 만들어 줄래?
그리고 AIDA 프레임워크를 활용해서 위 사업의 광고 문구를
제작해줘
```
#### 2)
```
너는 전기자전거 생산회사를 컨설팅하는 경영 컨설턴트야.
요즘 경쟁업체가 많아서 새로운 전략수립이 필요해, 현재 경제
상황, 배터리 시장동향, 레저 스포츠 동향 등을 수집하고
SWOT 분석을 통해 전기자전거 회사의 새로운 전략을
수립해줘
```


### 5.자료 조사

#### 1)
```
전기차 시장 전망에 대한 최신 자료 10건을 찾아줘
```
#### 2)
```
조직의 창의성 관련 논문 5건을 찾아서 요약하고 포스코에 주는 시사점을 도출해줘
```


### 6. 자료요약

#### 1)
```
제주도 2박 3일 여행에 필요한 항목들을 도출하고
마인드맵으로 그려줘
```
#### 2)
```
방금 업로드한 pdf 파일에서 주요 키워드를 도출하고
마인드맵으로 그려줘
```


### 7.이메일 작성

#### 1)
```
납품 계약요건 위반에 대한 항의 이메일을 작성해야 해, 
상대회사를 설득할 수 있는 문체로 작성해줘
```
#### 2)
```
직원들에게 "안전사고 예방 아이디어 토론" 회의 안내 이메일을 작성해야해,
자연스럽고 친근하게 작성해줘
```
#### 3)
```
긴급하게 건축자재를 발주하려해, 납품회사에 정중하게 
납품 요청하는 이메일을 작성해줘
```


### 8.PDF 요약
```
첨부한 파일은 포스코홀딩스 회사의 반기 보고서'입니다.
나는 포스코홀딩스에서 경영전략을 수립하는 부장입니다.
반기 보고서를 읽고 우리 부서 관련 핵심 경영개선 이슈를
찾아 요약하세요. 아래의 표형식으로 쓰세요.

#형식
-표는 5개의 열로 구성됩니다.
-1열부터 번호, 제목, 핵심내용, 중요도(5점 척도 별표시)
```


### 9.통계 분석
```
너는 통계 전문가야, 다음 데이터를 아래와 같이 분석해줘
   - A : 73.4  77.0  73.7  73.3  73.1  71.5  74.5  77.5  76.4 77.7
   -  B : 68.7  71.4  69.8  75.3  71.3  72.7  66.9  70.2  74.4  70.1
 ① 가설은 다음과 같이 수립
   - H0 : 두 집단의 모평균은 차이가 없다.
   - H1 : 두 집단의 모평균은 차이가 있다.
 ② 두집단간 모평균의 차이가 있는지 검정 (유의수준 0.05)
 ③ 두집단을 비교하는 박스플롯을 그려줘
 ④ 검정결과에 대해 통계량을 알려주고 해석해줘
```


### 10.스캔 이미지 분석
```
위 그래프를 설명하고 시사점을 도출해줘
```


### 11.스캔 이미지 요약
```
업로드한 카드 전표를 분석하여 아래와 같이 출력해줘
- 표로 만드는데 열을 '번호', '날짜', '거래처', '금액' 으로 구성해줘
```


### 12.아이디어 발굴 - 40 가지 발명원리
```
당신은 트리즈 전문가 입니다.
진공 청소기로 이불이나 카페트를 깨끗하게 청소하기 위해서는 흡인력을 강하게 해야합니다.
그러나 흡인력이 강화되면 이불이나 카페트가 청소기 흡입구에 붙어서 사용이 불가능 해집니다.
이 문제를 해결할 수 있는 아이디어를 40가지 발명 원리중 최적의 원리 5가지를 적용해서 도출해주세요.
상세한 설명 부탁드립니다.
```


### 13.아이디어 발굴 - 다빈치 스킬 (조합법)
```
새로운 김밥을 만들려고 합니다. 아래와 같은 절차로 새로운 김밥을 만들어 주세요.
(김밥 구성요소 : 주재료, 모양, 색깔, 향, 크기)
1. 구성 요소별 대안 도출 (5가지)
2. 대안들을 무작위로 조합하여 새로운 김밥 아이디어 도출
(5가지 추천)
```


### 14.아이디어 발굴 - Brainstorm
```
아파트 공사현장입니다.
끼임, 추락, 낙하, 폭발 등의 안전사고가 빈번하게 발생하여
안전사고 예방 아이디어를 도출하려고 브레인스토밍을 해야 합니다.
브레인스토밍 참여자 3명 중 A는 비판적 사고, B는 창의적 사고,
C는 경제적 관점에서 아이디어를 도출하는 유형입니다. 
3명의 입장에서 안전사고예방 아이디어를 3건씩 도출해 주세요. 
```


### 15.경영과학
```
제품 A를 1 kg 만드는데 원재료 5kg, 전력 1kw/h 가 필요하며
제품 B를 1kg 만드는데 원재료 3 kg과 전력 3 kw/h가 필요하다.
제품 A는 1kg 당 4000원, 제품 B는 1 kg당 7000원의 이익이
발생한다. 이때 각각의 제품을 몇 kg 만드는 것이 좋을까?
단, 공장 전체에서 1시간당 원재료는 21 kg, 전력은 9 kw/h 밖에
사용할 수 없다. 선형계획법으로 문제를 풀어줘 
```


### 16.Create an image 이미지 생성

#### 1)
```
샴 고양이를 그려줘
```
#### 2)
```
아래 내용을 참조하여 이미지를 생성해줘
- '포스코' 직원 3명이 슈트를 입고, 큰 창이 있는 회의실에서 회의를 하고 있음
- 창 너머에는 작은 산과 현대적 건물들이 보임, 회의실에는 시계와 노트북이 있으며
 'POSCO' 라는 액자가 벽에 걸려 있음
- 직원들이 웃으면서 커피를 마시며 이야기 하고 있음 
```