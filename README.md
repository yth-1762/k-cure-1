k-cure 첫번째 연구

# 주제
- Smoking Behavior Change and Noncombustible Tobacco Product Use Among Patients with Lung Cancer: A Nationwide Cohort Study

# 배경
- 전자담배 유무 및 흡연 유형에 따른 전체/폐암/비폐암 사망 위험도를 분석하고 전체/폐암/비폐암에 영향을 끼치는 개인 특성 요인이 무엇인지 분석하는 것을 목적으로 한다.
- 
# 주최
- 분당서울대병원 빅데이터센터

# 일정
- 2025.01.15 - 2026.01.14

# 데이터
- 폐암 환자 : 147303명 (건강검진데이터와 연계 가능한 인원)
- 표본1 : 30550명 (Never-smokers: 18093명/ Smoking quitters before diagnosis: 7742명/ Smoking quitters after diagnosis: 3414명/ Continuous smokers after diagnosis: 1301명)
- 표본2: 4715명 (Smoking quitters after diagnosis: 3414명/ Continuous smokers after diagnosis: 1301명)
- 표본3: 12457명 (Smoking quitters before diagnosis: 7742명/ Smoking quitters after diagnosis: 3414명/ Continuous smokers after diagnosis: 1301명)


# 사용 통계 모델
- logistic regression
- cox proportional hazard regression


# 분석1
- 사용모델: logistic regression 
- 표본: 4715명(Smoking quitters after diagnosis: 3414명/ Continuous smokers after diagnosis: 1301명)
- 종속변수: stop_yn(금연 여부)
- 독립변수: AGE,SEX,BMI,INCOME,CCI_SCORE(상병점수),STAGE(수술부위),수술여부,방사선치료여부,전신항암요법치료여부,폐암진단후전자담배사용여부
- 목적: 폐암 진단 당시 흡연자들을 대상으로, 진단 이후 금연 성공(Smoking cessation)에 기여하는 인구통계학적 요인, 임상적 특성 및 치료 요인을 규명하고자 함. 특히 폐암 진단 후의 전자담배 사용 여부가 실제 금연 여부(stop_yn)에 미치는 영향을 단변량 및 다변량 로지스틱 회귀분석을 통해 파악함.
- 분석결과: tables_20250901파일에서 table3에서 확인 가능

