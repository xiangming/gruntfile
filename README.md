# gruntfile

包含gruntfile等用于项目初始化的文件。
+ **.csscomb.json**：csscomb配置
+ **.gitignore**：git不应track的文件和目录列表
+ **gruntfile.js**：grunt配置
+ **package.json**：npm依赖管理


```bash
bower install gruntfile

# 复制repo里面的 **gruntfile.js**、**package.json**、**bower.json**到项目根目录。
# 根据具体项目需求，修改 **gruntfile.js**、**package.json**、**bower.json**。

## 手动安装或者使用bower_component/gruntfile/里面的bower.json
bower install

# 安装grunt的依赖包
npm install

grunt init
# 自动复制 **.csscomb.json** 到 `less/`。
# 自动复制 **.gitignore** 到根目录。
# 自动复制fonts/
# 自动watch
```

