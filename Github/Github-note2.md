# GITHUB



## 기본 명령어 정리

* git init

* git add .   <->  git restore --staged
* git commit -m "커밋메세지"
* git commit --amend  #커밋메세지를 바꿈
* git push

* git status #커밋이전의 것들
* git log #커밋이후의 것들
* git remote -v #원격저장소가 어디인지 보는 법

* git pull origin branchname

* git restore filename  

* git clone url
* git log --oneline 커밋리스트
* git reset -hard 커밋번호 #모든 변경 커밋을 지우는것 =>그냥 지움
* git reset --mixed 커밋번호 #작업물은 남겨줌
* git reset --soft 커밋번호 #모든 작업물 남겨줌
* git revert 커밋번호 #되돌렸다는 커밋을 남김
* git stash #임시공간에 보관
* git stash pop #임시공간에서 꺼내기





## Branch 명령어 정리

* git branch -b branchname

* git branch branchname
* git checkout -b branchname #생성
* git checkout branchname #옮겨가기
* git merge branchname #입력한 브랜치가 흡수됨
* git branch -d branchname