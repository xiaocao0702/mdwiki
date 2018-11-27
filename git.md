#### 获取github项目
* 1、生成SSH key 
`ssh-keygen -t rsa`
* 2、将生成的 
`id_rsa`
`id_rsa.pub`
放到（windows:C:\Users\Administrator\.ssh | Mac:~/.ssh)下面
* 3、将`id_rsa.pub`用编辑器打开，复制
* 4、GitHub/Settings，点击SSH and GPG keys，再新建一个SSH key，粘贴保存
id_rsa.pub文件中的内容放到key中。
* 5、测试SSH连接 
`ssh -T -v git@github.com` 
成功提示如下： You've successfully authenticated, but GitHub does not provide shell access. 
* 6、使用 
`$ git clone git@github.com:xiaocao0702/mdwiki.git`


