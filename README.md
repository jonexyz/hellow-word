# hellow-word
我的第一个Composer/Packagist包编写学习

入PHP也不算太久，但是总感觉编码水平一直都是搬运工水平。

戏称curdBoy都不为奇。

这是一个学习示例。

参照教程 https://www.cnblogs.com/zhangtianle/p/7687054.html


composer require jonexyz/hellow:dev-master




```
require_once './vendor/autoload.php';

use Hello\SayHellow;

echo Hello\SayHellow::world();
```
