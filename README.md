# YunHuBotSDK

基于Python编写的开源云湖机器人SDK，正在持续更新中

## 使用
由于SDK为单文件(懒得分了)，所有可以直接clone仓库
```bash
git clone https://gitcode.com/ZhaoCongshan-6884/YunHuBotSDK.git
```
然后在您的机器人文件中使用
```python
from sdk import BOT
```
实例化机器人
```python
bot = BOT(token="xxxxx")
```
当然您也可以使用Pip安装(目前尚未编写完毕，故没有推送)
```bash
pip install yh_sdk
```
然后以同样的方式引用并实例化即可。

更多内容请访问文档:[开发中](https://yhsdk.readthedocs.io)