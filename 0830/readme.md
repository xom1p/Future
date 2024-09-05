# 8월 30일 과제 
## 1. Windows terminal 설치
Wsl을 환경을 구축 하기 위해 WT(Windows Terminal)을 설치 해준다.

<br>![image](https://github.com/user-attachments/assets/9960a566-bbe0-4661-bd36-0c3d3a066443)</br>
Microsoft store에서 WT를 다운이 완료한다.

## 2.WSL2 설치
WSL 이란 
: Windows 운영 체제에서 Linux 환경을 실행할 수 있게 해주는 기능

<br>![image](https://github.com/user-attachments/assets/c52fd18e-7377-41b1-927f-4fc49b1cf855)</br>
관리자 권환으로 실행을 한다.

<br>![image](https://github.com/user-attachments/assets/99944cf9-3afa-4d70-ac7c-3bdc103053ac)</br>
(WT가 실행된모습)

WSL2 를 다운받기 위해 다음 명령어를 실행한다.
 
### ```$ wsl --install```
<br>![image](https://github.com/user-attachments/assets/ac3b4701-8246-4694-86c0-15c942b5361c)</br>
설치가 끝나고 WSL 버전 기본값을 2로 변경해준다.
### ```$ wsl --set-default-version 2```
<br>![image](https://github.com/user-attachments/assets/8a756102-4a98-44c1-a1ca-29563b0a1d96)</br>

### Microsoft store에서 Ubuntu다운
WSL에서 사용할 리눅스 배포판을 설치하기 위해  Microsoft store에서 Ubuntu 다운받아준다.
<br>![image](https://github.com/user-attachments/assets/988d57cf-7810-41c0-9383-22935b9b4ec2)</br>
가장 상단에 있는 Ubuntu를 설치한뒤 실행을 한다.

처음에 'Installing. this may take few minutes…'이라는 메시지가 뜨고 시간이 지나면 사용할 user name , password를 설정하는 입력창이 나타난다.
<br>![image](https://github.com/user-attachments/assets/3a24eef3-42cd-4bf9-a999-19008643703b)</br>
user name , password 셋업을 끝난다면 다시 wt를 켜준다.
### ```$ wsl -l -v```
위와 같은 명령어를 wt에 입력해 현재 설치된 리눅스를 확인한다.
<br>![image](https://github.com/user-attachments/assets/20341d2c-0d1d-4c4c-8570-7734b1fff950)</br>
*는 디폴트 머신 , STATE 머신상태 , VERSION은 WSL의 버전<br>
머신을 종료할 때는 -t 옵션을 사용한다.</br>
<br>![image](https://github.com/user-attachments/assets/62e596ab-573b-4f07-93c7-3576e8b03124)</br>
-t 옵션을 사용한뒤 STATE가 Stopped상태 즉 머신이 종료된걸 확인할 수 있다.
<br>이로써 wt, WSL2 설치가 끝난다.</br>
