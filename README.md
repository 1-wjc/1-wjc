<img src="assets/banner.svg" width="100%"/>

<h3 align="center">모델을 만드는 것에서 끝내지 않고, 실제로 쓰이는 결과를 만듭니다</h3>

<p align="center">
  <a href="#-featured-projects">Projects</a> &nbsp;|&nbsp;
  <a href="#-education--awards">Education & Awards</a> &nbsp;|&nbsp;
  <a href="#-tech-stack">Tech Stack</a>
</p>

<p align="center">
  <a href="https://1-wjc.notion.site/wj-portfolio"><img src="https://img.shields.io/badge/Notion-Portfolio-000000?style=flat-square&logo=notion&logoColor=white" alt="Notion Portfolio"/></a>
  <a href="mailto:choiwj98@naver.com"><img src="https://img.shields.io/badge/Email-choiwj98@naver.com-03C75A?style=flat-square&logo=naver&logoColor=white" alt="Email"/></a>
</p>

<br/>

## 📌 Featured Projects

### 🧠 Multimodal LLM
<!-- ✏️ Notion 링크는 노션 정리 후 프로젝트별 페이지 링크로 교체 -->

| 프로젝트명 | 대회 · 과정 / 기간 | 주요 내용 및 성과 | 기술 스택 | 링크 |
|---|---|---|---|---|
| **한국어 텍스트 이미지 VQA** | SSAFY 16기 AI 챌린지 (Kaggle)<br/>`2026.09` | · Qwen3.5-9B NF4 QLoRA 학습 · INT8 추론으로 단일 GPU에서 구동<br/>· 선지 순서 증강 · 오답노트 이어학습 · 저확신 문항 선지 순서 TTA<br/>· **Kaggle Private 0.97140 · 58위 / 217팀 (팀장)** | `Qwen3.5` `PyTorch` `PEFT` `bitsandbytes` | [Repo](https://github.com/1-wjc/vqa_text-image)<br/>[Notion](https://1-wjc.notion.site/wj-portfolio) |
| **개인정보 처리방침 준수 검토 AI Agent** | 서울대 KDT 캡스톤 · 금융보안원 연계<br/>`2025.04 - 2025.07` | · LangChain Agent · FAISS 검색 · 키워드 + LLM 하이브리드 조항 매핑<br/>· 수작업 조항 대조 → 1:N 매핑 · 충족 판정 · 근거 보고서 자동 생성<br/>· **금융보안원 연계 캡스톤 → 기관 컴플라이언스 AI 진단도구로 후속 개발** ([보도자료](https://www.fsec.or.kr/bbs/detail?menuNo=69&bbsNo=11788)) | `LangChain` `OpenAI` `FAISS` `Flask` `React` | [Repo](https://github.com/1-wjc/compliance_privacy)<br/>[Notion](https://1-wjc.notion.site/wj-portfolio) |

### 📈 Applied ML

| 프로젝트명 | 대회 · 과정 / 기간 | 주요 내용 및 성과 | 기술 스택 | 링크 |
|---|---|---|---|---|
| **P2P 대출 위험 대비 수익 극대화 승인 전략** | 서울대 KDT 과정 프로젝트<br/>`2025.01 - 2025.03` | · 사후 정보 제거 · 상관·VIF 기반 변수 검토 · 다중 모델 비교<br/>· 정확도 대신 Sharpe Ratio 기준으로 대출 승인 임계값 탐색<br/>· **Test Sharpe Ratio 약 1.21% 상대 상승 (임계값 0.5 → 0.87)** | `GBDT` `Logistic Regression` `SMOTE` `Grid Search` | [Notion](https://1-wjc.notion.site/wj-portfolio) |
| **중소 유통 물류 수요 예측** | 제3회 유통데이터 활용 경진대회<br/>`2024.09 - 2024.11` | · 순판매량 타깃 정의 · 경제 지표·검색 트렌드 외부 변수 수집 · 상관분석 기반 변수 선택<br/>· 무작위 분할 → 시점 기준 검증 전환 · 다중 모델 비교 · 데이터별 최적 모델 선택<br/>· **우수상 (산업통상자원부 주최)** | `Tree Ensemble` `MLP` `GridSearchCV` `scikit-learn` | [Repo](https://github.com/1-wjc/forecast_retail)<br/>[Notion](https://1-wjc.notion.site/wj-portfolio) |
| **도로망 최단거리 기반 바이오가스화 시설 입지 선정** | 2024 환경데이터 활용 및 분석 공모전<br/>`2024.03 - 2024.06` | · OSMnx 최근접 노드 매칭 · 다익스트라 최단거리 · 시설 쌍 중심점 산출<br/>· k-means 군집별 후보 산출 · 분위수 기반 버퍼 가중치 · QGIS 격자 제외 조건<br/>· **강원도 입지 후보 4곳 도출 · 기존 통합 시설 2곳과 위치 일치** | `OSMnx` `NetworkX` `GeoPandas` `k-means` `QGIS` | [Repo](https://github.com/1-wjc/location_biogas)<br/>[Notion](https://1-wjc.notion.site/wj-portfolio) |

> 프로젝트별 자세한 과정과 회고는 [노션 포트폴리오](https://1-wjc.notion.site/wj-portfolio)에 정리했습니다.

<br/>

## 🎓 Education & Awards
### 📚 Course
* **삼성청년 SW·AI 아카데미(SSAFY)** | 삼성전자 (2026.07 ~ )
* **서울대학교 빅데이터 핀테크 AI 고급 전문가 과정(KDT)** | 서울대학교 (2024.12 ~ 2025.07)

### 🏆 Award
* **제3회 유통데이터 활용 경진대회** | 우수상 | 산업통상자원부 주최 (2024.11)

### 📜 Certificate
* **데이터분석준전문가(ADsP)** | 한국데이터산업진흥원 (2024.11)
* **SQL개발자(SQLD)** | 한국데이터산업진흥원 (2024.12)

<br/>

## 💻 Tech Stack

| 분야 | 기술 |
|---|---|
| **Language** | <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white"/> <img src="https://img.shields.io/badge/R-276DC3?style=flat-square&logo=R&logoColor=white"/> <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=MySQL&logoColor=white"/> |
| **AI · LLM** | <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=PyTorch&logoColor=white"/> <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=TensorFlow&logoColor=white"/> <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=HuggingFace&logoColor=black"/> <img src="https://img.shields.io/badge/LangChain-7FC8FF?style=flat-square&logo=LangChain&logoColor=white"/> <img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=OpenAI&logoColor=white"/> |
| **ML · Data** | <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white"/> <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white"/> <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=NumPy&logoColor=white"/> |
| **Visualization · Geo** | <img src="https://img.shields.io/badge/Plotly-7A76FF?style=flat-square&logo=Plotly&logoColor=white"/> <img src="https://img.shields.io/badge/Leaflet-199900?style=flat-square&logo=Leaflet&logoColor=white"/> <img src="https://img.shields.io/badge/QGIS-589632?style=flat-square&logo=QGIS&logoColor=white"/> |
| **Database** | <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=MySQL&logoColor=white"/> <img src="https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=MariaDB&logoColor=white"/> |
| **Web** | <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=Flask&logoColor=white"/> <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=Streamlit&logoColor=white"/> <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=React&logoColor=black"/> <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=Vue.js&logoColor=black"/> <img src="https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=Node.js&logoColor=black"/> <img src="https://img.shields.io/badge/Netlify-00C7B7?style=flat-square&logo=Netlify&logoColor=black"/> |
| **Tools** | <img src="https://img.shields.io/badge/Git-F03C2E?style=flat-square&logo=Git&logoColor=white"/> <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white"/> <img src="https://img.shields.io/badge/GitLab-FC6D26?style=flat-square&logo=GitLab&logoColor=white"/> <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=Jupyter&logoColor=white"/> <img src="https://img.shields.io/badge/Anaconda-44A833?style=flat-square&logo=Anaconda&logoColor=white"/> <img src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=Figma&logoColor=white"/> |

<br/>

## 🌱 Contributions
<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/1-wjc/1-wjc/master/profile-3d-contrib/profile-night-green.svg">
  <img src="https://raw.githubusercontent.com/1-wjc/1-wjc/master/profile-3d-contrib/profile-green-animate.svg" alt="GitHub 3D Contribution" width="70%"/>
</picture>
</div>
