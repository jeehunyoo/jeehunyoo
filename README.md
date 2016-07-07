GIT 수업입니다.

git 협업 권장순서
pull -> work -> commit -> pull -> push

branch - 미래가 불안전한 작업(실험적인 작업할 때)
merge - master로 실험을 합칠 때 : master로 checkout 하고 우클릭하고 Merge 실험 into current branch

tip) 충돌방지하기 위해서 branch 한 것에서 master 틈틈히 merge

외부저장소 - 다른 사람들과 협업할 때. github의 저장소와 동기화시킨다.
            push : sourcetree에 있는 작업했던 기록들 외부저장소(github)에 올림
            pull : 다른 사람이 이 작업 같이 할 때 외부저장소(github)에 있는 clone path 통해서 clone project 해서 함. pull 하면 외부저장소에 있는 작업 내 컴퓨터로 가져옴.

stash - 작업 중 버그 발견되서 버그먼저 해결해야 될 때. 작업 중이던 코드는 완          성되지 않아서 그대로 놔두면 프로그램 돌아가지 않는다. 그래서 이 작업 중이던 코드 따로 저장해놓아야 할 때 씀.
stash에 저장되있는 것 우클릭하고 가져오거나 삭제할 수 있음.

태그 - 기념비적인 버전 기록,관리할 때
push 할때 tag도 함께 push할 수 있다.
원하는 버전에서 우클릭 후 tag 선택

ignore - 디렉토리 안에 파일 중 버전관리 필요하지 않은 파일있을 때
         Ustaged files에서 우클릭 후 ignore 선택
         .gitignore에 ignore하는 파일들 기록되있음(설정파일)
         www.gitignore.io에서 eclipse, java 등을 추가하면 알아서 ignore해줄 것들 generate 해줌 -> copy해서 .gitignore 파일에 paste.
