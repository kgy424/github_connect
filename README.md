# github_connect

## 🍬 [git setup](https://git-scm.com/download/win)
      
      git을 통해서 github과 연결 가능.
      git에 올려야 할 폴더에 shift+우클릭 > PowerShell 선택
      > "git init" 입력
      => .git 폴더가 생성됨.

----------------
## 🍬🍬 open 'Git Dash' after setup the git
![image](https://user-images.githubusercontent.com/129706828/235417876-203da90e-226f-4334-be0c-b39ee631f6f4.png)

* 유저 이름 설정하기

            git config --global user.name"kgy424"
                  
                  
* 유저 이메일 설정하기(반드시 github에 가입한 이메일 주소와 동일한 주소 기입)
                  
            git config --global user.email "kgy424@naver.com"
            
* 내 정보 확인하기

      git config --list

## 위 연결은 한 디바이스에서 한 번만 실행하면 됨.
-----------------------

## 🍬🍬🍬 uplode th codr on github

* 초기화
      
      git init
      
* 추가할 파일(폴더 안 내용을 모두 올림)
      
      git add .(한 칸 띄우고 점 찍기 .은 모든 파일 의미)
      
* 히스토리 만들기(-m=메세지 ""= 안에 쓴 내용은 히스토리 이름 적음)
      
      git commit -m"first commit"
