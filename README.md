# Today I learned


### Git

- cil
- git 명령어들 

밑에 터미널에 등록하세요!

### 원격 저장소 등록


``` 
git remote add origin https://github.com/HSungDuk/TIL.git

주소 그 홈페이지에 있는거 따와서 등록
```

### 원격 저장소 정보 조회

```
$ git remote -v
```

### Git push

```
#origin이라는 이름의 원격ㄱ저장소의 master 브랜치에 push하기
$ git push origin master

#-u 옵션을 사용한 후에는 저장소 이름(orgin), 브랜치 이림(master)를 생략 가능함

$ git push -u orgin master
#그 이후부터는

$ git push
```

- 원격 저장소에서 수정작업을 하지 않는다.
-   로컬 저장소에서 변경을 하고 이를 원격 저장소에 반영하는 방식을 취한다.
- 반드시 로컬 저장소에서 gid add -> git push 단계로 업로드한다.

#### .Gitignore

- 특정 파일 혹은 폴더에 대해 Git 버전 관리를 하지 않도록 설정

#### .gitignore에 작성하는 내용들

- 민감한 개인정보가 담긴 파일(전화번호, 각종 비밀번호, API KEY 등)
- 운영체제에서 사용되는 파일들
- IDE(통합개발환경) 혹은 Text 에디터 등에서 활용하는 파일
  - pycham -> idea 폴더
- 개발 언어 / 프레임워크에서 사용되는 파일
  - python 가상환경..

#### 주의 사항

- 반드시 파일 이름을 '.gitignore'로 작성
- '.gitignore'위치는 .git과 동일한 폴더에 존재
- 제외하고 싶은 파일들을 add하기 전에 .gitignore에 작성

#### .gitignore 쉽게 작성하기

