
<Github 협업>
내 작업물을 올리고, repostory에 있는 팀원 분들의 자료를 공유받는 과정

<Git 저장소(Repository)>
Git은 원격 저장소와 로컬 저장소 두 종류의 저장소를 제공한다.
원격 저장소(Remote Repository): 파일이 원격 저장소 전용 서버에서 관리되며 여러 사람이 함께 공유하기 위한 저장소.
로컬 저장소(Local Repository): 내 PC에 파일이 저장되는 개인 전용 저장소.
평소에는 내 PC의 로컬 저장소에서 작업하다가 작업한 내용을 공개하고 싶을 때에 원격 저장소에 업로드 합니다. 물론 원격 저장소에서 다른 사람이 작업한 파일을 로컬 저장소로 가져올 수도 있다.


* add
#local에서 remote로 파일 업로드
$git add .

* commit 
#팀원들끼리 규칙을 정해서, commit message를 정한다.
$git commit -m "first commit"

* push
$git push origin master

*브랜치 생성
$git chekout -b "이름"

*브랜치 전환
$git checkout "branch이름"

*Pull
$git pull

*clone
$git clone 'url'