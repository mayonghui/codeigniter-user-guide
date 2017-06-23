################
创建驱动器
################

驱动器目录及文件结构
===================================

下面是驱动器目录和文件结构布局的简单例子:

-  /application/libraries/Driver_name

   -  Driver_name.php
   -  drivers

      -  Driver_name_subclass_1.php
      -  Driver_name_subclass_2.php
      -  Driver_name_subclass_3.php

.. note:: 为了在大小写敏感的文件系统下保证兼容性，Driver_name 目录必须以
	``ucfirst()`` 函数返回的结果格式进行命名。

.. note:: 由于驱动器的架构是子驱动器并不继承主驱动器，因此在子驱动器里
	无法访问主驱动器中的属性或方法。
