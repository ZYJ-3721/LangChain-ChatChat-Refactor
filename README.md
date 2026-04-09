# LangChain-ChatChat-Refactor
原项目：https://github.com/chatchat-space/Langchain-Chatchat

- [x] 学习 poetry 项目管理
- [x] 梳理 settings 复杂配置
- [  ] 优化 webui 界面操作
- [  ] 重构 server 项目框架

## 环境搭建
```bash
conda create -n lc python=3.11
```

```bash
conda activate lc
```

```bash
pip install -e .
```

## 项目启动
```bash
python chatchat/settings/settings.py
```

```bash
python chatchat/server/api.py
```

```bash
streamlit run chatchat/web/webui.py
```
