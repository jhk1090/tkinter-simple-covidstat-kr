# 코로나 스탯
Tkinter의 기초만을 이용해 코로나 스탯을 만듭니다. (한국 전용)

## 시작하기
### 전제 조건
이 프로그램을 설치하려면 다음 조건이 충족되어야 합니다.
```
BeautifulSoap >= 4.9.1
Python >= 3.7.9
```

### 설치 방법
* 이 페이지의 우측의 릴리즈 부분에서 최신버전을 눌러 들어갑니다.
* 첨부된 압축파일을 받고 풀어줍니다.
* main.pyw를 실행합니다.

## 원리
BeautifulSoap 모듈을 이용해 한국의 코로나19 확진자 현황을 크롤링합니다.\
그리고 크롤링 된 정보를 tkinter 모듈를 이용해 gui로 표시합니다.

> 크롤링 된 사이트: https://ncov.kdca.go.kr/bdBoardList_Real.do?brdId=1&brdGubun=11&ncvContSeq=&contSeq=&board_id=&gubun=

## 주의사항
사이트를 크롤링하다보니 사이트가 다운되거나 잘못된 정보가 제공되었을 경우\
정확한 통계로 나오지 않을 수 있습니다.

## 스크린샷
![스크린샷](https://user-images.githubusercontent.com/72603240/122666555-e46e8c00-d1e8-11eb-9f22-7d911c9acf9e.png)
