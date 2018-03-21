b 认识bash

---

Bash是一种特殊的shell, 所谓shell,是用户使用命令行与系统进行沟通的系统沟通的介质。有了图形界面，为什还要用shell? 

* 大家都一样。不同发行版本的图形界面操作大不相同，单时shell命令都一样。
* 速度快。大多服务器版都没有提供图形界面。原因就是图形界面浪费资源。
* 学习shell,还可以自己编写shell脚本，更自如的管理系统。

shell依据发展者的不同有很多不同的版本，比如：sh(Bourne SHell)、C SHELL、K SHELL、TCSH。当然还有linux使用的版本 Bash (Bourne Again SHell)。

我们可以查看 /etc/shells文件，来了解我们系统可以使用的shell。

```
$ cat /etc/shells
# /etc/shells: valid login shells
/bin/sh
/bin/dash
/bin/bash
/bin/rbash
```

虽然各家的shell都差不多，但是语法表达上还是有所不同。我们重点来学习linux下常用的bash。



 