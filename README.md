# 내일배움캠프 sparta_data11_advanced-project

데이터 분석 및 머신러닝 심화 프로젝트

## ��� 환경 구축 방법

### 1. uv 설치 (처음 한 번만)

**Windows:**
```powershell
powershell -c "irm https://astral.sh/uv/install.ps1 | iex"
```

**macOS/Linux:**
```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

### 2. 프로젝트 시작하기
```bash
# 저장소 클론
git clone https://github.com/hanalo26/sparta_data11_advanced-project.git
cd sparta_data11_advanced-project

# 가상환경 생성 및 모든 패키지 자동 설치
uv sync

# 가상환경 활성화
source .venv/Scripts/activate  # Git Bash (Windows)
```

**끝!** Python 3.12와 모든 패키지가 자동으로 설치됩니다.

## ��� 설치된 주요 패키지

- **데이터 처리**: pandas, numpy
- **시각화**: matplotlib, seaborn, plotly
- **통계**: scipy, statsmodels, pingouin
- **머신러닝**: scikit-learn, xgboost, lightgbm, catboost
- **개발 도구**: jupyter, streamlit

## ��� 팀 협업 방법

### 새 패키지 추가 시:
```bash
uv add 패키지이름
git add pyproject.toml uv.lock
git commit -m "Add 패키지이름"
git push
```

### 다른 팀원이 변경사항 받을 때:
```bash
git pull
uv sync
```

## ��� 팀원

- [팀원 이름 추가]
