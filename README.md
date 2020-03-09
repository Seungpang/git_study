# git_study

## 브랜치, 언제 사용 할까?
+ 새로운 기능 추가
+ 버그 수정
+ 병합과 리베이스 테스트
+ 이전 코드 개선
+ 특정 커밋으로 돌아가고 싶을 때

## 브랜치 생성하기
+ git branch [-v]
+ git branch [-f] <브랜치이름> [커밋체크섬]
+ git branch -r[v]
+ git checkout <브랜치이름>
+ git checkout -b <브랜치이름> <커밋 체크섬>
+ git merge <대상 브랜치>
+ git rebase <대상 브랜치>
+ git branch -d <브랜치이름>
+ git branch -D <브랜치이름>
