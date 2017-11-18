## Login_3.80

***

###### LineagePLUS did not create L1Login, I am looking for the source-code or to decompile too rebuild

***

### Encode `v3.80`
#### Tab I
###### Left Sife
- Server Name
- IP / Domain Name
- Port 
- Client version

###### Right Side
- Packet Encrytion
- Anti-Plug
- Advanced Plug-In
- Pak version 
- LinHelper
- Mobile Packet not encrypted
- Allow multi open

###### Bottom
- Server #
- Save all the above settings

#### Tab II
###### Section I.
Generates `pack.properties`

	Autoentication=True
	RSA_KEY_E=########
	RSA_KEY_D=#########
	RSA_KEY_N=##########

###### Section II
- Copies data

###### Section III
- Select Client Version
- Creates `ver.pak` from `ver.txt`

#### Tab III

    Line 1 | http://update.domain.name/terms/index.html
    Line 2 | http://update.domain.name/login.ini
    Line 3 | http://update.domain.name/pc/update.ini
	Line 4 | http://ui.domain.name/index.html

***

##### 한국인을 위한 간략 설명

***

#### 1. Encode 폴더

- Encode 폴더에서 Encode.exe 실행
- 서버IP 와 포트 지정
- TW13081901 선택
- 버튼 클릭
- 생성된 Login.ini 파일을 복사하여 Login 폴더에 붙여넣기

#### 2. Login 폴더

- eat.exe 실행
- Login.exe 를 리니지 폴더에 붙여넣기
