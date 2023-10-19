# Cloud189Checkin
天翼网盘自动签到（随机容量) 和抽奖（三次，每次50M，共150M）获取空间  
## **目录**
- [GitHub Action运行](#GitHubAction运行)

## GitHub Action运行
### Fork此仓库
![](https://cdn.jsdelivr.net/gh/wes-lin/Cloud189Checkin/image/fork.png)
### 设置账号密码
新版本的git Action 需要创建environment来配合使用，创建一个名为user的环境。
![](https://cdn.jsdelivr.net/gh/wes-lin/Cloud189Checkin/image/env.png)
创建好后编辑user环境，添加两个变量TY_USER_NAME 是你的天翼网盘账号，TY_PASSWORD 是的你密码。现已支持多账户,最多可添加5个账户，第二个账户用户名变量是TY_USER_NAME1，密码变量是TY_PASSWORD1,以此类推，最多到TY_USER_NAME4,TY_PASSWORD4。
![](https://cdn.jsdelivr.net/gh/wes-lin/Cloud189Checkin/image/account.jpg)
### 执行任务
1. 点击**Action**，再点击**I understand my workflows, go ahead and enable them**  
2. 给自己仓库点个start或者修改任意文件后提交一次  
![](http://tu.yaohuo.me/imgs/2020/06/34ca160c972b9927.png)
3. 每天早上10点执行任务

### 查看运行结果
Actions > Cloud check in action > build
![](https://cdn.jsdelivr.net/gh/wes-lin/Cloud189Checkin/image/action.png)

## 更新内容

### 2023-08-14
[支持Telegram推送](https://github.com/wes-lin/Cloud189Checkin/pull/18)
### 2023-06-09
[添加错误重试](https://github.com/wes-lin/Cloud189Checkin/issues/14)
### 2023-06-05
[支持Server酱推送](https://github.com/wes-lin/Cloud189Checkin/issues/8)
### 2023-05-19
[支持多账户](https://github.com/wes-lin/Cloud189Checkin/issues/7)
### 2023-05-15
[更新appConf获取方式](https://github.com/wes-lin/Cloud189Checkin/issues/5)
