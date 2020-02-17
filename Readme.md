# git 사용법
## 기본
### git 파일 상태
* untracked: repository로 설정된 폴더 내 모든 파일의 기본 상태로 git이 이력관리 대상으로 인식하고 있지 않은 상태
* tracked: git이 이력관리 대상으로 인식하고 있는 상태. "git add" 명령어를 이용하여 untracked 파일을 tracked 파일로 변경 가능
* unstaged: commit을 할 때 제외되는 상태로 staged 파일을 수정하면 git이 자동으로 인식하여 staged 파일을 unstaged 상태로 변경함.
* staged: commit을 할 때 저장되는 파일의 상태. "git add" 명령어를 이용하여 unstaged 파일을 staged 파일로 변경 가능