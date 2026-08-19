# Battery Defect Analysis

2차전지 제조 공정 데이터를 활용한 불량 분석 프로젝트입니다. 원천 데이터, 전처리 데이터, 분석 노트북, 과제 가이드를 하나의 저장소에서 추적할 수 있도록 정리했습니다.

## Repository Layout

```text
.
├── data/
│   ├── raw/              # 원천 데이터
│   └── processed/        # 전처리 및 파생 데이터
├── docs/                 # 과제 가이드 및 참고 문서
├── notebooks/            # 탐색/모델링/검정 노트북
├── requirements.txt      # Python 분석 환경 의존성
└── .gitignore
```

## Data Files

- `data/raw/bat_raw.csv`: 원천 배터리 공정/품질 데이터
- `data/processed/bat_process.csv`: 공정 분석용 데이터
- `data/processed/new_process.csv`: 추가 전처리 데이터
- `data/processed/bat_tat.csv`: 공정 TAT 데이터

## Notebooks

- `notebooks/c2_류채원_작성코드 (1).ipynb`: 결측치 및 주요 변수 탐색 중심 분석
- `notebooks/c2_류채원_작성코드 (2).ipynb`: 공정별 유의차/분류 분석 중심 코드
- `notebooks/설비유의차.ipynb`: 설비 유의차 검토용 노트북
- `notebooks/test.ipynb`, `notebooks/test2.ipynb`: 실험 및 초안 노트북

## Setup

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
```

노트북은 `notebooks/` 폴더에서 실행하는 기준으로 데이터 경로가 `../data/...` 상대경로를 사용하도록 정리했습니다.
