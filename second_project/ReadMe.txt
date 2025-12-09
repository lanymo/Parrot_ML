1. 개발 환경 및 과정

Google colab에서 python을 사용하여 구현

데이터 전처리(이상치 처리, 결측치 처리, 로그 스케일) / 원핫 인코딩을 통한 칼럼 정리 / 랜덤포레스트를 이용한 머신러닝 모델을 돌려 결과 예측 및 측정

2. Data set

Data file : Kor_income.csv
-> column 설명

✓ Id : people’s id
✓ year : year of study
✓ wave : from wave 1st in 2005 to wave 14th in 2018
✓ region : 1) Seoul 2) Kyeong-gi 3) Kyoung-nam 4) Kyoung-buk 5) Chung-nam 6) Gang-won 
&. Chung-buk 7) Jeolla & Jeju
✓ income : yearly income in M KRW(Million Korean Won. 1100 KRW = 1 USD)
✓ family_member : number of family members
✓ gender : 1) male 2) female
✓ year_born
✓ education_level : 1) no education(under 7 yrs-old) 2) no education(7 & over 7 yrs-old) 3) 
elementary 4) middle school 5) high school 6) college 7) university degree 8) MA 9) 
doctoral degree
✓ marriage : marital status. 1) not applicable (under 18) 2) married 3) separated by death 4) 
separated 5) not married yet 6) others
✓ religion : 1) have religion 2) do not have
✓ occupation : this will be provided in separated code book
✓ company_size
✓ reason_none_worker : 1) no capable 2) in military service 3) studying in school 4) prepare 
for school 5) preprare to apply job 6) house worker 7) caring kids at home 8) nursing 9) 
giving-up economic activities 10) no intention to work 11) others
