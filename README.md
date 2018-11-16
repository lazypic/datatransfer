# Data Transfer
lazypic은 고객의 데이터를 AWS 서비스를 이용하여 데이터 전송합니다.

> 이 문서에서는 회사 이름 대신 clientname 이라는 문자를 대신 사용하였습니다.

## 데이터 다운로드

lazypic 에서 작업된 데이터를 다운로드 받기 위해서는 먼저 다운로드 받을 수 있는 계정등록이 필요합니다.
콘텐츠를 다운로드 하는 분이 2명이상이라면 각각 계정을 등록해야합니다.
아래 정보를 admin@lazypic.org로 보내주세요.
- 영문 Name
- E-mail

lazypic 관리자가 계정 발급이 끝나면, 총 4개 항목의 메일을 전송하게 됩니다.
- 콘텐츠를 다운로드 받을 수 있는 URL
- ID
- 최초 PW
- MPA 2중인증을 위한 QR코드

### 콘텐츠 다운로드 URL
아래 URL을 통해서 콘텐츠를 다운로드 받게 되며 clientname 대신 여러분의 회사명이 들어가게 됩니다.

https://lazypic.signin.aws.amazon.com/console/s3/?bucket=lazypic-clientname

### 최초 패스워드
최초 1회 접근 패스워드를 알려드리며, 이후 직접 사용할 패스워드로 변경하셔야 합니다.

### MPA 멀티팩터인증
![authentiator](https://lh3.googleusercontent.com/SClWEmbk7QxxuKiWshok2T45vAwEQYCduisnnGORqrha7KfpQsvFZa0xac_jyj_tE9Mn=w720-h310)

lazypic은 로그인시 멀티팩터인증을 사용합니다.

이 기능을 사용하기 위해서는 데이터를 다운로드 받는 사람 핸드폰에 Google Authenticator 앱을 먼저 설치 해야합니다.

다운로드 URL은 아래와 같습니다.

- iOS : https://itunes.apple.com/us/app/google-authenticator/id388497605?mt=8
- Android : https://play.google.com/store/apps/details?id=com.google.android.apps.authenticator2&hl=en

![qrcod](https://m.media-amazon.com/images/G/01/DeveloperBlogs/AmazonDeveloperBlogs/legacy/6a0148c71fb71b970c014e6015c37a970c-800wi._CB520194804_.png)

위 이미지처럼 보안인증번호 발급을 위한 QR코드를 메일로 같이 보내리게 되는데 Google Authenticator App에 등록해주세요.

![googel_authenticator](https://user-images.githubusercontent.com/1149996/48599454-13764e80-e9ab-11e8-91cd-1ea993bb4475.png)

등록이 정상적으로 되면, clientname대신 여러분의 계정이름이 보이며 로그인시 입력해야 하는 6자리 숫자가 생성되기 시작합니다.



## 규정준수 Reference
- https://aws.amazon.com/ko/compliance/programs/
- MPAA : https://www.mpaa.org/what-we-do/advancing-creativity/additional-resources/) : 
- AWS MPAA : https://aws.amazon.com/ko/compliance/mpaa/ 
