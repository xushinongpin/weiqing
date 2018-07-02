开启debug

```
$config['setting']['development'] = 0;
把0改为1
```

模拟 http 请求

```
ihttp_request($url, $post = '', $extra = array(), $timeout = 60)
官方：http://s.we7.cc/index.php?c=wiki&do=view&id=1&list=247
文件路径：\framework\function\communication.func.php
```

创建一个URL

```
url($segment, $params = array(), $noredirect = false)
官方：http://s.we7.cc/index.php?c=wiki&do=view&id=1&list=162
文件路径：\web\common\common.func.php
```

module\_entries

```
\framework\model\module.mod.php
```



utility/bindcall

```
\web\source\utility\bindcall.ctrl.php
```



