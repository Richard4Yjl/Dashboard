## 商家管理系统

|ID  |用例名  |重要度|代价(天)|简述                               |注释                    |
|:--:|:-----:|:---:|:-----:|:---------------------------------:|:---------------------:|
|1   |注册账号|90  |2      |商家通过管理系统，输入要求信息进行账号注册|输入信息要合法，账号不能重复|
|2   |登陆商家账号|90|2|商家注册账号后，输入要求信息进行登陆|输入信息要合法|
|3   |注销商家账号|90|2|商家登陆后，点击注销按钮退出登陆|无|
|4   |管理订单|100|4|商家登陆后，可以接收和处理订单，并查看历史订单|无|
|5   |管理餐台|90|4|商家登陆后，可以管理餐台，增加删除餐台|重要子用例为增加座位|
|6   |增加座位|70|3|商家管理餐台中，可以增加餐台，为其生成对应的二维码|餐台号不能重复，增加一个餐台要为其生成二维码|

## 顾客小程序

|ID  |用例名       |重要度|代价(天)|简述                               |注释                    |
|:--:|:----------:|:---:|:-----:|:---------------------------------:|:---------------------:|
|1   |扫码进入主程序|90   |2      |用户利用微信端扫一扫进入小程序主界面     |无|
|2   |点餐放入购物车|90   |4      |用户点击菜品加入购物车                 |无|
|3   |创建并支付订单|100  |5      |用户进入购物车下订单并支付订单          |无|