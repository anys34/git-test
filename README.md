# 깃허브 명령어 정리

### git init

- 저장소 생성

### git add .

- 저장소에 추가

### git commit -m "메세지"

- 커밋

### git push origin main(master)

- 커밋내용을 서버에 업로드

### git pull origin main(master)

- 서버 저장소의 변경 내용을 현재 디렉터리에 가져오기

### git remote reomve origin

- origin이라는 원격 저장소를 지우기

### git remote add origin "원격 저장소"

- origin이라는 이름으로 원격 저장소를 연결

### git log

- 지금까지 만든 커밋 확인

### git log --all

- 보이지 않는 모든 커밋 확인

### git log -p

- 이전 커밋과의 차이점 확인

### git checkout [commit ID] or [-]

- 해당(-는 최신) 커밋으로 이동

### git checkout main

- main 브렌치로 이동

### git status

- 파일의 상태를 분류하는 것

### git push -u origin main

- -u를 하면 다음부터 git push만 해도 된다

### git commit -am "메세지"

- add와 commit을 동시에 하기

### git clone "(상대의)원격 저장소.git"

- 폴더 생성 후 저장소 복제하기

### git clone "(상대의)원격 저장소 ."

- 폴더 생성 하지 않고 저장소 복제하기

### git pull "(상대의)원격 저장소"

- git clone을 하고난 후 상대가 push한 내용을 불러온다
