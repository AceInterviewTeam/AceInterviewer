### 项目概况

基于LLM的智能智能面试系统DEMO


### 环境配置


1. 在环境变量中设置OPENAI_API_KEY

2. 安装依赖

```bash
pip install -r requirements.txt
```

NOTE: MAC M1版本使用一下命令安装依赖

```bash
pip install --no-cache-dir --upgrade --force-reinstall -Iv grpcio gevent

pip install -r requirements.txt
```

### 运行项目

```bash
streamlit run interview_streamlit.py

# 本地启动
http://localhost:8501/

# 远程启动
streamlit run --server.headless true interview_streamlit.py --server.port 8502
```
