# 1，安装GO

# 2、安装go-ethereum

# 3、配置init.json


{
"config": {
        "chainId": 15,
        "homesteadBlock": 0,
        "eip155Block": 0,
        "eip158Block": 0
    },
"nonce": "0x0000000000000042",
"mixhash": "0x0000000000000000000000000000000000000000000000000000000000000000",
"difficulty": "0x400",
"alloc": {},
"coinbase": "0x3333333333333333333333333333333333333333",
"timestamp": "0x0",
"parentHash": "0x0000000000000000000000000000000000000000000000000000000000000000",
"extraData": "0x00",
"gasLimit": "0x8000000"
}
# 4
./geth --identity "TestNode" --rpc --rpcport "8545" --datadir ./blockchaindata --port "30303" --nodiscover console init init.json

--remmcond
geth --identity"TestNode"  --rpc  --rpcport "8545"  --port "30303"  --rpcapi "db,eth,net,web3,personal,admin,miner" console init genesis.json


centos

# 5.> personal.newAccount()
cnepay
cnepay
0x7952967025cea7d28e1cf78b0f1f33f4780013a4


UBUNTU:

> personal.newAccount()
Passphrase:
Repeat passphrase:
"0xeb697d0462f38e09ed6d6c06e93616fceb622967"


# 6、install cmake
https://bitshuo.com/topic/5833e6a58bf98a143753b85f

 
 

[root@localhost bin]#

 
0x7952967025cea7d28e1cf78b0f1f33f4780013a4
0x74a9cadcdded583cb3bf1ffb144b3d6c8052dda2   

# 8、命令

查账户列表

personal.listAccounts

查余额

web3.fromWei(eth.getBalance(eth.coinbase), "ether")

解锁账户

personal.unlockAccount("0x7952967025cea7d28e1cf78b0f1f33f4780013a4", "cnepay", 900)

发送交易

eth.sendTransaction({from: '0x7952967025cea7d28e1cf78b0f1f33f4780013a4', to: '0x74a9cadcdded583cb3bf1ffb144b3d6c8052dda2 ', value: web3.toWei(1, "ether")})

查询第二个账户
web3.fromWei(eth.getBalance(eth.accounts[1]),"ether")

 
账户操作

eth.accounts //查看账户

personal.listAccounts //查看账户

personal.newAccount("***")  //新建账户

personal.unlockAccount("**********")  //解锁账户

personal.lockAccount("**********")    //锁定账户


代币操作
eth.getBalance()   //查看余额

web3.fromWei()   //单位换算


节点操作 net模块

net.listening             //查看节点状态 

net.peerCount             // 查看节点链接的数量

admin模块

admin.nodeInfo          //查看节点信息

admin.addPeer()           //添加节点

admin.peers             //查看添加的节点的信息


一些设置命令

miner.setEtherbase(eth.accounts[n]) //etherbase地址并不需要一定是本机上

miner.setExtra("zhou")    //写一些额外信息

eth.getBlock(n)  //查看区块信息

mac  下安装ethereum 

1、brew  tap ethereal/ethereum 

2    brew install ethereal

3 打开终端，执行以下命令，以开发方式启动geth   

geth --datadir “~/ethdev” —dev

miner.setEtherbase("0x67b5c695e4c1c1ec3287585a41b9dd68e0ca0738")



# remix 安装：


git clone https://github.com/ethereum/remix-ide.git
cd remix-ide
npm install
启动：
npm run build && npm run serve


链接
geth attach                   # connect over IPC on default endpoint
geth attach ipc:/some/path    # connect over IPC on custom endpoint
geth attach http://host:8545  # connect over HTTP
geth attach ws://host:8546    # connect over websocket


ubuntu Mist链接私有geth

./ethereumwallet --rpc http://localhost:8545




 
