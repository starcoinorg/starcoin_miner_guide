# 使用说明

## Windows 桌面客户端
### 挖矿步骤

1. 安装驱动：[Starcoin矿机驱动](https://pan.baidu.com/s/1EBIiYLtSQ_07gY1eneM7Dw)；密码：chyz
2. 安装软件：[Starcoin挖矿客户端](https://pan.baidu.com/s/1x5sgl4mb2qtHYJDxK_RFCg)；密码：e4fj

3. 将矿机与电脑相连。

4. 设置矿池：打开 Starcoin Miner 软件，点击设置矿池图标，输入矿池名，端口号，用户名，矿工密码，点击确认。
   * 若要连接到 Starcoin node 进行挖矿。默认请连接至节点的 9880 端口，具体可在 starcoin 启动参数中进行 startum 服务的设置。
     ```bash
      --stratum-port <stratum-port> stratum port is 9880
      --stratum-address <address> Default adress is 0.0.0.0
     ```
5. 开始挖矿：点击启动矿机，等待片刻后能够看到有算力生成证明设备已开始工作。
6. 切换矿池：选择机器停止挖矿，设置矿池，开始挖矿。

### 注意事项

* 本手册只适用于挖 Starcoin 币种，测试网及主网均可。不支持其他币种。
* 使用前请尽量避免将矿机放置在空气流通性差和温度过高的环境下运行，否则可能导致工作异常甚至造成设备损坏。
* 使用前请保证网络通畅，否则会造成拒绝率上升影响机器算力。
* 使用时请勿私自超频，否则会导致芯片损坏，后果自负。
* 该客户端软件暂时仅支持 windows 系统, 非 windows 系统用户使用此矿机请参考：[starcoin mint usb solver](https://github.com/fikgol/usbsolver)
* 其余问题请添加 VX：Starcoinorg

