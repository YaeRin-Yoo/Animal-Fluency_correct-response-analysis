# Animal-Fluency_correct-response-analysis



## 논문

***동물 유창성 검사의 채점 및 군집 기준 확립과 자동 분석의 타당성 검증 연구 (유예린 외., 2024)***



## 프로젝트 목적

***동물 유창성 검사의 채점 및 군집 기준 확립과 자동 분석의 타당성 검증 연구 (유예린 외., 2024)*** 에서는 연구자마다 다르게 적용하고 있던 동물 유창성 검사의 양적 분석을 위한 정반응 채점 기준을 통일하여 5가지의 세부 채점 기준을 제시하였다. 본 연구에서는 재확립한 동물 유창성 정반응 채점 기준을 바탕으로 동물 유창성 검사의 정반응 수 (the number of correct responses)를 python 코드를 사용하여 분석할 수 있는 자동 분석 코드를 설계하였다. 이에 실제 임상 및 연구 현장에서 누구나 손쉽게 대상자의 동물 유창성 검사 양적 분석을 수행할 수 있도록 자동 분석 코드와 분석에 필요한 Inventory file을 공개한다.



## 사용 방법

1. [Animal Inventory File](https://github.com/YaeRin-Yoo/Animal-Fluency_correct-response-analysis/blob/aeefec559668a02a6979cad54a0dd6658c8b29fb/Animal%20Inventory%20File_240813.csv) 다운 받기 

  + Correct responses analysis를 위한 자동 분석은 해당 Animal Inventory File에 기반해 이루어진다.
    
  + 해당 파일에는 ***유예린 외., 2024*** 의 649명 대상자들이 산출한 동물 389개가 표준어를 기준으로 정리되어있다.
    
  + 파일은 새로운 연구 대상자의 추가에 따라 ***이화여자대학교 언어병리학과 신경언어연구실 유예린***에 의해 업데이트 될 예정이다.
 
  + 분석하려는 동물이 해당 파일 내에 존재하지 않는다면 코드 실행에 오류가 발생할 가능성이 있다. (혹은 최종 값에 '오류' 로 표기될 수 있다.)

    + 파일을 다운한 후, 분석에 필요한 동물을 직접 추가하여 사용할 수 있다. (추가 시, 논문 본문의 정반응 채점 기준을 참고해야 한다.)
   
    + 파일을 다운한 후, 분석하려는 동물 이름을 파일 내에 있는 동물 명과 일치하게 바꾸어 사용할 수 있다.
   
      + 예) 분석하려는 동물 명 '팬더' , 파일 내에 존재하는 동물 명 '판다' : 팬더 --> 판다 교체 후 분석 시행.

      
2. [Correct responses analysis] (https://github.com/YaeRin-Yoo/Animal-Fluency_correct-response-analysis/blob/90839abee8f02c9fa7df010498ccdf66a668a06c/Correct_response_analysis_open.ipynb) 코드 실행

  + Correct responses analysis의 자세한 분석 방법은 ***유예린 외., 2024*** 에서 소개하고 있다.

  + 코드 최종 실행 시 필요에 따라 calculate 함수와 final_performance 함수의 결과 값을 적절히 활용할 수 있다. 

  + 대상자가 발화한 동물들을 List 형태로 함수 ***calculate*** 에 넣으면 각 세부 반응 (동물) 별 정오 반응 결과 값을 return 받을 수 있다.
   
    + 예시 결과는 아래와 동일하다.
   
    + <img width="723" alt="image" src="https://github.com/user-attachments/assets/5503d9e0-25b5-4a49-bcbd-adfed787948b">

  + 대상자가 발화한 동물들을 List 형태로 함수 ***final_performance*** 에 넣으면 각 피험자의 최종 정반응 수를 return 받을 수 있다.

    + 예시 결과는 아래와 동일하다.
   
    + <img width="730" alt="image" src="https://github.com/user-attachments/assets/54250ed7-0dd6-41a7-9d45-f50a67485259">





## 저작권 및 사용권 정보

동물 유창성 검사 수행력 분석을 위해 해당 동물 분류 군집 기준이나, 자동 분석 방법을 활용할 때는 ***유예린 외., 2024*** 인용 및 언급이 필요하다.



## 업데이트 정보

Last Update : 2024.09.21



## FAQ

이화여자대학교 언어병리학과 신경언어연구실 유예린 (leader9390@ewhain.net or leader9390@naver.com)



## 감사합니다.
