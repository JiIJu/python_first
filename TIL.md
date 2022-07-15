# 7/15 배운 내용을 적는 공간
###  저장소를 만들 위치에 README.md파일 생성하기

vscode를 열었는데 터미널 안보임

=>vscode 메뉴의 터미널 > 새터미널 선택

vscode의 터미널을 파워쉘이 아니라 git bash로 바꾸기

1. '+'버튼 누르고 기본프로필 설정
2. 화면 위쪽에 선택가능한 프로그램 목록에서 git bash선택
3. 기존의 파워쉘 터미널은 휴지통 버튼을 통해 제거
4. 다시 새 터미널을 생성해서 bash로 되어있는지 확인

git init 명령어를 통해 저장소를 버전관리 하겠다고 설정

터미널을 사용할때 (CLI) 현재 작업경로가 내가 원하는 경로와 맞는지를 꼭 확인하세요!!
git config --global user.name "깃허브username"

git config --global user.email "깃허브email"

--global 옵션은 전역으로 설정하겠다는 뜻입니다.(현재 작업영역 외에서도 똑같이 사용)
README.md

git add . : 현재 작업영역의 모든 파일 staging area에 올리기

git commit -m "커밋 메시지" : staging area에 있는 관리 대상 파일 모두 commit, -m은 메시지를 남길수 있는 옵션입니다.

git remote add origin "깃허브 레포지토리 url" : 어떤 원격 저장소에 깃 작업을 할건지 등록

git push origin master : 내가 지금까지 커밋한 내용(파일들) 원격 저장소에 업데이트

git 인증 방법 : settings => developer settings => personal aceess tokens 가서 토큰 발급받기

(웹으로 인증하라고 알림이 뜰시엔 초록색 버튼 누르면 인증 완료)

발급한 토큰은 다시 볼수 없으므로 꼭 메모장 같은곳에 저장하기!

expiration date : 토큰의 만료 기간

권한 설정 : repo 부분만 체크 (저장소 관련 권한)

git clone "깃허브 레포지토리 url" : 해당 원격 저장소에 있는 파일들 현재 작업 영역으로 복사

⭐commit 하기전에 꼭 pull 을 통해서 원격 레포지토리와 로컬 레포지토리의 정보를 최신화⭐

__git pull origin master: 원격 저장소의 내용 현재 로컬 저장소로 가져와서 최신화하기

1. git init
2. git add .
3. git commit -m "커밋메세지"
4. github에서 레포지터리 만들기(readme.md만들지않기)
5. git remote add origin "github url"
6. git push origin master
