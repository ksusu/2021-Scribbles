# [Git] Tutorial

## Intro
- 이것도 오래 안 쓰니까 너무 자주 까먹는다

## Reference

### Programs
- Source tree (https://www.sourcetreeapp.com/)
	- Best Git GUI I ever used
- Git Bash (https://git-scm.com/)
	- 우리가 아는 그 Git Bash

### Blogs & etc.
- GIt 설치와 사용법 (https://gbsb.tistory.com/10)
- [Linux] 파일의 종류 / 절대경로와 상대경로 (https://neul-carpediem.tistory.com/49)


## Git Bash Command (Similar to Linux)
-   화면 초기화 : **Ctrl + L**
-   한 행의 처음과 끝 : **Ctrl + A**, **Ctrl + E**
-   목록 보기 : **ls** 또는 **dir**
-   파일의 내용 보기 : **cat**
-   특정 문자를 검색 : **grep**
-   디렉터리로 이동 : **cd**
-   디렉터리 생성 : **mkdir**
-   파일 삭제 : **rm**
-   파일 생성 : **touch**
### TMI
- dir path **~** : 시작 dir 위치 (절대경로: C:\Users\[Specified User], 사용자 폴더에서 시작)
- 절대경로
	- **/** 로 시작하는 경로이고 이 위치는 C 드라이브 보다 위에 있음
- 상대경로
	- 상대적인 경로이고 **/**가 아닌 것으로 시작 (ex. **~** or **.**)
	- **.** : 현재 dir
	- **.\.**: 상위 dir

## Git Command
### git config
git을 깔면 제일 먼저 해야함
안하면 git commit 할 때 오류남
아마도 commit 할 때 user specification이 필요해서 그런 듯

~~~cpp
git config --global user.name "My name"
git config --global user.email "My email@email"

# Check the configuration list
~~~
<!--stackedit_data:
eyJoaXN0b3J5IjpbNzY4OTgwNjAwLDE3NTUwNzYwMTZdfQ==
-->