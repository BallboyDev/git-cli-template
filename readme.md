# Git
## connection git / git init push
0. git init
    - 프로젝트 파일 git 초기설정
1. git remote add origin [URL]
    - 원격 저장소 추가
2. git add .
    - 작업물 및 수정, 생성 파일 staging 영역 추가
3. git commit -m "commit message"
    - staging 내용 커밋 메시지 작성 및 커밋
4. git branch -M main
    - 최초 브랜치 설정 -> main으로 이름 변경
5. git push -u origin main
    - 작업 내용 푸쉬

## 많이 쓰는 git 명령어
- git 
    - clone - git 저장소 복사
        - `git clone [URL]`
    - status - 현재 파일 상태 확인
        - `git status`
    - log - 현재 브랜치 기준 git commit 이력 조회
        - `git log`
    - branch - 현재 브랜치 리스트 조회 및 현재 브랜치 관련 수정
        - `git branch`
    - pull - 원격 저장소에서 로컬 저장소로 소스를 다운로드
        - `git pull`
    - push - 현재 프로젝트의 커밋된 내용을 원격 저장소로 업로드
        - `git push`
    - add - 작업 내용 staging 영역에 추가
        - `git log .`
        - `git log Readme.md`
    - commit - 작업 내용 로컬 repo 영역에 저장
        - `git commit -m "message"`

## git 