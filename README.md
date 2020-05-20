# Airplane-Shooting-Game
**1. 목표**   
Win32에서 ‘비행기 슈팅 게임’을 작성한다.  

**2. 요구 사항**   
다음 사항을 모두 만족하는 응용 프로그램을 작성한다.   
1. ‘배경 화면’은 다음 조건을 따른다.
Window의 크기는 800 x 600이다. 
1 프레임당 5만큼씩 오른쪽에서 왼쪽으로 스크롤하여 오른쪽으로 움직이는 효과 를 준다. 이때, 배경 이미지를 반복해서 그려서 끝나지 않도록 한다.   
2. ‘내 비행기’는 다음 조건을 따른다. ‘방향키’를 누를 때마다 10만큼 적절한 방향으로 움직인다. 이때, Window의 경계 밖으로 나갈 수 없다.
‘Space’를 누를 때마다 미사일을 발사한다. 1 프레임당 20만큼 오른쪽으로 움직인 다. 비동기식 입력으로 처리한다.
‘Z’를 누를 때마다 폭탄을 투하한다. 1 프레임당 Y 방향으로 속도가 10, 가속도가 -1인 포물선을 그리며 떨어진다. 동기식 입력으로 처리한다.
‘적 비행기’나 ‘적 탱크’와 부딪치면 프로그램을 종료한다.   
3. ‘적 비행기’는 다음 조건을 따른다. 
Window의 오른쪽 경계에서 1초에 약 1번꼴로 생성되고, 왼쪽 경계에서 소멸한다. 3.2 새로 생성되는 ‘적 비행기’의 Y 좌표는 Window 범위 안에서 랜덤하게 설정한다. 
1 프레임당 10만큼 왼쪽으로 움직인다. 
‘미사일’을 맞으면, 해당 ‘미사일’과 같이 소멸한다.   
4. ‘적 탱크’는 다음 조건을 따른다. 
Window의 오른쪽 경계에서 2초에 약 1번꼴로 생성되고, 왼쪽 경계에서 소멸한다. 
새로 생성되는 ‘적 탱크’의 Y 좌표는 50으로 설정한다. 
1 프레임당 5만큼 왼쪽으로 움직인다. 
‘폭탄’을 맞으면, 해당 ‘폭탄’과 같이 소멸한다.  

**4. 결과**   
![image](https://user-images.githubusercontent.com/38244836/82406323-4ec27380-9aa1-11ea-9075-2b7f5d3d0e21.png)
