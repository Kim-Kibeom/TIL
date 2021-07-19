## .gitignore

- git이 특정 파일을 추적하지 않게 하기 위한 규칙

  - 패턴 매치를 통해 찾아냄

- 문법

  - 디렉토리는 슬래시(/)를 끝에 사용하는 것으로 표현
  - 슬래시(/)로 시작하면 하위 디렉토리에 적용되지 않음
  - 느낌표(!)로 시작하는 패턴의 파일은 무시하지 않음

- 예시) .gitignore 파일을 생성하면

  - \*.html : 현재 dir 및 하위 dir 모두 포함하여 적용함
  - _/_.html : 현재 dir 미포함, 하위 dir 포함하여 적용함
  - !/\*.html : 현재의 dir 아래의 dir에서 html 파일을 무시하지 마라

- finding sample .gitignore files
  - https://github.com/github/gitignore
