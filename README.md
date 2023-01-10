## 주제📈
사용한 git 명령어 정리

## 기간📆
2022.11.11

## 목록📝 
1. `git init`
- 해당 디렉토리에서 git 관리를 시작하겠다

2. `git remote add origin https://github.com/(깃허브계정이름)/(레포지토리이름).git`
- 로컬에서 깃허브 레포지토리와 연결하기위해 입력하는 명령어
- 연결이 잘 됐는지 확인하는 명령어: `git remote --v`

3. `git add .`
- 수정/삭제/추가 된 모든 파일을 깃관리에 추가할 때 입력하는 명령어
- `.` 대신 파일명을 직접 지정할 수 있다 : git add `test.js`

4. `git commit -m "(내용)"`
- 깃 관리에 추가된 현재까지의 내용을 어떤 작업을 했는지 (내용)을 덧붙여 로그를 기록할 때 쓰는 명령어

5. `git push origin main`
- 2.에서 입력한 origin주소로 커밋된 git을 push하겠다

6. `git branch (이름)`
- (이름) 이라는 브랜치를 생성하겠다

7. `git branch`
- 생성되어있는 branch 리스트를 확인하겠다

8. `git checkout (이름)`
- 현재 있는 깃 브랜치에서 (이름)이라는 브랜치로 변경하겠다 
