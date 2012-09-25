simple-ictclas-wrapper
======================

simple-ictclas-wrapper

依赖
=============
 * swig:http://prdownloads.sourceforge.net/swig/swig-2.0.8.tar.gz
 
安装说明
=============
 
 cd simple-ictclas-wrapper

 cp libICTCLAS50.so /usr/lib/

 make

 cp _cnseg.so /usr/lib/python2.7/site-packages/
 cp cnseg.py  /usr/lib/python2.7/site-packages/


测试是否安装成功
================

import cnseg
