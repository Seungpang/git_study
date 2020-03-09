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


## 배포 버전에 태깅
+ git tag -a -m <간단한 메시지> <태그 이름> [브랜치 또는 체크섬]
    + -a로 주석 있는 태그를 생성, 메시지와 태그 이름은 필수 브랜치 이름을 생략하면 HEAD에 태그를 생성
+ git push <원격저장소 별명> <태그 이름>
    + 원격 저장소에 태그를 업로드