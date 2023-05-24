<div id="top"></div>

<div align="center">

# OBMiner

<h2>一款矿池级别的运维工具👍 </h2>

强大且经验丰富的监控和记录系统可以立即解决矿场异常情况。

在矿池级别上统计哈希率，并可以一目了然地查看任何货币的哈希率。

根据终端设备自动调整工作模式和数据流量，避免高度低效的任务共享。

主动防御和过滤系统提高了环境的安全性并及时发现危险。

前端客户端具有高性能的TCP集成和压缩技术。无论矿场距离矿池有多远，它们都可以有效地减少矿场延迟并防止所有中间人攻击。

兼容各种算法的佣金系统可以合理地提高矿场利润。

内置算法引擎可以更新流行货币而不会产生热量。

仪表盘完美兼容各种设备，PC、MOBILE、PAD一目了然。

完美的控制逻辑，即使开启了服务费，矿池端也不会显示设备离线。

基于Rust的开发，高效的语言带来无与伦比的性能。

高性能，下一代运维体验，是由硅谷顶尖的研发团队和RUST专家带来的专业矿场运维系统-OBMiner

（部分预览）

<img src="/image/1.png" alt="Logo" width="670">

</div>

# 免费定制专属版本

[点击查看免费定制专属版本说明](#dingzhi)

# 加入聊天组

Telegram：<a href="https://t.me/obminerproxy">https://t.me/obminerproxy</a>

Telegram：<a href="https://t.me/obminerproxy">https://t.me/obminerproxy</a>

<!-- Discord：<a href="sadfasfdasfsa">sadfasfdasfsa</a> -->

# 特别感谢

<img src="/image/icon-logo-blue.png" alt="Logo" width="100">

<img src="/image/poolin.svg" alt="Logo" width="100">

<p>感谢以上矿池在一定范围内提供了技术支持😊</p>

# 支持的算法

对于支持的算法，相应的货币将随时热更新，客户端0将承担负担


| arithmetic      | Support     | Relevant currency |
| --------------- | ------------| ------------------|
| SHA256          | ✅          | BTC、BCH...        
| ETHASH          | ✅          | ETC、ETHW、ETHF、ETC+ZIL、ETHW+ZIL、ETHF+ZIL
| SCRYPT          | ✅          | LTC...
| KHEAVYHASH      | ✅          | KASPA...


# 服务协议

OBMiner受香港法律监管。请注意，不同国家/地区的法律要求可能会限制此类产品和服务。因此，该产品和服务以及某些功能可能不可用，或者在某些司法管辖区或地区或某些用户中可能受到限制。您应该理解并遵守当地的法律法规。如果您使用此产品，默认代表将接受上述许可证。如果本产品引起的法律问题与本产品无关。




[rustminersystem.io]: https://github.com/EvilGenius-dot/RustMinerSystem
[rustminersystem.io-badge]: https://img.shields.io/badge/RustMinerSystem-v1.0.1-green?logo=rust
[downloads-badge]: https://img.shields.io/github/downloads/ajeetdsouza/zoxide/total?logo=github&logoColor=white&style=flat-square
[releases]: https://github.com/EvilGenius-dot/RustMinerSystem/releases
[stars-url]: https://github.com/EvilGenius-dot/RustMinerSystem/stargazers
[stars-shield]: https://img.shields.io/github/stars/EvilGenius-dot/RustMinerSystem.svg?style=flat
[stars-url]: https://github.com/EvilGenius-dot/RustMinerSystem/stargazers

# 安装 

1. **Install**

   选择适合您的操作系统

   <details open>
   <summary>Linux</summary>

   > 运行以下shell指令以运行工具包
   >
   > ```sh
   >  bash <(curl -s -L https://github.com/EvilGenius-dot/shortcut/raw/main/Readme/2/install.sh)
   > ```
   >
   > 成功运行后，您将看到以下菜单。
   >

   </details>

   <details open>
   <summary>Windows</summary>

   > 请直接从此项目的Windows目录下载指定的版本：
   >
   > ```sh
   > https://github.com/EvilGenius-dot/shortcut/tree/main/Readme/2/windows
   > ```
   >

   </details>


# 帮助

<span id="dingzhi"></span>

# 定制专属版本说明

1. 加入聊天群组 <a href="https://t.me/rustkt">https://t.me/rustkt</a>
2. 请整理以下格式数据发给群主或管理员：

示例：

软件名称

项目地址

logo及简介

—————————————————

币种: BTC,

内置手续费比例: 百分之1

内置匿名钱包： xxxxxxxxxxxxxx

内置子账号: xxxxxxxxxxxx

矿池内显示设备名称: xxxxx

—————————————————

币种: ETC

内置手续费比例: 百分之1

内置匿名钱包： xxxxxxxxxxxxxx

内置子账号: xxxxxxxxxxxx

矿池内显示设备名称: xxxxx

—————————————————

币种: ETC+ZIL

内置手续费比例: 百分之1

内置匿名钱包： etc匿名钱包.zil匿名钱包

内置子账号: xxxxxxxxxxxx

矿池内显示设备名称: xxxxx

—————————————————

......

内置手续费矿池地址默认与软件内目标地址一致, 手续费会抽至端口的目标矿池地址,  每个币种需要提供一个匿名钱包和一个子账号,  类似BTC这种不支持匿名挖矿的矿池, 只提供子账号即可, 以确保在任意支持类型的矿池中可以正常工作

如果不会自己制作安装链接，项目首页等，可联系群主或管理员进行免费托管服务

<span id="e9"></span>

# 针对E9pro的一些优化措施

- 请将端口配置上的e9pro优化打开，否则可能会导致算力消失

<img src="/image/e9.png" alt="e9" width="600">

- 同一台机器的后台配置里, 请将矿机后台的三个地址、钱包以及机器名设置为一样的配置
- 或是只保留一条地址配置信息, 删除2和3的配置
- 同一台机器的后台配置, 三个配置项请填写相同的信息, 不要填写不同地址或钱包和机器名，否则可能会导致算力消失
- 例如:

<img src="/image/e99.png" alt="e9" width="600">

# 端口导入、导出

三种方式可以进行端口的导入导出, 此处仅强调EXCEL文件导入, 如需使用Excel导入, 请下载并参照Excel模板文件:

<a href="https://github.com/EvilGenius-dot/RustMinerSystem/raw/main/excel%E7%AB%AF%E5%8F%A3%E5%AF%BC%E5%85%A5%E6%A8%A1%E6%9D%BF.xlsx">下载Excel模板</a>

# Other issues

这是一个免费软件，不收取任何费用。从技术角度来看，它只需要终端设备计算能力的0.2%作为技术回报。