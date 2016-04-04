                                   kubernetes的第一个Hello World例子
     由于在kubernetes官网上使用的都是gcr.io中的镜像，国内原因创建rc的时候都失败，所以修改了json的配置。然后frontend中用到的是我私人的镜像
     在系统中使用git clone https://github.com/9923/skubernetes.git 下载项目
     进入到skubernetes目录，根据配置文件创建rc，service等，其中fronent的service使用nodePort的模式就可以另外机器
     访问到页面了。
