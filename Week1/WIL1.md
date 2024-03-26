> ## :rotating_light:Git 설치 시 주의사항
>
> branch 설정: master보다는 main을 주로 사용하므로 설정 시 주의
>
> VS코드에서 터미널 열기
>
> "git help" 입력(명령어 많이 나와야함) -> 정상설치되었는지 확인해보기
>
> 안될경우 VS코드 재실행

-------------------------------------------------------------------------------------------------------------------------

# git 초기설정
**1. git에 정보 넣어주기**
```
git config --global user.name "깃허브 이름"
git config --global user.email "깃허브 이메일"
```

git init: 로컬 저장소를 초기화

**2. add 상태로 만들기**

파일명 + U = "Untracked"
```
git add .: 모든 파일을 Git으로 관리
git add <파일명>: 특정 파일을 Git으로 관리
```
**3. commit 상태로 만들기**

git commit -m "커밋 메세지"

commit 메세지 타입 종류
+ feat(기능 추가)
- refactor(기존 코드 개선)
+ fix(버그 수정)
- chore(코드 외 설정을 변경)
+ docs(문서화)
- test(테스트)

기존 레포지토리를 연결
```
git remote add origin (레포지토리 주소)
```
로컬에 있는 파일들 깃허브로 공유하기
```
git push -u origin main 
```
-u는 처음 깃허브로 업로드할때만

## 이후 파일 수정 방법 및 기타 참고사항

git branch -m main : branch 이름 main으로 변경

파일 수정 후 저장시 M(odified) 상태로 전환

.md: "이 문서는 마크다운 문법으로 작성되었다"라는 것을 나타내는 확장자명. 

<https://github.com/Yukise0707/Yukise0707>