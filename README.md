# ShiroVulnEnv

### 介绍
文章的漏洞环境，利用代码都在 test/java 下

### 步骤

#### Step1 
启动服务

#### Step2
来到 AESEncode 处，利用 AES 加密 tomcatHeader.ser 生成密文

#### Step3 
添加到 rememberMe 中进行发送，绕过 Tomcat Header 限制

#### Step4
来到 AESEncode 处，利用 AES 加密 tomcatInject.ser 生成密文

#### Step5
添加到 rememberMe 中进行发送，进行内存马的注入

#### Step6 
注入成功，回显如下





且都已处理好，生成的序列化文件在项目根目录下


### 参考链接
感谢三梦师傅和Litch1师傅，文章链接如下：

https://xz.aliyun.com/t/7388#toc-2
https://mp.weixin.qq.com/s?__biz=MzIwNDA2NDk5OQ==&mid=2651374294&idx=3&sn=82d050ca7268bdb7bcf7ff7ff293d7b3