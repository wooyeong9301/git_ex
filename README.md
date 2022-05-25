# git_ex

Git과 Github를 익히면서 필요한 내용들을 정리

### Local과 github 연결하기
##### Local 저장소에서 github repository로 업로드
- 업로드할 Local 저장소로 이동   
`cd ~`
- Git Initialize
`git init`
- 원격 저장소 등록 : github에 repository 있어야 함   
`git remote add origin [repository address]`   
`git fetch origin` ???
- 아래와 같이 commit 후 push   
`git add [file] or .`   
`git commit -m "message"`   
`git push origin main(master)`   
  - error: src refspec main does not match any    
error: failed to push some refs to 'https://github.com/wooyeong9301/Topic_practice'
  - *main 브랜치를 찾을 수 없다는 말인가??*

- Username과 password 입력 : github ID와 token 입력 후 pull   
`git pull`


##### github repository에서 
