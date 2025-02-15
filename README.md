# 애움길: aeum_gil
<img src="image/002.png" alt="drawing" width="200"/>

안녕하세요, :raised_hand:  
AIFFEL 해커톤 "자연어처리 알고리즘을 활용한 느린학습자 교육 컨텐츠 제작" 프로젝트 "애움길" 팀입니다.

저희는 전체 인구의 12-14%에 해당하지만 교육의 사각지대에 놓여있는 느린학습자를 위한 쉬운 교육 컨텐츠를 만들고자 합니다. 느린학습자가 익숙하지는 않으실텐데요. 이들은 특수교육 대상은 아니지만 평균보다 지능이 낮아 일반 학급 수업은 따라가기 어려운 사람들입니다. 일반 지능과 지능 장애 사이 경계선에 놓여있다고 해서 경계선급 지능을 가진 사람들이라고도 불립니다.

느린학습자에 대한 **사회적 인식**과 **교육 제도** 및 **학습 컨텐츠**가 부족한 상황에서 "애움길" 팀은 쉬운 컨텐츠를 제작하는 알고리즘을 만들어 느린학습자의 사회적 환경을 개선하고자 합니다.

> 애움길 홈페이지 (노션) : [애움길 페이지](https://absorbing-bagel-96e.notion.site/41b53ec4d26a42a0ad786504f23cb107)

<br/>

## 1. 팀원 소개

| 이름 | 닉네임 | 소개 |
| :---: | :---: | :---: |
| 정민지 | 만두(mandoo) | 애움길 팀장을 맡았습니다. AI/ML 기술로 사회적 가치를 창출하고, 더 이로운 세상을 만들고 싶습니다. |
| 권승민 |클로버| 애움길 nlp 모델링을 담당합니다. 하나하나 배워나가 보겠습니다! |
| 김은서 |느티(rtee)| 애움길의 data scientist! 데이터 관련된 일을 담당합니다. 찬찬히 깊이있게 배워가고 싶어요~|
| 문영민 | 배롱배롱  | 애움길의 웹 개발자! 프론트/백엔드를 담당합니다. 잘은 못하지만 열심히 하겠습니다. |

<br/>

## 2. 진행상황
1) **미니 해커톤** (2021.09 - 2021.10 공부하면서 중간중간 해커톤 진행)
    - 원문 - 쉬운글 pair 데이터 쌍을 구축하기 위해 크롤링 작업 진행 (webscraping 파이썬 패키지)
    - 데이터 수집, EDA, preprocess, baseline model train and test - transformers, KoBART summarization 진행 (minji/model)  

<br/>

2) **해커톤** (2021.11.10 - 2021.12.15) 
    - 역할 분담  
    모든 task 를 팀원들이 함께 하지만, 특별히 더 신경써서 담당하는 역할을 정했습니다.  

    | task | 담당자 | 기타 |
    | :---: | :---: | :---: |
    | 모델링 (쉬운글 생성 요약 모델 NLP 모델링, 개선, MLOps) | 정민지, 권승민 | huggingface/transformers, BERT, BART 등 공부 |
    | 프로토타입 제작 (프론트/백엔드 개발) | 문영민 | Flask(or FastAPI), streamlit, 프론트엔드, 백엔드 |
    | 데이터 수집 / 분석 / 정제 (python, jupyter notebook) | 김은서 | EDA, preprocessing |
