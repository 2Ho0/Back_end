![image](https://user-images.githubusercontent.com/68044527/126106928-61ac6d6f-f7fd-40cc-9693-457561b8a83c.png)

우분투 리눅스에서 E325는 실행하려는 프로그램이 비정상적인 종료로 .swp 파일이 남겨져 있을 때 발생하는 오류이다.

이럴 때는

1\. 위 사진처럼 오류가 뜬 상태에서 **엔터**를 눌러서 **vi**로 이동한다

![image](https://user-images.githubusercontent.com/68044527/126106949-193ee140-84d5-47f0-ae8e-ea3483a6fd4f.png)

2\. **:q**를 입력해서 **vi**를 **종료**한다

![image](https://user-images.githubusercontent.com/68044527/126106958-cfea4613-8d5e-4c91-ae86-dae45044507d.png)

3\. **vi**를 나온 다음 "**ls -la"**를 입력해서 **.swp** 파일을 찾고 

![image](https://user-images.githubusercontent.com/68044527/126106974-2f705d9d-f669-499f-b39e-71d8c7488d50.png)

4\. **sudo rm .파일명.swp**를 입력해서 **삭제**한다

![image](https://user-images.githubusercontent.com/68044527/126107037-5d01985f-f2e4-4024-854a-857725e91c84.png)

앞에 **"sudo"**를 안붙이면 허가 거부가 떠서 삭제가 되지 않으므로 **주의!!**
![image](https://user-images.githubusercontent.com/68044527/126107046-821ced60-84fa-4707-96fb-c987489de7d1.png)
