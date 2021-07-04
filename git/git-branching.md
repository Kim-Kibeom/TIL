### branching

    - 독립적으로 특정 작업을 진행하기 위한 개념. 필요에 의해 만들어진 개별 브랜치는 다른 브랜치의 영향을 받지 않기 때문에 동시에 여러 작업이 가능.
    - 작업 후 다른 브랜치와 병합(merge) 함으로써, 하나의 브랜치로 모을 수 있음
    - repository를 새로 만들면 master라는 이름의 브랜치를 만듬.

### stash란

    - 커밋하지 않은 변경 내용이나 새롭게 추가한 파일이 인덱스와 작업 트리에 남아있는 채로 checkout 하면, 변경 내용은 기존 브랜치가 아닌 전환된 브랜치에서 커밋할 수 있음.
    - 이때 전환된 브랜치에서 변경이 있는 경우 체크아웃에 실패할 수 있음. 따라서 이전 브랜치에서 커밋하지 않은 변경내용을 커밋하거나, stash를 사용해서 임시로 변경 내용을 다른 곳에 저장하여 충돌을 피해야함.
    - stash 란, 파일의 변경 내용을 일시적으로 기록해두는 영역. stash 를 사용하여 작업 트리와 인덱스 내에서 아직 커밋하지 않은 변경을 일시적으로 저장해 둘 수 있음. 이 stash 에 저장된 변경 내용은 나중에 다시 불러와 원래의 브랜치나 다른 브랜치에 커밋할 수 있음.

### 명령어

    - git branch (branchname) : 새로운 브랜치 생성
    - git checkout -b (branchname) : 새로운 브랜치 생성과 동시에 전환
    - git branch : 브랜치 목록을 보여줌
    - git checkout (branchname) : 해당 브랜치로 변경
    - git branch -d (branchname) : 해당 브랜치 삭제
    - git branch -all : local과 remote 브랜치들을 보여줌
    - git branch -r : remote 저장소의 브랜치를 보여줌
    - git branch -v : 브랜치의 마지막 커밋 내역과 보여줌
    - git branch -avv : branch link도 보여줌
