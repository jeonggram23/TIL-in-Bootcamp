# git 명령어

## 파일 관리
- `git init`
    - 현재 폴더에 새로운 `.git` 폴더를 생성

- `git add <file, folder name>`
    - `working directory`에서 `staging area`로 추가
    - 일반적으로 모든 파일, 폴더를 추가하기 위해 아래의 코드를 사용
    - `git add .'`

- `git commit -m `message`
    - `staging area`에 올라간 파일들의 스냅샷을 찍어 `.git directory`에 저장
    -일반적으로 `-m` 옵션을 넣어서 커밋메세지를 추가하여 등록

- `git push origin master`
    - `master`브랜치를 원격저장소 `origin`으로 업로드하는 명령어

## 설정
- `git status`
    - 현재 상태를 체크하는 명령어


- `git config`
    - git 설정을 하는 명령어
    - 일반적으로 `--global` 옵션으로 최초 한번만 실행
    - git config --global user.email 'your@email.com'
    -git config --global user.name 'yourname'

- `git remote`
    - `git remote add origin <remote url>`
    - remote 저장소 주소를 추가하는 명령어

# 2023-07-25

- `git clone <remote url>`
    
    - 원격 저장소에 있는 레포를 현재 폴더에 복제
    - 작업해야 할 문서가 아직 없을 시 git bash terminal을 이용하여 입력




- `git pull origin master`

    - 원격 저장소에 마지막 코드 상태를 다운로드



### branch 관련

- `git branch`

    - branch의 위치를 확인



- `git branch -c` 

    - branch 생성



- `git branch switch ~~`


    - ~~로 이동



- `git push origin master ~~`
   
   - master로 push



그 후 pull request 기능과 fork 기능으로 기여하는 것에 대해 배움

