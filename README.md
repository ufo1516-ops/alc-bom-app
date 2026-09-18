# ALC/BOM 자재 조회 앱

## 실행 방법 (로컬)
```
pip install -r requirements.txt
streamlit run app.py
```

## Streamlit Community Cloud 배포 방법
1. 이 폴더(app.py, data.xlsx, requirements.txt)를 GitHub 저장소에 올립니다.
2. https://share.streamlit.io 에서 "New app" → 저장소 선택 → main file: app.py 로 배포합니다.

## 데이터 업데이트 방법
ALC/BOM 원본 엑셀 파일이 바뀌면, 이 폴더의 data.xlsx 파일만 새 파일로 교체하고
GitHub 저장소에 다시 커밋/푸시하면 앱에 자동 반영됩니다. (ALC, BOM 두 시트 이름은 그대로 유지해야 합니다.)
