# myvim
- 将本地vim修改更新到仓库
```bash
./update update
```

- 将仓库中的vim配置安装到本地
```bash
./update install
```

# vim使用
- cscope
1. 在工程目录下运行

>用于函数定义、调用以及符号搜索等查找

`cscope -Rbkq`
生成对应cscope索引文件
2. 打开vim
"；" + "f" + "a": 打开所有搜索

- ctrlp
>用于根据文件名查找文件
1. 打开工程目录，按下f7，出现文件搜索列表
2. ctrl + d切换搜索路径名或者搜索文件名
3. enter选择查找文件

- nertdtree
>用于目录管理
1. ";" + "lf": 打开当前路径下目录
2. 选择文件后，回车覆盖打开文件，s和i分别时垂直和水平分割打开新文件

...

