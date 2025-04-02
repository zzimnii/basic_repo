1. fast-forward merge : 처음 기능 추가/수정 시 사용하는 merge 방법
1-1) hj 브랜치 생성 후 fast-forward.txt에 commit 생성
1-2) master 브랜치에서 fast-forward merge 실행

2. 3-way merge : ex) 로그인 기능 구현 - 한명은 아이디 한명은 비밀번호를 담당했을때, 팀원이 모두 구현 후 merge 하는 방법
2-1) hj 브랜치, main 브랜치 양쪽에서 3way.txt 수정 후 commit 생성
2-2) conflict 해결 후 
2-3) 3way merge 실행

3. rebase merge : 기능 구현이 완성되었을 때 rebase를 통해 변경이력 정렬을 통해 파악에 용이하기 때문에 기능 구현 후 merge 하는 방법
2-1) hj 브랜치, main 브랜치 양쪽에서 rebase.txt 수정 후 commit 생성
2-2) rebase merge
2-3) conflict 해결 후
2-4) git rebase --continue

4. squash : 간단한 수정을 여러번 했을 경우 commit을 하나로 합쳐서 히스토리를 깔끔하게 유지할 때 merge 하는 방법