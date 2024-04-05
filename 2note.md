部署 InternLM2-Chat-1.8B 模型进行智能对话
部署实战营优秀作品 八戒-Chat-1.8B 模型
通过 InternLM2-Chat-7B 运行 Lagent 智能体 Demo
实践部署 浦语·灵笔2 模型
和第一期差不多课程 换了个小的模型，要单独申请，就懒的申请了。

基础作业步骤
studio-conda -o internlm-base -t demo

conda activate demo


pip install huggingface-hub==0.17.3
pip install transformers==4.34 
pip install psutil==5.9.8
pip install accelerate==0.24.1
pip install streamlit==1.32.2 
pip install matplotlib==3.8.3 
pip install modelscope==1.9.5
pip install sentencepiece==0.1.99
InternLM2-Chat-1.8B 模型 在ahare 里 所以没有下载 
双击打开 /root/demo/cli_demo.py 文件 按照文档结束。
