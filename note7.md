初始环境按照文档操作

![image](https://github.com/ZPfree/InternLM2_HOMEWORK/assets/16116418/36d4f71e-535b-4676-9f4a-a7585d931c73)

到后面执行
python tools/list_configs.py internlm ceval

各种少包，确定不是环境少包了，安装不提示少包以后


![image](https://github.com/ZPfree/InternLM2_HOMEWORK/assets/16116418/28194a1e-41cb-4648-83c8-45a83789f78d)

最上面的错误是Error: mkl-service + Intel(R) MKL 
于是有下面
export MKL_THREADING_LAYER=GNU

![image](https://github.com/ZPfree/InternLM2_HOMEWORK/assets/16116418/eff04b56-86cc-4c26-be35-945f5c81dab4)

后面就是正常加载数据。

![image](https://github.com/ZPfree/InternLM2_HOMEWORK/assets/16116418/593fa6ac-c22d-499b-a8e1-45231df6fde9)
