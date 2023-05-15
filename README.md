# github_connect

## 🍬 [git setup](https://git-scm.com/download/win) 🍄
      
      git을 통해서 github과 연결 가능.
      git에 올려야 할 폴더에 shift+우클릭 > PowerShell 선택
      > "git init" 입력
      => .git 폴더가 생성됨.

----------------
## 🍬🍬 open 'Git Dash' after setup the git 🍄🍄
![image](https://user-images.githubusercontent.com/129706828/235417876-203da90e-226f-4334-be0c-b39ee631f6f4.png)

* 유저 이름 설정하기

            git config --global user.name"kgy424"
                  
                  
* 유저 이메일 설정하기(반드시 github에 가입한 이메일 주소와 동일한 주소 기입)
                  
            git config --global user.email "kgy424@naver.com"
            
* 내 정보 확인하기

      git config --list

## 위 연결은 한 디바이스에서 한 번만 실행하면 됨.
-----------------------

## 🍬🍬🍬 uplode th codr on github  🍄🍄🍄

### on visiual code 
 
      * menu list -> dir
      * go in     -> cd
      * go back   -> cd..

* 초기화
      
      git init
      
* 추가할 파일(폴더 안 내용을 모두 올림)
      
      git add .(한 칸 띄우고 점 찍기 .은 모든 파일 의미)
      
* 히스토리 만들기(-m=메세지 ""= 안에 쓴 내용은 히스토리 이름 적음)
      
      git commit -m"first commit"

* github에 repository를 만들고 그 주소와 연결하기(리드미 생성금지)

      git remote add origin https://github.com/kgy424/css_flex.git
      
* 연결 확인(사용 안 해도 되는데 혹시나 싶자너~)

      git remote -v
      
* github에 올리기

      git push origin master
      
---------------------------
## 🩹 edit it and upload it again 🩹

__1. 초기화__
      
      git init
      
__2. 추가할 파일(폴더 안 내용을 모두 올림)__
      
      git add .(한 칸 띄우고 점 찍기 .은 모든 파일 의미)
      
__3. 히스토리 만들기(-m=메세지 ""= 안에 쓴 내용은 히스토리 이름 적음)__
      
      git commit -m"first commit"
      
__4. 기존 코드를 먼저 다운 받음__

            git pull origin master
      
__5. 다시 push하기__
      
            git push origin master


---------------------------

### 🍬🍬🍬🍬 How to Collaboration in GitHub 🍄🍄🍄🍄

__1. Download sourec code__
      
      ![image](https://github.com/kgy424/github_connect/assets/129706828/ff5900a3-ce13-4a85-88b8-5b693ade9a70)
      
__2. Write "git clone + link" where you want to download__      
      ex> git colne https://github.com/kgy424/hanacard.gi


            
