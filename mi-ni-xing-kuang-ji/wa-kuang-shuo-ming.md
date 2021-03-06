# 使用说明

## Windows 桌面客户端
### 挖矿步骤

1. 安装驱动：[Starcoin 矿机驱动](https://pan.baidu.com/s/1EBIiYLtSQ_07gY1eneM7Dw)；密码：chyz
2. 安装软件：[Starcoin 挖矿客户端](https://github.com/starcoinorg/starcoin_mini_miner/releases/download/starcoin-mini-miner-v1.0.2/Starcoin.Setup.1.0.2.rar)
3. 将矿机与电脑相连。
4. 更新固件: 软件识别出矿机后，点击更新固件。将 [Starcoin mini 矿机固件](https://github.com/starcoinorg/starcoin_mini_miner/releases/download/v0.0.2/starcoin_mini_miner_recovery_v0.0.2.bin) 下载后上传。

5. 设置矿池：打开 Starcoin Miner 软件，点击设置矿池图标，输入矿池名，端口号，用户名，矿工密码，点击确认。
   * 若要连接到 Starcoin node 进行挖矿。默认请连接至节点的 9880 端口，具体可在 starcoin 启动参数中进行 startum 服务的设置。
   (注:该功能需在  starcoin master 分支或release 版本>=v1.0.0-beta.5上支持)
      ```
       --stratum-port <stratum-port> stratum port is 9880
       --stratum-address <address> Default adress is 0.0.0.0
      ```
   * 设置可乐矿池
   
     1. 下载安装 [bixin](https://bixin.com)。
     2. 依次点击[发现]->[可乐矿池]->[挖矿]。
     3. 点击左上方[总算力]->[创建子账户],填写**账户名**，选择地址。
     4. 设置收款地址。**注:此处需要填写starcoin account 的 public_key,而不是 address**
     5. 配置矿机: 设置账户名为第三步的账户名。设置矿池地址:	 
       ```
        cn-test.stc.kelepool.com:5555
        cn-test.stc.kelepool.com:6666
        cn2-test.stc.kelepool.com:9999
       ```
6. 开始挖矿：点击启动矿机，等待片刻后能够看到有算力生成证明设备已开始工作。
7. 切换矿池：选择机器停止挖矿，设置矿池，开始挖矿。

### 注意事项

* 本手册只适用于挖 Starcoin 币种，测试网及主网均可。不支持其他币种。
* 使用前请尽量避免将矿机放置在空气流通性差和温度过高的环境下运行，否则可能导致工作异常甚至造成设备损坏。
* 使用前请保证网络通畅，否则会造成拒绝率上升影响机器算力。
* 使用时请勿私自超频，否则会导致芯片损坏，后果自负。
* 该客户端软件暂时仅支持 windows 系统, 非 windows 系统用户使用此矿机请参考：[starcoin mint usb solver](https://github.com/fikgol/usbsolver)
* 其余问题请添加 VX：Starcoinorg

