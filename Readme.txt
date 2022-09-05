<Github 협업>
내 작업물을 올리고, repository에 있는 팀원 분들의 자료를 공유받는 과정


<Git 저장소(Repository)>
Git은 원격 저장소와 로컬 저장소 두 종류의 저장소를 제공한다.
원격 저장소(Remote Repository): 파일이 원격 저장소 전용 서버에서 관리되며 여러 사람이 함께 공유하기 위한 저장소.
로컬 저장소(Local Repository): 내 PC에 파일이 저장되는 개인 전용 저장소.
평소에는 내 PC의 로컬 저장소에서 작업하다가 작업한 내용을 공개하고 싶을 때에 원격 저장소에 업로드 합니다. 물론 원격 저장소에서 다른 사람이 작업한 파일을 로컬 저장소로 가져올 수도 있다.


<커밋규칙>
## ADD - 코드,테스트,예제,문서 등 추가
ex. Add ERR_INSPECTOR_COMMAND error

## IMPLEMENT - 구현(코드가 추가된 정도보다 더 주목할 만한 구현체를 완성시켰을 때 사용)
ex. Implement date object

## FIX - 버그,에러 수정
ex. Fix broken jsiexecutor search path

## REMOVE - 코드 삭제
ex. Remove fallback cache

## UPDATE - 코드 수정
ex. Update app icons

## RENAME - 이름 변경
ex. Rename node-report to report


<기본 설정>
- 윈도우에서 git을 활용하기 위해 git bash를 설치한다.
- 처음 설치 후, 컴퓨터한테 계정 정보를 입력해야한다.

$ git config --global user.email '메일주소'
$ git config --global user.name '유저명'
ex.
git config --global user.name 이 우 철
git config --global user.email dncjf1970@gmail.com


<bash 입력 코드>
*상태확인
$git log

*설정확인
$ git config --global -l

* add
#local에서 remote로 파일 업로드
$ git add "파일명"
$git add .

* commit 
#팀원들끼리 규칙을 정해서, commit message를 정한다.
$git commit -m "first commit"

* push
$git push origin master

*브랜치 생성
#git checkout 에 -b 옵션을 입력하면 브랜치 전환과 동시에 새로운 브랜치를 생성할 수 있다.
$git chekout -b "생성 후 전환할 브랜치 이름"

*브랜치 전환
$git checkout "전환할 브랜치 이름"

*브랜치 목록 확인
$git branch

*Pull
$git pull

*clone
$git clone 'url'

*이전 커밋으로 돌아가기
$git reset 'commit id'