## git log

+ commit 기록 확인(최신순 정렬)

+ --oneline: 각 커밋별 한줄요약


## HEAD

+ 현재 작업 중인 브랜치의 위치

+ "~ 브랜치의 commit이다."

## git status

+ 커밋 준비 완료/not staged/untracked로 분류하여 표시


## commit --amend

+ vim 진입하여 commit 내용 수정할 때 사용

+ 새로운 commit으로 대체(= ID 변경됨)

+ -m "<커밋 메세지>": vim 진입 없이 수정

+ --no-edit: 커밋 메세지는 수정 X

+ :rotating_light:주의: 다른 사람이 작업 기반으로 삼는, 또는 여러 브랜치를 이용한 commit은 amend 금지.(충돌 발생)


## git reset <--option> <commit ID>(지정된 커밋보다 나중에 만들어진 커밋을 삭제)

+ 커밋 삭제, 다른 브랜치 영향 가능성 있음 -> 위험함. 사용 지양할 것

#### 옵션들(commit 취소, 리셋 깊이의 차이)

+ soft: 변경사항이 staging area로 돌아감

+ mixed(기본값): 변경사항이 working directory로 돌아감 

+ hard: 변경사항 제거, 이전 커밋으로 돌아감


## git revert <commitID>(되돌리기)

+ 커밋 제거 X, reset에 비해 비교적 안전함

+ 새로운 커밋을 생성해서 되돌림()

+ --edit, --no-edit (편집기 사용여부)

+ --no-commit: 직접 커밋 X, revert한 내용을 staging area에 올림(추가 작업 가능)