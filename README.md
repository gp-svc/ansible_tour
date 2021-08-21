Installing python 3.9 version 
download the tar ball from python org

yum install gcc openssl-devel bzip2-devel libffi-devel zlib-devel xz-devel
cd /usr/src
wget https://www.python.org/ftp/python/3.9.0/Python-3.9.0.tgz
tar -xvf py
tar -xvf Python-3.9.0.tgz
cd pytohon 3.9
 ./configure --enable-optimizations
 make altinstall
 
 cd /usr/bin/
 ln -s  /usr/local/bin/python3.9 python
   
 cd /usr/local/bin/
 cp pip3.9 pip
    
