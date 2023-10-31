# 통화정책결정문 연구 작업 코드

> 한국은행 통화정책결정문의 시그널링 효과 분석 연구의 작업 코드 공유용 리포지토리입니다


### 구조

##### 폴더

- `DATA/`: 가공을 거친 데이터 파일 저장
- `DATA_RAW/`: 경제변수 가공 전 원본 데이터
- `DATA_xlsx/`: 엑셀 형태로 저장하는 파일 위치
- `model_result/`: 모델 적합 결과 저장
- `plot/`: 그래프 저장
- `통화정책결정문/`: 통화정책결정문에서 추출한 원본 텍스트 위치
- `통화정책방향_processed/`: 통화정책방향만 따로 추출하여 저장한 텍스트 파일 위치

##### 파일

- `1_hanja.ipynb`: 통화정책결정문 텍스트 중 한자를 한글로 변환
- `2_data.ipynb`: 데이터 전처리, 병합
- `3_model.ipynb`: 모델 적합, 결과 저장
- `4_graph.ipynb`: 그래프 생성
- `5_additional.ipynb`: 부가적인 작업 사항
- `to_send.ipynb`



### 참고문헌

- 우신욱 and 장영재. (2020). 미 연준 통화정책방향 의결문의 시그널링 효과 분석. 응용통계연구, 33(3), 321-334.