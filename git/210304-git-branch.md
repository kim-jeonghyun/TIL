
Branch

git branch 확인
Git branch -a
리모트와 로컬 모두 확인 가능

Git checkout 이동 (공간이동 혹은 시간이동)
--> 최근 명령어는 git switch로 명령어가 바뀌었다.

Git merge : 병합 
내가 옮겨올 main 에서 병합하고 싶은 브랜치를 가져오는 것임

git branch -D [지울 브랜치]

git push -u origin [오리진에 올릴 새 브랜치]
로컬에서 새 브랜치를 만들어서 작업한 다음에 오리진에 처음 올릴 때 
오리진에도 내가 로컬에서 만든 새 브랜치와 같은 브랜치가 생기고 둘이 연결된다.


Conflict problem
서로 다른 브랜치에서 서로 개선을 해서 merge 하려고 할 때 문제 발생.
1. 둘 중의 하나를 선택하거나
2. 조합한다.

Git merge 하면 conflict 라고 뜬다.
vi 로 문제 발생한 파일로 가면 어떤 문제가 있는지 뜬다.g


