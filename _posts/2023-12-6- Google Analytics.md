---
layout: post
published: true
title: "Google Analytiecs"
date: 2023-12-4
tags: [pygame function]
---
##구글 Analytiecs기능
지난번 만든 Gihub 블로그에 Google Analytics를 적용해 보도록 하겠습니다.

전체 과정은 꽤 심플합니다.

1.Google Marketing Platform 에서 GA 계정을 생성하고
2.GA 와 깃허브 블로그를 연동합니다.
그럼 시작해보도록 하겠습니다.



GA 계정 생성
https://analytics.google.com/ 으로 이동하여 ‘측정 시작’ 클릭
‘계정이름’ 입력하고 ‘다음’ 클릭
‘웹’ 선택하고 ‘다음’ 클릭
웹사이트 이름 : ㅇㅇ 블로그 웹사이트 URL : xxx.github.io 업종 카테고리 : 인터넷 및 통신 보고 시간대 : 대한민국
‘만들기’ 선택


깃허브 블로그 연동
GA 계정을 생성하고 관리자 화면의 상단에 추적 ID 를 복사합니다.
깃허브 블로그 repository 의 _config.yml 파일을 수정합니다.
# /_config.yml

...

google_analytics:
  id: '추적 ID 붙여넣기'  # UA-123456789-1

...


연동 성공

##나의경우
나의 경우에는 처음에 config 파일에 이미 테마작성자가 Google Analytiecs를 이미 추가해둬서 추가할 필요가 없었다.