# 내일의창업 tmrfounders

# 웹페이지 설명
내일의창업 공식 홈페이지를 들어갔을때 가장 먼저 보이는 랜딩페이지.
내일의창업의 주요 기능, 고객들의 후기, 요금제별로 달라지는 혜택등을 요약해서 보여주어 

# 만들면서 어려웠던 점
1. 
<img width="800" alt="어려웠던 점1" src="https://user-images.githubusercontent.com/97889490/200298524-d0ae8493-6385-4c60-b0ab-70d9e2d92ee7.png">
이 부분에서 네개의 이미지를 한 줄로 나열하고 중앙정렬하는 동시에 각 이미지 위에 텍스트를 올리는 것

2. 
<img width="800" alt="어려웠던 점2" src="https://user-images.githubusercontent.com/97889490/200298635-591e2fe2-d0d4-487c-a444-5669712c0dc2.png">
이 부분에서 프로필 사진과 카페이름의 배치간격을 조정하는 것. 조정하기 전에는 <img width="800" alt="스크린샷 2022-11-07 오후 8 26 01" src="https://user-images.githubusercontent.com/97889490/200299041-05402443-b9ab-4bf3-b319-486fa3a7baed.png"> 이렇게 보였다.


# 위 문제를 어떻게 해결했는가
1. 이미지 네개를 한 줄로 중앙정렬하고 이미지 위에 올릴 텍스트들도 각각의 div를 하나의 div로 묶어서 z-index를 2로 설정하고 일단 이미지 밑쪽에 둔 다음에 이미지 네개에 margin-bottom: -10%, z-index:1; 을 줬다.
<img width="535" alt="해결방법1-1" src="https://user-images.githubusercontent.com/97889490/200300108-f81b3dc0-a28e-44a7-b84a-167fe5a6302f.png">
<img width="246" alt="해결방법1-2" src="https://user-images.githubusercontent.com/97889490/200300279-bb41c5fe-9583-45ce-9ec3-2bb57ae93d02.png">

2. 
<img width="536" alt="해결방법2-1" src="https://user-images.githubusercontent.com/97889490/200299412-9061fe63-72d1-4a3e-838b-8ec05f9f27d1.png">
<img width="199" alt="해결방법2-2" src="https://user-images.githubusercontent.com/97889490/200299524-bace74f6-4bde-4cb5-a731-4635e8b0b6d3.png">
카페 대표님이름과 카페 이름을 한 p 태그 안에 넣고 span으로 css만 다르게 해서 두 텍스트의 간격을 맞추고 1번에서 했던것처럼 사진의 margin-bottom 을 조절해서 사진의 가운데 높이에 텍스트들이 올 수 있게 했다.

# 사용된 기술 스택
1. HTML
2. CSS

# 이번 개발을 통해 느낀 점
간격 맞추는 것이 생각보다 어렵다.
html과 css를 실전에서 사용할때는 배울때 접했던 정석적인 코드보다 더 다양한 방법으로 사용할 수 있다. 
