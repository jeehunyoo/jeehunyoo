GIT 수업입니다.

git 협업 권장순서
pull -> work -> commit -> pull -> push

branch - 미래가 불안전한 작업(실험적인 작업할 때)
merge - master로 실험을 합칠 때 : master로 checkout 하고 우클릭하고 Merge 실험 into current branch

tip) 충돌방지하기 위해서 branch 한 것에서 master 틈틈히 merge

외부저장소 - 다른 사람들과 협업할 때. github의 저장소와 동기화시킨다.
            push : sourcetree에 있는 작업했던 기록들 외부저장소(github)에 올림
            pull : 다른 사람이 이 작업 같이 할 때 외부저장소(github)에 있는 clone path 통해서 clone project 해서 함. pull 하면 외부저장소에 있는 작업 내 컴퓨터로 가져옴.
