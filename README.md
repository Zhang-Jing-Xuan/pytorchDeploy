## pytorch_deploy
### 通过Flask将深度学习项目部署到网页

### 使用方法（Mac）
* ssh -L 5000:127.0.0.1:5000 username@remote_server_ip -p 端口号（eg. ssh -L 5000:127.0.0.1:5000 mist@gpu180.mistgpu.xyz -p 10000）
* python main.py
* 浏览器上输入 127.0.0.1:5000 回车
