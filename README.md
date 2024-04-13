# robot
这个项目是用GPT写的
实现的功能：
调用微信消息转发
可以调用语言模型对消息进行回复
没有实现的功能：
多模态的输入
上下文

先下载并安装ollama
然后再在终端运行pip install --upgrade wcferry 安装WeChatFerry 注意：安装时要确保电脑微信版本必须为3.9.2.23记得取消自动更新
具体请看https://github.com/lich0821/WeChatFerry?tab=readme-ov-file
再运行demo.py
然后到终端运行wcfhttp --cb http://localhost:9998/text （后面的http://localhost:9998/text是消息转发的地址 可以更改）
demo.py中有
from flask import Flask, request
import requests # type: ignore
import json
请自行安装（不是我不负责 是我真的不懂编程，只是一个兴趣）

希望有大佬可以帮助实现未实现的功能
感谢

本开源项目依靠
ollama （网址：https://ollama.com/ 模型下载地址：https://ollama.com/library）
WeChatFerry （开源项目https://github.com/lich0821/WeChatFerry?tab=readme-ov-file）
