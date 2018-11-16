# Data Transfer
lazypic은 고객의 데이터를 AWS 서비스를 이용하여 데이터 전송합니다.

## 데이터 다운로드

작업된 데이터를 다운로드 받는 URL입니다.
콘텐츠를 다운로드 하는 분이 2명이상이라면 각각 계정을 등록해야합니다.
아래 정보를 영문으로 보내주세요.
- Name
- E-mail

https://lazypic.signin.aws.amazon.com/console/s3/?bucket=lazypic-{clientname}

최초 1회 접근 패스워드를 알려드리며, 이후 직접 사용할 패스워드를 변경하셔야 합니다.

로그인시 멀티팩트인증을 사용합니다.
실제 데이터를 다운로드 받는 사람 핸드폰에 Google Authenticator를 설치해주세요.

![authentiator](https://lh3.googleusercontent.com/SClWEmbk7QxxuKiWshok2T45vAwEQYCduisnnGORqrha7KfpQsvFZa0xac_jyj_tE9Mn=w720-h310)
- iOS : https://itunes.apple.com/us/app/google-authenticator/id388497605?mt=8
- Android : https://play.google.com/store/apps/details?id=com.google.android.apps.authenticator2&hl=en

아래 이미지처럼 보안인증번호 발급을 위한 QR코드를 메일로 같이 보내드리면 Google Authenticator App에 등록해주세요. (아래 QR코드 이미지는 예 입니다.)

![qrcod](https://m.media-amazon.com/images/G/01/DeveloperBlogs/AmazonDeveloperBlogs/legacy/6a0148c71fb71b970c014e6015c37a970c-800wi._CB520194804_.png)

등록이 정상적으로 되면, clientname대신 여러분의 계정이름이 보이며 로그인시 입력해야 하는 6자리 숫자가 생성되기 시작합니다.

![googel_authenticator](https://user-images.githubusercontent.com/1149996/48599454-13764e80-e9ab-11e8-91cd-1ea993bb4475.png)a


## Console 로그인
AWS S3를 이용한 전송 이외에 다른 서비스를 이용하여 고객과 업무시 사용하게되는 console URL 입니다.

https://lazypic.signin.aws.amazon.com/console


## 규정준수
- https://aws.amazon.com/ko/compliance/programs/
- MPAA : https://www.mpaa.org/what-we-do/advancing-creativity/additional-resources/) : 
- AWS MPAA : https://aws.amazon.com/ko/compliance/mpaa/ 
