
# CLI 이란
- 컴퓨터를 조작하기 위한 방법 중 하나이다
# Git hub Bash 명령어

##  전제조건

- 이것을 쓴다는 것은 컴잘알이라는 뜻

- 어떤 명령을 실행하면 그 명령이 가져올 결과를 이미 알고 
  있다는 전제하에 사용한다고 생각함
  
- 보통 파일 삭제를 하면 휴지통으로 가지만, 여기서 삭제하면
  영구삭제가 됨
  
# 명령어들
touch - 파일 생성하기

  - toch a.txt
  - .뒤에는 파일 형태가 온다. txt-텍스트 .py- 파이썬 파일

  list(ls) - 목록 보기

  - 폴더/파일을 보여준다
  - ls -a 숨김 파일까지 보여준다

  .hidden - 숨김파일

  - 윈도우 환경에서는 보이지만 리눅스 mac os 환경에서는 파일이 숨겨진다
  - mv - 파일을 이동할때, 생성할때 쓰인다

  사용법 - 'mv aaa.txt CLI' 처럼 입력하면 aaa.txt 파일이 CLI폴더 내로 이동한다

  - rm - 파일 삭제
  - /cd 파일위치 : ~위치 변경



### 초기화 시점에 1회 입력
```
-  $git init
```
### 작업하며 계속 입력
```
- $git add <filename>
- $git add . : 모든 파일 등록
- $git commit -m 'MESSAGE'
```
### 모니터링 명령어
```
$git status #현재 상황
$git log  #commit 로그

```
## ** 절대 하지 말아야 할 것 **
```
1. ~에서 $git init 진행
2. 리포 안에 리포 만들기
3. 3.$git init 입력 전 확인할 점
   1.~위치 인지
   2.(master) 떠 있는지

```
## 원격 저장소 사용하기
1. 원격 저장소(remote repo)등록하기 (처음)
 - $git remote add origin <URL>  
2. 원격 저장소에 PUSH 하기 (추가할때 )
- git push origin master

















