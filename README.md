# 수업 내용

## 1일차

git github/bash

* GUI 
* TUI>CLI(cmd, powershell, bash(window에서 리눅스 명령어 사용가능.편리.간편.))


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

* HTML 구조
* CSS 꾸미기
* JavaScript 로직

* 프론트엔드 클라이언트
* 백엔드 서버

- [ ] API > 클라이언트가 서버에게 요청하는 규칙
- [ ] JSON > KEY: VALUE 형식으로 저장

api로 클라이언트가 서버에게 요청을 보내면, json으로 응답을 받음

## 2일차

### Markdown
헤더: # 띄어쓰기 중요(여러개 하면 작은거)
[url](https://cdn.imweb.me/upload/S201910012ff964777e0e3/62f9a36ea3cea.jpg)

### CLI
커맨드라인 인터페이스
 = 개발자의 기본소양이기에 사용한다

### Git
**협업을 원활하게 하는 도구**/ 개발자의 기본 소양
분산 버전 관리 시스템 (<>중앙집중)

인터넷X 이용가능

* GITHUB에 다운/업로드
* working directory>ADD>staging area>COMMIT (변경된 파일들을 저장하는 행위)>repository

* GIT = local repository
* GITHUB = remote repository

* git>github = PUSH
* github>git = PULL

commit 작성자 설정
* git config --global user.name 김도희
* git config --global user.email cathy950720@gmail.com
* git config --global -l
* git init

* echo c.txt >>.gitignore
* rm .gitignore

* git add
* git status
* git reset

---

1.  commit 작성자 설정
git config --global user.name 장상호

git config --global user.email sangho.jang@mincoding.co.kr

1-1. commit 작성자 확인
git config --global -l

2. git 실행(git 저장소 생성) , git 실행 취소
git init

rm -rf .git

3. git ignore
echo b.txt >> .gitignore

4. git add
git add .

4-1. commit 준비가 되었는지 확인
git status

4-2. add 취소(staging area에서 working directory로)
git reset

5. commit
git commit -m 'add a.txt'

5-1. commit 확인
git log

5-2 commit 취소
rm -rf .git

---
## 3일차

* git remote add origin https://github.com/dorykim/First.git
* git remote -v
* git push origin +master
* git pull origin master
* git clone https://github.com/dorykim/First

백엔드 DJango
프론트엔드 