## git log

- 깃은 레포지토리의 모든 것을 추적함

  - 따라서 git log 를 통해 이전 커밋들을 볼 수 있음

- git log

  - --graph
    - 최근 커밋부터 그래프 형식으로 보여줌
  - -숫자
    - 과거 (숫자) 개의 커밋을 보여줌
  - --oneline
    - 매 커밋을 한 줄로 표시
    - git hash는 처음 7개만 표시
  - --all
    - 조상이 아닌 커밋이 있어도 모두 표시

- git shortlog

  - 커밋의 요약 내용을 얻을 수 있음

- Searching git history
  - git log --author=(name)
    - (name)이 커밋한 것을 보여줌
    - 이름에 공백이 있는 경우 큰 따옴표로 묶기
  - git log --grep=ideas
    - 커밋 메세지에 ideas가 있는 커밋을 찾는 경우
  - git log (filename) / (dirname)
    - 파일이나 dir에서 일어난 커밋을 보여줌
  - git log --oneline -p (fliename)
    - 매 커밋 결과 보여줌
  - git log --oneline --stat
    - 변경 내용 상세 설명
