Aleo完成2亿美元B轮融资，SoftBank和Kora Management领投，a16z、Tiger Global、Samsung Ventures等参投。

![image](https://github.com/Jermyo/coin/assets/23717512/2ce568ce-9a09-4143-b3b9-6ff654398c5a)


Aleo空投已经确认，有两种方式去获得空投，一是：0撸交互。二就是搭建节点，这个节点的话是最重要的，之前的SOL,TIA,MINA搭建节点的都赚的不少，所以节点有可能会占据大部分空投份额。目前Aleo有几百个节点运行，提前布局有可能你就是早期参与者。

好了，不多说了，直接开始教程！！

1.Leo Wallet（Aleo区块链上的隐私保护钱包）

访问Leo钱包：https://www.leo.app/，将Leo Wallet扩展添加到浏览器，创建一个新钱包，自定义钱包

2：将钱包添加到绿名单中

访问：https://faucetgreenlist.snarkos.net/，复制钱包地址，将地址粘贴到指定字段中以添加到绿名单中

![image](https://github.com/Jermyo/coin/assets/23717512/e916ea8a-1f96-49c5-bdc0-216bcf995ca4)


3. Faucet

访问：https://faucet.aleo.org/，复制钱包地址，使用手机粘贴地址和申请ALEO代币，访问：https://sepoliafaucet.com/，使用邮件登录。粘贴钱包地址和申请ETH。

![image](https://github.com/Jermyo/coin/assets/23717512/4b0abd41-3d32-4645-ad11-6437a8bf6efd)


4. New faucet

打开https://discord.com/invite/cpCrGwfWCs，加入Leo Wallet的discord，访问：https://t.co/F84rSYnI4D，完成验证，填入Aleo地址

5.桥接

访问：https://testnet-bridge.izar.xyz/bridge。连接Aleo钱包，连接MetaMask钱包从Sepolia ETH跨链到ALEO 网络可以停止等待并继续前进

6.AleoSwap Faucet

访问https://app.alphaswap.pro/faucet，连接Aleo钱包，领取ALEO积分，领取USDT，领取WETH。

![image](https://github.com/Jermyo/coin/assets/23717512/c0570ace-6a14-418a-8380-c2089d60a434)


7.AleoSwap

访问：https://app.alphaswap.pro/swap/public，将ALS兑换为USDT，然后，将USDT兑换成WETH，重复几次该过程

8.创建NFT

访问：https://aleo.store/collection/create，连接Aleo钱包，添加图片，填写必填项，继续创建NFT。

![image](https://github.com/Jermyo/coin/assets/23717512/c619c3b4-68ac-49a9-8345-80d7592e0282)


9. Aleo Domain

访问：https://testnet3.aleonames.id/，连接Aleo钱包。用小写字母输入域名，创建域名

![image](https://github.com/Jermyo/coin/assets/23717512/384f0b3b-8789-4718-99a2-234fd2fa4932)


10. Aleo Discord

访问：https://t.co/XF90WdwMb5，进入Discord，积极主动地与他人交往。在社区内获得相关角色

![image](https://github.com/Jermyo/coin/assets/23717512/efe46cd9-07c8-4d23-92ba-4c0138ccfaa6)


二：搭建节点，详细教程

1：第一步需要购买虚拟机：https://www.vultr.com/

2：打开以后注册

![image](https://github.com/Jermyo/coin/assets/23717512/7860e1e2-af18-49ce-8df5-3ba7718b878f)


3：注册完成点击Products

![image](https://github.com/Jermyo/coin/assets/23717512/caf4b9d6-9fb3-4ec0-a6d6-020b712e4cdb)


4：点击部署deploy now

![image](https://github.com/Jermyo/coin/assets/23717512/39171183-51a5-4df2-af71-e5f3d84acd45)


5：Choose Sever：选择Cloud Compute

CPU & Storage Technology：选择AMD

![image](https://github.com/Jermyo/coin/assets/23717512/3d9ea542-ed71-46ec-bba4-16d7bbf81ef1)


6：Sever Location：选择美国一个地方就行

![image](https://github.com/Jermyo/coin/assets/23717512/0cf17c88-bfa3-4827-a87f-ea2c838c22ed)


7：Sever Image：选择ubuntu的20系统

![image](https://github.com/Jermyo/coin/assets/23717512/3f0f0942-c8df-4f7a-8386-a6419ab14fff)


8：Sever Size选择：96美金一个月的

记得关闭备份功能，如下图，点一下on变成off

![image](https://github.com/Jermyo/coin/assets/23717512/be3d70b2-4891-4ce5-b5ef-e36347d884d0)


9：然后点击Deploy Now，付款方式选择最后一个，用支付宝扫码支付10美金。

成功以后，稍等几分钟再点击products，等看到你的服务器显示running时候就可以打开服务器了。

![image](https://github.com/Jermyo/coin/assets/23717512/f165fe5c-204c-4dc5-9011-a1e789ac8f1d)


10：然后点击三个点，打开服务信息

![image](https://github.com/Jermyo/coin/assets/23717512/1f7c4391-1589-45e8-a836-8506af2f8f83)


11：点击进入控制台

![image](https://github.com/Jermyo/coin/assets/23717512/fd8a3ce0-f09f-4f02-a4e6-b7839fc3c544)


12：进入控制台后，输入root用户名登陆，密码在网页里点击复制。然后登陆。

![image](https://github.com/Jermyo/coin/assets/23717512/680ab35d-1b4c-436d-8b20-ca0cd021aa61)


13：登陆成功后输入以下命令：apt install curl

然后输入命令安装rust：curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh

安装完以后，输入代码，利用git克隆这个库：git clone https://github.com/AleoHQ/snarkOS.git --depth 1

进入OS目录：cd snarkOS

运行sh：（等待个10多分钟也许）：./build_ubuntu.sh

最后，安装OS：cargo install --path .

接下来，要启动客户端节点，请从snarkOS目录中运行：./run-client.sh

接下来生成Aleo账户地址：snarkos account new

这将在终端中输出一个新的 Aleo 帐户。

**请记得保存账户私钥和查看密钥。**以下是示例输出：

Attention - Remember to store this account private key and view key.

  Private Key  APrivateKey1xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx  <-- Save Me And Use In The Next Step

     View Key  AViewKey1xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx  <-- Save Me

      Address  aleo1xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx  <-- Save Me

接下来，要启动一个证明节点，从snarkOS目录中运行：./run-prover.sh

出现提示时，输入您的 Aleo 私钥：

Enter the Aleo Prover account private key:

APrivateKey1xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

至此，教程结束，可以关闭服务器窗口，但不要关闭服务器！过大概1-2小时，可以前往官网区块链浏览器输入自己的钱包地址查看有没有爆块得到积分奖励：https://aleo123.io/

如果有就会显示数量，如果没有请重置虚拟机再从头到尾试一次，如果还有什么其他问题，可以点击下面的推特私聊我！

节点的话如果有条件可以搭建下，不想花钱的那就0撸交互，但是根据以往来看，节点搭建会有不错的奖励！！
