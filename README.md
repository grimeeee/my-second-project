# TIL

## 리눅스 명령어

1. ls

   > list ( 목록 표시 )

2. cd
   change directory ( 작업 경로 변경 )

3. rm
   remove ( 파일 삭제 )

4. mkdir  
   make directory ( 작업 목록 생성 )

5. rmdir  
   remove directory ( 작업 목록 삭제 )

6. touch
   파일생성

7. cat
   파일의 내용 출력

## Git

1. init  
   git 생성
2. add <파일명>  
   staging area로 이동
3. commit -m <메세지>  
   Repository로 이동
4. push <원격저장소><브랜치>  
   원격(GitHub)으로 이동
5. pull <원격저장소><브랜치>  
   원격에서 로컬로 복사
6. clone <원격저장소><브랜치>  
   원격에서 로컬로 복제
7. status
   Staging Area의 상태
8. log
   repository의 상태
9. git commit --amend
   바로 전 commit과 Staging Area의 Merge을 할 때
10. git restore --staged <파일명>
    Staging Area의 파일을 Working  
    Directory로 가져옴

![Git Sheat Sheet](asset/git.jpg)

**spacebar 3번 줄바꿈**

1. 문자코드 : 문자와 숫자를 1:1로 매핑시켜놓은 값이다

   컴퓨터가 사용하는 0과 1로 변환할 때 사용되는 기준

2. 진법 (진수) : 10(사람), 2, 8, 16

   -Bit : 0과 1만 표현

   -Byte : 8비트

   2진법 : 0과 1

   8진법 : 0~7

   10진법 : 0~9

   16진법 : 0~9 A(10) B(11) C(13) E(14) F(15)

3. 인코딩 : 유니코드(utf-8(:가변), utf-16, utf-32)

문자코드 : ASCII코드(7비트), 확장ASCII(= ANSI : 8비트 ANSI 각 나라의 코드값을 불러와야함

cp949로 인코딩 ) , 유니코드, EUC-KR코드

![Git Sheat Sheet](asset/base64.png)
![Git Sheat Sheet](asset/ASCII.png)
