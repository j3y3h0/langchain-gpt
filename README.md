# Requirements

- python 3.11.2

# Commands

```bash

# 가상환경 생성
python -m venv .venv

# 가상환경 접속
# powershell
. .venv/Scripts/activate.ps1

# mac/리눅스 bash
source .venv/bin/activate

# 패키지 설치 명령어
pip install -r requirements.txt

# 프로젝트 실행
python app.py

# 가상환경 연결해제
deactivate

# 신규 패키지 설치 명령어
pip install LIBRARY_NAME

# 패키지 리스트 조회
pip list

# 신규 설치된 패키지 Export 최신화
pip freeze > requirements.txt

# pip 업그레이드
python -m pip install --upgrade pip

```
