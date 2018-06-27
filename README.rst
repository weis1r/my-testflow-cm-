如何下载工程？通过命令行进行如下操作

git clone https://github.com/weis1r/my-testflow-cm-.git

pip install -e my-testflow


标准化自动化工程---- 简单介绍下，各个目录的作用

.. code-block:: text

    ─ my_testflow/
        ├─ cmtest/            <-------   此文件是一个标识符，标记我们测试项目
        |   ├─ __init__.py
        |   ├─ lib/           <-------   此文件是一个公共目录，存放一些库代码，也可以自己添加一些代码
        |   |   ├─ __init__.py
        |   |   ├─ case.py
        |   |   └─ player.py
        |   └─ scripts/       <-------   此文件存放一些游戏自动化的脚本
        |       ├─ __init__.py
        |       ├─ test1.py
        |       └─ folder/
        |           ├─ __init__.py
        |           └─ test2.py
        ├─ res/               <-------   此文件存放一些资源目录，其实没啥用，可以不用管
        |   └─ ...
        ├─ pocounit-results/  <-------   此文件存放报告的一些结果
        ├─ setup.py
        ├─ requirements.txt
        └─ .gitignore
    
    
   
