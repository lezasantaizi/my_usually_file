#linux 下安装pip 和 numpy的简易教程
1. [下载pip]
* 依次执行以下命令：*
> - wget "https://pypi.python.org/packages/source/p/pip/pip-1.5.4.tar.gz#md5=834b2904f92d46aaa333267fb1c922bb" --no-check-certificate
- tar -xzvf pip-1.5.4.tar.gz
- cd pip-1.5.4
- sudo python setup.py install

2. [下载setuptools包]
* 依次执行以下命令：*
> - wget http://pypi.python.org/packages/source/s/setuptools/setuptools-2.0.tar.gz
- tar zxvf setuptools-2.0.tar.gz
- cd setuptools-2.0
- python setup.py build
- sudo python setup.py install

3. [下载numpy]
> - sudo pip install numpy