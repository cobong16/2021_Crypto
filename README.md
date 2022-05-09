# 2021_Crypto

2021 정보보안 프로젝트

파이썬으로 구현한 대칭키 암호 알고리즘

헥사도쿠를 인덱스 테이블로 이용하여 비트 단위의 전치를 수행함

How? 헥사도쿠는 16 * 16 2차원 테이블이며 4 * 4 2차원 테이블이 16개 존재함

헥사도쿠를 키를 통해 고정된 규칙으로 채워넣으면 전치에 사용할 인덱스 테이블이 생성됨

인덱스 테이블에서 첫 번째 (좌측 상단) 4 * 4 테이블 중 1이 위치한 행과 열의 위치가

전치할 테이블의 1열 1행 값을 해당 위치에 이동하는 것을 의미함

이것을 1,1 부터 16, 16까지 반복...

(이해를 돕기 위한 그림 파일 추가 예정)
