# Git/GitHub를 사용하는 이유
내가 생성한 파일의 버전을 관리할 수 있다.
다른 개발자와 협업 시에 사용한다.

# Git/GitHub 사용
## 명령어
### 디렉토리 등록
*파일 경로 잘 확인하고* git init 
### 파일 등록
모든 파일 한 번에 등록 git add .  
하나씩 등록 git add <파일명>
### 커밋
git commit -m "<커밋 메시지>"
### 상태 확인하기
git log  
git status
### GitHub에 올리기 전
git remote add origin <리포지토리 주소>  
git branch -M main  
git push -u origin main  
### GItHub에 올리기
git add <파일명>  
git commit -m "<커밋 메시지>"  
git push origin main

# 마크다운 문법
## 제목
- ===== 를 사용한다
## 부제목 
- ------를 사용한다
## 글머리
- #을 사용한다. (최대 6개까지)
## 강조
- 기울임체: * *, _ _
- 볼드체: ** **, __ __
- 취소선: ~~ ~~


# 과제 제출
- https://github.com/daavn/daavn