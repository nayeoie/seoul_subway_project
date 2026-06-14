# seoul_subway_project

# 서울시 지하철 호선별/시간대별 승하차 데이터 분석

서울시 지하철의 호선별, 역별, 시간대별 승하차 인원 정보를 활용하여 대중교통 이용 패턴을 탐색하고 시각화하는 데이터 분석 프로젝트입니다.

## 프로젝트 기간
* 2026년 05월 ~ 06월

## 사용 기술 및 라이브러리
* **Language:** Python (v3.12)
* **Data 전처리:** Pandas, NumPy, Seaborn
* **데이터 시각화:** Plotly Express (Interactive 시각화), Matplotlib, Seaborn

## 폴더 구조 (Directory Structure)
```text
seoul_subway_project/
│
├── data/                 # 데이터 파일 모음
│   ├── raw/              # 서울시 지하철 원본 데이터
│   │   └── 서울시 지하철 호선별 역별 시간대별 승하차 인원 정보.csv
│   │
│   └── processed/        # 전처리가 완료된 정제 데이터
│       ├── subway_clean.csv
│       ├── subway_with_transfer.csv
│       └── team_B_week2_summary.xlsx
│
├── notebooks/            # 주피터 노트북 파일
│   ├── Week1_data_processing.ipynb
│   ├── Week2_advanced_data_analysis.ipynb
│   └── Week3_visualization.ipynb
│
└── reports/              # 최종 생산물
    └── poster/           # 포스터
