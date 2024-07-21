# NodePay Multi Account 100% Uptime FREE Python Bot [v2] Bot

This Python Bot script manages WebSocket connections through specified HTTP proxies, Unlimited Proxies and multiple Nodepay Accounts handling authentication and maintaining persistent connections with a server. The script also includes functionality to periodically send ping messages to keep the connection alive forever. If you can run your pc 24/7 then you dont need a Vps or proxy server lol.

## Features

- Connects to a WebSocket server using HTTP proxies.
- Handles Multiple Nodepay User IDs at once !! Multiple Proxies (1 Proxy ~60 $NODEPAY)
- Per Proxy ~1400 ** $NODEPAY per day** Unlimited proxies Make Unlimited Money !
- Handles All kinds of Error such a Dead proxy/ SSL: WRONG_VERSION_NUMBER / sent 1011 (internal error) keepalive ping timeout; no close frame received / 500 Internal Server Error / sent 1011 (internal error) keepalive.
- Automatically removes the dead proxy from the File!!

#Get NP_TOKEN

1. Open the link and log in [https://app.nodepay.ai/dashboard](https://app.nodepay.ai/dashboard)
2. Press F12 on the page to open the console and enter the code (Ctrl + Shift + i) inspect
3. Write `localStorage.getItem('np_token');` in the console
4. "PRINTED TEXT IS THE Np _TOKEN"
5. ![image](https://github.com/Solana0x/nodepay/assets/142747768/bf907faa-0e56-4935-a5dc-da95f612fa07)

#Get USer_Id (NOT NEEDED IN NEW CODE) 

1. Press F12 on the page to open the console and enter the code (Ctrl + Shift + i) inspect
2. Go To Networks Tab in the Inspect
3. Search for the Devices then check the response
4. You will Get the User-id there
5. ![image](https://github.com/Solana0x/nodepay/assets/142747768/d9b07511-0554-4330-8d7c-81395b92c25b)

#Get Proxies IP address HTTP

1. Create a Account in  [https://www.webshare.io/?referral_code=gppl5h10bwn5](https://www.webshare.io/?referral_code=gppl5h10bwn5)
2. For webshare plan are 1000 Proxy for 1 Month !! hence total earning is => 43,200,000 $NODEPAY Points
3. ![image](https://github.com/Solana0x/nodepay/assets/142747768/82eb59b5-9f74-4d14-96b0-c35bb1e8925e)
4. You Got 1000 Ips now => Earning == ~1,440,000 Tokens per day and distribute Ips across multiple accounts / User ID !! You get 250GB bandwidth so create 20-30 Nodepay accounts to get 25-30M nodepay points per day
5. USe only webshare to Buy proxy because as of now only webshare website opened port for nodepay ! other proxy sellers i dont know !

## Requirements

- Invitation link Nodepay Accounts ( [https://app.nodepay.ai/register?ref=PGiwMlh6dQJVmxE](https://app.nodepay.ai/register?ref=PGiwMlh6dQJVmxE) )
- Python (install Python By - https://www.python.org/downloads/ [windows/mac]) or Ubuntu Server [`sudo apt install python3`]
- VPS Server ! You can get Via AWS free Tier or Google Free tier or Gitpod or any online for just ~ 2-5$ per month
- Proxy Server - you can buy DataCenter Proxies to Earn $NODEPAY Some Free Cheap proxies (Best proxy providers is webshare)
- Get NP_token andcUser ID from Nodepay Dashboard

## SETPS TO RUN THE CODE -

Before running the script, ensure you have Python installed on your machine. Then, install the necessary Python packages using:

1. ``` git clone https://github.com/Solana0x/nodepay.git ```
2. ``` cd nodepay ```
3. ``` pip install -r requirements.txt ```
4. Replace `NP TOken` list in correct formate in `node.py` File Line ```9```.
5. By default 100 proxies will be taken randomly if you wana change then change here `active_proxies = [proxy for proxy in all_proxies[:100] if is_valid_proxy(proxy)]` line 169. Here 100 means 100 proxy will be used at once.
6. Dont Forget to add multiple proxies in the proxy.txt file you can add 1000+ proxy !! Formate # `HTTP://username:pass@ip:port`.
7. You can get Multiple Proxy Ip address from Proxies.fo Website !! [use multiple IP ! `1 IP == ~1400 $NODEPAY per Day `.
8. To Run Script `python3 node.py` - Proxy one
10. To Run multiple User ID just copy paste the `node.py` file code and create new python file and repeat the process !!. 

**Note** - 1 ip == 1000-1400 $Nodepay Per Day.

![image](https://github.com/Solana0x/nodepay/assets/142747768/cbfd5d20-6d30-494c-9af1-34c2415d27d1)

## FOR ANY KIND OF HELP CONTACT : ` 0xphatom ` on Discord  https://discord.com/users/979641024215416842




# NodePay 多账户 100% 在线免费 Python 机器人 [v1]

此 Python 机器人脚本通过指定的 HTTP 代理管理 WebSocket 连接，支持无限代理和多个 Nodepay 账户，处理身份验证并保持与服务器的持久连接。脚本还包括定期发送 ping 消息以保持连接永久在线的功能。如果你可以全天候运行电脑，就不需要 VPS 或代理服务器。

## 功能

- 使用 HTTP 代理连接到 WebSocket 服务器。
- 同时处理多个 Nodepay 用户 ID！多个代理 (1 代理 ~60 $NODEPAY)。
- 每个代理每天约 1400 $NODEPAY，无限代理无限赚钱！
- 处理各种错误，如死代理/SSL: WRONG_VERSION_NUMBER/发送 1011（内部错误）保持连接 ping 超时；未收到关闭帧/500 内部服务器错误/发送 1011（内部错误）保持连接。
- 自动从文件中删除死代理！

#获取 NP_TOKEN

1. 打开链接并登录 [https://app.nodepay.ai/dashboard](https://app.nodepay.ai/dashboard)
2. 在页面上按 F12 打开控制台并输入代码（Ctrl + Shift + i）检查
3. 在控制台中输入 `localStorage.getItem('np_token');`
4. "打印的文本是 NP_TOKEN"
5. ![image](https://github.com/Solana0x/nodepay/assets/142747768/bf907faa-0e56-4935-a5dc-da95f612fa07)

#获取用户 ID （新代码中不需要）

1. 在页面上按 F12 打开控制台并输入代码（Ctrl + Shift + i）检查
2. 转到检查中的网络标签
3. 搜索设备然后检查响应
4. 你会在那里得到用户 ID
5. ![image](https://github.com/Solana0x/nodepay/assets/142747768/d9b07511-0554-4330-8d7c-81395b92c25b)

#获取代理 IP 地址 HTTP

1. 创建一个账户在 [https://www.webshare.io/?referral_code=gppl5h10bwn5](https://www.webshare.io/?referral_code=gppl5h10bwn5)
2. 对于 webshare 计划，每月 1000 个代理！！因此总收入为 => 43,200,000 $NODEPAY 点数
3. ![image](https://github.com/Solana0x/nodepay/assets/142747768/82eb59b5-9f74-4d14-96b0-c35bb1e8925e)
4. 你现在有了 1000 个 IP => 收入 == 每天约 1,440,000 代币，并在多个账户/用户 ID 中分配 IP！你有 250GB 带宽，因此可以创建 20-30 个 Nodepay 账户，每天获得 25-30M nodepay 点数
5. 只使用 webshare 购买代理，因为目前只有 webshare 网站为 nodepay 打开端口！其他代理卖家我不知道！

## 要求

- 邀请链接 Nodepay 账户 ( [https://app.nodepay.ai/register?ref=PGiwMlh6dQJVmxE](https://app.nodepay.ai/register?ref=PGiwMlh6dQJVmxE) )
- Python (通过 https://www.python.org/downloads/ [windows/mac] 安装 Python) 或 Ubuntu 服务器 [`sudo apt install python3`]
- VPS 服务器！你可以通过 AWS 免费套餐或 Google 免费套餐或 Gitpod 或任何在线获得，只需每月约 2-5 美元
- 代理服务器 - 你可以购买数据中心代理来赚取 $NODEPAY 一些免费便宜的代理（最佳代理提供商是）
- 从 Nodepay 仪表板获取 NP_token 和用户 ID

## 运行代码的步骤 -

在运行脚本之前，确保你的计算机上已安装 Python。然后，使用以下命令安装必要的 Python 包：

1. ``` git clone https://github.com/Solana0x/nodepay.git ```
2. ``` cd nodepay ```
3. ``` pip install -r requirements.txt ```
4. 在“node.py”文件行“``9```中以正确的格式替换“NP TOken”列表。
5. 默认情况下，如果您想更改，将随机获取 100 个代理，然后在此处更改 `active_proxies = [proxy for proxy in all_proxies[:100] if is_valid_proxy(proxy)]` 第 169 行。这里 100 表示将同时使用 100 个代理。
6. 不要忘记在 proxy.txt 文件中添加多个代理，你可以添加 1000+ 个代理！格式 # `HTTP://username:pass@ip:port`。
7. 你可以从 Proxies.fo 网站获取多个代理 IP 地址！！[使用多个 IP！`1 IP == 每天约 1400 $NODEPAY`。WEBSHARE
8. 运行脚本 `python3 node.py` - 代理一个
9. 要运行多个用户 ID，只需复制粘贴 `node.py` 文件代码并创建新 Python 文件并重复该过程！！

**注意** - 1 个 IP == 每天 1000-1400 $Nodepay。

![image](https://github.com/Solana0x/nodepay/assets/142747768/52323bc5-a151-44de-8038-f79b970736b5)

## 任何帮助请联系：` 0xphatom ` 在 Discord 上 https://discord.com/users/979641024215416842

