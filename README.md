# Attention

为了更好地研究LLM推理的因果关系，我在`https://github.com/mattneary/attention`的基础上
 - 适配了更多的大模型
 - 加入了模型不同layer，不同head的attention

## How to Run
```sh
$ poetry install
$ python main.py
在服务器上部署代码后运行，一般来说会转发到本地的5000端口
```
 - 首先在main中输入prompt（鉴于转义字符，没有在前端写输入框）
 - 打开本地浏览器，访问 `http://127.0.0.1:5000/static/index.html`
 - 输入模型的绝对路径，点击submit
 - 等待片刻即可
