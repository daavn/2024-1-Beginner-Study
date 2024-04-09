# git log
- commit 기록을 최신 순으로 보여준다.
- --oneline 옵션 사용 시 각 커밋을 한 줄에 요약한다.
## commit id
- commit 식별을 위해 사용한다.
## head
- 현재 작업 중인 위치를 나타낸다.


# reset
- commit을 제거하는 데 사용한다
## soft
- git reset --soft "commit id"
- commit만 취소하고, 변경 사항은 staging area로 돌아간다.
## mixed
- git reset --mixed "commit id"
- commit 취소 후 변경 사항은 working directory로 돌아간다.
## hard
- git reset --hard "commit id"
- 변경 사항을 모두 삭제하고 이전 커밋으로 돌아간다.

# revert
## git revert --no-edit "commit id"
- 편집기 진입 없이 바로 revert가 가능하다.
## git revert --no-commit
- 직접 commit하지 않고, revert 내용을 staging area에 올린다.
## revert vs reset
- reset의 경우 commit을 삭제하는 것이므로 위험하다. 따라서 commit을 삭제하지 않고 새로 생성하는 방식으로 되돌리는 revert 사용을 권장한다.


