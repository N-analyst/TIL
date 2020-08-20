# git프로그램 설치

- github의 markdown을 지원해주는 프로그램 Typora설치하기.
- gitbash를 사용하여 cmd창 이용하기.



## git프로그램 이용 사항

1. git은 폴더 단위로 파일을 관리한다.

2. 관리 관련 내용은 .git/ 폴더 안에 저장된다.

3. git init으로 폴더를 관리하고 더 이상 관리하기 싫으면 rm -r .git/을 통해서 폴더를 지운다.

4. git상태를 저장 == commit (현재 상태를 보기 위해서는 git status명령어 사용)

5. git config --global user.email "이메일" (이메일은 git에 가입된 이메일 사용하는게 좋다 log를 남기기 위해)

6. git config --global user.name "영문명"

7. git diff --staged로 전과의 차이점을 볼 수 있다.

8. git remote add "별명" "진짜 주소"로 주소 추가.

   

---



- git init

  *git status

- git add
- git commit
- git log
- git push