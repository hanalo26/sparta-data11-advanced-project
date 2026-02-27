# 내일배움캠프 sparta_data11_advanced-project

데이터 분석 및 머신러닝 심화 프로젝트

## ��� 프로젝트 일정

- **프로젝트 기간**: 2026.02.27 ~ 2026.03.11
- **목표 마감일**: 2026.03.09 (월)

## ⚠️ 주의사항

- **`git add .` 사용 금지** - 필요한 파일만 개별적으로 add
- **대용량 파일 업로드 금지** - `.gitignore`에 등록된 파일 확인 필수

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

## 팀 협업 방법
 - 대용량 파일은 구글 드라이브에서 관리할 예정 
 https://drive.google.com/drive/folders/1IMVPgwf0CiSJpoj3M5u2CaK_VY-qpvNe?usp=drive_link
 - 각자 이름으로 된 파일에서 개인 작업물을 관리하고, 공용 파일은 추후 폴더 제작하여 관리할 예정

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

