# Installing Bash on Windows 10  
***  
1. Select the developer mode in the Developer tab in the "windows update settings"  
2. After confirming "Windows subsystem for Linux" in the "window operation tuning/off", reboot  
3. Enter bash in cmd  
# bash shell  
***  
sudo(Substitute User Do) 명령어 리눅스, 유닉스 계열에서 구동할 수 있게 해주는 프로그램  
APT(Advanced Packaging Tool) 리눅스에서 소프트웨어 설치 또는 제거 작업을 할 때 사용  
apt-get 패키지를 설치하는 명령어  
  
file delete : `find /root -name 'file' -exec rm -r {} \;`  
error : the program 'rpm' is currently not installed  
`sudo apt install rpm`  
error : the program 'yum' is currently not installed  
`sudo apt install yum`  
error : no acceptable C compiler found in $PATH  
`apt-get update`  
`apt-get upgrade`  
`sudo apt-get install build-essential`  
build-essential 소프트웨어를 빌드하는데 수많은 패키지 참조


