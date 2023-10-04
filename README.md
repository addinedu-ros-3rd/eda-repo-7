# EDA 프로젝트 7조 저장소 / 칠면조 / 주제 : 2015-2023년 한국 드라마 분석
---
## 파일 설명
1. mydramalist_crawling.ipynb
> myDramaList 사이트에서 크롤링 하여 excel로 저장하는 코드.   
크롤링 도중 여러가지 상황으로 멈추는 것을 대비해 excel을 사용하였음.

2. kdrama_preprocessing.ipynb
> ```mydramalist_crawling.ipynb``` 파일로 크롤링한 데이터를 전처리하는 코드

3.  upload_to_aws.ipynb
> 전처리까지 완료한 excel 파일을 aws에 업로드하는 코드

4. kdrama.ipynb
> aws에 저장된 데이터를 이용해 분석하는 코드
---
## 사이트 설명

- MyDramaList 사이트
![Alt text](./images/MyDramaList.png)

- 검색 리스트와 드라마 페이지는 크롤링을 막고 있지 않음.
![Alt text](./images/robots.png)

- 드라마 리스트에는 다음과 같이 옵션을 지정할 수 있으며, url의 변수를 바꿔서 옵션을 바꿔줄 수 있음.
![Alt text](./images/drama_list.png)
![Alt text](./images/drama_list_url.png)
---
## 드라마 페이지 설명

![Alt text](./images/drama_page.png)