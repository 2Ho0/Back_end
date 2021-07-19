![image](https://user-images.githubusercontent.com/68044527/126106928-61ac6d6f-f7fd-40cc-9693-457561b8a83c.png)

우분투 리눅스에서 E325는 실행하려는 프로그램이 비정상적인 종료로 .swp 파일이 남겨져 있을 때 발생하는 오류이다.

이럴 때는

1\. 위 사진처럼 오류가 뜬 상태에서 **엔터**를 눌러서 **vi**로 이동한다

[##_Image|kage@bwAj22/btq9uAdCJVF/SQ5H0pC0ykwwCGFPKDeBaK/img.png|alignLeft|data-origin-width="140" data-origin-height="557" width="126" height="501" data-ke-mobilestyle="widthOrigin"|||_##]

2\. **:q**를 입력해서 **vi**를 **종료**한다

[##_Image|kage@sp6vX/btq9pDvV0Ur/BDUbXkBxxoQ31Z6g53XYD0/img.png|alignLeft|data-origin-width="185" data-origin-height="596" width="136" height="438" data-ke-mobilestyle="widthOrigin"|||_##]

3\. **vi**를 나온 다음 "**ls -la"**를 입력해서 **.swp** 파일을 찾고 

[##_Image|kage@NYo9k/btq9rcEPVTr/mqLSaNNmCuUowv9WKFAp80/img.png|alignLeft|data-origin-width="546" data-origin-height="169" data-ke-mobilestyle="widthOrigin"|||_##]

4\. **sudo rm .파일명.swp**를 입력해서 **삭제**한다

[##_Image|kage@PXc0k/btq9ll90wGy/XVtzXU10vI8ZGZXB6K6dFk/img.png|alignLeft|data-origin-width="630" data-origin-height="168" data-ke-mobilestyle="widthOrigin"|||_##]

앞에 **"sudo"**를 안붙이면 허가 거부가 떠서 삭제가 되지 않으므로 **주의!!**
