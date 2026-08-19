# Data

이 폴더는 분석에 사용한 CSV 데이터를 보관합니다.

## raw

- `bat_raw.csv`: 원천 데이터입니다. 원본 인코딩은 노트북에서 `euc-kr`로 읽던 이력이 있습니다.

## processed

- `bat_process.csv`: 공정 변수 중심의 분석 데이터입니다.
- `new_process.csv`: 추가 전처리 결과 데이터입니다.
- `bat_tat.csv`: 공정별 TAT 관련 데이터입니다.

원자료와 가공자료를 분리해 두었으므로, 새 전처리 결과를 만들 때는 `data/processed/`에 별도 파일명으로 저장하는 것을 권장합니다.
