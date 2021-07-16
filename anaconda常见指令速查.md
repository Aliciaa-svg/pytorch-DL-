- **列出已创建的环境**

  ```python
  conda env list
  ```

  ![Screen Shot 2021-07-16 at 10.25.15 AM](/Users/zhao/Desktop/Screen Shot 2021-07-16 at 10.25.15 AM.png)(<u>注意安装路径</u>)

  

- **创建新环境**

  ```python
  conda create -n env1 python=3.7（指定python版本,也可不指定）
  ```

- **删除某环境**（假设该环境被命名为env1）

  ```python
  conda remove --name env1 --all
  ```

  

- **切换到某个环境**（假设该环境叫env1）

  ```python
  source/conda activate env1
  ```

  (mac和linux用source命令激活，win可直接用activate env1命令激活)

- **退出当前环境**

  ```python
  source/conda deactivate
  ```

  (相当于退出env1，回到base，如果想要接着退出base，继续执行conda deactivate命令即可)

