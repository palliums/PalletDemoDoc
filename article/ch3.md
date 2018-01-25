## Pallet 03

本段将进行Pallet的Demo情境操作解说：

##### 将Jury注册至Attorney

![](./img/notary_list.png)

##### 创建合约(Demo1)
![](./img/create_contract1.png)

##### 产生多签地址以及合约对应的区块链交易. 部属合约使用者使用私钥签署合约
![](./img/create_contract1_1.png)

##### 合约部属成功
![](./img/create_contract1_2.png)

##### 合约功能解说
本合约的功能很简单，使用者可以设定两个可以接收合约裡面押金的地址，透过合约的参数呼叫可以将押金分给给这两个地址
* set_address [A] [B]
* A [amount]
* B [amount]

##### set_address [A] [B] - 准备
![](./img/create_contract1_3.png)

##### set_address [A] [B] - 产生结果(Attorney side)
![](./img/create_contract1_4.png)

##### set_address [A] [B] - 产生结果(Jury 完成确认)
![](./img/create_contract1_5.png)

##### 检查A address拥有的Utxo [情境解释与合约执行无关]
![](./img/create_contract1_6.png)

##### 设定转钱给A 1000聪 - 准备
![](./img/create_contract1_7.png)

##### 设定转钱给A 1000聪 - 产生结果(Attorney side)
![](./img/create_contract1_8.png)

##### 设定转钱给A 1000聪 - 产生结果(Jury 完成确认)
![](./img/create_contract1_9.png)

##### 检查A address拥有的Utxo [情境解释与合约执行无关]
* address 获得合约所转的1000聪的Utxo

![](./img/create_contract1_10.png)
