<!--
- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
# LeeChaeYeon
   
 [![Tech Blog Badge](http://img.shields.io/badge/-naver%20blog-lightgreen?style=flat-square&logo=naver&link=https://blog.naver.com/chland23)](https://blog.naver.com/chland23) </br>
 
  👋 Hi, My name is ChaeYeonLee! 👋 <br>
 Machine Learning and Development, from Data to Algorithms
  
  <p></p>
  <div align = "center">
  <h3 align="center">🛠️ Skills 🛠️</h3>
  <img src="https://img.shields.io/badge/Python-3766AB?style=flat-square&logo=Python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=Java&logoColor=white"/>
  <img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=C&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=JavaScript&logoColor=white"/></a>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=Linux&logoColor=white"/>
  <img src="https://img.shields.io/badge/Red Hat-EE0000?style=flat-square&logo=RedHat&logoColor=white"/>
  <br/>
  <img src="https://img.shields.io/badge/CSS-1572B6?style=flat-square&logo=CSS3&logoColor=white"/></a>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=HTML5&logoColor=white"/></a>
  <img src="https://img.shields.io/badge/Mysql-4479A1?style=flat-square&logo=Mysql&Studio&logoColor=white"/></a>

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=LeeChaeY&show_icons=true&theme=merko)

</div>

## Projects
| **Date** | **contents** | **Skill** |
|:--------:|:--------:|:--------:|
| 2020.01 | 리뷰를 활용한 나에게 맞는 호텔 찾기 | R |
| 2021.02 ~ 2021.07 | 이사 지역 추천 시스템 | Python |
| 2021.03 ~ 2021.06 | 소셜미디어 데이터를 활용한 탈모 성분 효과 예측 | Pytorch |
| 2021.07 ~ 2022.02 | BERT를 이용한 약물부작용 시그널 파악 시스템 | Bio-BERT |
| 2021.07 ~ 2022.08 | 인공지능에 의한 동작인식 기반 피트니스 운동 추천 시스템 | Azure Kinect 활용 |
</br>
</br>
</br>
</br>

<p>
  1. 2020.01 교내 R을 활용한 텍스트 마이닝 공모전, 리뷰를 활용한 나에게 맞는 호텔 찾기</br>
  R을 통해 아마존 리뷰 크롤링 및 감성분석 특강을 진행</br>
  팀 프로젝트로 트립어드바이저 리뷰를 크롤링한 후, 감성분석을 진행해 호텍 롼련 키워드 찾기, 긍정 키워드를 통해 내가 원하는 서비스가 평가가 좋은 호텔찾기</br>
  더 나아가 html 사이트로 구현하여 나에게 맞는 호텔을 찾아주는 서비스, hohae 개발</br>
  </br>
  2. 2021.02 ~ 2021.07 아웃라이어 프로젝트, 이사 지역 추천 시스템</br>
  공공데이터 포털 등으로 부산 동별 문화 시설 수, 치안시설 수 등의 데이터 수집</br>
  부산의 총 104개의 행정동별 아파트 매매 거래가, 치안시설, 음식 등 총 15개의 변수 활용</br>
  동별 집값 평균으로 k-means 군집하여 사용자가 원하는 가격대의 군집을 선택</br>
  변수별 척도를 생성해 사용자가 변수별 중요도를 입력하면 그 중요도에 따라 1차로 아이템기반 추천시스템 적용 후 나온 1순위의 동과 </br>
  동별 연령대별 인구수를 만족도로 치환하여 사용가 기반 추천 시스템 적용하여 최종 3개의 동을 결정, 이때 추천시스템 2개 모두 유클리디안 거리 사용</br>
  동별 지가변동률을 LSTM을 이용하여 상승세 파악 및 아파트 매매 실거래가를 ARIMA를 이용하여 상승세 파악 후 2개의 결과를 합쳐 상승세가 높은 최종 동 하나를 결정</br>
  2015년-2021년 단지별 아파트 평균가격을 시계열 군집하여 상승세가 있는 단지 군집을 선택, 최종으로 최종 동의 상승세 있는 아파트 군집을 출력</br>
  </br>
  3. 2021.03 ~ 2021.06 기계학습 과목, 소셜미디어 데이터를 활용한 탈모약 긍부정 평가</br>
  네이버 기사를 크롤링 후 키워드 분석해 탈모 성분명 15개를 얻음</br>
  탈모 + 성분명 을 키워드로 네이버 카페, 블로그를 크롤링하여 15개의 성분 모두 합쳐서 9524개의 텍스트 데이터 얻음</br>
  전처리 후 워드 클라우드, 빈도분석 등 진행, 군산대 KNU 감성 사전을 통해 각 리뷰의 감성점수를 얻어 -, 0, +로 나우러 레리블링 진행</br>
  문장 전체를 분석하기 위해 Ko-BERT를 적용하여 감성점수 예층을 진행, train acc: 0.95, test acc: 0.68로 나왔음</br>
  해당 성분의 탈모약을 구매하여 나타난 증상들을 텍스트로 집어넣으면 해당 성분 효과를 예측하는 시스템 개발</br>
  </br>
  4. 2021.07 ~ 2022.02 BERT를 이용한 약물부작용 시그널 파악 시스템</br>
  약물부작용 신고 절차가 복잡해 신고 건수가 매우 적은 편</br>
  트위터와 같이 sns에서 약물과 그에 대한 증상을 기록한, 즉 간단한 리뷰를 통해 약물 부작용을 파악하는 시스템</br>
  BIO-BERT를 활용해 해당 리뷰의 NER을 파악하도록 학습 진행 후, 캐글의 약물 리뷰와 만족도 점수 데이터를 가지고</br>
  만족도가 낮은 리뷰에서 약물 부작용을 나타내는 NER을 억을 수 있도록 작업 중</br>
  리뷰에 나온 약물 관련 단어들이 증상-약물 복용인지 약물복용-부작용인지 구분하여 파악하는 것이 중요</br>
  후에 나온 NER을 가지고 약물 부작용 지식그래프를 그릴 예정</br>
  </br>
  5. 2021.07 ~ 2022.08 인공지능에 의한 동작인식 기반 피트니스 운동 추천 시스템</br>
  Azure Kinect를 활용하여 사람의 동작을 인식 후 해당 동작이 정확한 요가 동작인지 파악하는 알고리즘을 개발
  영상에서 3D로 객체 인식, 신체 치수 측정 알고리즘 등을 연구 중
  건국대에서 알고리즘 코드를 넘겨주면 해당 코드를 Azure Kinect 기계와 연결하여 적용 진행 예정
  최종적으로는 어플의 형태로 발표할 예정
  </br>
  
</p>
