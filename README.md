# bbrplus
//编写中  

在https://blog.csdn.net/dog250/article/details/80629551 中，  
dog250大神提到了bbr初版的两个问题：bbr在高丢包率下易失速以及bbr收敛慢的问题，  
并提到了谷歌对这两个问题的修正，  
并在文末给出了修正后的完整代码。我叫它bbr修正版，或者  
  
由于编译修正后的模块需要4.14版的内核，  
以及需要修改内核的部分源码，所以需要重新编译整个内核。  
这里提供一下编译好的适合centos7的内核



