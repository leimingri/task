---
title: "准备工作及一些操作流程"
date: "2021/8/29"
documentclass: ctexart
output:
  html_document:
    df_print: paged
  pdf_document: default
---  

## 准备工作  
1.注册一个[**GitHub账户**](https://github.com)    
2.安装或者更新**R**和**RStudio**  
3.安装[**Git(windows)**](https://gitforwindows.org/)   
4.已经在Git上介绍了自己  
git config --global user.name 'leimingri'  
git config --global user.email 'lmr18845128812@163.com'  
git config --global --list  
替换您的名称和与GitHub帐户相关的电子邮件  
5.已确认可以从命令行对GitHub推/拉

## 连接Git GitHub,RStudio
首先，在GitHub上面创建一个项目repository，然后将项目地址克隆到RStudio中，接着进行本地的更改、保存及提交，将新增更改的内容保存到GitHub该项目存储库中，下面将运用图示法进行详细的流程介绍。  
1.连接RStudio到Git和GitHub
在GitHub上创建存储库（项目）,然后通过RStudio将新的GitHub存储库克隆到您的计算机上。在RStudio中，*File > New Project > Version Control > Git*:  
<img src="http://r.photo.store.qq.com/psc?/V54AC60s2AQkQe24IJrU0a9knd0j1QQg/45NBuzDIW489QBoVep5mcWqp6iCnBt6LgMYnnO6B5HpXjXKlbYxFk46xki6v1zZcEaLKDpUiI.MLcBVFuPNGdKY.JLtle6Q57.*tknTqg3k!/r" width = "400" height = "275" align=center />      
<img src="http://r.photo.store.qq.com/psc?/V54AC60s2AQkQe24IJrU0a9knd0j1QQg/45NBuzDIW489QBoVep5mcT7P9tdwXVcQslYJNuCoe7W6hmCqubVl3HuUivpwPir.KRmHsZwkPDJyMmRkW4WZ6C2jNxt*phmYwxIP7IVIALo!/r" width = "400" height = "275" align=center />    
<img src="http://r.photo.store.qq.com/psc?/V54AC60s2AQkQe24IJrU0a9knd0j1QQg/45NBuzDIW489QBoVep5mcT7P9tdwXVcQslYJNuCoe7VnCuhp9oP3UJXscyIvhykoRRAjVXj5hwQz1nFPXdgwFJhCCezbOKtjKDMgqj0vSv0!/r" width = "400" height = "275" align=center />  
<img src="http://r.photo.store.qq.com/psc?/V54AC60s2AQkQe24IJrU0a9knd0j1QQg/45NBuzDIW489QBoVep5mcT7P9tdwXVcQslYJNuCoe7VyroulROJQ3b42cW5GC0dZCEBNkSoiv4IA*whdlrb834MPsCW0Jk7Y1GrpFMW*ZFM!/r" width = "400" height = "275" align=center />  

2.进行本地更改，保存、提交：下载我们在GitHub上创建的README.md文件，在RStudio的文件浏览器窗格中查看README.md文件,从RStudio中修改文件。  
<img src="http://r.photo.store.qq.com/psc?/V54AC60s2AQkQe24IJrU0a9knd0j1QQg/45NBuzDIW489QBoVep5mcT7P9tdwXVcQslYJNuCoe7XxWjr.9heo*14lh0n7j..AY*WsAR3aJ763ojGHfyK0m09NzLViBpZiLcDkw99sjCQ!/r" width = "400" height = "275" align=center />   
3.保存更改，将您在本地进行的更改在线推送到GitHub，操作如下:  
<img src="http://r.photo.store.qq.com/psc?/V54AC60s2AQkQe24IJrU0a9knd0j1QQg/45NBuzDIW489QBoVep5mcXs7nTmmgbXR5sVjMg16OdQNCoHfjdD1DEGsjiNFJ19ugvqH76Ps6i.OufOQg0NsO1H1upexja1vlGr2gXIkH1c!/r" width = "400" height = "275" align=center /> 

4.最后，确认传播到GitHub远程存储器的本地更改。    
注：[R Markdown官网地址](http://rmarkdown.rstudio.com)      
    以上内容参考文献[happy-git-with-R](https://happygitwithr.com/)   

## 遇到的问题  
1.在RStudio中直接导入GitHub中项目的URL与在RStudio中创建项目再将RStudio中的项目导入GitHub中，两者区别是什么？(将RStudio中的项目导入GitHub中具体操作是怎样的，应该通过在RStudio中键入GitHub账号邮箱还是在GitHub中直接导入项目所在位置呢)    
2.rmarkdown中采取“-”没有生成无序列表，是什么原因呢？  
3.怎样将自己操作步骤的截图图片放入到rmarkdown文档中？  
4.导入GitHub中的URL时，出现‘...Connection was reset, errno 10054’错误时，解决办法：*git config --global http.sslVerify "false"*即解除ssl验证，再次git  
5.设置图片的大小和位置问题  
6.为什么生成的pdf里面没有图片，而html里面可以显示出图片？  
