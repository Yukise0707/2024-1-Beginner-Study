Git 설치 시 주의사항

git init 사용시 branch 설정되는데 요즘 main이 주로 사용되므로 master 대신 사용

VS코드에서 터미널 열기

git help로 명령어 잔뜩 나오면 git 설치 정상적으로 완료된거임
안될경우 VS코드 재실행


git 초기설정
	git config --global user.name "깃허브 이름"
	git config --global user.email "깃허브 이메일"
git에 정보 넣어주기

폴더 하나 만들고 열기

git init 로 로컬 저장소를 초기화

파일 하나 만들기

.md: 마크다운

파일명 + U = untracked
staged 상태로 만들어야함 (git add .)
폴더 디렉토리의 모든 파일을 Git으로 관리하겠다 선언

파일 commit하기
git commit -m "메세지"

레포지토리 생성(Public)

기존 레포지토리를 연결(git remote add origin (레포지토리 주소))
git branch -m main : branch 이름 변경
git push -u origin main 로컬에 있는 파일들이 깃허브로 공유됨
-u는 처음에만
###여기까지 하면 됨.

이후 파일 수정

파일 수정 후 저장시 M(odified) 상태로 전환
add -> commit -> push하면 됨
git add .
git commit -m "이름"
git push origin main(-u 없어도 됨)