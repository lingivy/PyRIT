# Crescendo


## 🚀 快速开始

### 1\. 环境配置

使用 `environment.yml` 文件来创建并激活 Conda 环境。

```bash
conda env create -f environment.yml
conda activate [your_env_name]
```

### 2\. 配置 API KEY

复制 `.env_example` 文件为 `.env`，然后修改文件内容以配置你的 API KEY。

```bash
# 复制文件
cp .env_example .env
```

接着，编辑新创建的 `.env` 文件：

```dotenv
# .env
KEY="PASTE_YOUR_API_KEY_HERE"
```

### 3\. 运行程序

执行主程序脚本 `crescendo_attack.py`。

```bash
python crescendo_attack.py
```

### 4\. 查看日志

程序运行后，相关的输出日志会自动保存在项目根目录下的 `log/` 文件夹中。
