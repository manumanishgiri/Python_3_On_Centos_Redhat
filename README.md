# Python_3_On_Centos_Redhat
Python_3_On_Centos_Redhat

# Dependecies
sudo yum install -y update
suod yum install -y vim httpd wget
sudo yum -y install gcc gcc-c++ 
sudo yum -y install zlib zlib-devel
sudo yum -y install libffi-devel 

# Download Python
wget https://www.python.org/ftp/python/3.7.1/Python-3.7.1.tgz

# Extract the content in new folder
tar xvzf Python-3.7.1.tgz

# Step into the folder
cd Python-3.7.1

# Run below code step by step :
./configure
make
make install
