# text_mining
AWS - comprehend, Glue, Athena, S3, Quicksight

<img width="800" alt="ta-architecture" src="https://github.com/jenny5587/text_mining/assets/103649749/ddc1caf6-6e33-42a6-b628-9762b62e7c6a">

쿠팡의 릴 리뷰 데이터를 크롤링 한 후 S3에 넣고 AWS comprehend Sentiment를 작업한 후 
Output의 경로를 S3로 놓은 후 Glue crawler로 결과 테이블을 Athena와 연결하여 Quicksight로 감정분석 시각화
