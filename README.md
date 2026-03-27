# ⚽ EPL Club Success Factor Analysis & Top-Tier Prediction
## (EPL 구단 상위권 유지 요인 분석 및 머신러닝 예측 프로젝트)

> **"What makes a Premier League club stay at the top?"**
>
> 이 프로젝트는 2014년부터 2024년까지의 10개 시즌 데이터를 바탕으로, 프리미어리그 상위권 클럽들의 성공 요인을 분석하고 신생 클럽의 전략 수립을 위한 인사이트를 도출합니다.

---

## 📋 Project Overview (프로젝트 개요)

이 프로젝트는 단순한 경기 결과 분석을 넘어, 구단의 경제적 지표(수익, 선수 몸값, 연봉)와 물리적 지표(선수들의 키, 나이 등)가 리그 성적에 미치는 영향을 데이터로 증명합니다. 최종적으로 로지스틱 회귀(Logistic Regression) 모델을 사용하여 특정 구단이 상위권에 안착할 확률을 예측합니다.

- **Goal**: Identify key success factors for EPL top-tier clubs.
- **Duration**: 2014-2015 Season ~ 2023-2024 Season (10 Seasons)
- **Methodology**: Web Crawling -> EDA -> Statistical Analysis -> Machine Learning

---

## 🛠 Tech Stack (사용 기술)

- **Language**: Python 3.x
- **Libraries**:
  - `Pandas`, `NumPy`: 데이터 전처리 및 분석
  - `Matplotlib`, `Seaborn`: 데이터 시각화
  - `Selenium`, `BeautifulSoup4`: 웹 크롤링을 통한 데이터 수집
  - `Scikit-learn`: 로지스틱 회귀 모델 구현 및 하이퍼파라미터 튜닝
- **Tools**: Jupyter Notebook, Google Colab

---

## 📂 Repository Structure (파일 구조)

```text
.
├── data/               # Raw & Processed CSV datasets
├── notebooks/          # Main Analysis Jupyter Notebook (.ipynb)
├── reports/            # Project PDF Summary & Presentation
├── assets/             # Visualizations for README (Coming soon)
├── requirements.txt    # Python dependencies
└── .gitignore          # Files to ignore in Git
```

---

## 📊 Key Findings (주요 분석 내용)

- **경제적 요인**: 구단의 수익(Profit)과 선수단의 총 시장가치(Market Value)는 리그 순위와 매우 높은 상관관계를 보였습니다.
- **물리적 요인**: 선수들의 평균 연령과 키(Height)가 전술적 유연성과 성적에 미치는 영향을 통계적으로 분석했습니다.
- **머신러닝**: 로지스틱 회귀를 통해 상위권(Top-Tier) 진입 요인을 모델링했으며, 유의미한 예측 성능을 확보했습니다.

---

## 🚀 Getting Started (시작하기)

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/epl-data-analysis.git
   cd epl-data-analysis
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the analysis**:
   - `notebooks/` 폴더 내의 `.ipynb` 파일을 주피터 노트북이나 Google Colab에서 실행하세요.

---

## 👤 Author (작성자)
- **User Name** (Your Portfolio Link / Email)
- [LinkedIn Profile] | [Blog/Portfolio]

---

> [!NOTE]
> 본 프로젝트는 교육 및 포트폴리오 목적으로 작성되었습니다. 데이터 출처는 GitHub 및 축구 관련 통계 사이트입니다.
