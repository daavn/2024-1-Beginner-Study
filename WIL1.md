# Git/GitHub를 사용하는 이유
내가 생성한 파일의 버전 관리 가능
다른 개발자와 협업 시 사용


# Git/GitHub 사용

## 명령어

### 디렉토리 등록
**파일 경로 잘 확인하고** git init 

### 파일 등록
모든 파일 한 번에 등록 git add .
하나씩 등록 git add <파일명>

### 커밋
git commit -m "<commit message>"

### 상태 확인하기
git log
git status

### GitHub에 올리기 전
git remote add origin <리포지토리 주소>
git branch -M main
git push -u origin main

### GItHub에 올리기
git add <파일명>
git commit -m "<commit message>"
git push origin main


# 과제 제출
<https://github.com/daavn/davvn>