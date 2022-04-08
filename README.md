# Covid-19VisualizationBackend

疫情可视化后端

[FastAPI](https://fastapi.tiangolo.com/zh/) + [uvicorn](https://www.uvicorn.org/)

> [Vue3 + vite + Ts + pinia + 实战 + 源码 +全栈_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV1dS4y1y7vd?p=51&spm_id_from=333.1007.top_right_bar_window_history.content.click)

---

## 部署说明

- `clone` 本项目

  ```git
  git clone https://github.com/Ayusummer/Covid-19VisualizationBackend.git
  ```

配置 python 环境, 可以选择 virtualenv 或者 conda 进行环境配置

### 1.使用 virtualenv 配置环境

- `clone` 完项目后首先创建虚拟环境并激活虚拟环境

  ```shell
  # 安装 virtualenv
  pip install virtualenv

  # 使用 virtualenv 创建虚拟环境
  virtualenv -p python3 env

  # 激活虚拟环境(Windows)
  .\env\Scripts\activate
  ```

  > 使用 Pipenv 或者其他工具(如 Pycharm)创建 python 环境亦可

- 执行 `pip 命令` 安装依赖

  ```bash
  pip install -r config/requirements.txt
  ```

  > 使用 `conda` 或者使用国内镜像需要注意执行 `pip 命令` 时关掉 `vpn`
