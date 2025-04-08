# PyFJ

A tool for creating django-ninja projects, based on the following template:
```bash
# A project tempalte for django-ninja
https://github.com/olivetree123/django_ninja_template
```

## 安装

推荐使用pipx安装：
```bash
pipx install pyfj
```

也可以使用pip安装：
```bash
pip install pyfj
```

或者使用poetry:

```bash
poetry add pyfj
```

## 使用方法

安装后，您可以使用以下命令：

### 创建新项目

```bash
# 交互模式
pyfj create

# 直接指定名称
pyfj create --name=myproject
```

### 重命名项目

```bash
# 交互模式
pyfj rename

# 直接指定名称
pyfj rename --name=old_project_name --new_name=new_project_name
```

### 查看帮助

```bash
pyfj --help
pyfj create --help
pyfj rename --help
```

## 功能

1. 创建新项目 - 从Django Ninja模板创建项目
2. 重命名项目 - 将现有项目重命名，包括文件内容和目录名

## 要求

- Python 3.8+
- Git (仅用于创建新项目)

## 开发

```bash
# 克隆仓库
git clone https://github.com/olivetree123/pyfj.git
cd pyfj

# 安装依赖
poetry install

# 以开发模式安装
poetry install -e .

# 或者直接运行测试脚本
python test.py
```
