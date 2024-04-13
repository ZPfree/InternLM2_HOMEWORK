直接复制internlm2_1_8b_qlora_alpaca_e3 的配置 ，这个dataset_map_fn=openai_map_fn,也没有改到，然后发现字段映射不对，比如

![image](https://github.com/ZPfree/InternLM2_HOMEWORK/assets/16116418/07209aa6-c4fe-4168-961d-cca4c6f2346d)


我用默认的default_map_fn 改成
![image](https://github.com/ZPfree/InternLM2_HOMEWORK/assets/16116418/22a0990b-7301-48a0-a2d8-29de8b75da63)

哈哈，果然不行的，这种其实还不如直接直接去看它需要的格式，自己处理就好。瞎了。最后换成openai 格式处理。
训练中

![image](https://github.com/ZPfree/InternLM2_HOMEWORK/assets/16116418/c6cce541-a9ab-46d2-af13-636a585d3afd)


小结 没有改动什么 只需要对应权重地址 和数据处理格式符合要求即可。

