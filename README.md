# gruntfile

包含gruntfile等用于项目初始化的文件。
+ **.csscomb.json**：csscomb配置
+ **.gitignore**：git不应track的文件和目录列表
+ **gruntfile.js**：grunt配置
+ **package.json**：npm依赖管理


```bash
bower install gruntfile
bower install jquery#1.11.1
bower install bootstrap
bower install font-awesome#4.2
bower install ...

# 复制repo里面的 **gruntfile.js**、**package.json**到项目根目录。
# 根据具体项目需求，修改 **gruntfile.js**、**package.json**。

# 安装grunt的依赖包
npm install

grunt init
# 自动复制 **.csscomb.json** 到 `less/`。
# 自动复制 **.gitignore** 到根目录。
# 自动复制fonts/
# 自动watch
```

