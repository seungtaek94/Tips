# Tips for Linux

네트워크 드라이브 마운트  

``` shell
sudo apt-get install cifs-utils

sudo mount -t cifs -o username=계정,password=비밀번호 -o uid=소유자id,gid=소유그룹id //아이피/원격_디렉토리 /로컬_디렉토리
```  
