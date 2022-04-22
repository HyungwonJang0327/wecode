# 1. git init
해당 명령어를 실행하게 되면 이제부터 이 로컬 저장소를 git에서 관리할 수 있도록 초기화를 시켜주는 작업이 된다.<br>
실제로 `git init을 하기 전과 후에 git status를 실행시켜보게 되면 그 결과값이 다르게 나옴`을 확인할 수 있다.

git init전의 git status는 git의 관리 영역이 아니라는
```
fatal: not a git repository (or any of the parent directories): .git
```
명령어가 뜨고, 
git init 후의 git status는
```
On branch master
No commits yet
nothing to commit (create/copy files and use "git add" to track)
```
이라는 명령어가 뜬다.
<br>
<br>
<br>
<br>

# 2. git status
`git의 상태를 확인`해 주는 명령어이다.
<br>
<br>
<br>
<br>


# 3. git remote add origin "github url"
해당 명령어는 로컬에 저장되어 있는 저장소에 github 주소를 연동해 `push할 수 있는 상태로 만들어 줄 수` 있다.<br>
나 이제 여기 주소 github이랑 연동할 거야!
<br>
<br>
<br>
<br>

# 4. git add .
github에 `push하기 전`, 변경사항이 있는 파일들을 `push 직전의 테이블로 올리는` 작업이다.<br>

나 이 파일들 github에 업로드 할거야!<br>

`.` 이라고 입력하는 것은 변경된 파일 모두를 add한다는 의미이다.
<br>
<br>
<br>
<br>

# 5. git commit -m ""
`변경된 사항의 내용을 설명하는` 명령어이다.<br>
나 이거 이렇게 이렇게 바꿨어!

<br>
<br>
<br>
<br>

# 6. git push origin master
`commit`까지 마쳤으면, 이제 진짜로 github저장소에 파일들을 업로드 시키는 명령어이다.

<br>
<br>
<br>
<br>

# 7. git branch
보통 default값 branch는 `main` 혹은 `master`이다.<br>
여기에 다른 branch를 만들어 작업을 하고 싶다면 `git branch branchname` 명령어를 통해 branch를 생성할 수 있다.
<br>
<br>
<br>
<br>

# 8. git checkout
자신이 원하는 branch로 이동할 수 있는 명령어이다.
