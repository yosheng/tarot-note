# 介绍

使用 sphinx 搭建的塔罗牌学习笔记


## 本地开发环境配置

请确认事先安装好 Python 环境 (建议使用 3.x 版本)

使用管理员打打开 cmd 安装相关依赖如下

```sh
pip install sphinx
pip install myst-parser
pip install sphinx_rtd_theme
```

推荐使用 VS Code 进行编辑

安装插件 reStructuredText 默认会自动带上相关依赖，同意即可


修改完成本地输入下列命令可以编译查看

```
make html
```

