# git 프로젝트 관리



## 설치 프로그램

- VS code 다운로드
  - 환경변수 설정하기
  - start page없애기



## code

- 폴더 생성 후 `code` 커맨드 입력을 하면 **VS code** 프로그램이 실행된다.
- 현재 폴더에서 **VS code**를 실행 하고 싶으면 `code .`  실행 한다.
- **VS code**에서 확장자 `.md`파일을 만들고  마크다운 문법을 사용
- 마크다운 문법이 적용된걸 보고 싶으면 오른쪽 위에  `Open Preview to the Side(Ctrl+ K V)` 클릭.



## git 관리

- 현재 .git/폴더가 있는 위치에 파일을 관리하게 된다.
- 여기서 모두 다 `add` 하고 싶으면 `git add .` 사용
- `add`후에는 꼭 `commit`한다. 
- github pages로 홈페이지로 사용하고 싶은경우
  - 저장소 이름을 "user.name".github.io로 형식을 지켜줘야 한다.

- 원격으로 저장하고 자세히 확인하려면 `git remote -v`



## 홈페이지로 관리

> git은 스태틱 웹사이트로 구성 된다.
>
> - 스태틱 웹사이트(Static): 사용자가 누구든 같은 화면을 보여주는 사이트.
> - 다이나믹(동적) 웹사이트(Dynamic): 사용자에 따라 다르게 보여줄 수 있는 사이트.



- **VS code**이용하여 html 만든다.

- `!tab` 을 누르면 html의 기본 템플릿이 자동 완성된다.

- 내 홈페이지로 들어가고 싶으면 "user.name".github.io로 주소를 입력하고 들어간다.

- 첫 화면은 무조건 index.html로 만들어야 인식 가능.

- index.html을 수정한 경우 `F12`버튼을 통해 개발자 모드에서 강력 새로고침으로 바로 확인 가능. 

- 나중에 **Gatsby**를 이용하여 정적페이지를 더 잘 만들 수 있다. 

  

## 다음 단계

- 네이버 boostcamp
- README generator를 통해서 만든다.
  - [부스트캠프](https://github.com/connect-foundation/2019-projectsinfo)
  - [README generator](https://github.com/kefranabg/readme-md-generator )



## 협업을 위한 단계

### l. 기초 단계

- aws에서 서버 돌리려면 ALLOWED_HOSTS(settings.py)에 서버의 주소를 넣는다.
  - 모든 주소를 다 받으려면 '*'의 값을 입력한다.
  - 해당 주소만 받으려면 받으려는 주소를 넣어 준다.
- [ide.cs50.io](ide.cs50.io)(깃허브 필요)이 사이트를 통해서 공동 협업이 가능 하다.
- 실시간으로 같이 작업하려면 자신의 주소를 공유하여 작업을 할 수 있다.

- 도메인 사서 배포하고 싶으면 도메인은 [godaddy](https://kr.godaddy.com/)



### ll. push & pull

> 협업을 위한 `push`,`pull`명령어는 동시에 같은 작업을 할 수 없다.
>
> 또한, 협력자를 정해서 권한을 부여해야 해서 제약사항이 존재한다.(초대가 필요)

- `push`,`pull`명령어를 통해서 작업을 수행한다.



### lll. Fork & PR(Pull Request)

> 오픈 소스 일때

- 오른쪽 위 `Fork`버튼을 통해서 자신 저장소에 복제본을 만든다.
- 내가 수정한 코드를 반영하고 싶으면 `Pull requests`버튼을 통해서 요청한다. 
- `New pull request`버튼 클릭.



### lV. Shared Repository

> **현업 필수**
>
> - Git Flow
>
> - Github Flow

#### (1) `git branch`

- 현재 존재하는 branch



#### (2) `git branch [브랜치명]`

- 브랜치를 생성한다.



#### (2) `git checkout [브랜치명]`

- 브랜치를 이동한다.



#### (4) git branch -d [브랜치명]

- (빈) branch를 삭제



#### (5) git branch -D [브랜치명]

- 비어있지 않은, 병합되지 않는 브랜치 삭제



#### (6) `git merge [브랜치명]`

- 브랜치를 합친다.





### V. 기타

- [기술면접](https://github.com/JaeYeopHan/Interview_Question_for_Beginner)(github JaeYeopHan)
- [브랜치 시각화](https://git-school.github.io/visualizing-git/)

