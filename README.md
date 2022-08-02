# thinkphp5.0 数据库迁移工具

## 安装
~~~
composer require carolsail/think-migration dev-master
~~~

## 修复implode()函数报错问题
~~~
/think-migration/phinx/src/Phinx/Util/Util.php  ->  implode('_', $arr)
~~~