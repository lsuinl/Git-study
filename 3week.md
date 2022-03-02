# 3주차 

### Git Branch (뻗어나가는 가지같은 느낌)	
- git branch suin (suin이라는 브랜치를 만들어줌)
- git checkout master (마스터를 빠져나감?)
- git marge suin (다른 브랜치와 병합)
- git log —oneline —graph —branchs (무슨 기록,, 브랜치 기록 보여줌?)      

+서로 다른 브랜치에 같은 파일이 존재하는 경우, 하나로 값을 병합(선택)해주어야 함

+master에서는 작업을 하면 안된다.


- git stash -커밋을 쌓지 않고 어딘가에 숨겨서 보관만 해줌 (다른 브랜치로 checkout 하는 경우에는 stash로 임시저장을 해두고 가는게 좋다)
- git stash drop-드랍
- git stash pop-꺼내오고 드랍
- git stash list  -리스트 보여주기

### branch에서
- git checkout -b Quinn (새로운 브랜치 Quinn 을 만드는동시에 저장)
- git branch -v (어 몰라)

- git merge2 (gui 환경에서 충돌들 어쩌고 알려주는 프로그램임  필요하면 설치해서 사용)
- git rebase -base (커밋을 다시 정의 하겠다는 의미(merge와 비슷한개념) 웬만하면 지양하는 방법)


https://ansohxxn.github.io/git/branch/

졸았다. 나중에 참고해서 다시 복습할 것.

3-way marge/알아서 공부
