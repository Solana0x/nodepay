# NodePay Multi Account 100% Uptime FREE Python Bot [v1] Bot

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

#Get USer_Id

1. Press F12 on the page to open the console and enter the code (Ctrl + Shift + i) inspect
2. Go To Networks Tab in the Inspect
3. Search for the Devices then check the response
4. You will Get the User-id there
5. ![image](https://github.com/Solana0x/nodepay/assets/142747768/d9b07511-0554-4330-8d7c-81395b92c25b)

#Get Proxies IP address HTTP

1. Create a Account in [https://app.proxies.fo/ref/662f6ec9716d5c33a8b89d14](https://app.proxies.fo/ref/662f6ec9716d5c33a8b89d14) or [https://www.webshare.io/?referral_code=gppl5h10bwn5](https://www.webshare.io/?referral_code=gppl5h10bwn5)
2. For webshare plan are 1000 Proxy for 1 Month !! hence total earning is => 43,200,000 $NODEPAY Points
3. ![image](https://github.com/Solana0x/nodepay/assets/142747768/82eb59b5-9f74-4d14-96b0-c35bb1e8925e)
4. Go To https://app.proxies.fo/plans and buy the below plan
5. 3. ![image](https://github.com/Solana0x/getgrass/assets/142747768/3512c651-0f7a-416a-b783-34d2e28bbcee)
6. **Best** - You can use Crypto and Binance to Pay here !!!
7. Now go to DashBoard and `click Go to Generator` button
8. Now change the Proxy formate to ` USER:PASS@HOST:PORT ` and use ` HTTP` in proxy count write 200 or any number.
9. Now Click on Save to generate.
10. ![image](https://github.com/Solana0x/nodepay/assets/142747768/679797fd-bc9f-4671-bc58-5d283a05adc7)
11. You Got 200 Ips now => Earning == ~220k Tokens per day and distribute Ips across multiple accounts / User ID !!

## Requirements

- Invitation link Nodepay Accounts ( [https://app.nodepay.ai/register?ref=PGiwMlh6dQJVmxE](https://app.nodepay.ai/register?ref=PGiwMlh6dQJVmxE) )
- Python (install Python By - https://www.python.org/downloads/ [windows/mac]) or Ubuntu Server [`sudo apt install python3`]
- VPS Server ! You can get Via AWS free Tier or Google Free tier or Gitpod or any online for just ~ 2-5$ per month
- Proxy Server - you can buy DataCenter Proxies to Earn $NODEPAY Some Free Cheap proxies (Best proxy providers are)
- Proxies.fo -  [https://app.proxies.fo/ref/662f6ec9716d5c33a8b89d14](https://app.proxies.fo/ref/662f6ec9716d5c33a8b89d14) [Buy Only 1GB Plan Enough for 1-6 months and you get Unlimited Accounts or proxies]
- Get NP_token andcUser ID from Nodepay Dashboard

## SETPS TO RUN THE CODE -

Before running the script, ensure you have Python installed on your machine. Then, install the necessary Python packages using:

1. ``` git clone https://github.com/Solana0x/nodepay.git ```
2. ``` cd nodepay ```
3. ``` pip install -r requirements.txt ```
4. Replace `NP TOken`, `User ID` and `Proxy server file location` list in correct formate in `node.py` File Line ```12 , 49 and 40```.
5. By default 50 proxies will be taken randomly if you wana change then change here `active_proxies = [proxy for proxy in all_proxies[:50] if is_valid_proxy(proxy)]` line 143. Here 50 means 50 proxy will be used at once.
6. Dont Forget to add multiple proxies in the proxy.txt file you can add 1000+ proxy !! Formate # `HTTP://username:pass@ip:port`.
7. You can get Multiple Proxy Ip address from Proxies.fo Website !! [use multiple IP ! `1 IP == ~1400 $NODEPAY per Day `.
8. To Run Script `python3 node.py` - Proxy one
10. To Run multiple User ID just copy paste the `node.py` file code and create new python file and repeat the process !!. 

**Note** - 1 ip == 1000-1400 $Nodepay Per Day.

![image](https://github.com/Solana0x/nodepay/assets/142747768/65143054-80b5-4785-b5cf-4e5333b02b70)

## FOR ANY KIND OF HELP CONTACT : ` 0xphatom ` on Discord  https://discord.com/users/979641024215416842
