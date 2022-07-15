# 오늘 배운 내용을 적는 공간
###  저장소를 만들 위치에 README.md파일 생성하기

vscode를 열었는데 터미널 안보임

=>vscode 메뉴의 터미널 > 새터미널 선택

vscode의 터미널을 파워쉘이 아니라 git bash로 바꾸기

1. '+'버튼 누르고 기본프로필 설정
2. 화면 위쪽에 선택가능한 프로그램 목록에서 git bash선택
3. 기존의 파워쉘 터미널은 휴지통 버튼을 통해 제거
4. 다시 새 터미널을 생성해서 bash로 되어있는지 확인

get init을 통해 

###  터미널을 사용할 때 (CLI) 현재 작업 경로가 내가 원하는 경로와 맞는지를 꼭 확인

git remote add origin "깃허브 url"

git push origin master

여기가 저장소가 될 위치(디렉토리)입니다.

**__README.md__**

**git diff**

**git remote add origin "https://github.com/JiIJu/python_first.git"**

**git status**

**git add. : 현재 작업영역의 모든파일 staging area에 올리기**

**git commin -m "커밋메세지" : staging area 에 있는 관리 대상 파일 모두 commit ,-m은 메세지를 남길수있는 옵션**

**git remote add origin "git hub url" : 어떤 원격저장소에 깃작업 할 건지 등록**

**git push origin master : 내가 지금까지 커밋한 내용(파일들) 원격 저장소에 업데이트**

**git 인증방법 : settings => developer settings => personal access tokens가서 토큰 발급받기 (웹으로 인증하라고 알림뜨면 초록색 버튼)**

**발급된 토큰은 다시 볼 수 없으므로 꼭 어딘가 메모**

**expiration date : 토큰의 만료기간**

**권한설정 : repo부분만 체크 (저장소 관련 권한)**

**git clone "git hub url" : 해당 원격저장소에 있는 파일들 현재 작업영역으로 복사**

**commit 하기전에 꼭 pull을 통해서 원격 레포지토리와 로컬 레포지토리의 정보를 최신화**