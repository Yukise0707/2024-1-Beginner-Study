 ### Fork
 
+ 다른 사용자의 레포지토리 복사해서 독립적으로 관리할 수 있는 기능.
 
+ 다른 사용자와 공동 프로젝트를 할 때 코드 수정&제안 용도로 사용 가능함.


 ### Star (즐겨찾기 기능과 유사)

+ Repository나 프로젝트에 북마크처럼 이용 가능


 ### Issue

+ 포스트 형식으로 글을 올리는 것과 같음

+ 작업 계획, 토론, 추적 등을 위해 활용


### Branch 

+ :sparkles: "type/ - <issue 번호> <간략한 설명>"로 브랜치명 지을 것 :sparkles:

+ 기존 브랜치에서 뻗어나오는 또 다른 작업공간("가지") 

+ 동일 리포지토리에 생성

'''
브랜치 확인
git branch
git branch -a

브랜치 생성/삭제
git branch "브랜치 이름"
git branch -D "브랜치 이름"

브랜치 이동
git chechout "브랜치 이름"

브랜치 생성 후 이동
git checkout -b "브랜치 이름"
'''

### Pull request

+ 분기된 브랜치 병합

+ 새로운 변경 제안, 병합시 발생하는 충돌 해결


### Merge

+ Merge commit: 신규 브랜치 + 기존 브랜치로 새로운 커밋 생성

+ Squach and Merge: 생성된 Branch에 있는 커밋들을 하나의 커밋으로 병합

+ Rebase and Merge: 생성된 Branch에 있는 커밋들을 모두 새로운 커밋으로 기존 브랜치에 재생성 (*주의: 오류 가능성 높음)


 ### Commit ID

 + hash값을 사용(40자 길이의 16진수)

 + 중복 확률 있긴 하지만 매우 낮음 

<https://github.com/Yukise0707/2024-1-Beginner-Study/pull/3>