# chatgpt-demo

代码出自极客时间课程 [AI 大模型之美](https://time.geekbang.org/column/intro/100541001?tab=catalog)

本 repo 只用于学习用途。

# 环境准备

```

conda create --name py310 python=3.10
conda activate py310
conda install -c conda-forge jupyterlab
conda install -c conda-forge ipywidgets
conda install -c conda-forge openai
conda install -c conda-forge matplotlib
conda install -c conda-forge plotly
conda install -c conda-forge scipy
conda install -c conda-forge scikit-learn

export OPENAI_API_KEY=在这里写你获取到的ApiKey
make run-jupyter-lab

# 还有很多依赖，在后面的课程中逐步安装上
# 10.ipynb 和 11.ipynb 针对 llama_index==v0.6.1 版本做了改造

```

# 部分数据引用

https://github.com/openai/openai-cookbook

课程官方 repo

https://github.com/xuwenhao/geektime-ai-course
