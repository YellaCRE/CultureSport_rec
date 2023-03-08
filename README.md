# Sport Recommend System

문화관광 데이터분석대회 출품작 - 여가활동 추천을 통한 국민건강증진 

여가활동 설문조사에 따른 해당 여가활동의 선호도를 기반으로 사용자기반 협업필터링을 활용하여 스포츠여가활동을 추천

<img width="1210" alt="image" src="https://user-images.githubusercontent.com/76480887/220229996-1cdb3e7a-0922-4876-88fd-cf2a6e290280.png">

# Model

![스포츠 drawio](https://user-images.githubusercontent.com/76480887/223597297-564904ff-8df8-4b01-8e26-86881987a01d.png)

"스포츠에 대한 평가 점수도 중요하지만 그 스포츠를 경험했다"라는 사실도 중요하다고 판단되어  
해당 스포츠에 설문조사를 했다면 1 / 0 으로 경험여부를 표시  
이를 클러스터링하여 경험한 스포츠 기반 군집을 형성하였다  

따라서 군집내 평균 점수의 의미는 "특정 스포츠를 경험한 군집이 평가한 점수"이다  
이를 전체 평균 점수와 비교함으로서 특정 스포츠를 경험한 군집은 전체와 비교하여  
특정 스포츠를 좋게 평가했다, 나쁘게 평가했다를 파악할 수 있다

# Results

![image](https://user-images.githubusercontent.com/76480887/220252209-5e8f814d-4d82-4d01-b8d2-05aca4d877e2.png)
