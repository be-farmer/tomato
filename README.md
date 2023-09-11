## tomato

작업을 할 때 각자의 작업을 식별하고, 작업의 충돌을 방지하기 위해 branch를 사용합니다.

**사용 방법**

1. 새 작업 시작시 git bash에서 브랜치 생성, git checkout -b 브랜치명
   * 예시) git checkout -b choi/crawling
2. 작업물 추가 git add .
3. 커밋 git commit -m "브랜치명 커밋내용" 
4. git push origin 브랜치명
5. git checkout main
6. 작업물 당겨오기 git pull origin main
7. git branch -d 브랜치명
