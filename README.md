./data              公钥和私钥存储的文件夹
./lib/account.py    管理账户的类（一个节点可以有多个账户）
./lib/chain.py      管理区块链的类（每个节点维护自己的类，并同步）
./lib/crypto.py     进行加密、散列、验证，计算节点地址的一些方法
./lib/network.py    维护网络数据，包括网络通信和节点的维护
./main.py           主函数，用户入口