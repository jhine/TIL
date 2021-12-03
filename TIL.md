
# CLI 이란
- 컴퓨터를 조작하기 위한 방법 중 하나이다
# Git hub Bash 명령어

##  전제조건

- 이것을 쓴다는 것은 컴잘알이라는 뜻
- 어떤 명령을 실행하면 그 명령이 가져올 결과를 이미 알고 
  있다는 전제하에 사용한다고 생각함
- 보통 파일 삭제를 하면 휴지통으로 가지만, 여기서 삭제하면
  영구삭제가 됨



### 초기화 시점에 1회 입력
```
-  $git init
```
### 작업하며 계속 입력
```
- $git add <filename>
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

















