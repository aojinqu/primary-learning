
第一步是安装git，网上搜或者去官网直接一路回车确定安装即可，问题不大。



https://blog.51cto.com/lxw1844912514/2982366

区别是最后一步，因为我设置成了master而不是main

解答在这https://cloud.tencent.com/developer/article/1504684
$ git push -u origin master
由于新建的远程仓库是空的，所以要加上-u这个参数，等远程仓库里面有了内容之后，下次再从本地库上传内容的时候只需下面这样就可以了。
$ git push origin master
(是master还是main看情况)


第一步帮我给git和github之间建立联系了，因为输入完会跳转到一个登录的页面。  
然后再commit就成功了。

管理仓库的话，之前做项目的时候学长做个一个pdf文档教学，这里借来描述。
