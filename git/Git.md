# Git

##  Unix / Linux 명령어

* ls : 현재 위치의 폴더, 파일 목록보기

* cd : 현재 위치 이동하기 (cd .. 상위 폴더로 이동)

* mkdir <name> : 폴더 생성하기

* touch<name> : 파일 생성하기

* rm<name> :파일 삭제하기 (rm -r<name> 폴더 삭제하기)

* clear : 화면 정리하기

* git 기본기

  * Working Directory : 내가 작업하고 있는 실제 디렉토리
  * Staging Area 커밋(commit)으로 남기고 싶은 파일
  * Repository : 커밋(commit)들이 저장되는 곳

* git init : 특정 디렉토리를 관리하는 로컬 저장소 생성하기(.git)   - - > local Area

  * git status = 현재  git의 상태를 알 수 있다
  * git add : git 버전으로 관리 할 파일  추적되는 파일들을 Staging Area에 올린다.

  - git commit -m "commit_message" : git 버전으로 관리 시작

    * *  git config --global user.email "github 이메일 기입"

    - *  git config --global user.name "github 닉네임 기입"
    - * git log : Repository에 저장된 commit 파일 history 보기
    - * git diff 두 commit 간 차이 보기

* GITHUB 연결

  * git remote add origen 주소  ==> git을 주소로 이동
  * git push -u origin master ==> 주소로 master권한으로 푸쉬
  * git clone {remote_repo} : remote repo를 local로 복사합니다.
  * git push origin master : local repo의 최신 커밋을 remote repo로 push 합니다.