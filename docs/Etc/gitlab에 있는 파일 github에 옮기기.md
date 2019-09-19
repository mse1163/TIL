# gitlab에 있는 파일 github에 옮기기

1. 바탕화면에서 gitbash 열기
2. gitlab에 있는 프로젝트 하나열어서 clone복사.(Clone with HTTPS)
3. 바탕화면 gitbash에서 git clone 복사한 clone주소
4. 복사한 폴더를 열어 gitbash열음
5. git remote -v 로 주소 확인
   - `origin`으로 되있으면 이것을 **다른거**로 바꿈, **같으면 안됨**
6. github의 리포지토리 주소 복사함. -> `remote` 어쩌고 되있는거.
7. git remote add `github` github의 레포지토리 주소 
8. git push `github` master

