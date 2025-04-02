1. fast-forward merge : 기능 추가/수정 시 사용하는 merge 방법
1-1) hj 브랜치 생성 후 fast-forward.txt에 commit 생성
1-2) master 브랜치에서 fast-forward merge 실행

2. 3-way merge : ex) 로그인 기능 구현 - 한명은 아이디 한명은 비밀번호를 담당했을때, 두명이 모두 구현 후 merge 하는 방법
2-1) hj 브랜치, main 브랜치 양쪽에서 3way.txt 수정 후 commit 생성
2-2) conflict 해결 후 
2-3) 3way merge 실행

3. rebase merge : 새 브랜치 commit의 시작점을 master의 최근 commit으로 이동 후 merge


4. squash : 브랜치의 여러 commit을 하나로 합쳐서 master에 merge