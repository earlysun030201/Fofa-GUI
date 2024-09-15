# Pre-Release
|已完成✅|正在做的▶️|计划📌|
|-----|-----|-----|
|HTTP Lua API|Menu Lua API|Lua市场|
|Socket Lua API|Proxy Lua API||
|JSON Lua API|Poc管理器||
|YAML Lua API|Database Lua API||
|Lua5.4支持|Scan Lua API|
|WebSocket Lua API||
|Event Lua API||

## Lua API
https://earlysun.gitbook.io/kanade-lua-api

# Fofa-GUI
来自Kanade-Project的第一个组件，通过Tauri构建的跨平台Fofa图形化工具。

## 此仓库仅分发二进制程序，不发布源码。
## 如何使用？

#### 应用已损坏(MacOS)

应用没有签名导致，终端运行以下命令再次打开即可。
`xattr -cr /Applications/Kanade-FOFA.app`

#### 在设置中填入FOFA API Key即可使用
所有的设置项是自动保存在系统中的。
<img width="1476" alt="image" src="https://github.com/earlysun030201/Fofa-GUI/blob/main/images/iShot_2024-09-02_18.19.05.png">

<img width="1476" alt="image" src="https://github.com/earlysun030201/Fofa-GUI/blob/main/images/iShot_2024-09-02_18.19.32.png">

<img width="1476" alt="image" src="https://github.com/earlysun030201/Fofa-GUI/blob/main/images/iShot_2024-09-02_18.20.54.png">

<img width="1476" alt="image" src="https://github.com/earlysun030201/Fofa-GUI/blob/main/images/iShot_2024-09-02_18.21.28.png">


#### 查询字段

即返回结果中显示的字段内容。
所有API支持字段均开放选择。

#### 结果去重

根据ip-port进行结果重复项筛选并去除。

#### 静默存活检测

多线程扫描器，在结果返回并处理后进行ip-port扫描，目前仅支持ipv4地址扫描。

#### 语法

语法请参考fofa.info。



#### 导出数据

导出当前选中页的数据。

## 为什么要做这个？

计划做一个一体化的渗透测试工具，Fofa-GUI只是第一个组件，将来会在一体化工具内添加联动（存活检测、POC验证等）功能。

## 构建状态

| 版本  | MacOS | Windows | Linux |
| ----- | ----- | ------- | ----- |
| 0.0.1 |✅|✅|❌|
| 0.0.2(pre-release)|✅|✅|✅|
| 0.0.3|✅|✅|✅|
| 0.0.4|✅|✅|✅|

## 贡献POC

将在3个版本内更新POC管理器，届时上线POC仓库。

## Star Chart
[![Stargazers over time](https://starchart.cc/earlysun030201/Fofa-GUI.svg?variant=adaptive)](https://starchart.cc/earlysun030201/Fofa-GUI)
