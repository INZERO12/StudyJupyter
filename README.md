# StudyJupyter
Jupyter NoteBook 학습 리포지토리


![Jupyter](https://media.vlpt.us/images/seokbin/post/e14f498a-a0b1-4880-9a88-98be38c50267/jupyter_logo_icon_169453.png)

### 1일차
1. 아나콘다 설치
2. 파일데이터 불러오기
	- CSV 파일 불러들이기
	- 엑셀 파일 읽어 들이기
	- Json 파일 읽어 들이기
3. 파일 저장하기
	- csv 파일 저장하기
4.  공공데이터 Open API 데이터 읽어오기
5. 웹크롤링

### 2일차
1. 판다스 데이터구조
	- 시리즈(Series)
	- 데이터프레임(DataFrame)
2. 데이터프레임 조작하기
	- 데이터 요약 확인하기 info
	- 데이터행 조회하기 head/tail
	- numpy의 loc와 iloc 사용하기
	- 행 삭제 drop
	- 포함 유무 확인하기 isin
	- 컬럼 추가하기
	- 데이터 타입 변환하기 -> 형변환 astype
	- 데이터 갯수 확인하기 
	  count/len/index/columns/values
	- 정렬하기 sort
	- 데이터 합하기 concat/merge
	
### 3일차
1. 빈도 및 교차 데이터 만들기
	- 빈도분석 value_counts
	- 교차분석 pd.crosstab
		- 빈도 비율 확인 apply
		- 연속형데이터 describe()
2. 결측치 처리하기
	- 결측치 확인 isnull / notnull
	- 결측치 제거 dropna
	- 결측치 대체 fillna

### 4일차
1. 이상치 처리하기
	- 인덱스 번호 재배열 reset_index
	- boxplot으로 이상치 확인하기
	- 기초통계 확인 describe()
	- 최대값/최소값 계산하여 제거하기
		- percentile()함수
		- IQR 값 계산
		- 이상치값 조회
	- 행 번호만 조회 np.where
	- 이상치 제거하기				
2. 함수/모듈 생성
	- 매개변수가 없는 함수 만들기
	- 매개변수가 1개 있는 함수 만들기
	- 매개변수가 2개 있는 함수 만들기
	- 모듈 만들기