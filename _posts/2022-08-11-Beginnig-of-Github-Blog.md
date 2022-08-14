---
layout: post
title:  "Beginnig of Github Blog"
---


# A first step
- 커스터마이징을 해야한다는 배움의 장점과, 깃헙 블로그에 대부분의 기능을 추가할 수 있다고 하여 learning curve를 감수하고 시작

## Reference for making this blog
- [테디노트 TeddyNote](https://www.youtube.com/watch?v=ACzFIAOsfpM)
- [guide to create post](https://jekyllrb.com/docs/posts/)
- [minimal mistakes setting doc](https://mmistakes.github.io/minimal-mistakes/docs/layouts/#sidebars)
- [Build a Data Science Portfolio (Free & Easy) with Jekyll & GitHub Pages \| Part 1: Site Configuration](https://www.youtube.com/watch?v=wCOInE7-E0I)

### [EP03. 업데이트 내역을 실시간 확인하기!! (로컬 개발환경 설정방법)](https://www.youtube.com/watch?v=0TeHUqSAb6Q)
  - _config.yml은 실시간 반영이 되지 않아서 서버를 다시 실행해야함
  - [Ruby installation steps to follow](https://jekyllrb.com/docs/installation/windows/)
    - [download Ruby](https://rubyinstaller.org/downloads/)
      - press 3 and enter to finish the Ruby installation
        - open terminal and type : `gem install jekyll bundler` enter
    - bundle install at github.io directory
      <p align = "left"><img src="/images/installation_ruby_setup.png" width="" height="300"></p>
    - local 에서 server 실행
      - `bundle exec jekyll serve`
        - if error occur ->  `bundle add webrick`
    - md 파일을 수정하고 저장하면 실시간 반영 및 확인이 가능함
      - 이상이 없으면 github에 commit and push~!!

### [EP04. 블로그 설정 매우 쉽게 변경하기 - NO코딩! (config.yml 활용)](https://www.youtube.com/watch?v=c-h3XcDjHtQ&list=PLIMb_GuNnFwfQBZQwD-vCZENL5YLDZekr&index=4)
  - 테마 변경
  - [locale 변경 reference](https://docs.microsoft.com/en-us/previous-versions/commerce-server/ee825488(v=cs.20)?redirectedfrom=MSDN)


## jupyter note 업로드 하는법
- jupyternote 를 md 파일로 받는다 (파일명은 영어로 하는게 좋다)
- \_posts에 drag and drop후 commit changes 하면 -끝-
