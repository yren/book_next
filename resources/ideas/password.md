# 无密码的世界

用户拥有一个主私钥，存储在手机端。在「注册」时，服务端将该私钥的公钥添加到数据库中。「注册」信息的私密部分会以 hash 的形式发送给服务端，该 hash 和「注册」信息的公开部分会一同存入数据库。

当这个过程完成后，用户注册成功。

之后，其它 app 或者任何终端上的 app 需要用这个身份时，需要获得授权。



