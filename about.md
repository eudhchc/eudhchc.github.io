---
layout: page
title: 블로그 제작 방법
description: An optional about page for Scriptor Jekyll theme
---

Git hub 블로그 만들기!!
1. 새로운 Repository를 만들자
 


 

Repository name : username.github.io 의 형식으로 만들어 줍니다!
 

 


 

Public으로 설정!

 

Add a README file 체크!

 

마지막으로 Create repository!!

 


 

새로운 repository가 만들어 졌습니다!!

2.  자신의 컴퓨터 또는 노트북에 repository를 clone 하자
 

동일한 페이지에서 초록색 Code 버튼을 누르면 Clone을 할 수 있는 주소가 나옵니다.

 


 

HTTPs의 주소를 복사합니다.

 

그리고 컴퓨터의 터미널을 열어 clone하고 싶은 폴더에서 아래와 같이 명령어를 입력합니다. 

 

git clone HTTPs주소
 

저는 git_blog 라는 폴더를 먼저 만들었습니다.

 

그 폴더로 이동한 후 git clone을 실행하였습니다.

 


 

혹시 git clone 또는 push 과정에서 permission error가 뜨는 분들이 계실 수 있습니다.

user id에 본인의 account username을 쓰고, password에서는 본인의 발급받은 token password를 입력해야 합니다!
자세한 내용은 아래의 블로그를 참고해주세요
https://jason-api.tistory.com/79

 

 

다시 원래 내용으로 돌아와 폴더를 확인해 보면 자신의 repository name으로 된 폴더가 잘 생성 되었음을 알 수 있습니다.

 


3.  Clone 한 폴더에서 index.html 파일을 생성하자
 

윈도우 익스플로러나 사파리 같은 웹 브라우저가 홈페이지 url에 처음 접근하였을때 읽는 파일입니다.

즉, 홈페이지를 접근하였을때 처음 보여지는 화면을 결정하는 파일이 됩니다.

html 언어로 구성되어 있습니다.

 

터미널에서 아래의 형식으로 index.html 파일을 만들 수 있습니다.

 

cd username.github.io
echo "Hello World" > index.html
 


 

4. 생성한 파일을 원격 저장소로 Push 해주자
 

git add *
git commit -m "Start git blog"
git push -u origin main
 


 

5. 홈페이지가 만들어졌다. 확인해보자.
