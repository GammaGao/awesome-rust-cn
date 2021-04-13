# Rust资源大全
  - [Rust基础语法学习](https://www.runoob.com/rust/rust-tutorial.html)

  - Rust特性
    - Rust作为新一代系统级编程语言，聚焦内存"安全"、"并发"、"实用"的设计原则。
    - Rust核心概念是"不可变"、"所有权"、"Trait"。
    - Rust不玩虚拟机和垃圾回收，通过"不可变"、"所有权"，牺牲一定的编程灵活性，增加一些编程复杂性来实现内存安全；通过Trait来实现多态。
	
## 目录

  - [应用](#应用程序)
    - [音频和音乐](#音频和音乐)
    - [加密货币](#加密货币)
    - [数据库](#数据库)
    - [仿真器](#仿真器)
    - [游戏类](#游戏)
    - [图形学](#图形学)
    - [工业自动化](#工业自动化)
    - [可观察性](#可观察性)
    - [操作系统](#操作系统)
    - [生产率工具](#生产率工具)
    - [安全工具](#安全工具)
    - [系统工具](#系统工具)
    - [文本编辑器](#文本编辑器)
    - [文本处理](#文本处理)
    - [图像处理](#图像处理)
    - [实用工具](#[实用工具)
    - [视频](#视频)
    - [虚拟化](#虚拟化)
    - [网页](#网页)
    - [Web服务器](#Web服务器)
  - [开发工具](#开发工具)
    - [构建系统](#构建系统)
    - [调试](#调试)
    - [部署](#部署)
    - [嵌入式](#嵌入式)
    - [语言交互接口](#语言交互接口)
    - [IDE工具](#IDE工具)
    - [模式识别](#模式识别)
    - [剖析工具](#剖析工具)
    - [服务](#服务)
    - [静态分析](#静态分析)
    - [测试](#测试)
    - [转换](#转换)
  - [Rust库](#Rust库)
    - [人工智能](#人工智能)
      - [遗传算法](#遗传算法)
      - [机器学习](#机器学习)
    - [天文学](#天文学)
    - [异步](#异步)
    - [音频和音乐](#音频和音乐-1)
    - [认证](#认证)
    - [汽车行业](#汽车行业)
    - [生物信息学](#生物信息学)
    - [缓存](#缓存)
    - [并发](#并发)
    - [云计算](#云计算)
    - [命令行](#命令行)
    - [压缩](#压缩)
    - [计算](#计算)
    - [配置](#配置)
    - [密码学](#密码学)
    - [数据库](#数据库-1)
    - [数据处理](#数据库)
    - [数据结构](#数据结构)
    - [数据可视化](#数据可视化)
    - [日期和时间](#日期和时间)
    - [分布式系统](#分布式系统)
    - [电子邮件](#电子邮件)
    - [编码方式](#编码方式)
    - [文件系统](#文件系统)
    - [函数式编程](#函数式编程)
    - [游戏开发](#游戏开发)
    - [地理空间](#地理空间)
    - [图形学](#图形学-1)
    - [图形处理](#图形处理)
    - [GUI](#GUI)
    - [图像处理](#图像处理)
    - [语言规范](#语言规范)
    - [日志](#日志)
    - [宏](#宏)
    - [标记语言](#标记语言)
    - [移动开发](#移动开发)
    - [网络编程](#网络编程)
    - [解析器](#解析器)
    - [打包格式](#打包格式)
    - [外围设备](#外围设备)
    - [平台相关](#平台相关)
    - [脚本](#脚本)
    - [模拟](#模拟)
    - [任务调度](#任务调度)
    - [模版引擎](#模版引擎)
    - [文本处理](#文本处理-1)
    - [文本搜索](#文本搜索)
    - [非安全性](#非安全性)
    - [虚拟化](#虚拟化-1)
    - [Web编程](#Web编程)
  - [Rust registries](#Registries)
  - [资源](#资源)
  - [许可](#许可)

## 应用程序

* [alacritty](https://github.com/alacritty/alacritty) — 跨平台，GPU增强的终端仿真器
* [AnderEnder/s3find-rs](https://github.com/AnderEnder/s3find-rs) — 用于遍历Amazon S3层次结构（类似于Amazon S3的find）的命令行实用工具 [![build badge](https://api.travis-ci.org/AnderEnder/s3find-rs.svg?branch=master)](https://travis-ci.org/AnderEnder/s3find-rs)
* [andschwa/rust-genetic-algorithm](https://github.com/andschwa/rust-genetic-algorithm) — 解决学术基准问题的遗传算法 [![build badge](https://api.travis-ci.org/andschwa/rust-genetic-algorithm.svg?branch=master)](https://travis-ci.org/andschwa/rust-genetic-algorithm)
* [asm-cli-rust](https://github.com/cch123/asm-cli-rust) — 一种用rust实现交互式程序集shell
* [ballista](https://github.com/ballista-compute/ballista) — 基于Rust，Apache Arrow和Kubernetes的分布式计算平台的PoC
* [cloudflare/boringtun](https://github.com/cloudflare/boringtun) — 一种用户空间WireGuard VPN实现 [![build badge](https://img.shields.io/badge/crates.io-v0.2.0-orange.svg)](https://crates.io/crates/boringtun)
* [darrint/device-blocker](https://github.com/darrint/device-blocker) — 通过阻止家庭Wifi路由器上的互联网访问，限制儿童在各种移动设备的使用时间
* [denoland/deno](https://github.com/denoland/deno) — 基于V8，Rust和Tokio构建的安全JavaScript/TypeScript运行时 [![Build Status](https://github.com/denoland/deno/workflows/ci/badge.svg?branch=master&event=push)](https://github.com/denoland/deno/actions)
* [dlecan/generic-dns-update](https://github.com/dlecan/generic-dns-update) — 使用IP地址更新DNS区域文件的工具 [![build badge](https://api.travis-ci.org/dlecan/generic-dns-update.svg?branch=master)](https://travis-ci.org/dlecan/generic-dns-update)
* [Factotum](https://github.com/snowplow/factotum) — [一种编程运行数据管道的系统](https://snowplowanalytics.com/blog/2016/04/09/introducing-factotum-data-pipeline-runner/) [![build badge](https://api.travis-ci.org/snowplow/factotum.svg?branch=master)](https://travis-ci.org/snowplow/factotum)
* [fcsonline/drill](https://github.com/fcsonline/drill) — 灵感来自Ansible语法启发的HTTP负载测试应用程序 [![build badge](https://api.travis-ci.org/fcsonline/drill.svg?branch=master)](https://travis-ci.org/fcsonline/drill)
* [Fractalide](https://github.com/fractalide/fractalide) — 简单的Rust微服务
* [habitat](https://community.chef.io/products/chef-habitat/) — 由[Chef](https://www.chef.io/)创建的用于构建，部署和管理应用程序的工具
* [Herd](https://github.com/imjacobclark/Herd) — 一个HTTP负载测试应用程序
* [intecture/api](https://github.com/intecture/api) — API驱动的服务器管理和配置工具 [![build badge](https://api.travis-ci.org/intecture/api.svg?branch=master)](https://travis-ci.org/intecture/api)
* [ivanceras/diwata](https://github.com/ivanceras/diwata) — 用于PostgreSQL的数据库管理工具 [![build badge](https://api.travis-ci.org/ivanceras/diwata.svg?branch=master)](https://travis-ci.org/ivanceras/diwata)
* [jedisct1/flowgger](https://github.com/awslabs/flowgger) — 快速，简单，轻巧的数据收集器
* [kbknapp/docli](https://github.com/kbknapp/docli-rs) — 用于管理DigitalOcean基础设施的命令行实用程序 [![build badge](https://api.travis-ci.org/kbknapp/docli-rs.svg?branch=master)](https://travis-ci.org/kbknapp/docli-rs)
* [kytan](https://github.com/changlan/kytan) — 高性能P2P VPN
* [limonite](https://crates.io/crates/limonite) — 静态博客/网站生成器 [![build badge](https://api.travis-ci.org/qmx/limonite.svg?branch=master)](https://travis-ci.org/qmx/limonite)
* [linkerd/linkerd2-proxy](https://github.com/linkerd/linkerd2-proxy) — Kubernetes的Ultralight服务网格
* [MaidSafe](https://maidsafe.net) — 一个去中心化的平台
* [mdBook](https://crates.io/crates/mdbook) — 用于从markdown文件创建书籍的命令行实用程序 [![Build Status](https://github.com/rust-lang/mdBook/workflows/CI/badge.svg?branch=master)](https://github.com/rust-lang/mdBook/actions)
* [nicohman/eidolon](https://github.com/nicohman/eidolon) — 适用于linux和macosx的Steam平台上的无数字版权保护的游戏注册和启动器 [![build badge](https://api.travis-ci.org/nicohman/eidolon.svg?branch=master)](https://travis-ci.org/nicohman/eidolon)
* [notty](https://github.com/withoutboats/notty) — 一种新型的终端
* [Pijul](https://pijul.org) — 基于补丁的分布式版本控制系统
* [rsign](https://crates.io/crates/rsign) — 一个简单的命令行工具，用于生成/签名/验证数字签名，旨在与Minisign兼容 ![Codeship Status for danielrangel/rsign](https://app.codeship.com/projects/60b28d80-7645-0135-4402-1639b58199d0/status?branch=master)
* [Rudr](https://github.com/oam-dev/rudr) — [开放应用程序模型规范](https://oam.dev/)的Kubernetes实现 [![](https://github.com/oam-dev/rudr/workflows/Rust/badge.svg?branch=master)](https://github.com/oam-dev/rudr/actions)
* [rx](https://github.com/cloudhead/rx) — 灵感来自Vi的现代像素艺术编辑器
* [Sandstorm Collections App](https://github.com/sandstorm-io/collections-app)
* [Servo](https://github.com/servo/servo) — 原型Web浏览器引擎
* [tiny](https://github.com/osa1/tiny) — IRC客户端
* [trust-dns](https://crates.io/crates/trust-dns) — DNS服务器 [![build badge](https://api.travis-ci.org/bluejekyll/trust-dns.svg?branch=master)](https://travis-ci.org/bluejekyll/trust-dns)
* [updns](https://github.com/wyhaya/updns) — DNS代理工具
* [Weld](https://github.com/serayuzgur/weld) — fake REST API生成器 [![build badge](https://api.travis-ci.org/serayuzgur/weld.svg?branch=master)](https://travis-ci.org/serayuzgur/weld)
* [wezterm](https://github.com/wez/wezterm) —  GPU加速的跨平台终端仿真器和多路复用器

### 音频和音乐

* [enginesound](https://github.com/DasEtwas/enginesound) — 一个GUI和命令行应用程序，用于按程序生成半现实的引擎声音。具有深层的配置，可变的采样率和频率分析窗口。
* [indiscipline/zrtstr](https://github.com/indiscipline/zrtstr) — 一种命令行实用程序，用于检查立体声wav文件是否为仿立体声（即具有相同的通道）并将此类文件转换为单声道 [![build badge](https://api.travis-ci.org/indiscipline/zrtstr.svg?branch=master)](https://travis-ci.org/indiscipline/zrtstr)
* [Lyriek](https://github.com/bartwillems/lyriek) — 一个多线程GTK 3应用程序，用于获取当前正在播放的歌曲的歌词 [![build badge](https://github.com/bartwillems/lyriek/workflows/Rust/badge.svg?branch=master)](https://github.com/BartWillems/lyriek/actions)
* [Phate6660/musinfo](https://github.com/Phate6660/musinfo) — 一个用于从mpd中查询音乐信息并将其显示在通知中的程序
* [Phate6660/rsmpc](https://github.com/Phate6660/rsmpc) — 一个mpc的实现
* [Phate6660/rsmpc](https://github.com/Phate6660/rsmpc-gui) — 一个mpd的gtk前端
* [Polaris](https://github.com/agersant/polaris) — 一种音频流应用程序.  [![build badge](https://api.travis-ci.org/agersant/polaris.svg?branch=master)](https://travis-ci.org/agersant/polaris)
* [Spotify TUI](https://github.com/Rigellute/spotify-tui) — 用Rust编写Spotify客户端 ![Continuous Integration](https://github.com/Rigellute/spotify-tui/workflows/Continuous%20Integration/badge.svg?branch=master)
* [Spotifyd](https://github.com/Spotifyd/spotifyd) — 可以以UNIX守护程序运行的开源Spotify客户端 ![Continuous Integration](https://github.com/Spotifyd/spotifyd/workflows/Continuous%20Integration/badge.svg?branch=master)

### 加密货币

* [Bitcoin Satoshi's Vision](https://github.com/brentongunning/rust-sv) — 用于使用比特币SV的Rust库
* [cardano-cli](https://github.com/input-output-hk/cardano-cli) — Cardano命令行界面（CLI）
* [ChainX](https://github.com/chainx-org/ChainX) — Polkadot上的完全去中心化的链间加密资产管理
* [CITA](https://github.com/citahub/cita) — 适用于企业用户的高性能区块链内核
* [coinbase-pro-rs](https://github.com/inv2004/coinbase-pro-rs) — Rust实现的Coinbase pro客户端，支持同步/异步/websocket [![build badge](https://api.travis-ci.org/inv2004/coinbase-pro-rs.svg?branch=master)](https://travis-ci.org/inv2004/coinbase-pro-rs)
* [ethaddrgen](https://github.com/Limeth/ethaddrgen) — Rust实现的自定义以太坊虚荣地址生成器 [![build badge](https://api.travis-ci.org/Limeth/ethaddrgen.svg?branch=master)](https://travis-ci.org/Limeth/ethaddrgen)
* [Grin](https://github.com/mimblewimble/grin/) — MimbleWimble协议的演进
* [hdwallet](https://github.com/jjyr/hdwallet) — BIP-32 HD钱包相关的密钥派发实用程序
* [Holochain](https://github.com/holochain/holochain) — 可扩展的P2P替代区块链的工具，可用于您一直希望构建的所有分布式应用程序 [![Build Status](https://api.travis-ci.com/holochain/holochain-rust.svg?branch=master)](https://travis-ci.com/holochain/holochain-rust)
* [ibc-rs](https://github.com/informalsystems/ibc-rs) - [区块链间通信协议](https://cosmos.network/ibc/)的Rust实现
* [infincia/bip39-rs](https://github.com/infincia/bip39-rs) — BIP39的Rust实现
* [Joystream](https://github.com/Joystream/joystream) — 用户控制的视频平台 [![Build Status](https://api.travis-ci.org/Joystream/joystream.svg?branch=master)](https://travis-ci.org/Joystream/joystream)
* [Diem](https://github.com/diem/diem) — Diem的使命是建立一种简单的全球货币和金融基础设施，以赋能数十亿人口
* [Lighthouse](https://github.com/sigp/lighthouse) — Rust实现的Ethereum 2.0客户端 [![Build Status](https://github.com/sigp/lighthouse/workflows/test-suite/badge.svg?branch=master)](https://github.com/sigp/lighthouse/actions)
* [near/nearcore](https://github.com/near/nearcore) — 用于低端移动设备的去中心化智能合约平台
* [Nervos CKB](https://github.com/nervosnetwork/ckb) — 是一个公共的，未经许可的区块链，是Nervos网络的共识层
* [Nimiq](https://github.com/nimiq/core-rs) — Nimiq节点的Rust实现 [![Build Status](https://api.travis-ci.com/nimiq/core-rs.svg?branch=master)](https://travis-ci.com/nimiq/core-rs)
* [Parity-Bitcoin](https://github.com/paritytech/parity-bitcoin) — 奇偶校验比特币客户端 [![build badge](https://api.travis-ci.org/paritytech/parity-bitcoin.svg?branch=master)](https://travis-ci.com/paritytech/parity-bitcoin)
* [Parity-Bridge](https://github.com/paritytech/parity-bridge) — 任何两个基于以太坊的网络之间的桥梁
* [Parity-Ethereum](https://github.com/openethereum/openethereum) — 快速，轻巧，强大的以太坊客户端
* [Parity-Zcash](https://github.com/paritytech/parity-zcash) — Zcash协议的Rust实现
* [Phala-Network/phala-blockchain](https://github.com/Phala-Network/phala-blockchain) — 基于英特尔SGX和Substrate的机密智能合约区块链
* [Polkadot](https://github.com/paritytech/polkadot) — 具有集合安全性的异构多链技术
* [rbtc](https://github.com/lucawen/rbtc) — 将BTC转换为任何货币，反之亦然 [![Build Status](https://api.travis-ci.com/lucawen/rbtc.svg?branch=master)](https://travis-ci.com/lucawen/rbtc)
* [rust-cardano](https://github.com/input-output-hk/rust-cardano) — Cardano primitives，helpers和相关应用程序的Rust实现
* [Substrate](https://github.com/paritytech/substrate) — 用Rust编写的通用模块化区块链模板
* [tendermint-rs](https://github.com/informalsystems/tendermint-rs) - Tendermint区块链数据结构和客户端的Rust实现
* [wagyu](https://github.com/AleoHQ/wagyu) [[wagyu](https://crates.io/crates/wagyu)] — 用于生成加密货币钱包的Rust库 [![build badge](https://api.travis-ci.com/AleoHQ/wagyu.svg?branch=master)](https://api.travis-ci.com/AleoHQ/wagyu.svg?branch=master)
* [zcash](https://github.com/zcash/zcash) — Zcash是“Zerocash”协议的实现
* [YeeCo yeeroot](https://github.com/yeeco/yeeroot) — YeeCo yeeroot是一个无许可，安全，高性能和可扩展的公共区块链平台，由基于Rust编写的PoW共识的完整分片技术提供支持

### 数据库

* [indradb](https://crates.io/crates/indradb) — Rust实现的图形数据库 [![build badge](https://api.travis-ci.org/indradb/indradb.svg?branch=master)](https://travis-ci.org/indradb/indradb)
* [Materialize](https://github.com/MaterializeInc/materialize) - 由Timely Dataflow支持的流式SQL数据库 :heavy_dollar_sign: [![Build status](https://badge.buildkite.com/97d6604e015bf633d1c2a12d166bb46f3b43a927d3952c999a.svg?branch=main)](https://buildkite.com/materialize/tests)
* [noria](https://crates.io/crates/noria) — 用于web应用程序的数据流 [![build badge](https://api.travis-ci.org/mit-pdos/noria.svg?branch=master)](https://travis-ci.org/mit-pdos/noria)
* [Lucid](https://github.com/lucid-kv/lucid) — 高性能和分布式KV存储，可通过HTTP API访问 [![Build Status](https://github.com/lucid-kv/lucid/workflows/Lucid/badge.svg?branch=master)](https://github.com/lucid-kv/lucid/actions?workflow=Lucid)
* [ParityDB](https://github.com/paritytech/parity-db) — 快速可靠的数据库，针对读取操作进行了优化
* [PumpkinDB](https://github.com/PumpkinDB/PumpkinDB) — 事件源数据库引擎 [![build badge](https://api.travis-ci.org/PumpkinDB/PumpkinDB.svg?branch=master)](https://travis-ci.org/PumpkinDB/PumpkinDB)
* [seppo0010/rsedis](https://github.com/seppo0010/rsedis) — 用Rust重新实现的Redis [![build badge](https://api.travis-ci.org/seppo0010/rsedis.svg?branch=master)](https://travis-ci.org/seppo0010/rsedis)
* [TerrabaseDB](https://github.com/terrabasedb/terrabasedb) — 多模型NoSQL数据库 ![GitHub Workflow Status](https://img.shields.io/github/workflow/status/terrabasedb/terrabasedb/Tests?style=flat-square)
* [tikv](https://github.com/tikv/tikv) — Rust实现的分布式KV数据库 [![build badge](https://circleci.com/gh/tikv/tikv.svg?style=shield&circle-token=36bab0a8e43edb0941b31c38557d2d9d0d58f708)](https://app.circleci.com/pipelines/github/tikv/tikv)
* [sled](https://crates.io/crates/sled) — 一个（beta版）现代嵌入式数据库 [![Build Status](https://github.com/spacejam/sled/workflows/Rust/badge.svg?branch=master)](https://github.com/spacejam/sled/actions?workflow=Rust)
* [TerminusDB](https://github.com/terminusdb/terminusdb-store) - 开源图形和文档存储数据库 [![Build Status](https://github.com/terminusdb/terminusdb-store/workflows/Build/badge.svg)](https://github.com/terminusdb/terminusdb-store/actions)

### 仿真器

* Commodore 64
  * [kondrak/rust64](https://github.com/kondrak/rust64) — [![build badge](https://api.travis-ci.org/kondrak/rust64.svg?branch=master)](https://travis-ci.org/kondrak/rust64)
* Flash播放器
  * [Ruffle](https://github.com/ruffle-rs/ruffle) — Ruffle是用Rust编程语言编写的Adobe Flash Player模拟器。[![build badge](https://img.shields.io/circleci/build/github/ruffle-rs/ruffle)](https://app.circleci.com/pipelines/github/ruffle-rs/ruffle)
* Gameboy
  * [Gekkio/mooneye-gb](https://github.com/Gekkio/mooneye-gb) — [![build badge](https://api.travis-ci.org/Gekkio/mooneye-gb.svg?branch=master)](https://travis-ci.org/Gekkio/mooneye-gb)
  * [mvdnes/rboy](https://github.com/mvdnes/rboy) — [![build badge](https://api.travis-ci.org/mvdnes/rboy.svg?branch=master)](https://travis-ci.org/mvdnes/rboy)
  * [NivenT/RGB](https://github.com/nivent/RGB) — [![build badge](https://api.travis-ci.org/NivenT/RGB.svg?branch=master)](https://travis-ci.org/NivenT/RGB)
  * [mohanson/gameboy](https://github.com/mohanson/gameboy) — 功能齐全的跨平台GameBoy模拟器
* Gameboy Advance
  * [michelhe/rustboyadvance-ng](https://github.com/michelhe/rustboyadvance-ng) - RustboyAdvance-ng是Gameboy Advance模拟器，支持桌面，Android和WebAssembly [![build badge](https://github.com/michelhe/rustboyadvance-ng/workflows/Deploy/badge.svg?branch=master)](https://github.com/michelhe/rustboyadvance-ng/actions?query=workflow%3ADeploy)
* NES
  * [iamsix/oxidenes](https://github.com/iamsix/oxidenes)
  * [koute/pinky](https://github.com/koute/pinky) — [![build badge](https://api.travis-ci.org/koute/pinky.svg?branch=master)](https://travis-ci.org/koute/pinky)
  * [pcwalton/sprocketnes](https://github.com/pcwalton/sprocketnes)
  * [Amjad50/plastic](https://github.com/Amjad50/plastic) — plastis是一款Rust实现的全功能NES模拟器 [![build badge](https://github.com/Amjad50/plastic/workflows/Rust/badge.svg?branch=master)](https://github.com/Amjad50/plastic/actions?query=workflow%3ARust)
* Playstation
  * [rustation-ng](https://gitlab.com/flio/rustation-ng/) — Rust编写的Playstation模拟器
* ZX Spectrum
  * [pacmancoder/rustzx](https://github.com/pacmancoder/rustzx) — [![build badge](https://api.travis-ci.org/pacmancoder/rustzx.svg?branch=master)](https://travis-ci.org/pacmancoder/rustzx)
  * [rodrigorc/raze](https://github.com/rodrigorc/raze) — For WebAssembly, [live version here](https://rodrigorc.github.io/raze/)
* Virtual Boy
  * [emu-rs/rustual-boy](https://github.com/emu-rs/rustual-boy) — [![build badge](https://api.travis-ci.org/emu-rs/rustual-boy.svg?branch=master)](https://travis-ci.org/emu-rs/rustual-boy)
* Intel 8080 CPU
  * [mohanson/i8080](https://github.com/mohanson/i8080) — Rust编写的Intel 8080 cpu模拟器
* 模拟器开发工具
  * SNES
    * [ioncodes/snesutilities](https://github.com/ioncodes/snesutilities) — ROM分析器/提取器

### 游戏

* [lifthrasiir/angolmois-rust](https://github.com/lifthrasiir/angolmois-rust) — 支持BMS格式的简约音乐视频游戏 [![build badge](https://api.travis-ci.org/lifthrasiir/angolmois-rust.svg?branch=master)](https://travis-ci.org/lifthrasiir/angolmois-rust)
* [citybound](https://github.com/citybound/citybound) — 模拟城市
* [schulke-214/connect-four](https://github.com/schulke-214/connect-four) — 一个简单的connect four实现
* [doukutsu-rs](https://github.com/doukutsu-rs/doukutsu-rs) — 对Cave Story引擎的Rust重新实现，并进行了一些增强
* [rsaarelm/magog](https://github.com/rsaarelm/magog) — Rust实现的roguelike游戏
* [schulke-214/rsnake](https://github.com/schulke-214/rsnake) — 用Rust写的Snake游戏.
* [soydos](https://github.com/soydos/pusoy_dos2) — Pusoy Dos的wasm实现
* [cristicbz/rust-doom](https://github.com/cristicbz/rust-doom) — 《毁灭战士》的渲染器，可能会发展成为一款可玩的游戏 [![build badge](https://api.travis-ci.org/cristicbz/rust-doom.svg?branch=master)](https://travis-ci.org/cristicbz/rust-doom)
* [Thinkofname/rust-quake](https://github.com/Thinkofname/rust-quake) — Rust实现的Quake地图渲染器
* [rhex](https://github.com/dpc/rhex) — ascii风格roguelike
* [garkimasera/rusted-ruins](https://github.com/garkimasera/rusted-ruins) — 可扩展的open world roguelike游戏 [![build badge](https://api.travis-ci.org/garkimasera/rusted-ruins.svg?branch=master)](https://travis-ci.org/garkimasera/rusted-ruins)
* [Veloren](https://gitlab.com/veloren/veloren) — alpha版本的开源多人RPG游戏 [![build badge](https://gitlab.com/veloren/veloren/badges/master/pipeline.svg)](https://gitlab.com/veloren/veloren/commits/master)
* [swatteau/sokoban-rs](https://github.com/swatteau/sokoban-rs) — 推箱子游戏的一种实现
* [aleshaleksey/TGWM](https://github.com/aleshaleksey/TGWM) — 基于回合机制的RPG游戏 [![build badge](https://api.travis-ci.org/aleshaleksey/TGWM.svg?branch=master)](https://travis-ci.org/aleshaleksey/TGWM)
* [ozkriff/zemeroth](https://github.com/ozkriff/zemeroth) — 一个小型的2D策略游戏 [![build badge](https://api.travis-ci.org/ozkriff/zemeroth.svg?branch=master)](https://travis-ci.org/ozkriff/zemeroth)
* [Zone of Control](https://github.com/ozkriff/zoc) — 一个回合制的策略游戏 [![build badge](https://api.travis-ci.org/ozkriff/zoc.svg?branch=master)](https://travis-ci.org/ozkriff/zoc)
* [phantomion/snake_game](https://github.com/phantomion/snake_game) - 用Rust编写的简单的Snake游戏.

### 图形学

* [Limeth/euclider](https://github.com/Limeth/euclider) — 实时4D CPU光线跟踪器 [![build badge](https://api.travis-ci.org/Limeth/euclider.svg?branch=master)](https://travis-ci.org/Limeth/euclider)
* [RazrFalcon/resvg](https://github.com/RazrFalcon/resvg) — SVG渲染库 [![build badge](https://api.travis-ci.org/RazrFalcon/resvg.svg?branch=master)](https://travis-ci.org/RazrFalcon/resvg)
* [ivanceras/svgbob](https://github.com/ivanceras/svgbob) — 将ASCII图转换为SVG图形 [![build badge](https://api.travis-ci.org/ivanceras/svgbob.svg?branch=master)](https://travis-ci.org/ivanceras/svgbob)
* [RazrFalcon/svgcleaner](https://github.com/RazrFalcon/svgcleaner) — 整理SVG图形
* [Twinklebear/tray_rust](https://github.com/Twinklebear/tray_rust) — 光线追踪器 [![build badge](https://api.travis-ci.org/Twinklebear/tray_rust.svg?branch=master)](https://travis-ci.org/Twinklebear/tray_rust)
* [turnage/valora](https://crates.io/crates/valora) — 生成式艺术库 ![Rust](https://github.com/turnage/valora/workflows/Rust/badge.svg?branch=master)
* 图形处理:
  * [mikigraf/Image-Processing-CLI-in-Rust](https://github.com/mikigraf/Image-Processing-CLI-in-Rust) — 用于处理图像，生成直方图的CLI [![Build Status](https://api.travis-ci.org/spejss/Image-Processing-CLI-in-Rust.svg?branch=master)](https://travis-ci.org/spejss/Image-Processing-CLI-in-Rust)

### 工业自动化

* [locka99/opcua](https://github.com/locka99/opcua) — rust OPCUA库
* [slowtec/tokio-modbus](https://github.com/slowtec/tokio-modbus) — 基于tokio的modbus库 [![Build Status](https://api.travis-ci.org/slowtec/tokio-modbus.svg?branch=master)](https://travis-ci.org/slowtec/tokio-modbus)
* [BiancoRoyal/modbus-iiot-rust](https://github.com/BiancoRoyal/modbus-iiot-rust) — 无依赖的rust modbus库 [![Build Status](https://api.travis-ci.org/BiancoRoyal/modbus-iiot-rust.svg?branch=master)](https://travis-ci.org/BiancoRoyal/modbus-iiot-rust)

### 可观察性

* [timberio/vector](https://github.com/timberio/vector) — 高性能，日志，指标和事件路由器
* [Mnwa/gtsa](https://github.com/Mnwa/gtsa) — 一种将Gelf消息（Graylog的消息）代理到Sentry的简单解决方案
* [OpenTelemetry](https://crates.io/crates/opentelemetry) — OpenTelemetry提供了一组API，库，代理和收集器服务，以捕获应用程序中的分布式跟踪和度量。您可以使用Prometheus，Jaeger和其他可观察性工具对其进行分析 [![GitHub Actions CI](https://github.com/open-telemetry/opentelemetry-rust/workflows/CI/badge.svg?branch=master)](https://github.com/open-telemetry/opentelemetry-rust/actions?query=workflow%3ACI+branch%3Amaster)

### 操作系统

* [nebulet/nebulet](https://github.com/nebulet/nebulet) — 实现在Ring 0中运行的WebAssembly“用户模式”的微内核
* [redox-os/redox](https://gitlab.redox-os.org/redox-os/redox) — [![build badge](https://api.travis-ci.org/redox-os/redox.svg?branch=master)](https://travis-ci.org/redox-os/redox)
* [thepowersgang/rust_os](https://github.com/thepowersgang/rust_os) — [![build badge](https://api.travis-ci.org/thepowersgang/rust_os.svg?branch=master)](https://travis-ci.org/thepowersgang/rust_os)
* [tock/tock](https://github.com/tock/tock) — 用于基于Cortex-M的微控制器的安全嵌入式操作系统

### 生产率工具
* [espanso](https://github.com/federico-terzi/espanso) — 用Rust编写的跨平台文本扩展器 [![Build Status](https://dev.azure.com/freddy6896/espanso/_apis/build/status/federico-terzi.espanso?branchName=master)](https://dev.azure.com/freddy6896/espanso/_build)
* [eureka](https://crates.io/crates/eureka) — 一个CLI工具，用于输入和存储您的想法而无需离开终端
* [pier-cli/pier](https://github.com/pier-cli/pier) — 管理（添加，搜索元数据等）所有单行代码，脚本，工具和CLI的中央存储库 [![build badge](https://api.travis-ci.com/BenSchZA/pier.svg?branch=master)](https://travis-ci.com/BenSchZA/pier)
* [subilo](https://github.com/Bansco/subilo) - 持续部署代理 [![Build Status](https://github.com/Bansco/subilo/workflows/Rust/badge.svg?branch=master)](https://github.com/Bansco/subilo/actions?query=workflow%3ARust)

### 安全工具

* [kpcyrd/badtouch](https://github.com/kpcyrd/badtouch) — 可编写脚本的网络身份验证破解程序 [![build badge](https://api.travis-ci.org/kpcyrd/badtouch.svg?branch=master)](https://travis-ci.org/kpcyrd/badtouch)
* [lethe](https://github.com/kostassoid/lethe) — 安全的跨平台驱动器擦除实用程序 [![Version info](https://img.shields.io/crates/v/lethe.svg)](https://crates.io/crates/lethe) [![Build Status](https://api.travis-ci.org/kostassoid/lethe.svg?branch=master)](https://travis-ci.org/kostassoid/lethe)
* [arvancloud/libinjection-rs](https://github.com/arvancloud/libinjection-rs) — [libinjection](https://github.com/client9/libinjection)的Rust绑定 [![build badge](https://api.travis-ci.org/arvancloud/libinjection-rs.svg?branch=master)](https://travis-ci.org/arvancloud/libinjection-rs)
* [ripasso](https://github.com/cortex/ripasso/) — 密码管理器，与pass兼容的文件系统
* [kpcyrd/rshijack](https://github.com/kpcyrd/rshijack) — 一个TCP连接劫持程序，用Rust对shijack进行了重写 [![build badge](https://api.travis-ci.org/kpcyrd/rshijack.svg?branch=master)](https://travis-ci.org/kpcyrd/rshijack)
* [rustscan/rustscan](https://github.com/RustScan/RustScan) — Nmap端口扫描工具的更快版本 [![build badge](https://github.com/RustScan/RustScan/workflows/Continuous%20integration/badge.svg?branch=master)](https://github.com/RustScan/RustScan/actions?query=workflow%3A%22Continuous+integration%22)
* [kpcyrd/sniffglue](https://github.com/kpcyrd/sniffglue) — 安全的多线程数据包嗅探器 [![build badge](https://api.travis-ci.org/kpcyrd/sniffglue.svg?branch=master)](https://travis-ci.org/kpcyrd/sniffglue)
* [kpcyrd/sn0int](https://github.com/kpcyrd/sn0int) — 半自动OSINT框架和程序包管理器 [![build badge](https://api.travis-ci.org/kpcyrd/sn0int.svg?branch=master)](https://travis-ci.org/kpcyrd/sn0int)
* [phra/rustbuster](https://github.com/phra/rustbuster) — 综合性的Web Fuzzer和内容发现工具
* [epi052/feroxbuster](https://github.com/epi052/feroxbuster) - 用Rust编写的简单，快速，递归的内容发现工具 (

### 系统工具

* [ajeetdsouza/zoxide](https://github.com/ajeetdsouza/zoxide/) — 可以学习你的习惯的`cd`命令快速替代工具 [![release](https://github.com/ajeetdsouza/zoxide/workflows/.github/workflows/release.yml/badge.svg)](https://github.com/ajeetdsouza/zoxide/actions)
* [bandwhich](https://github.com/imsnif/bandwhich) — 终端带宽利用率工具 [![build badge](https://api.travis-ci.com/imsnif/bandwhich.svg?branch=master)](https://travis-ci.com/imsnif/bandwhich)
* [brocode/fblog](https://github.com/brocode/fblog) — 小型命令行JSON日志查看器 [![build badge](https://api.travis-ci.org/brocode/fblog.svg?branch=master)](https://travis-ci.org/brocode/fblog)
* [buster/rrun](https://github.com/buster/rrun) — Linux的命令启动器，类似于gmrun  [![build badge](https://api.travis-ci.org/buster/rrun.svg?branch=master)](https://travis-ci.org/buster/rrun)
* [cristianoliveira/funzzy](https://github.com/cristianoliveira/funzzy) — 灵感来自[entr](http://eradman.com/entrproject/)的可配置的文件系统监控程序 [![build badge](https://api.travis-ci.org/cristianoliveira/funzzy.svg?branch=master)](https://travis-ci.org/cristianoliveira/funzzy)
* [dalance/procs](https://github.com/dalance/procs) — 用Rust编写的'ps'命令的现代替代 [![Build Status](https://api.travis-ci.org/dalance/procs.svg?branch=master)](https://travis-ci.org/dalance/procs)
* [diskonaut](https://github.com/imsnif/diskonaut) — 终端可视磁盘空间导航器 [![build badge](https://api.travis-ci.com/imsnif/diskonaut.svg?branch=main)](https://travis-ci.com/imsnif/diskonaut)
* [dust](https://github.com/bootandy/dust) — du的更直观的版本
* [ddh](https://github.com/darakian/ddh) — 快速重复文件查找器 [![build badge](https://api.travis-ci.org/darakian/ddh.svg?branch=master)](https://travis-ci.org/darakian/ddh)
* [fselect](https://crates.io/crates/fselect) — 使用类似SQL的查询查找文件 [![build badge](https://api.travis-ci.org/jhspetersson/fselect.svg?branch=master)](https://travis-ci.org/jhspetersson/fselect)
* [gitui](https://github.com/extrawurst/gitui) - 用Rust编写的git的快速客户端 [![build](https://github.com/extrawurst/gitui/workflows/CI/badge.svg?branch=master)](https://github.com/extrawurst/gitui/actions)
* [k0pernicus/zou](https://github.com/k0pernicus/zou) — 一个下载加速器
* [Kondo](https://github.com/tbillington/kondo) - CLI和GUI工具，用于删除软件项目工件并回收磁盘空间
* [lotabout/rargs](https://github.com/lotabout/rargs) [[rargs](https://crates.io/crates/rargs)] — 支持正则匹配的xargs + awk [![build badge](https://api.travis-ci.org/lotabout/rargs.svg?branch=master)](https://travis-ci.org/lotabout/rargs)
* [lotabout/skim](https://github.com/lotabout/skim) — Rust实现的模糊查找器 [![build badge](https://api.travis-ci.org/lotabout/skim.svg?branch=master)](https://travis-ci.org/lotabout/skim)
* [mitnk/cicada](https://github.com/mitnk/cicada) — 类似bash的Unix shell [![build badge](https://api.travis-ci.org/mitnk/cicada.svg?branch=master)](https://travis-ci.org/mitnk/cicada)
* [mmstick/concurr](https://github.com/mmstick/concurr) — CS体系结构的GNU Parallel的替代方案
* [mmstick/fontfinder](https://github.com/mmstick/fontfinder) — GTK3应用程序，用于预览和安装Google的字体
* [mmstick/parallel](https://github.com/mmstick/parallel) — GNU Parallel的重新实现
* [mmstick/tv-renamer](https://github.com/mmstick/tv-renamer) — 带有可选GTK3前端的电视系列重命名应用程序 [![build badge](https://api.travis-ci.org/mmstick/tv-renamer.svg?branch=master)](https://travis-ci.org/mmstick/tv-renamer)
* [organize-rt](https://gitlab.com/FixFromDarkness/organize-rt) — 根据正则表达式规则组织文件（默认情况下为文件扩展名） [![pipeline status](https://gitlab.com/FixFromDarkness/organize-rt/badges/master/pipeline.svg)](https://gitlab.com/FixFromDarkness/organize-rt/-/commits/master)
* [orhun/kmon](https://github.com/orhun/kmon) — Linux内核管理器和活动监视器 ![https://github.com/orhun/kmon/actions](https://img.shields.io/github/workflow/status/orhun/kmon/Continuous%20Integration/master?label=build)
* [Peltoche/lsd](https://github.com/Peltoche/lsd) — 具有很多漂亮颜色和精美图标的ls [![build badge](https://api.travis-ci.org/Peltoche/lsd.svg?branch=master)](https://travis-ci.org/Peltoche/lsd)
* [ogham/exa](https://github.com/ogham/exa) — 'ls'的替代实现 [![build badge](https://api.travis-ci.org/ogham/exa.svg?branch=master)](https://travis-ci.org/ogham/exa)
* [pop-os/debrep](https://github.com/pop-os/debrepbuild) — 用于构建和管理APT存储库的APT存储工具
* [pop-os/popsicle](https://github.com/pop-os/popsicle) — GTK3和CLI实用程序，用于并行刷新多个USB设备
* [pueue](https://github.com/nukesor/pueue) — 管理长时间运行的shell命令 [![GitHub Actions Workflow](https://github.com/nukesor/pueue/workflows/Test%20build/badge.svg?branch=master)](https://github.com/Nukesor/pueue/actions)
* [Luminarys/synapse](https://github.com/Luminarys/synapse) — 灵活，快速的BitTorrent守护程序 [![Build Status](https://api.travis-ci.org/Luminarys/synapse.svg?branch=master)](https://travis-ci.org/Luminarys/synapse)
* [pop-os/system76-power](https://github.com/pop-os/system76-power/) — 具有CLI工具的Linux电源管理守护程序（DBus接口）
* [mxseev/logram](https://github.com/mxseev/logram) — 将日志文件的更新推送到Telegram
* [redox-os/ion](https://github.com/redox-os/ion) — 下一代系统shell [![build badge](https://api.travis-ci.org/redox-os/ion.svg?branch=master)](https://travis-ci.org/redox-os/ion)
* [unwrittenfun/hotkey-rs](https://github.com/unwrittenfun/hotkey-rs) — Rust写的用于侦听全局热键的库
* [nivekuil/rip](https://github.com/nivekuil/rip) - 一种安全且符合人体工程学的`rm` 替代 [![build badge](https://api.travis-ci.org/nivekuil/rip.svg?branch=master)](https://travis-ci.org/nivekuil/rip)
* [sharkdp/bat](https://github.com/sharkdp/bat) — cat(1)的克隆 [![build badge](https://api.travis-ci.org/sharkdp/bat.svg?branch=master)](https://travis-ci.org/sharkdp/bat)
* [sharkdp/fd](https://github.com/sharkdp/fd) — 一种简单，快速且用户友好的find实现 [![Build Status](https://api.travis-ci.org/sharkdp/fd.svg?branch=master)](https://travis-ci.org/sharkdp/fd)
* [sitkevij/hex](https://github.com/sitkevij/hex) — 彩色的hexdump终端实用程序 [![build badge](https://api.travis-ci.org/sitkevij/hex.svg?branch=master)](https://travis-ci.org/sitkevij/hex)
* [slai11/goto](https://github.com/slai11/goto) — 一种跳转到索引目录的简单且用户友好的实现 [![GitHub Workflow Status](https://img.shields.io/github/workflow/status/slai11/goto/release)](https://github.com/slai11/goto/actions)
* [m4b/bingrep](https://github.com/m4b/bingrep) — 浏览来自各种操作系统和体系结构的二进制文件，并对它们进行着色 [![build badge](https://api.travis-ci.org/m4b/bingrep.svg?branch=master)](https://travis-ci.org/m4b/bingrep)
* [uutils/coreutils](https://github.com/uutils/coreutils) — Rust重写的跨平台GNU coreutils [![build badge](https://api.travis-ci.org/uutils/coreutils.svg?branch=master)](https://travis-ci.org/uutils/coreutils)
* [watchexec](https://github.com/watchexec/watchexec) — 执行命令以响应文件修改 [![build badge](https://api.travis-ci.org/watchexec/watchexec.svg?branch=master)](https://travis-ci.org/watchexec/watchexec)
* [XAMPPRocky/tokei](https://github.com/XAMPPRocky/tokei) — 统计代码行数 [![build badge](https://api.travis-ci.org/XAMPPRocky/tokei.svg?branch=master)](https://travis-ci.org/XAMPPRocky/tokei)
* [yake](https://crates.io/crates/yake) — Yake是基于yaml文件的任务运行器 [![build badge](https://gitlab.com/elbartus/yake/badges/master/pipeline.svg)](https://gitlab.com/elbartus/yake)
* [ytop](https://github.com/cjbassi/ytop) - 用Rust编写的TUI系统监视器 [![Build status](https://github.com/cjbassi/ytop/workflows/Rust%20CI/badge.svg?branch=master)](https://github.com/cjbassi/ytop/actions?query=workflow%3A%22Rust+CI%22)
* [cocom](https://github.com/LamdaLamdaLamda/cocom) - 用Rust编写的NTP客户端 [![Build Status](https://travis-ci.com/LamdaLamdaLamda/cocom.svg?branch=main)](https://travis-ci.com/LamdaLamdaLamda/cocom)

### 文本编辑器

* [amp](https://amp.rs) — 灵感来自Vi/Vim的工具 [![build badge](https://api.travis-ci.org/jmacdonald/amp.svg?branch=master)](https://travis-ci.org/jmacdonald/amp)
* [gchp/iota](https://github.com/gchp/iota) — 一个简单的文本编辑器 [![build badge](https://api.travis-ci.org/gchp/iota.svg?branch=master)](https://travis-ci.org/gchp/iota)
* [ilai-deutel/kibi](https://github.com/ilai-deutel/kibi) — 小型（≤1024LOC）文本编辑器，具有语法突出显示，增量搜索等功能 [![build badge](https://api.travis-ci.com/ilai-deutel/kibi.svg?branch=master)](https://travis-ci.com/ilai-deutel/kibi)
* [vamolessa/pepper](https://github.com/vamolessa/pepper) [[pepper](https://crates.io/crates/pepper)] — 个模式编辑器，可简化从终端进行的代码编辑 [![build badge](https://github.com/vamolessa/pepper/workflows/rust/badge.svg?branch=master)](https://github.com/vamolessa/pepper)
* [mathall/rim](https://github.com/mathall/rim) — 用Rust编写的类似于Vim的文本编辑器
* [ox](https://github.com/curlpipe/ox) — 一个Rust编写的文本编辑器 
* [Remacs](https://github.com/remacs/remacs) — 由社区驱动的Emacs移植到Rust [![build badge](https://api.travis-ci.org/remacs/remacs.svg?branch=master)](https://travis-ci.org/remacs/remacs)
* [xi-editor](https://github.com/xi-editor/xi-editor) — 一个现代的编辑器，其后端使用Rust编写
* [xray](https://github.com/atom-archive/xray) — 实验性的下一代基于电子的文本编辑器 [![build badge](https://api.travis-ci.org/atom/xray.svg?branch=master)](https://travis-ci.org/atom/xray)

### 文本处理

* [cpc](https://github.com/probablykasper/cpc) - 解析和计算数学字符串，支持从`1+2` 到`1% of round(1 lightyear / 14!s to km/h)`的单位和单位转换
* [grex](https://github.com/pemistahl/grex) — 一个命令行工具和库，用于从用户提供的测试用例中生成正则表达式 [![build badge](https://api.travis-ci.org/pemistahl/grex.svg?branch=master)](https://travis-ci.org/pemistahl/grex)
* [TankerHQ/ruplacer](https://github.com/TankerHQ/ruplacer) — 在源文件中查找和替换文本 [![build badge](https://api.travis-ci.org/TankerHQ/ruplacer.svg?branch=master)](https://travis-ci.org/TankerHQ/ruplacer)
* [ripgrep](https://crates.io/crates/ripgrep) — 结合了Silver Searcher的可用性和grep的原始速度的工具 [![build badge](https://api.travis-ci.org/BurntSushi/ripgrep.svg?branch=master)](https://travis-ci.org/BurntSushi/ripgrep)
* [phiresky/ripgrep-all](https://github.com/phiresky/ripgrep-all) — ripgrep，但也可以搜索PDF，电子书，Office文档，zip，tar.gz等 [![Build Status](https://api.travis-ci.org/phiresky/ripgrep-all.svg?branch=master)](https://travis-ci.org/phiresky/ripgrep-all)
* [replicadse/complate](https://github.com/replicadse/complate) — 一种终端内文本模板工具，旨在标准化消息（例如用于GIT提交） [![crates.io](https://img.shields.io/crates/v/complate.svg)](https://crates.io/crates/complate) [![crates.io](https://img.shields.io/crates/d/complate?label=crates.io%20downloads)](https://crates.io/crates/complate) [![build badge](https://github.com/replicadse/complate/workflows/pipeline/badge.svg?branch=master)](https://github.com/replicadse/complate/actions)
* [sd](https://crates.io/crates/sd) — 直观的查找和替换CLI
* [lavifb/todo_r](https://github.com/lavifb/todo_r) — 用一个命令查找所有待办事项! [![build badge](https://api.travis-ci.org/lavifb/todo_r.svg?branch=master)](https://travis-ci.org/lavifb/todo_r)
* [whitfin/runiq](https://github.com/whitfin/runiq) — 一种有效的方法，可从未排序的输入中过滤出重复的行
* [whitfin/bytelines](https://github.com/whitfin/bytelines) — 将输入行作为字节片读取，以提高效率
* [vishaltelangre/ff](https://github.com/vishaltelangre/ff) — 按名称查找文件（ff） [![build badge](https://api.travis-ci.org/vishaltelangre/ff.svg?branch=master)](https://travis-ci.org/vishaltelangre/ff)
* [xsv](https://crates.io/crates/xsv) — 快速CSV命令行工具（切片，索引，选择，搜索，采样等） [![build badge](https://api.travis-ci.org/BurntSushi/xsv.svg?branch=master)](https://travis-ci.org/BurntSushi/xsv)
* [Lisprez/so_stupid_search](https://github.com/Lisprez/so_stupid_search) — 一种简单，快速的字符串搜索工具

### 图像处理

* [Imager](https://github.com/imager-io/imager) — 自动图形优化

### 实用工具

* [aleshaleksey/AZDice](https://github.com/aleshaleksey/AZDice) — 骰子掷骰生成器 [![build badge](https://api.travis-ci.org/aleshaleksey/AZDice.svg?branch=master)](https://travis-ci.org/aleshaleksey/AZDice)
* [yaa110/cb](https://github.com/yaa110/cb) — 用于管理剪贴板的命令行界面 [![Build Status](https://api.travis-ci.org/yaa110/cb.svg?branch=master)](https://travis-ci.org/yaa110/cb)
* [brycx/checkpwn](https://github.com/brycx/checkpwn) — 一个“我曾经被拥有”（HIBP）命令行实用工具，可让您轻松检查受到破坏的帐户和密码
* [vamolessa/copycat](https://github.com/vamolessa/copycat) [[copycat](https://crates.io/crates/copycat)] — 支持文本和bmp的Windows的简单剪贴板cli界面
* [evansmurithi/cloak](https://github.com/evansmurithi/cloak) — 一个命令行OTP（一次性密码）身份验证器应用程序 [![build badge](https://api.travis-ci.com/evansmurithi/cloak.svg?branch=master)](https://travis-ci.com/evansmurithi/cloak) [![build badge](https://ci.appveyor.com/api/projects/status/9mlfpfru3ng4c689/branch/master?svg=true)](https://ci.appveyor.com/project/evansmurithi/cloak)
* [replydev/cotp](https://github.com/replydev/cotp) - 与外部备份兼容的可信加密一次性密码验证器应用程序 [![Actions Status](https://github.com/replydev/cotp/workflows/Rust/badge.svg)](https://github.com/replydev/cotp/actions)
* [arthrp/consoletimer](https://github.com/arthrp/consoleTimer) — 面向终端的简单计时器 [![build badge](https://api.travis-ci.org/arthrp/consoleTimer.svg?branch=master)](https://travis-ci.org/arthrp/consoleTimer)
* [tversteeg/emplace](https://github.com/tversteeg/emplace) — 同步多台计算机上已安装的软件包
* [myfreeweb/freepass](https://github.com/myfreeweb/freepass) — 适用于高级用户的免费密码管理器
* [yoannfleurydev/gitweb](https://github.com/yoannfleurydev/gitweb) — 在浏览器中打开当前的远程存储库 [![GitHub Actions](https://github.com/yoannfleurydev/gitweb/workflows/Publish/badge.svg?branch=master)](https://github.com/yoannfleurydev/gitweb/actions)
* [mme](https://github.com/GoberInfinity/mme) — 记住您有时忘记的命令的命令行工具 [![Build Status](https://api.travis-ci.org/GoberInfinity/mme.svg?branch=master)](https://travis-ci.org/GoberInfinity/mme)
* [raftario/licensor](https://github.com/raftario/licensor) — 将许可证写入stdout [![GitHub Actions](https://github.com/raftario/licensor/workflows/Build/badge.svg?branch=master)](https://github.com/raftario/licensor/actions?workflowID=Build)
* [arthrp/quick-skeleton](https://github.com/arthrp/quick-skeleton) — 项目脚手架工具，类似于Yeoman和Slush [![build badge](https://api.travis-ci.org/arthrp/quick-skeleton.svg?branch=master)](https://travis-ci.org/arthrp/quick-skeleton)
* [repoch](https://github.com/lucawen/repoch) — 将epoch转换为日期时间，并将日期时间转换为epoch [![build badge](https://api.travis-ci.com/lucawen/repoch.svg?branch=master)](https://travis-ci.com/lucawen/repoch/)
* [whitfin/s3-concat](https://github.com/whitfin/s3-concat) — 一种命令行工具，可使用灵活的模式远程连接AmazonS3文件
* [whitfin/s3-meta](https://github.com/whitfin/s3-meta) — 一种命令行工具，用于收集有关您的AmazonS3存储桶的元数据
* [whitfin/s3-utils](https://github.com/whitfin/s3-utils) — 一个小型工具，其中包含基于AmazonS3的实用程序，以提供其他便利API
* [gorros/s3-edit-rs](https://github.com/gorros/s3-edit-rs) — 一个命令行工具，可直接在AmazonS3上编辑文件
* [fcsonline/tmux-thumbs](https://github.com/fcsonline/tmux-thumbs) — 用Rust编写的tmux-fingers的闪电般快速版本，像vimium/vimperator一样复制/粘贴
* [amar-laksh/workstation](https://github.com/amar-laksh/workstation) — 一个命令行工具，可通过使您与屏幕保持一定距离来帮助您管理工作站，并在您不使用OPENCV时锁定屏幕（不包括屏幕）！
* [guoxbin/dtool](https://github.com/guoxbin/dtool) — 一个有用的命令行工具集合，以帮助开发，包括转换，编解码器，哈希，加密等 [![Build Status](https://api.travis-ci.org/guoxbin/dtool.svg?branch=master)](https://travis-ci.org/guoxbin/dtool)
* [nomino](https://github.com/yaa110/nomino) — 开发人员的批量重命名实用程序 [![Build Status](https://api.travis-ci.org/yaa110/nomino.svg?branch=master)](https://travis-ci.org/yaa110/nomino)
* [barberousse](https://github.com/zeapo/barberousse) — -AWS Secrets Manager编辑器 ![build](https://github.com/zeapo/barberousse/workflows/build/badge.svg?branch=master)
* [vamolessa/verco](https://github.com/vamolessa/verco) [[verco](https://crates.io/crates/verco)] — 一个专注于键盘快捷键的简单Git/Hg tui客户端

### 视频

* [Phate6660/rsmpv](https://github.com/Phate6660/rsmpv) — MPV的控制器，要求在MPV中启用IPC
* [tgotwig/vidmerger](https://github.com/tgotwig/vidmerger) —  ffmpeg周围的包装器，可简化多个视频的合并🎞
* [xiph/rav1e](https://github.com/xiph/rav1e) — 最快，最安全的AV1编码器 [![build badge](https://api.travis-ci.org/xiph/rav1e.svg?branch=master)](https://travis-ci.org/xiph/rav1e)
* [yuvadm/slingr](https://github.com/yuvadm/slingr) — 一个简单的CLI，用于通过本地网络将媒体文件流式传输到UPnP媒体渲染器 [![build badge](https://api.travis-ci.org/yuvadm/slingr.svg?branch=master)](https://travis-ci.org/yuvadm/slingr)
* [yuvadm/streamlib](https://github.com/streamlib/streamlib) — 从命令行播放您喜欢的实时视频和音频流

### 虚拟化

* [firecracker-microvm/firecracker](https://github.com/firecracker-microvm/firecracker) — 用于容器工作负载的轻型虚拟机 [Firecracker Microvm](https://firecracker-microvm.github.io/)
* [oracle/railcar](https://github.com/oracle/railcar) — Rust实现的类似Docker的容器OCI运行时实现 [![wercker status](https://app.wercker.com/status/730e874772dc02c6005f4ae4e42b0ca4/s/master "wercker status")](https://app.wercker.com/applications/59696a02ee70670100155ae2 )
* [tailhook/vagga](https://github.com/tailhook/vagga) — 不用守护程序的容器化工具 [![build badge](https://api.travis-ci.org/tailhook/vagga.svg?branch=master)](https://travis-ci.org/tailhook/vagga)

### 网页

* [Plume-org/Plume](https://github.com/Plume-org/Plume) — ActivityPub联合博客应用程序 [![build badge](https://api.travis-ci.org/Plume-org/Plume.svg?branch=master)](https://travis-ci.org/Plume-org/Plume)
* [LemmyNet/lemmy](https://github.com/LemmyNet/lemmy) — fediverse的链接聚合器 [![Build Status](https://api.travis-ci.org/LemmyNet/lemmy.svg?branch=master)](https://travis-ci.org/LemmyNet/lemmy)

### Web服务器

* [mufeedvh/binserve](https://github.com/mufeedvh/binserve) — 一种非常快速的静态Web服务器，在单个二进制文件中具有路由，模板和安全性，您可以使用零代码进行设置 [![build badge](https://github.com/mufeedvh/binserve/workflows/CICD/badge.svg?branch=master)](https://github.com/mufeedvh/binserve/actions)
* [thecoshman/http](https://github.com/thecoshman/http) — 请托管这些东西—基本的http服务器，用于快速，简单地托管文件夹 [![build badge](https://api.travis-ci.org/thecoshman/http.svg?branch=master)](https://travis-ci.org/thecoshman/http)
* [svenstaro/miniserve](https://github.com/svenstaro/miniserve) — 一个小型，独立的跨平台CLI工具，使您可以抓取二进制文件并通过HTTP服务一些文件 [![build badge](https://github.com/svenstaro/miniserve/workflows/CI/badge.svg?branch=master)](https://github.com/svenstaro/miniserve/actions)
* [TheWaWaR/simple-http-server](https://github.com/TheWaWaR/simple-http-server) — 简单的静态http服务器
* [wyhaya/see](https://github.com/wyhaya/see) — 静态HTTP文件服务器 [![Build Status](https://api.travis-ci.org/wyhaya/see.svg?branch=master)](https://travis-ci.org/wyhaya/see)
* [ronanyeah/rust-hasura](https://github.com/ronanyeah/rust-hasura) — 演示如何将Rust GraphQL服务器用作Hasura的远程模式 [Hasura](https://hasura.io/) ![Rust](https://github.com/ronanyeah/rust-hasura/workflows/Rust/badge.svg?branch=master)

## 开发工具

* [clippy](https://crates.io/crates/clippy) — Rust lint检查项 [![build badge](https://api.travis-ci.com/rust-lang/rust-clippy.svg?branch=master)](https://travis-ci.org/rust-lang/rust-clippy)
* [clog-tool/clog-cli](https://github.com/clog-tool/clog-cli) — 从git元数据生成更改日志（传统的changelog）([传统的changelog](https://blog.thoughtram.io/announcements/tools/2014/09/18/announcing-clog-a-conventional-changelog-generator-for-the-rest-of-us.html)) [![build badge](https://api.travis-ci.org/clog-tool/clog-cli.svg?branch=master)](https://travis-ci.org/clog-tool/clog-cli)
* [dan-t/rusty-tags](https://github.com/dan-t/rusty-tags) — 为cargo项目及其所有依赖项创建ctags/etags [![build badge](https://api.travis-ci.org/dan-t/rusty-tags.svg?branch=master)](https://travis-ci.org/dan-t/rusty-tags)
* [datanymizer/datanymizer](https://github.com/datanymizer/datanymizer) - 具有灵活规则的强大数据库匿名器 [![build badge](https://github.com/datanymizer/datanymizer/workflows/CI/badge.svg?branch=main)](https://github.com/datanymizer/datanymizer/actions?query=workflow%3ACI+branch%3Amain)
* [delta](https://crates.io/crates/git-delta) — git和diff输出的语法高亮显示 [![build badge](https://api.travis-ci.com/dandavison/delta.svg?branch=master)](https://travis-ci.com/dandavison/delta)
* [dotenv-linter](https://github.com/dotenv-linter/dotenv-linter) — `.env`文件的拼写检查器 [![build badge](https://github.com/dotenv-linter/dotenv-linter/workflows/CI/badge.svg?branch=master)](https://github.com/dotenv-linter/dotenv-linter/actions?query=workflow%3ACI+branch%3Amaster)
* [frewsxcv/crate-deps](https://github.com/frewsxcv/crate-deps) — 为托管在crates.io上的机箱生成依赖关系图
* [geiger](https://github.com/rust-secure-code/cargo-geiger) — 一个程序，该程序列出Rust代码的不安全用法 [![Build Status](https://dev.azure.com/cargo-geiger/cargo-geiger/_apis/build/status/rust-secure-code.cargo-geiger?branchName=master)](https://dev.azure.com/cargo-geiger/cargo-geiger/_build/latest?definitionId=1&branchName=master)
* [git-journal](https://github.com/saschagrunert/git-journal/) — Git提交信息和变更日志的生成框架 [![build badge](https://api.travis-ci.org/saschagrunert/git-journal.svg?branch=master)](https://travis-ci.org/saschagrunert/git-journal)
* [gstats](https://github.com/boonshift/gstats/) — 命令行工具，用于在当前目录下打印所有git仓库的开发人员摘要
* [rust-lang/rustfix](https://github.com/rust-lang/rustfix)  — 自动应用rustc的建议
* [just](https://github.com/casey/just) — 一个方便的命令运行程序，用于执行特定于项目的任务 [![build badge](https://api.travis-ci.org/casey/just.svg?branch=master)](https://travis-ci.org/casey/just)
* [mask](https://github.com/jakedeichert/mask) — 由简单的markdown文件定义的CLI任务运行程序 [![build badge](https://github.com/jakedeichert/mask/workflows/CI/badge.svg?branch=master)](https://github.com/jakedeichert/mask/actions?query=workflow%3ACI)
* [Module Linker](https://github.com/fiatjaf/module-linker) — 在GitHub `mod`, `use` 和`extern crate` 声明中增加了`<a>` 链接引用的扩展
* [ptags](https://github.com/dalance/ptags) — git仓库的并行通用ctags包装器 [![Build Status](https://api.travis-ci.org/dalance/ptags.svg?branch=master)](https://travis-ci.org/dalance/ptags)
* [Racer](https://github.com/racer-rust/racer) — Rust的代码补全 [![build badge](https://api.travis-ci.org/racer-rust/racer.svg?branch=master)](https://travis-ci.org/racer-rust/racer)
* [rustfmt](https://github.com/rust-lang/rustfmt) — Rust代码格式化程序 [![build badge](https://api.travis-ci.com/rust-lang/rustfmt.svg?branch=master)](https://travis-ci.com/rust-lang/rustfmt)
* [Rustup](https://github.com/rust-lang/rustup) — Rust工具链安装程序 [![build badge](https://github.com/rust-lang/rustup/workflows/Linux%20(master)/badge.svg?branch=master)](https://github.com/rust-lang/rustup/actions)
* [Rust Language Server](https://github.com/rust-lang/rls) — 在后台运行的服务器，为IDE，编辑器和其他工具提供有关Rust程序的信息
* [Rust Regex Playground](https://2fd.github.io/rust-regex-playground/#method=find&regex=%5Cw%2B&text=abc) — 用于评估rust正则表达式的Web工具
* [Rust Search Extension](https://github.com/huhu/rust-search-extension) — 方便的浏览器扩展程序，用于在地址栏（多功能框）中搜索装箱和文档 [![Build Status](https://github.com/huhu/rust-search-extension/workflows/build/badge.svg?branch=master)](https://github.com/huhu/rust-search-extension/actions)
* [artifact](https://github.com/vitiral/artifact) — 为开发人员设计的设计文档工具 [![Build Status](https://api.travis-ci.org/vitiral/artifact.svg?branch=master)](https://travis-ci.org/vitiral/artifact)
* [semantic-rs](https://github.com/semantic-rs/semantic-rs) — 自动装箱发布 [![build badge](https://api.travis-ci.org/semantic-rs/semantic-rs.svg?branch=master)](https://travis-ci.org/semantic-rs/semantic-rs)
* [fw](https://github.com/brocode/fw) — 工作区生产力的助推器 [![build badge](https://api.travis-ci.org/brocode/fw.svg?branch=master)](https://travis-ci.org/brocode/fw)
* [tinyrick](https://github.com/mcandre/tinyrick) 一个基本的任务依赖工具，它着重于原始shell命令之上的Rust功能
* [scriptisto](https://github.com/igor-petruk/scriptisto) 一种与语言无关的"shebang解释器", 使您可以用已编译的语言编写一个文件脚本 [![Build Status](https://cloud.drone.io/api/badges/igor-petruk/scriptisto/status.svg)](https://cloud.drone.io/igor-petruk/scriptisto)

### 构建系统

* [Cargo](https://crates.io/) — Rust包管理器
  * [cargo-benchcmp](https://crates.io/crates/cargo-benchcmp) — 用于比较Rust微型基准的实用程序 [![build badge](https://api.travis-ci.org/BurntSushi/cargo-benchcmp.svg?branch=master)](https://travis-ci.org/BurntSushi/cargo-benchcmp)
  * [cargo-bitbake](https://crates.io/crates/cargo-bitbake) — 一种包管理器的扩展，可以利用meta-rust中的类生成BitBake条目 [![build badge](https://api.travis-ci.org/cardoe/cargo-bitbake.svg?branch=master)](https://travis-ci.org/cardoe/cargo-bitbake)
  * [cargo-cache](https://crates.io/crates/cargo-cache) — 检查/管理/清洁您的包管理缓存（~/.cargo// ${CARGO_HOME}），打印尺寸等 [![Build Status](https://github.com/matthiaskrgr/cargo-cache/workflows/ci/badge.svg?branch=master)](https://github.com/matthiaskrgr/cargo-cache/actions)
  * [cargo-check](https://crates.io/crates/cargo-check) — `cargo rustc -- -Zno-trans` 包装器，如果您只需要进行正确性检查，则可更快的编译程序 [![build badge](https://api.travis-ci.org/rsolomo/cargo-check.svg?branch=master)](https://travis-ci.org/rsolomo/cargo-check)
  * [cargo-count](https://crates.io/crates/cargo-count) — 列出cargo项目的源代码行数和详细信息，包括不安全的统计信息 [![build badge](https://api.travis-ci.org/kbknapp/cargo-count.svg?branch=master)](https://travis-ci.org/kbknapp/cargo-count)
  * [cargo-deb](https://crates.io/crates/cargo-deb) — 生成二进制Debian软件包 [![build badge](https://api.travis-ci.org/mmstick/cargo-deb.svg?branch=master)](https://travis-ci.org/mmstick/cargo-deb)
  * [cargo-deps](https://crates.io/crates/cargo-deps) — 构建Rust项目的依赖图 [![build badge](https://api.travis-ci.com/m-cat/cargo-deps.svg?branch=master)](https://travis-ci.org/m-cat/cargo-deps)
  * [cargo-do](https://crates.io/crates/cargo-do) — 连续运行多个cargo命令 [![build badge](https://api.travis-ci.org/pwoolcoc/cargo-do.svg?branch=master)](https://travis-ci.org/pwoolcoc/cargo-do)
  * [cargo-ebuild](https://crates.io/crates/cargo-ebuild) — 使用in-tree eclasses来生成ebuilds的cargo扩展 [![build badge](https://api.travis-ci.org/cardoe/cargo-ebuild.svg?branch=master)](https://travis-ci.org/cardoe/cargo-ebuild)
  * [cargo-edit](https://crates.io/crates/cargo-edit) — 允许您通过从命令行读取/写入Cargo.toml文件来添加和列出依赖项 [![build badge](https://api.travis-ci.org/killercup/cargo-edit.svg?branch=master)](https://travis-ci.org/killercup/cargo-edit)
  * [cargo-generate](https://github.com/cargo-generate/cargo-generate) 通过利用预先存在的git仓库作为模板来生成Rust项目的生成器
  * [cargo-get](https://crates.io/crates/cargo-get) - Cargo插件可轻松查询Cargo.toml文件中的信息 ![GitHub Workflow Status](https://img.shields.io/github/workflow/status/nicolaiunrein/cargo-get/CI)
  * [cargo-graph](https://crates.io/crates/cargo-graph) — `cargo-dot` 具有其他功能的更新的fork。无需维护，请参阅`cargo-deps` [![build badge](https://api.travis-ci.org/kbknapp/cargo-graph.svg?branch=master)](https://travis-ci.org/kbknapp/cargo-graph)
  * [cargo-info](https://crates.io/crates/cargo-info) — 从命令行查询crates.io以获crate详细信息 [![build badge](https://api.travis-ci.org/imp/cargo-info.svg?branch=master)](https://travis-ci.org/imp/cargo-info)
  * [cargo-license](https://crates.io/crates/cargo-license) — cargo子命令，用于快速查看所有依赖项的许可信息 [![build badge](https://api.travis-ci.org/onur/cargo-license.svg?branch=master)](https://travis-ci.org/onur/cargo-license)
  * [cargo-make](https://crates.io/crates/cargo-make) — Rust任务运行器和构建工具 [![build badge](https://api.travis-ci.org/sagiegurari/cargo-make.svg?branch=master)](https://travis-ci.org/sagiegurari/cargo-make)
  * [cargo-modules](https://crates.io/crates/cargo-modules) — 一个cargo插件，用于显示crate模块的树状概览 [![build badge](https://api.travis-ci.org/regexident/cargo-modules.svg?branch=master)](https://travis-ci.org/regexident/cargo-modules)
  * [cargo-multi](https://crates.io/crates/cargo-multi) — 在多个crate上运行指定的cargo命令 [![build badge](https://api.travis-ci.org/imp/cargo-multi.svg?branch=master)](https://travis-ci.org/imp/cargo-multi)
  * [cargo-outdated](https://crates.io/crates/cargo-outdated) — 当有新版本的Rust依赖项可用或已过期时提示 [![build badge](https://api.travis-ci.org/kbknapp/cargo-outdated.svg?branch=master)](https://travis-ci.org/kbknapp/cargo-outdated)
  * [cargo-release](https://crates.io/crates/cargo-release) — 用于发布由git管理的cargo项目，构建，标记，发布，文档和推送的工具 [![build badge](https://api.travis-ci.org/sunng87/cargo-release.svg?branch=master)](https://travis-ci.org/sunng87/cargo-release)
  * [cargo-script](https://crates.io/crates/cargo-script) — 使人们可以快速轻松地运行Rust的“scripts”，这些脚本可以利用Cargo包生态圈 [![build badge](https://api.travis-ci.org/DanielKeep/cargo-script.svg?branch=master)](https://travis-ci.org/DanielKeep/cargo-script)
  * [cargo-testify](https://crates.io/crates/cargo-testify) — 通过友好的OS通知监视文件更改，运行测试并通知结果 [![build badge](https://api.travis-ci.org/greyblake/cargo-testify.svg?branch=master)](https://travis-ci.org/greyblake/cargo-testify)
  * [cargo-tree](https://github.com/sfackler/cargo-tree) – Cargo子命令，以树状格式可视化crate的依存关系图 [![CircleCI](https://circleci.com/gh/sfackler/cargo-tree.svg?style=shield)](https://app.circleci.com/pipelines/github/sfackler/cargo-tree)
  * [cargo-update](https://crates.io/crates/cargo-update) — 用于检查并将更新应用于已安装的可执行文件的cargo子命令 [![build badge](https://api.travis-ci.org/nabijaczleweli/cargo-update.svg?branch=master)](https://travis-ci.org/nabijaczleweli/cargo-update)
  * [cargo-watch](https://crates.io/crates/cargo-watch) — 实用cargo程序，用于在源发生更改时编译项目 [![build badge](https://api.travis-ci.org/passcod/cargo-watch.svg?branch=master)](https://travis-ci.org/passcod/cargo-watch)
  * [liuchong/cargo-x](https://github.com/liuchong/cargo-x) — 一个非常简单的第三方cargo子命令，用于执行自定义命令 [![build badge](https://api.travis-ci.org/liuchong/cargo-x.svg?branch=master)](https://travis-ci.org/liuchong/cargo-x)
  * [dtolnay/cargo-expand](https://github.com/dtolnay/cargo-expand) — 在源代码中扩展宏
* CMake
  * [Devolutions/CMakeRust](https://github.com/Devolutions/CMakeRust) — 用于将Rust库集成到CMake项目中
  * [SiegeLord/RustCMake](https://github.com/SiegeLord/RustCMake) — 一个示例项目，展示CMake与Rust的结合使用 [![build badge](https://api.travis-ci.org/SiegeLord/RustCMake.svg?branch=master)](https://travis-ci.org/SiegeLord/RustCMake)
* Github actions
  * [icepuma/rust-action](https://github.com/icepuma/rust-action) — Rust github动作
  * [peaceiris/actions-mdbook](https://github.com/peaceiris/actions-mdbook) — mdBook的GitHub操作
* GitHub webhooks
  * [snare](https://tratt.net/laurie/src/snare/) — GitHub webhooks运行程序守护程序
* Webpack
  * [mxseev/rust-loader](https://github.com/mxseev/rust-loader) — Webpack Rust加载程序（wasm）

### 调试

* GDB
  * [rust-gdb](https://github.com/rust-lang/rust/blob/master/src/etc/rust-gdb)
  * [gdbgui](https://github.com/cs01/gdbgui) — 基于浏览器的gdb前端，用于调试C，C++，Rust和go [![build badge](https://api.travis-ci.org/cs01/gdbgui.svg?branch=master)](https://travis-ci.org/cs01/gdbgui)
* LLDB
  * [lldb_batchmode.py](https://github.com/rust-lang/rust/blob/master/src/etc/lldb_batchmode.py) — 允许以类似于GDB批处理模式的方式使用LLDB
  * [CodeLLDB](https://marketplace.visualstudio.com/items?itemName=vadimcn.vscode-lldb) — [Visual Studio Code](https://code.visualstudio.com/)的LLDB扩展

### 部署

* Docker
  * [emk/rust-musl-builder](https://github.com/emk/rust-musl-builder) — 使用musl-libc和musl-gcc以及静态版本的C库，编译静态Rust二进制文件的Docker镜像
  * [kpcyrd/mini-docker-rust](https://github.com/kpcyrd/mini-docker-rust) — 很小的rust docker镜像的示例工程 [![build badge](https://api.travis-ci.org/kpcyrd/mini-docker-rust.svg?branch=master)](https://travis-ci.org/kpcyrd/mini-docker-rust)
  * [liuchong/docker-rustup](https://github.com/liuchong/docker-rustup) — 多个版本（带有Musl工具）Rust Docker镜像
  * [messense/rust-musl-cross](https://github.com/messense/rust-musl-cross) — 用于使用musl-cross编译静态Rust二进制文件的Docker镜像 [![build badge](https://api.travis-ci.org/messense/rust-musl-cross.svg?branch=master)](https://travis-ci.org/messense/rust-musl-cross)
  * [rust-lang-nursery/docker-rust](https://github.com/rust-lang/docker-rust) — 官方Rust Docker镜像
* Github Pages
  * [wasm-template-rust](https://github.com/sn99/wasm-template-rust) — Wasm模板，Rust无需npm-deploy即可发布到gh页 [![Build Status](https://travis-ci.com/sn99/wasm-template-rust.svg?branch=master)](https://travis-ci.com/sn99/wasm-template-rust)
* Google App Engine
  * [DenisKolodin/rust-app-engine](https://github.com/DenisKolodin/rust-app-engine) — App Engine Rust样板
* Heroku
  * [emk/heroku-buildpack-rust](https://github.com/emk/heroku-buildpack-rust) — 用于Heroku上Rust应用程序的构建包

### 嵌入式

[Rust嵌入式](https://rust-embedded.org/)

* 交叉编译
  * [japaric/rust-cross](https://github.com/japaric/rust-cross) — 关于交叉编译Rust程序，您需要了解的所有信息 [![build badge](https://api.travis-ci.org/japaric/rust-cross.svg?branch=master)](https://travis-ci.org/japaric/rust-cross)
  * [japaric/xargo](https://github.com/japaric/xargo) — 轻松地将Rust程序交叉编译到定制的裸机目标，如ARM Cortex-M [![build badge](https://api.travis-ci.org/japaric/xargo.svg?branch=master)](https://travis-ci.org/japaric/xargo)
* 树莓派
  * [Ogeon/rust-on-raspberry-pi](https://github.com/Ogeon/rust-on-raspberry-pi) — 有关如何为树莓派交叉编译Rust项目的说明
* Arduino
  * [avr-rust/ruduino](https://github.com/avr-rust/ruduino) Arduino的可重用组件

### 语言交互接口FFI

* C
  * [rlhunt/cbindgen](https://github.com/eqrion/cbindgen) — 从Rust源文件生成C头文件。在Gecko中用于WebRender [![build badge](https://api.travis-ci.org/eqrion/cbindgen.svg?branch=master)](https://travis-ci.org/eqrion/cbindgen)
  * [Sean1708/rusty-cheddar](https://github.com/Sean1708/rusty-cheddar) — 从Rust源文件生成C头文件 [![build badge](https://api.travis-ci.org/Sean1708/rusty-cheddar.svg?branch=master)](https://travis-ci.org/Sean1708/rusty-cheddar)
* C++
  * [rust-lang/rust-bindgen](https://github.com/rust-lang/rust-bindgen) — Rust绑定生成器
  * [dtolnay/cxx](https://github.com/dtolnay/cxx) — Rust和C++之间的安全互操作 [![build badge](https://img.shields.io/badge/github-dtolnay/cxx-8da0cb?style=for-the-badge&labelColor=555555&logo=github)](https://github.com/dtolnay/cxx)
  * [rust-cpp](https://crates.io/crates/cpp) - 将C++代码直接嵌入Rust中 [![Build Status](https://api.travis-ci.org/mystor/rust-cpp.svg?branch=master)](https://travis-ci.org/mystor/rust-cpp) [![Build status](https://ci.appveyor.com/api/projects/status/uu76vmcrwnjqra0u/branch/master?svg=true)](https://ci.appveyor.com/project/mystor/rust-cpp/branch/master)
* Erlang
  * [rusterlium/rustler](https://github.com/rusterlium/rustler) — 用于创建Erlang NIF函数的安全Rust桥接 [![build badge](https://api.travis-ci.org/rusterlium/rustler.svg?branch=master)](https://travis-ci.org/rusterlium/rustler)
* Haskell
  * [mgattozzi/curryrs](https://github.com/mgattozzi/curryrs) — 弥补Haskell和Rust之间的鸿沟
  * [mgattozzi/haskellrs](https://github.com/mgattozzi/haskellrs) — Rust in Haskell FFI示例
  * [mgattozzi/rushs](https://github.com/mgattozzi/rushs) — Haskell in Rust FFI示例
* Java
  * [j4rs](https://crates.io/crates/j4rs) — use Java from Rust [![build badge](https://api.travis-ci.org/astonbitecode/j4rs.svg?branch=master)](https://travis-ci.org/astonbitecode/j4rs)
  * [bennettanderson/rjni](https://github.com/benanders/rjni) — Rust中使用Java
  * [drrb/java-rust-example](https://github.com/drrb/java-rust-example) — Java使用Rust [![build badge](https://api.travis-ci.org/drrb/java-rust-example.svg?branch=master)](https://travis-ci.org/drrb/java-rust-example)
  * [jni](https://crates.io/crates/jni) — Java使用Rust [![build badge](https://api.travis-ci.org/jni-rs/jni-rs.svg?branch=master)](https://travis-ci.org/jni-rs/jni-rs)
  * [jni-sys](https://crates.io/crates/jni-sys) — 对应于jni.h的Rust定义 [![build badge](https://api.travis-ci.org/sfackler/rust-jni-sys.svg?branch=master)](https://travis-ci.org/sfackler/rust-jni-sys)
  * [rucaja](https://crates.io/crates/rucaja) — Rust中使用Java [![build badge](https://api.travis-ci.org/kud1ing/rucaja.svg?branch=master)](https://travis-ci.org/kud1ing/rucaja)
  * [rawrafox/rust-jdbc](https://github.com/rawrafox/rust-jdbc) — Rust中使用JDBC
* Lua
  * [jcmoyer/rust-lua53](https://github.com/jcmoyer/rust-lua53) — Rust的Lua 5.3绑定 [![build badge](https://api.travis-ci.org/jcmoyer/rust-lua53.svg?branch=master)](https://travis-ci.org/jcmoyer/rust-lua53)
  * [lilyball/rust-lua](https://github.com/lilyball/rust-lua) — Lua 5.1的Rust安全绑定 [![build badge](https://api.travis-ci.org/lilyball/rust-lua.svg?branch=master)](https://travis-ci.org/lilyball/rust-lua)
  * [tickbh/td_rlua](https://github.com/tickbh/td_rlua) — Rust的零成本高级lua 5.3包装器 [![build badge](https://api.travis-ci.org/tickbh/td_rlua.svg?branch=master)](https://travis-ci.org/tickbh/td_rlua)
  * [tomaka/hlua](https://github.com/tomaka/hlua) — 与Lua交互的Rust库 [![build badge](https://api.travis-ci.org/tomaka/hlua.svg?branch=master)](https://travis-ci.org/tomaka/hlua)
* mruby
  * [anima-engine/mrusty](https://github.com/anima-engine/mrusty) — 用于Rust的mruby安全绑定 [![build badge](https://api.travis-ci.org/anima-engine/mrusty.svg?branch=master)](https://travis-ci.org/anima-engine/mrusty)
* Node.js
  * [neon-bindings/neon](https://github.com/neon-bindings/neon) — 用于编写安全且快速的本机Node.js模块的Rust绑定 [![build badge](https://api.travis-ci.org/neon-bindings/neon.svg?branch=master)](https://travis-ci.org/neon-bindings/neon)
  * [infinyon/node-bindgen](https://github.com/infinyon/node-bindgen) - 使用Rust生成nodejs模块的简单方法
* Objective-C
  * [SSheldon/rust-objc](https://github.com/SSheldon/rust-objc) — Rust的Objective-C运行时绑定和包装
* Perl
  * [vickenty/mi-rust](https://github.com/vickenty/mi-rust) — 为M::I添加了对使用Cargo构建模块的支持
  * [vickenty/perl-xs](https://github.com/vickenty/perl-xs) — 使用Rust创建Perl XS模块 [![build badge](https://api.travis-ci.org/vickenty/perl-xs.svg?branch=master)](https://travis-ci.org/vickenty/perl-xs)
* Python
  * [getsentry/milksnake](https://github.com/getsentry/milksnake) — python setuptools的扩展，允许您以可想象的最可移植的方式在Python wheels中分发动态链接库
  * [dgrunwald/rust-cpython](https://github.com/dgrunwald/rust-cpython) — Python绑定 [![build badge](https://api.travis-ci.org/dgrunwald/rust-cpython.svg?branch=master)](https://travis-ci.org/dgrunwald/rust-cpython)
  * [PyO3/PyO3](https://github.com/PyO3/PyO3) — Python解释器的Rust绑定 [![build badge](https://api.travis-ci.org/PyO3/pyo3.svg?branch=master)](https://travis-ci.org/PyO3/pyo3)
* Ruby
  * [d-unseductable/ruru](https://github.com/d-unseductable/ruru) — 用Rust编写的本机Ruby扩展 [![build badge](https://api.travis-ci.org/d-unseductable/ruru.svg?branch=master)](https://travis-ci.org/d-unseductable/ruru)
  * [danielpclark/rutie](https://github.com/danielpclark/rutie) — 用Rust编写的本机Ruby扩展，反之亦然 [![Build Status](https://api.travis-ci.org/danielpclark/rutie.svg?branch=master)](https://travis-ci.org/danielpclark/rutie)
  * [tildeio/helix](https://github.com/tildeio/helix) — 在Rust中编写Ruby类 [![build badge](https://api.travis-ci.org/tildeio/helix.svg?branch=master)](https://travis-ci.org/tildeio/helix)
* Web Assembly
  * [rustwasm/wasm-pack](https://github.com/rustwasm/wasm-pack) — :package: :sparkles: 打包wasm并将其发布到npm! [![build badge](https://api.travis-ci.com/rustwasm/wasm-pack.svg?branch=master)](https://travis-ci.org/rustwasm/wasm-pack)
  * [rustwasm/wasm-bindgen](https://github.com/rustwasm/wasm-bindgen) — 一个项目，用于促进wasm模块和JS之间的高层交互 [![build badge](https://api.travis-ci.com/rustwasm/wasm-bindgen.svg?branch=master)](https://travis-ci.org/rustwasm/wasm-bindgen)
  * [rhysd/wain](https://github.com/rhysd/wain) - wain: WebAssembly解释器 [![build badge](https://github.com/rhysd/wain/workflows/CI/badge.svg?branch=master&event=push)](https://github.com/rhysd/wain/actions?query=workflow%3ACI+branch%3Amaster+event%3Apush)

### IDE工具

  * [Atom](https://atom.io/)
    * [zargony/atom-language-rust](https://github.com/zargony/atom-language-rust)
    * [rust-lang/atom-ide-rust](https://github.com/rust-lang/atom-ide-rust) — 由Rust语言服务器（RLS）支持的Rust IDE支持 [![Build Status](https://api.travis-ci.com/rust-lang/atom-ide-rust.svg?branch=master)](https://travis-ci.com/rust-lang/atom-ide-rust)
  * [Eclipse](https://www.eclipse.org/)
    * [Eclipse Corrosion](https://github.com/eclipse/corrosion)
    * [RustDT](https://github.com/RustDT/RustDT) — [![build badge](https://api.travis-ci.org/RustDT/RustDT.svg?branch=master)](https://travis-ci.org/RustDT/RustDT)
  * [Emacs](https://www.gnu.org/software/emacs/)
    * [rust-mode](https://github.com/rust-lang/rust-mode) — Rust主模式
    * [rustic](https://github.com/brotzeit/rustic) - Emacs的Rust开发环境 [![build badge](https://api.travis-ci.com/brotzeit/rustic.svg?branch=master)](https://travis-ci.com/brotzeit/rustic)
    * [flycheck-rust](https://github.com/flycheck/flycheck-rust) — [Flycheck](https://github.com/flycheck/flycheck)的Rust支持
    * [emacs-racer](https://github.com/racer-rust/emacs-racer) — 自动补全 (查看[company](https://company-mode.github.io) 和 [auto-complete](https://github.com/auto-complete/auto-complete))
  * [gitpod.io](https://gitpod.io) — 基于Rust Language Server(RLS)的完全Rust支持的在线IDE
  * [gnome-builder](https://wiki.gnome.org/Apps/Builder) 自3.22.2版以来对rust和cargo的本地支持
  * [Kakoune](http://kakoune.org/)
    * [kak-lsp/kak-lsp](https://github.com/kak-lsp/kak-lsp/) — [LSP](https://microsoft.github.io/language-server-protocol/) 客户端
  * [NetBeans](https://netbeans.org/)
    * [drrb/rust-netbeans](https://github.com/drrb/rust-netbeans)
  * [IntelliJ](https://www.jetbrains.com/idea/)
    * [intellij-rust/intellij-rust](https://github.com/intellij-rust/intellij-rust) — [![build badge](https://api.travis-ci.org/intellij-rust/intellij-rust.svg?branch=master)](https://travis-ci.org/intellij-rust/intellij-rust)
    * [intellij-rust/intellij-toml](https://github.com/intellij-rust/intellij-toml) — 基本的Toml支持
  * [Ride](https://github.com/madeso/ride) — [![build badge](https://api.travis-ci.org/madeso/ride.svg?branch=master)](https://travis-ci.org/madeso/ride)
  * [SolidOak](https://github.com/oakes/SolidOak) — 基于GTK+和[Neovim](https://github.com/neovim/neovim)简单的Rust IDE
  * [Sublime Text](https://www.sublimetext.com/)
    * [rust-lang/rust-enhanced](https://github.com/rust-lang/rust-enhanced) — 官方Rust包
    * [sublimehq/packages](https://github.com/sublimehq/Packages/tree/master/Rust) — 本机Sublime支持（已安装）
  * [Vim](https://vim.sourceforge.io/) — 普遍使用的文本编译器
    * [rust.vim](https://github.com/rust-lang/rust.vim) — 提供文件检测，语法突出显示，格式设置，语法集成等
    * [vim-cargo](https://github.com/timonv/vim-cargo) — 用于快速运行vim中的cargo的命令绑定
    * [vim-racer](https://github.com/racer-rust/vim-racer) — 允许vim使用[Racer](https://github.com/racer-rust/racer)进行Rust代码的补全和向导
    * [autozimu/LanguageClient-neovim](https://github.com/autozimu/LanguageClient-neovim) — [LSP](https://microsoft.github.io/language-server-protocol/) 客户端
  * Visual Studio
    * [PistonDevelopers/VisualRust](https://github.com/PistonDevelopers/VisualRust) — Rust的一个Visual Studio扩展 [![Build status](https://ci.appveyor.com/api/projects/status/5nw5no10jj0y4p3f?svg=true)](https://ci.appveyor.com/project/vosen/visualrust)
    * [dgriffen/rls-vs2017](https://github.com/ZoeyR/rls-vs2017) — Visual Studio 2017 Preview的Rust支持 [![build badge](https://ci.appveyor.com/api/projects/status/d2lxlincwninhsng?svg=true)](https://ci.appveyor.com/project/dgriffen/rls-vs2017)
  * [Visual Studio Code](https://code.visualstudio.com/)
    * [rust-lang/rls-vscode](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust) — Visual Studio Code的Rust支持
    * [rust-analyzer](https://marketplace.visualstudio.com/items?itemName=matklad.rust-analyzer) — 替代RLS的rust语言服务器
    * [CodeLLDB](https://marketplace.visualstudio.com/items?itemName=vadimcn.vscode-lldb) — LLDB扩展
    * [crates](https://github.com/serayuzgur/crates) — crates.io依赖的扩展工具 [![build badge](https://img.shields.io/vscode-marketplace/v/serayuzgur.crates.svg">](https://github.com/serayuzgur/crates) [<img src="https://api.travis-ci.org/serayuzgur/crates.svg?branch=master)](https://travis-ci.org/serayuzgur/crates)

### 模式识别

* [sfikas/rusteval](https://github.com/sfikas/rusteval) — 用于评估检索算法输出的工具 [![Build Status](https://api.travis-ci.org/sfikas/rusteval.svg?branch=master)](https://travis-ci.org/sfikas/rusteval)

### 剖析工具

* [bheisler/criterion.rs](https://github.com/bheisler/criterion.rs) — Rust的统计驱动的基准测试库 [![Build Status](https://api.travis-ci.org/bheisler/criterion.rs.svg?branch=master)](https://travis-ci.org/bheisler/criterion.rs)
* [sharkdp/hyperfine](https://github.com/sharkdp/hyperfine) — 命令行基准测试工具 [![Version info](https://img.shields.io/crates/v/hyperfine.svg)](https://crates.io/crates/hyperfine) [![Build Status](https://api.travis-ci.org/sharkdp/hyperfine.svg?branch=master)](https://travis-ci.org/sharkdp/hyperfine)
* [performancecopilot/hornet](https://github.com/performancecopilot/hornet) — Co-Pilot内存映射值仪表库 [![crates.io badge](https://img.shields.io/crates/v/hornet.svg)](https://crates.io/crates/hornet) [![build badge](https://api.travis-ci.org/performancecopilot/hornet.svg?branch=master)](https://travis-ci.org/performancecopilot/hornet)
* [koute/memory-profiler](https://github.com/koute/memory-profiler) — 用于Linux的内存分析器 [![Build Status](https://api.travis-ci.org/koute/memory-profiler.svg?branch=master)](https://travis-ci.org/koute/memory-profiler)
* [ellisonch/rust-stopwatch](https://github.com/ellisonch/rust-stopwatch) — 秒表库 [![build badge](https://api.travis-ci.org/ellisonch/rust-stopwatch.svg?branch=master)](https://travis-ci.org/ellisonch/rust-stopwatch)
* FlameGraphs
  * [mrhooray/torch](https://github.com/mrhooray/torch) — 根据DWARF调试信息生成FlameGraphs
  * [llogiq/flame](https://github.com/llogiq/flame) — [![build badge](https://api.travis-ci.org/llogiq/flame.svg?branch=master)](https://travis-ci.org/llogiq/flame)

### 服务

* [deps.rs](https://github.com/deps-rs/deps.rs) — 检测过时或不安全的依赖项
* [docs.rs](https://docs.rs) — crate的自动文档生成

### 静态分析

* [facebookexperimental/MIRAI](https://github.com/facebookexperimental/mirai) — 在Rust的中级中间表示（MIR）上运行的抽象解释器 [![Build Status](https://api.travis-ci.com/facebookexperimental/MIRAI.svg?branch=master)](https://travis-ci.org/facebookexperimental/MIRAI/)
* [static_assertions](https://crates.io/crates/static_assertions) — 编译时断言，以确保满足不变式 [![Build Status](https://api.travis-ci.org/nvzqz/static-assertions-rs.svg?branch=master)](https://travis-ci.org/nvzqz/static-assertions-rs/)

### 测试

* [laboratory](https://crates.io/crates/laboratory) — 一个Rust简单的单元测试框架 ![build](https://github.com/enokson/laboratory/workflows/build/badge.svg?branch=master)
* [cucumber-rust](https://crates.io/crates/cucumber-rust) — Rust的Cucumber测试框架的实现 [![Build Status](https://github.com/bbqsrc/cucumber-rust/workflows/CI/badge.svg?branch=master)](https://github.com/bbqsrc/cucumber-rust)
* [demonstrate](https://crates.io/crates/demonstrate) — 声明式测试框架 [![Build Status](https://github.com/austinsheep/demonstrate/workflows/Continuous%20Integration/badge.svg?branch=master)](https://github.com/austinsheep/demonstrate)
* [httpmock](https://github.com/alexliesenfeld/httpmock) — HTTP mock测试 [![build badge](https://dev.azure.com/alexliesenfeld/httpmock/_apis/build/status/alexliesenfeld.httpmock?branchName=master)](https://dev.azure.com/alexliesenfeld/httpmock/_build/latest?definitionId=2&branchName=master)
* [mockiato](https://crates.io/crates/mockiato) — 一个严格而友好的Rust 2018 mock测试库 [![build badge](https://api.travis-ci.com/mockiato/mockiato.svg?branch=master)](https://travis-ci.com/mockiato/mockiato)
* [mutagen](https://crates.io/crates/mutagen) — 源码级变化测试框架 [![build badge](https://api.travis-ci.org/llogiq/mutagen.svg?branch=master)](https://travis-ci.org/llogiq/mutagen)
* [AlKass/polish](https://github.com/AlKass/polish) — 迷你测试/测试驱动框架 [![Build Status](https://api.travis-ci.org/AlKass/polish.svg?branch=master)](https://travis-ci.org/AlKass/polish) [![Crates Package Status](https://img.shields.io/crates/v/polish.svg)](https://crates.io/crates/polish)
* [proptest](https://crates.io/crates/proptest) — 灵感来自[Hypothesis](https://hypothesis.works/) Python框架的测试框架 [![build badge](https://api.travis-ci.org/altsysrq/proptest.svg?branch=master)](https://travis-ci.org/altsysrq/proptest)
* [quickcheck](https://crates.io/crates/quickcheck) — [QuickCheck](https://wiki.haskell.org/Introduction_to_QuickCheck1)的Rust实现 [![build badge](https://api.travis-ci.org/BurntSushi/quickcheck.svg?branch=master)](https://travis-ci.org/BurntSushi/quickcheck)
* [mockito](https://crates.io/crates/mockito) — HTTP mock测试 [![build badge](https://api.travis-ci.org/lipanski/mockito.svg?branch=master)](https://travis-ci.org/lipanski/mockito)
* [speculate](https://crates.io/crates/speculate) — 灵感来自迷你测试框架的Rust RSpec
* [rstest](https://crates.io/crates/rstest) — Rust测试框架 [![Build Status](https://github.com/la10736/rstest/workflows/Test/badge.svg?branch=master)](https://github.com/la10736/rstest/actions)
* [ruspec](https://crates.io/crates/ruspec) — 类似RSpec的Rust测试框架 [![Build Status](https://github.com/k-nasa/ruspec/workflows/CI/badge.svg?branch=master)](https://github.com/k-nasa/ruspec/actions)
* [rust-fuzz/afl.rs](https://github.com/rust-fuzz/afl.rs) — 使用[AFL](https://lcamtuf.coredump.cx/afl/)的Rust fuzz测试工具 [![build badge](https://api.travis-ci.org/rust-fuzz/afl.rs.svg?branch=master)](https://travis-ci.org/rust-fuzz/afl.rs)
* [tarpaulin](https://crates.io/crates/cargo-tarpaulin) — 一个Rust代码覆盖率工具 [![build badge](https://api.travis-ci.org/repositories/xd009642/tarpaulin.svg?branch=master)](https://travis-ci.org/xd009642/tarpaulin)
* [trust](https://github.com/japaric/trust) — 一个Travis CI和AppVeyor模版，可以在5中架构上测试Rust crate，并针对Linux，macOS和Windows发布二进制版本
* [fake-rs](https://github.com/cksac/fake-rs) —  用于造假数据的库 [![build badge](https://api.travis-ci.org/repositories/cksac/fake-rs.svg?branch=master)](https://travis-ci.org/cksac/fake-rs)
* [goldenfile](https://github.com/calder/rust-goldenfile) - 为goldenfile测试提供简单API的库 [![build badge](https://api.travis-ci.org/calder/rust-goldenfile.svg?branch=master)](https://travis-ci.org/calder/rust-goldenfile)
* [cargo-dinghy](https://crates.io/crates/cargo-dinghy/) - 一个cargo扩展，用于简化在智能手机和其他小型处理器设备上运行库测试

### 转换

* [immunant/c2rust](https://github.com/immunant/c2rust) — 在Clang/LLVM上构建的C到Rust转换器和交叉检查器 [![Build Status](https://api.travis-ci.org/immunant/c2rust.svg?branch=master)](https://travis-ci.org/immunant/c2rust)
* [jameysharp/corrode](https://github.com/jameysharp/corrode) — 用Haskell编写的AC到Rust转换器

## Rust库

* [Phate6660/nixinfo](https://github.com/Phate6660/nixinfo) [[crate](https://crates.io/crates/nixinfo)] — 一个用于收集系统信息（如cpu，发行版，环境，内核等）的库

### 人工智能

#### 遗传算法

* [Martin1887/oxigen](https://github.com/Martin1887/oxigen) — 快速，并行，可扩展和适应性强的遗传算法库。使用该库的示例仅在几秒钟内并使用了不到1MB的内存即可解决N=255的N皇后问题
* [innoave/genevo](https://github.com/innoave/genevo) — 可定制和可扩展的方式执行遗传算法（GA）仿真
* [willi-kappler/darwin-rs](https://github.com/willi-kappler/darwin-rs) — 进化算法 [![Build Status](https://api.travis-ci.org/willi-kappler/darwin-rs.svg?branch=master)](https://travis-ci.org/willi-kappler/darwin-rs)
* [m-decoster/RsGenetic](https://github.com/m-decoster/RsGenetic) — Rust写的遗传算法库
* [mneumann/evo-rs](https://github.com/mneumann/evo-rs) — Rust写的进化算法库
* [yurytsoy/revonet](https://github.com/yurytsoy/revonet) — 实数编码遗传算法的Rust实现，用于解决优化问题和神经网路训练
* [pkalivas/radiate](https://github.com/pkalivas/radiate) — 一个可定制的并行遗传编程引擎，能够解决有监督，无监督和强化学习问题。带有NEAT和Evtree的完整且可自定义的实现。 [![Build Status](https://api.travis-ci.com/pkalivas/radiate.svg?branch=master)](https://travis-ci.com/pkalivas/radiate)
![Crates.io](https://img.shields.io/crates/v/radiate)

#### 机器学习

* [rust-ml/linfa](https://github.com/rust-ml/linfa) — 机器学习框架
* [AtheMathmo/rusty-machine](https://github.com/AtheMathmo/rusty-machine) — Rust写的机器学习库 [![Build Status](https://api.travis-ci.org/AtheMathmo/rusty-machine.svg?branch=master)](https://travis-ci.org/AtheMathmo/rusty-machine)
* [avinashshenoy97/RusticSOM](https://github.com/avinashshenoy97/RusticSOM) — 用于自组织地图（SOM）的Rust库 [![Build Status](https://api.travis-ci.org/avinashshenoy97/RusticSOM.svg?branch=master)](https://travis-ci.org/avinashshenoy97/RusticSOM)
* [autumnai/leaf](https://github.com/autumnai/leaf) — 开放机器智能框架 [![Build Status](https://api.travis-ci.org/autumnai/leaf.svg?branch=master)](https://travis-ci.org/autumnai/leaf). Abandoned project. The most updated fork is [spearow/juice]( https://github.com/spearow/juice).
* [tensorflow/rust](https://github.com/tensorflow/rust) — TensorFlow的Rust语言绑定 [![Build Status](https://api.travis-ci.org/tensorflow/rust.svg?branch=master)](https://travis-ci.org/tensorflow/rust)
* [maciejkula/rustlearn](https://github.com/maciejkula/rustlearn) — Rust的机器学习crate [![Circle CI](https://circleci.com/gh/maciejkula/rustlearn.svg?style=svg)](https://app.circleci.com/pipelines/github/maciejkula/rustlearn)
* [LaurentMazare/tch-rs](https://github.com/LaurentMazare/tch-rs) — PyTorch的Rust语言绑定 [![Build Status](https://api.travis-ci.org/LaurentMazare/tch-rs.svg?branch=master)](https://travis-ci.org/LaurentMazare/tch-rs)
* [huggingface/tokenizers](https://github.com/huggingface/tokenizers) - Hugging Face的令牌生成器，用于用Rust（原始实现）编写的现代NLP管道，并带有Python绑定 [![Build Status](https://github.com/huggingface/tokenizers/workflows/Rust/badge.svg?branch=master)](https://github.com/huggingface/tokenizers/actions)

### 天文学

* [saurvs/astro-rust](https://github.com/saurvs/astro-rust) — Rust的天文学库 [![build badge](https://api.travis-ci.org/saurvs/astro-rust.svg?branch=master)](https://travis-ci.org/saurvs/astro-rust)
* [fitsio](https://crates.io/crates/fitsio) — 包装cfitsio的接口库 [![build badge](https://api.travis-ci.org/mindriot101/rust-fitsio.svg?branch=master)](https://travis-ci.org/mindriot101/rust-fitsio)
* [flosse/rust-sun](https://github.com/flosse/rust-sun) — JS库suncalc的rust端口 [![build badge](https://api.travis-ci.org/flosse/rust-sun.svg?branch=master)](https://travis-ci.org/flosse/rust-sun)

### 异步

* [zonyitoo/coio-rs](https://github.com/zonyitoo/coio-rs) — 具有可窃用调度程序的协程I/O库 [![build badge](https://api.travis-ci.org/zonyitoo/coio-rs.svg?branch=master)](https://travis-ci.org/zonyitoo/coio-rs)
* [dpc/mioco](https://github.com/dpc/mioco) — 可扩展的，基于协程的异步IO处理库 [![build badge](https://api.travis-ci.org/dpc/mioco.svg?branch=master" alt="Travis CI Build Status)](https://travis-ci.org/dpc/mioco)
* [TeaEntityLab/fpRust](https://github.com/TeaEntityLab/fpRust) — Monad/MonadIO, Handler, Coroutine/doNotation, Rust函数式编程 [![build badge](https://api.travis-ci.org/TeaEntityLab/fpRust.svg?branch=master" alt="Travis CI Build Status)](https://travis-ci.org/TeaEntityLab/fpRust)
* [rust-lang/futures-rs](https://github.com/rust-lang/futures-rs) — 零成本future库 [![build badge](https://api.travis-ci.com/rust-lang/futures-rs.svg?branch=master" alt="Travis CI Build Status)](https://travis-ci.org/rust-lang/futures-rs)
* [mio](https://github.com/tokio-rs/mio) — MIO是Rust的轻量级IO库，着重于在OS抽象上增加尽可能少的开销 [![build badge](https://api.travis-ci.org/tokio-rs/mio.svg?branch=master)](https://travis-ci.org/tokio-rs/mio)
* [Xudong-Huang/may](https://github.com/Xudong-Huang/may) — rust协程库 [![build badge](https://api.travis-ci.org/Xudong-Huang/may.svg?branch=master)](https://travis-ci.org/Xudong-Huang/may)
* [rustasync/runtime](https://github.com/rustasync/runtime) — 一种运行时API，旨在使用异步感觉像stdlib的一部分 [![Crates.io](https://img.shields.io/crates/v/runtime.svg?style=flat-square)](https://crates.io/crates/runtime) [![Build status](https://img.shields.io/azure-devops/build/yoshuawuyts/rustasync/2/master.svg?style=flat-square)](https://dev.azure.com/yoshuawuyts/rustasync/_build?definitionId=2)

### 音频和音乐-1

* [GuillaumeGomez/rust-fmod](https://github.com/GuillaumeGomez/rust-fmod) — [FMOD](https://www.fmod.com) 绑定 [![Build Status](https://api.travis-ci.org/GuillaumeGomez/rust-fmod.svg?branch=master)](https://travis-ci.org/GuillaumeGomez/rust-fmod)
* [jhasse/ears](https://github.com/jhasse/ears) — 基于OpenAL和libsndfile的播放音频和音乐的简单的库 [![build badge](https://api.travis-ci.org/jhasse/ears.svg?branch=master)](https://travis-ci.org/jhasse/ears)
* [jpernst/alto](https://github.com/jpernst/alto) — OpenAL 1.1的绑定 [![build badge](https://api.travis-ci.org/jpernst/alto.svg?branch=master)](https://travis-ci.org/jpernst/alto)
* [musitdev/portmidi-rs](https://github.com/musitdev/portmidi-rs) — [PortMidi](http://portmedia.sourceforge.net/portmidi/) 绑定 [![build badge](https://api.travis-ci.org/musitdev/portmidi-rs.svg?branch=master)](https://travis-ci.org/musitdev/portmidi-rs)
* [hound](https://crates.io/crates/hound) — 一个WAV编解码库 [![build badge](https://api.travis-ci.org/ruuda/hound.svg?branch=master)](https://travis-ci.org/ruuda/hound)
* [RustAudio](https://github.com/RustAudio)
  * [RustAudio/cpal](https://github.com/RustAudio/cpal) - Rust写的底层跨平台音频I/O库 [![Actions Status](https://github.com/RustAudio/cpal/workflows/cpal/badge.svg?branch=master)](https://github.com/RustAudio/cpal/actions)
  * [RustAudio/rodio](https://github.com/RustAudio/rodio) — Rust音频播放库 [![Build Status](https://api.travis-ci.org/RustAudio/rodio.svg?branch=master)](https://travis-ci.org/RustAudio/rodio)
  * [RustAudio/rust-portaudio](https://github.com/RustAudio/rust-portaudio) — [PortAudio](http://www.portaudio.com/) 绑定 [![build badge](https://api.travis-ci.org/RustAudio/rust-portaudio.svg?branch=master)](https://travis-ci.org/RustAudio/rust-portaudio)
* [ozankasikci/rust-music-theory](https://github.com/ozankasikci/rust-music-theory) — Rust音乐理论库 [![Build Status](https://api.travis-ci.com/ozankasikci/rust-music-theory.svg?branch=master)](https://travis-ci.org/ozankasikci/rust-music-theory)
* [MoAlyousef/soloud-rs](https://github.com/MoAlyousef/soloud-rs) — [soloud audio engine library](https://sol.gfxile.net/soloud/)的Rust绑定 [![Build](https://github.com/MoAlyousef/soloud-rs/workflows/Build/badge.svg?branch=master)](https://github.com/MoAlyousef/soloud-rs/actions)

### 认证

* [Keats/jsonwebtoken](https://github.com/Keats/jsonwebtoken) — [JSON Web Token](https://en.wikipedia.org/wiki/JSON_Web_Token) rust库 [![Build Status](https://api.travis-ci.org/Keats/jsonwebtoken.svg?branch=master)](https://travis-ci.org/Keats/jsonwebtoken)
* [sgrust01/jwtvault](https://github.com/sgrust01/jwtvault) — 用于管理和编排JWT工作流程的异步库  [![Build Status](https://api.travis-ci.org/sgrust01/jwtvault.svg?branch=master)](https://travis-ci.org/sgrust01/jwtvault)
* [oauth2](https://github.com/ramosbugs/oauth2-rs) — 可扩展的，强类型的Rust OAuth2客户端库 [![Build Status](https://api.travis-ci.org/ramosbugs/oauth2-rs.svg?branch=main)](https://travis-ci.org/ramosbugs/oauth2-rs)
* [oxide-auth](https://github.com/HeroicKatora/oxide-auth) — OAuth2服务器库，与actix或其他前端结合使用，具有一组可配置和可插入的后端 [![Build Status](https://api.cirrus-ci.com/github/HeroicKatora/oxide-auth.svg?branch=master)](https://cirrus-ci.com/github/HeroicKatora/oxide-auth)
* [yup-oauth2](https://github.com/dermesser/yup-oauth2) — 提供设备，已安装和服务帐户流的oauth2客户端实现 [![Build Status](https://api.travis-ci.org/dermesser/yup-oauth2.svg?branch=master)](https://travis-ci.org/dermesser/yup-oauth2)

### 汽车行业

* [canparse](https://crates.io/crates/canparse) — CAN信号和定义解析器 [![build badge](https://api.travis-ci.org/jmagnuson/canparse.svg?branch=master)](https://travis-ci.org/jmagnuson/canparse)
* [j2534](https://crates.io/crates/j2534) — J2534 PassThru绑定
* [JulianSchmid/dlt_parse](https://github.com/JulianSchmid/dlt-parse-rs) — Rust DLT（诊断日志和跟踪）数据包解析器 [![build badge](https://api.travis-ci.org/JulianSchmid/dlt-parse-rs.svg?branch=master)](https://travis-ci.org/JulianSchmid/dlt-parse-rs)
* [JulianSchmid/someip_parse](https://github.com/JulianSchmid/someip-parse-rs) [[someip_parse](https://crates.io/crates/someip_parse)] — 用于解析SOME/IP网络协议的库（无有效载荷解释） [![build badge](https://api.travis-ci.org/JulianSchmid/someip-parse-rs.svg?branch=master)](https://travis-ci.org/JulianSchmid/someip-parse-rs)
* [LibreTuner/tuneutils](https://github.com/LibreTuner/tuneutils) [[tuneutils](https://crates.io/crates/tuneutils)] — 用于与汽车接口，诊断和调整的实用程序
* [marcelbuesing/can-dbc](https://github.com/marcelbuesing/can-dbc) [[can-dbc](https://crates.io/crates/can-dbc)] — DBC格式的解析器 [![build badge](https://api.travis-ci.org/marcelbuesing/can-dbc.svg?branch=dev)](https://travis-ci.org/marcelbuesing/can-dbc)
* [marcelbuesing/tokio-socketcan-bcm](https://github.com/marcelbuesing/tokio-socketcan-bcm) [[tokio-socketcan-bcm](https://crates.io/crates/tokio-socketcan-bcm)] — tokio的Linux SocketCAN BCM支持 [![build badge](https://api.travis-ci.org/marcelbuesing/tokio-socketcan-bcm.svg?branch=master)](https://travis-ci.org/marcelbuesing/tokio-socketcan-bcm)
* [mbr/socketcan](https://github.com/mbr/socketcan-rs) [[socketcan](https://crates.io/crates/socketcan)] — Linux SocketCAN库 [![build badge](https://api.travis-ci.org/mbr/socketcan-rs.svg?branch=master)](https://travis-ci.org/mbr/socketcan-rs)
* [oefd/tokio-socketcan](https://github.com/oefd/tokio-socketcan) [[tokio-socketcan]](https://crates.io/crates/tokio-socketcan)] — 基于socketcan crate的tokio Linux SocketCAN支持
* [Sensirion/lin-bus](https://github.com/Sensirion/lin-bus-rs) [[lin-bus](https://crates.io/crates/lin-bus)] — LIN总线驱动程序特征和协议实现 [![build badge](https://circleci.com/gh/Sensirion/lin-bus-rs.svg?style=svg)](https://app.circleci.com/pipelines/github/Sensirion/lin-bus-rs)

### 生物信息学

* [Rust-Bio](https://github.com/rust-bio) — Rust写的生物信息学库

### 缓存

* [mozilla/sccache](https://github.com/mozilla/sccache/) - 共享编译缓存，非常适合Rust编译 [![build badge](https://api.travis-ci.org/mozilla/sccache.svg?branch=master)](https://travis-ci.org/mozilla/sccache)
* [jaysonsantos/bmemcached-rs](https://github.com/jaysonsantos/bmemcached-rs) — 完全rust写的Memcached库 [![build badge](https://api.travis-ci.org/jaysonsantos/bmemcached-rs.svg?branch=master)](https://travis-ci.org/jaysonsantos/bmemcached-rs)
* [jaemk/cached](https://github.com/jaemk/cached) — 简单的功能缓存/存储
* [aisk/rust-memcache](https://github.com/aisk/rust-memcache) — Memcached客户端库 [![build badge](https://api.travis-ci.org/aisk/rust-memcache.svg?branch=master)](https://travis-ci.org/aisk/rust-memcache)

### 并发

* [aymanmadkour/glock](https://github.com/aymanmadkour/glock) – Rust的细粒度锁crate [![build badge](https://api.travis-ci.org/aymanmadkour/glock.svg?branch=master)](https://travis-ci.org/aymanmadkour/glock)
* [crossbeam-rs/crossbeam](https://github.com/crossbeam-rs/crossbeam) – 支持Rust并行和底层并发 [![build badge](https://api.travis-ci.org/crossbeam-rs/crossbeam.svg?branch=master)](https://travis-ci.org/crossbeam-rs/crossbeam)
* [orium/archery](https://github.com/orium/archery) [[archery](https://crates.io/crates/archery)] —`Rc`/`Arc` 指针类型抽象的库 [![build badge](https://api.travis-ci.org/orium/archery.svg?branch=master)](https://travis-ci.org/orium/archery)
* [pop-os/bus-writer](https://github.com/pop-os/bus-writer) — 通用的单读多写
* [Rayon](https://github.com/rayon-rs/rayon) – Rust的数据并行库 [![build badge](https://api.travis-ci.org/rayon-rs/rayon.svg?branch=master)](https://travis-ci.org/rayon-rs/rayon)
* [rustcc/coroutine-rs](https://github.com/rustcc/coroutine-rs) – Rust的协程库 [![build badge](https://api.travis-ci.org/rustcc/coroutine-rs.svg?branch=master)](https://travis-ci.org/rustcc/coroutine-rs)
* [zonyitoo/coio-rs](https://github.com/zonyitoo/coio-rs) – Rust的协程I/O [![build badge](https://api.travis-ci.org/zonyitoo/coio-rs.svg?branch=master)](https://travis-ci.org/zonyitoo/coio-rs)

### 云计算

* AWS [[aws](https://crates.io/keywords/aws)]
  * [rusoto/rusoto](https://github.com/rusoto/rusoto) — [![build badge](https://api.travis-ci.org/rusoto/rusoto.svg?branch=master)](https://travis-ci.org/rusoto/rusoto)

### 命令行

* Argument parsing
  * [clap-rs](https://github.com/clap-rs/clap) [[clap](https://crates.io/crates/clap)] — 一个易于使用的全功能命令行参数解析器 [![build badge](https://api.travis-ci.org/clap-rs/clap.svg?branch=master)](https://travis-ci.org/clap-rs/clap)
  * [docopt/docopt.rs](https://github.com/docopt/docopt.rs) [[docopt](https://crates.io/crates/docopt)] — [DocOpt](http://docopt.org) Rust实现 [![build badge](https://api.travis-ci.org/docopt/docopt.rs.svg?branch=master)](https://travis-ci.org/docopt/docopt.rs)
  * [z5labs/pflag](https://github.com/z5labs/pflag) [[pflag](https://crates.io/crates/pflag)] — 一个关于@spf13 Go语言POSIX兼容的参数解析库的移植 [![Build Status](https://github.com/z5labs/pflag/workflows/Rust/badge.svg?branch=master)](https://github.com/z5labs/pflag/actions)
  * [TeXitoi/structopt](https://github.com/TeXitoi/structopt) [[structopt](https://crates.io/crates/structopt)] — 通过定义结构来解析命令行参数 [![build badge](https://api.travis-ci.org/TeXitoi/structopt.svg?branch=master)](https://travis-ci.org/TeXitoi/structopt)
  * [killercup/quicli](https://github.com/killercup/quicli) [[quicli](https://crates.io/crates/quicli)] — Rust的快速构建很酷的CLI应用程序 [![build badge](https://api.travis-ci.org/killercup/quicli.svg?branch=master)](https://travis-ci.org/killercup/quicli)
  * [ksk001100/seahorse](https://github.com/ksk001100/seahorse) [[seahorse](https://crates.io/crates/seahorse)] — 一个Rust的迷你的CLI框架 [![Build status](https://github.com/ksk001100/seahorse/workflows/CI/badge.svg?branch=master)](https://github.com/ksk001100/seahorse/actions)
* Data visualization
  * [nukesor/comfy-table](https://github.com/nukesor/comfy-table) [[comfy-table](https://crates.io/crates/comfy-table)] — 用于cli工具的漂亮动态表 [![Build status](https://github.com/Nukesor/comfy-table/workflows/Tests/badge.svg?branch=master)](https://github.com/nukesor/comfy-table/actions)
  * [reugn/rspark](https://github.com/reugn/rspark) [[rspark](https://crates.io/crates/rspark)] — ▁▂▆▇▁▄█▁ 适用于Rust应用的迷你图 [![build badge](https://api.travis-ci.org/reugn/rspark.svg?branch=master)](https://travis-ci.org/reugn/rspark)
* Human-centered design
  * [rust-cli/human-panic](https://github.com/rust-cli/human-panic) [[human-panic](https://crates.io/crates/human-panic)] — 具有可读性的pani消息[![build badge](https://api.travis-ci.org/rust-cli/human-panic.svg?branch=master)](https://travis-ci.org/rust-cli/human-panic)
* Line editor
  * [srijs/rust-copperline](https://github.com/srijs/rust-copperline) [[copperline](https://crates.io/crates/copperline)] — 纯Rust实现的命令行编辑库
  * [MovingtoMars/liner](https://github.com/MovingtoMars/liner) [[liner](https://crates.io/crates/liner)] — 提供类似readline功能的库 [![build badge](https://api.travis-ci.org/MovingtoMars/liner.svg?branch=master)](https://travis-ci.org/MovingtoMars/liner)
  * [murarth/linefeed](https://github.com/murarth/linefeed) [[linefeed](https://crates.io/crates/linefeed)] — 可配置的，可扩展的，交互式的行读入器 [![build badge](https://api.travis-ci.org/murarth/linefeed.svg?branch=master)](https://travis-ci.org/murarth/linefeed)
  * [kkawakam/rustyline](https://github.com/kkawakam/rustyline) [[rustyline](https://crates.io/crates/rustyline)] — Rust的readline实现 [![build badge](https://api.travis-ci.org/kkawakam/rustyline.svg?branch=master)](https://travis-ci.org/kkawakam/rustyline)
* Pipeline
  * [imp/pager-rs](https://gitlab.com/imp/pager-rs) [[pager](https://crates.io/crates/pager)] — 通过外部页输出
  * [hniksic/rust-subprocess](https://github.com/hniksic/rust-subprocess) [[subprocess](https://crates.io/crates/subprocess)] — 与外部管道交互的工具 [![build badge](https://api.travis-ci.org/hniksic/rust-subprocess.svg?branch=master)](https://travis-ci.org/hniksic/rust-subprocess)
  * [oconnor663/duct.rs](https://github.com/oconnor663/duct.rs) [[duct](https://crates.io/crates/duct)] — 子流程管道和IO重定向的构建器 [![build badge](https://api.travis-ci.org/oconnor663/duct.rs.svg?branch=master)](https://travis-ci.org/oconnor663/duct.rs)
  * [philippkeller/rexpect](https://github.com/philippkeller/rexpect) [[rexpect](https://crates.io/crates/rexpect)] — 自动执行诸如ssh，ftp，passwd等的交互式应用程序 [![build badge](https://api.travis-ci.org/philippkeller/rexpect.svg?branch=master)](https://travis-ci.org/philippkeller/rexpect)
* Progress
  * [mitsuhiko/indicatif](https://github.com/mitsuhiko/indicatif) [[indicatif](https://crates.io/crates/indicatif)] — 向用户展示进度
  * [a8m/pb](https://github.com/a8m/pb) [[pbr](https://crates.io/crates/pbr)] — Rust的控制台进度栏
  * [FGRibreau/spinners](https://github.com/FGRibreau/spinners) [[spinners](https://crates.io/crates/spinners)] — 60多个优雅的终端旋转器
* Prompt
  * [hashmismatch/terminal_cli.rs](https://github.com/hashmismatch/terminal_cli.rs) [[terminal_cli](https://crates.io/crates/terminal_cli)]  — 构建交互式命令提示符 [![build badge](https://api.travis-ci.org/hashmismatch/terminal_cli.rs.svg?branch=master)](https://travis-ci.org/hashmismatch/terminal_cli.rs)
  * [starship/starship](https://starship.rs/) [[starship](https://crates.io/crates/starship)]  — 任一shell的最小，极快，可自定制性强的提示 [![Build status](https://github.com/starship/starship/workflows/Main%20workflow/badge.svg?branch=master)](https://github.com/starship/starship/actions)
* Style
  * [ogham/rust-ansi-term](https://github.com/ogham/rust-ansi-term) [[ansi_term](https://crates.io/crates/ansi_term)] — 在ANSI终端上控制颜色和格式 [![build badge](https://api.travis-ci.org/ogham/rust-ansi-term.svg?branch=master)](https://travis-ci.org/ogham/rust-ansi-term)
  * [LukasKalbertodt/term-painter](https://github.com/LukasKalbertodt/term-painter) [[term-painter](https://crates.io/crates/term-painter)] — 跨平台的样式的终端输出 [![build badge](https://api.travis-ci.org/LukasKalbertodt/term-painter.svg?branch=master)](https://travis-ci.org/LukasKalbertodt/term-painter)
  * [vitiral/termstyle](https://github.com/vitiral/termstyle) [[termstyle](https://docs.rs/termstyle/0.1.2/termstyle/)] — 构建（和测试）格式化和样式化的命令行应用程序
  * [SergioBenitez/yansi](https://github.com/SergioBenitez/yansi) [[yansi](https://crates.io/crates/yansi)] — 一个简单的ANSI终端颜色绘画库
  * [mackwic/colored](https://github.com/mackwic/colored) [[colored](https://crates.io/crates/colored)] — 彩色终端非常简单，容易上手！
* TUI
  * [TimonPost/crossterm](https://github.com/crossterm-rs/crossterm) [[crossterm](https://crates.io/crates/crossterm)] — 跨平台终端库
  * [gyscos/Cursive](https://github.com/gyscos/Cursive) [[cursive](https://crates.io/crates/cursive)] — 构建丰富的TUI应用程序 [![build badge](https://api.travis-ci.org/gyscos/Cursive.svg?branch=master)](https://travis-ci.org/gyscos/Cursive)
  * [ogham/rust-term-grid](https://github.com/ogham/rust-term-grid) [[term_grid](https://crates.io/crates/term_grid)] — 用于将东西放入网格中的Rust库 [![build badge](https://api.travis-ci.org/ogham/rust-term-grid.svg?branch=master)](https://travis-ci.org/ogham/rust-term-grid)
  * [redox-os/termion](https://github.com/redox-os/termion) [[termion](https://crates.io/crates/termion)] — 用于控制终端/TTY的非绑定库 [![build badge](https://api.travis-ci.org/redox-os/termion.svg?branch=master)](https://travis-ci.org/redox-os/termion)
  * [fdehau/tui-rs](https://github.com/fdehau/tui-rs) [[tui](https://crates.io/crates/tui)] — 灵感来自[blessed-contrib](https://github.com/yaronn/blessed-contrib) 和 [termui](https://github.com/gizak/termui) 的TUI库 [![build badge](https://api.travis-ci.org/fdehau/tui-rs.svg?branch=master)](https://travis-ci.org/fdehau/tui-rs)
  * BearLibTerminal
    * [cfyzium/bearlibterminal](https://github.com/nabijaczleweli/BearLibTerminal.rs) [[bear-lib-terminal](https://crates.io/crates/bear-lib-terminal)] — [BearLibTerminal](https://github.com/tommyettinger/BearLibTerminal) 绑定 [![build badge](https://api.travis-ci.org/nabijaczleweli/BearLibTerminal.rs.svg?branch=master)](https://travis-ci.org/nabijaczleweli/BearLibTerminal.rs)
  * ncurses
    * [jeaye/ncurses-rs](https://github.com/jeaye/ncurses-rs) [[ncurses](https://crates.io/crates/ncurses)] — [ncurses](https://www.gnu.org/software/ncurses/) 绑定 [![build badge](https://api.travis-ci.org/jeaye/ncurses-rs.svg?branch=master)](https://travis-ci.org/jeaye/ncurses-rs)
    * [ihalila/pancurses](https://github.com/ihalila/pancurses) [[pancurses](https://crates.io/crates/pancurses)] — curses库，支持linux和Windows [![build badge](https://api.travis-ci.org/ihalila/pancurses.svg?branch=master)](https://travis-ci.org/ihalila/pancurses)
  * Termbox
    * [gchp/rustbox](https://github.com/gchp/rustbox) [[rustbox](https://crates.io/crates/rustbox)] — [Termbox](https://github.com/nsf/termbox) 绑定 [![build badge](https://api.travis-ci.org/gchp/rustbox.svg?branch=master)](https://travis-ci.org/gchp/rustbox)
  * [ivanceras/titik](https://github.com/ivanceras/titik) - 一个跨平台的TUI小部件库，旨在提供交互式小部件 [![Build Status](https://api.travis-ci.com/ivanceras/titik.svg?branch=master)](https://travis-ci.com/github/ivanceras/titik)

### 压缩

* [Brotli](https://opensource.googleblog.com/2015/09/introducing-brotli-new-compression.html)
  * [ende76/brotli-rs](https://github.com/ende76/brotli-rs) — Brotli压缩的实现
  * [dropbox/rust-brotli](https://github.com/dropbox/rust-brotli) — Rust写的Brotli压缩程序，可以选择避免使用stdlib
* bzip2
  * [alexcrichton/bzip2-rs](https://github.com/alexcrichton/bzip2-rs) — [libbz2](https://www.sourceware.org/bzip2/) 绑定 [![build badge](https://api.travis-ci.com/alexcrichton/bzip2-rs.svg?branch=master)](https://travis-ci.org/alexcrichton/bzip2-rs)
* Columnar compression
  * [velvia/compressed-vec](https://github.com/velvia/compressed-vec) - SIMD浮点和整数压缩向量库 [![CircleCI](https://circleci.com/gh/velvia/compressed-vec.svg?style=shield)](https://app.circleci.com/pipelines/github/velvia/compressed-vec)
* gzip
  * [carols10cents/zopfli](https://github.com/carols10cents/zopfli) — [Zopfli](https://github.com/google/zopfli)压缩算法的实现
* miniz
  * [rust-lang/flate2-rs](https://github.com/rust-lang/flate2-rs) — [miniz](https://code.google.com/archive/p/miniz) 绑定 [![build badge](https://github.com/rust-lang/flate2-rs/workflows/CI/badge.svg?branch=master)](https://github.com/rust-lang/flate2-rs/actions)
* snappy
  * [JeffBelgum/rust-snappy](https://github.com/JeffBelgum/rust-snappy) — [snappy](https://github.com/google/snappy) 绑定 [![build badge](https://api.travis-ci.org/JeffBelgum/rust-snappy.svg?branch=master)](https://travis-ci.org/JeffBelgum/rust-snappy)
* tar
  * [alexcrichton/tar-rs](https://github.com/alexcrichton/tar-rs) — rust写的读写tar归档文件 [![build badge](https://api.travis-ci.com/alexcrichton/tar-rs.svg?branch=master)](https://travis-ci.org/alexcrichton/tar-rs)
* zip
  * [zip-rs/zip](https://github.com/zip-rs/zip) — 读写ZIP文件 [![Build Status](https://api.travis-ci.org/mvdnes/zip-rs.svg?branch=master)](https://travis-ci.org/mvdnes/zip-rs)

### 计算

* [argmin-rs/argmin](https://github.com/argmin-rs/argmin) [[argmin](https://crates.io/crates/argmin)] — 一个纯Rust优化库 [![build badge](https://api.travis-ci.org/argmin-rs/argmin.svg?branch=master)](https://travis-ci.org/argmin-rs/argmin)
* [BLAS](https://en.wikipedia.org/wiki/Basic_Linear_Algebra_Subprograms) [[blas](https://crates.io/keywords/blas)]
  * [mikkyang/rust-blas](https://github.com/mikkyang/rust-blas) — BLAS绑定
  * [stainless-steel/blas](https://github.com/blas-lapack-rs/blas) — BLAS绑定 [![build badge](https://api.travis-ci.org/blas-lapack-rs/blas.svg?branch=master)](https://travis-ci.org/blas-lapack-rs/blas)
* [Conjugate Gradient](https://en.wikipedia.org/wiki/Limited-memory_BFGS)
  * [noshu/cg-sys](https://github.com/noshu/cg-sys) — fortran CG+子例程的Rust绑定
* [GMP](https://gmplib.org/)
  * [fizyk20/rust-gmp](https://github.com/fizyk20/rust-gmp) — libgmp绑定 [![build badge](https://api.travis-ci.org/fizyk20/rust-gmp.svg?branch=master)](https://travis-ci.org/fizyk20/rust-gmp)
* [GSL](http://www.gnu.org/software/gsl/)
  * [GuillaumeGomez/rust-GSL](https://github.com/GuillaumeGomez) — GSL绑定 [![build badge](https://api.travis-ci.org/GuillaumeGomez/rust-GSL.svg?branch=master)](https://travis-ci.org/GuillaumeGomez/rust-GSL)
* [LAPACK](https://en.wikipedia.org/wiki/LAPACK)
  * [stainless-steel/lapack](https://github.com/blas-lapack-rs/lapack) — LAPACK绑定 [![build badge](https://api.travis-ci.org/blas-lapack-rs/lapack.svg?branch=master)](https://travis-ci.org/blas-lapack-rs/lapack)
* [L-BFGS-B](https://en.wikipedia.org/wiki/Limited-memory_BFGS)
  * [noshu/lbfgsb-sys](https://github.com/noshu/lbfgsb-sys) — fortran L-BFGS-B子例程的Rust绑定
* [dimforge/nalgebra](https://github.com/dimforge/nalgebra) — 低维线性代数库 [![build badge](https://api.travis-ci.org/dimforge/nalgebra.svg?branch=dev)](https://travis-ci.org/dimforge/nalgebra)
* Parallel
  * [arrayfire/arrayfire-rust](https://github.com/arrayfire/arrayfire-rust) — [Arrayfire](https://github.com/arrayfire) 绑定
  * [autumnai/collenchyma](https://github.com/autumnai/collenchyma) — 用于CUDA，OpenCL和通用主机CPU上的并行，高性能计算的可扩展，可插拔的框架 [![build badge](https://api.travis-ci.org/autumnai/collenchyma.svg?branch=master)](https://travis-ci.org/autumnai/collenchyma)
  * [luqmana/rust-opencl](https://github.com/luqmana/rust-opencl) — [OpenCL](https://www.khronos.org/opencl/) 绑定
* Scirust
  * [indigits/scirust](https://github.com/indigits/scirust) — Rust的科学计算库 [![Build Status](https://api.travis-ci.org/indigits/scirust.svg?branch=master)](https://travis-ci.org/indigits/scirust)
* Statrs
  * [boxtown/statrs](https://github.com/boxtown/statrs) — Rust强大的统计计算库 [![Build Status](https://api.travis-ci.org/boxtown/statrs.svg?branch=master)](https://travis-ci.org/boxtown/statrs)
* Rustimization [[rustimization](https://crates.io/crates/rustimization)]
  * [noshu/rustimization](https://github.com/noshu/rustimization) — 包含L-BFGS-B和共轭梯度算法的Rust优化库
* [calebwin/emu](https://github.com/calebwin/emu) — 一种从Rust宏进行GPGPU数值计算的语言

### 配置

* [mehcode/config-rs](https://github.com/mehcode/config-rs) [[config](https://crates.io/crates/config)] — 用于Rust应用程序的分层配置系统（支持12因子应用程序） [![build badge](https://api.travis-ci.org/mehcode/config-rs.svg?branch=master)](https://travis-ci.org/mehcode/config-rs)
* [theimpossibleastronaut/configster](https://github.com/theimpossibleastronaut/configster) [[configster](https://crates.io/crates/configster)] — 用于解析配置文件的Rust库 [![build badge](https://api.travis-ci.com/theimpossibleastronaut/configster.svg?branch=trunk)](https://travis-ci.com/theimpossibleastronaut/configster)
* [Kixunil/configure_me](https://github.com/Kixunil/configure_me) [[configure_me](https://crates.io/crates/configure_me)] — 用于轻松处理应用程序配置的库
* [andoriyu/uclicious](https://github.com/andoriyu/uclicious) [[uclicious](https://crates.io/crates/uclicious)] — 基于[libUCL](https://github.com/vstakhov/libucl)的功能丰富的配置库 [![CircleCI](https://circleci.com/gh/vstakhov/libucl.svg?style=svg)](https://app.circleci.com/pipelines/github/vstakhov/libucl)
* [FlashSystems/justconfig](https://github.com/FlashSystems/just-config) - 易于扩展的分层配置库，不会在您的项目中引入任何其他依赖项
* [ANtlord/yasec](https://github.com/ANtlord/yasec/) [[Yasec](https://crates.io/crates/yasec)] - 来自环境变量的全功能齐全的配置 [![build badge](https://api.travis-ci.org/ANtlord/yasec.svg?branch=master)](https://travis-ci.org/ANtlord/yasec)

### 密码学

[[加密](https://crates.io/keywords/crypto), [密码学](https://crates.io/keywords/cryptography)]

* [briansmith/ring](https://github.com/briansmith/ring) — 安全，快速，小型使用BoringSSL加密原语的Rust加密库 [![build badge](https://api.travis-ci.org/briansmith/ring.svg?branch=master)](https://travis-ci.org/briansmith/ring)
* [briansmith/webpki](https://github.com/briansmith/webpki) — Rust的网络PKI TLS X.509证书验证 [![build badge](https://api.travis-ci.org/briansmith/webpki.svg?branch=master)](https://travis-ci.org/briansmith/webpki)
* [brycx/orion](https://github.com/brycx/orion) — 该库旨在提供简单易用的加密。“可用”是指公开易用且难以滥用的高级API [![build badge](https://api.travis-ci.org/brycx/orion.svg?branch=master)](https://travis-ci.org/brycx/orion)
* [cossacklabs/themis](https://github.com/cossacklabs/themis) [[themis](https://crates.io/crates/themis)] — 一个高级密码库，用于解决典型的数据安全任务，最适合多平台应用程序 [![build badge](https://circleci.com/gh/cossacklabs/themis/tree/master.svg?style=shield)](https://app.circleci.com/pipelines/github/cossacklabs/themis)
* [ctz/rustls](https://github.com/ctz/rustls) — TLS的Rust实现
* [DaGenix/rust-crypto](https://github.com/DaGenix/rust-crypto) — Rust实现的加密算法 [![build badge](https://api.travis-ci.org/DaGenix/rust-crypto.svg?branch=master)](https://travis-ci.org/DaGenix/rust-crypto)
* [dalek-cryptography/curve25519-dalek](https://github.com/dalek-cryptography/curve25519-dalek) — Curve25519操作的纯Rust实现
* [dalek-cryptography/ed25519-dalek](https://github.com/dalek-cryptography/ed25519-dalek) — Ed25519数字签名的纯Rust实现
* [dalek-cryptography/x25519-dalek](https://github.com/dalek-cryptography/x25519-dalek) — X25519密钥交换的纯Rust实现
* [debris/tiny-keccak](https://github.com/debris/tiny-keccak) — Keccak系列（SHA3）的纯Rust实现
* [defund/pw](https://github.com/defund/pw) — CLI密码管理器
* [sodiumoxide/sodiumoxide](https://github.com/sodiumoxide/sodiumoxide) — [libsodium](https://github.com/jedisct1/libsodium) 绑定 [![build badge](https://api.travis-ci.org/sodiumoxide/sodiumoxide.svg?branch=master)](https://travis-ci.org/sodiumoxide/sodiumoxide)
* [doublify/libblockchain](https://github.com/doublify/libblockchain) — 一种区块链的实现 [![build badge](https://api.travis-ci.org/doublify/libblockchain.svg?branch=master)](https://travis-ci.org/doublify/libblockchain)
* [exonum/exonum](https://github.com/exonum/exonum) [[exonum](https://crates.io/crates/exonum)] — 用于区块链项目的可扩展框架 [![build badge](https://api.travis-ci.com/exonum/exonum.svg?branch=master)](https://travis-ci.org/exonum/exonum)
* [klutzy/suruga](https://github.com/klutzy/suruga) — [TLS 1.2](https://tools.ietf.org/html/rfc5246)的Rust实现
* [libOctavo/octavo](https://github.com/libOctavo/octavo) — Rust实现的模块化哈希和加密库 [![build badge](https://api.travis-ci.org/libOctavo/octavo.svg?branch=master)](https://travis-ci.org/libOctavo/octavo)
* [novifinancial/opaque-ke](https://github.com/novifinancial/opaque-ke) — 最新的[OPAQUE](https://datatracker.ietf.org/doc/draft-krawczyk-cfrg-opaque/)密码验证密钥交换的纯Rust实现 [![build badge](https://github.com/novifinancial/opaque-ke/workflows/Rust%20CI/badge.svg?branch=master)](https://github.com/novifinancial/opaque-ke)
* [RustCrypto/hashes](https://github.com/RustCrypto/hashes) — 纯Rust编写的加密哈希函数的集合 [![build badge](https://api.travis-ci.org/RustCrypto/hashes.svg?branch=master)](https://travis-ci.org/RustCrypto/hashes)
* [rustindia/mpw-rs](https://github.com/rustindia/mpw-rs) — Master Password密码管理器的纯Rust实现 [![build badge](https://api.travis-ci.org/rustindia/mpw-rs.svg?branch=master)](https://travis-ci.org/rustindia/mpw-rs)
* [Fraunhofer-AISEC/rabe](https://github.com/Fraunhofer-AISEC/rabe) — 提供几种基于属性的加密（ABE）方案的库
* [racum/rust-djangohashers](https://github.com/racum/rust-djangohashers) — Django项目中使用的密码原语的Rust端口。它不需要Django，仅根据其样式哈希并验证密码。 [![build badge](https://api.travis-ci.org/Racum/rust-djangohashers.svg?branch=master)](https://travis-ci.org/Racum/rust-djangohashers)
* [RNCryptor/rncryptor-rs](https://github.com/RNCryptor/rncryptor-rs) — RNCryptor AES文件格式的纯Rust实现
* [conradkleinespel/rooster](https://github.com/conradkleinespel/rooster) [[rooster](https://crates.io/crates/rooster)] — 在终端中使用的简单密码管理器
* [sfackler/rust-native-tls](https://github.com/sfackler/rust-native-tls) — 本地TLS库的绑定
* [sfackler/rust-openssl](https://github.com/sfackler/rust-openssl) — [OpenSSL](https://www.openssl.org/) 绑定 [![build badge](https://api.travis-ci.org/sfackler/rust-openssl.svg?branch=master)](https://travis-ci.org/sfackler/rust-openssl)
* [kornelski/rust-security-framework](https://github.com/kornelski/rust-security-framework) — 安全框架绑定（OSX native）
* [steffengy/schannel-rs](https://github.com/steffengy/schannel-rs) — Schannel绑定 (Windows native TLS)
* [zebradil/rustotpony](https://github.com/zebradil/rustotpony) — 一次性密码生成器（又名Google Authenticator）的CLI管理器

### 数据库-1

[[数据库](https://crates.io/keywords/database)]

* [sfackler/r2d2](https://github.com/sfackler/r2d2) — 通用连接池 [![build badge](https://api.travis-ci.org/sfackler/r2d2.svg?branch=master)](https://travis-ci.org/sfackler/r2d2)

* NoSQL [[nosql](https://crates.io/keywords/nosql)]

  * [ArangoDB](https://www.arangodb.com)
     * [Rincon](https://github.com/innoave/rincon) — Rust的ArangoDB（NoSQL和图存储库）驱动程序
  * [Cassandra](https://cassandra.apache.org) [[cassandra](https://crates.io/keywords/cassandra), [cql](https://crates.io/keywords/cql)]
    * [AlexPikalov/cdrs](https://github.com/AlexPikalov/cdrs) [[cdrs](https://crates.io/crates/cdrs)] — 用Rust编写的本地客户端 [![build badge](https://api.travis-ci.org/AlexPikalov/cdrs.svg?branch=master)](https://travis-ci.org/AlexPikalov/cdrs)
    * [Metaswitch/cassandra-rs](https://github.com/Metaswitch/cassandra-rs) —  DataStax C/C++客户端的绑定 [![build badge](https://api.travis-ci.org/Metaswitch/cassandra-rs.svg?branch=master)](https://travis-ci.org/Metaswitch/cassandra-rs)
  * CouchDB [[couchdb](https://crates.io/keywords/couchdb)]
    * [chill-rs/chill](https://github.com/chill-rs/chill) [[couchdb](https://crates.io/crates/chill)] — 基于Elastic REST API的Rust客户端 [![build badge](https://api.travis-ci.org/chill-rs/chill.svg?branch=master)](https://travis-ci.org/chill-rs/chill)
    * [Sofa](https://github.com/66Origin/sofa) — CouchDB HTTP REST API的rust接口
  * Crux [[crux](https://crates.io/keywords/crux)]
    * [naomijub/transistor](https://github.com/naomijub/transistor) — 一个Crux数据库客户端 [![Build Status](https://api.travis-ci.org/naomijub/transistor.svg?branch=master)](https://travis-ci.org/naomijub/transistor)
  * [DynamoDB](https://aws.amazon.com/dynamodb/) [[dynamodb](https://crates.io/keywords/dynamodb)]
    * [softprops/dynomite](https://github.com/softprops/dynomite) - 强类型的与`rusoto_dynamodb` 交互方便的库 [![build badge](https://github.com/softprops/dynomite/workflows/Main/badge.svg?branch=master)](https://github.com/softprops/dynomite/actions)
  * Elasticsearch [[elasticsearch](https://crates.io/keywords/elasticsearch)]
    * [benashford/rs-es](https://github.com/benashford/rs-es) [[rs-es](https://crates.io/crates/rs-es)] — 基于[Elastic](https://www.elastic.co/) REST API的Rust客户端 [![build badge](https://api.travis-ci.org/benashford/rs-es.svg?branch=master)](https://travis-ci.org/benashford/rs-es)
    * [elastic-rs/elastic](https://github.com/elastic-rs/elastic) [[elastic](https://crates.io/crates/elastic)] — elastic是一个用Rust编写的用于Elasticsearch的高效模块化API客户端 [![build badge](https://ci.appveyor.com/api/projects/status/csa78tcumdpnbur2?svg=true)](https://ci.appveyor.com/project/KodrAus/elastic)
  * etcd
    * [jimmycuadra/rust-etcd](https://github.com/jimmycuadra/rust-etcd) [[etcd](https://crates.io/crates/etcd)] — CoreOS的etcd客户端库 [![build badge](https://api.travis-ci.org/jimmycuadra/rust-etcd.svg?branch=master)](https://travis-ci.org/jimmycuadra/rust-etcd)
    * [luncj/etcd-rs](https://github.com/luncj/etcd-rs) — An asynchronous etcd client for rust [![build badge](https://api.travis-ci.org/luncj/etcd-rs.svg?branch=master)](https://travis-ci.org/luncj/etcd-rs)
  * ForestDB
    * [vhbit/sherwood](https://github.com/vhbit/sherwood) — [ForestDB](https://github.com/couchbase/forestdb) 绑定 [![build badge](https://api.travis-ci.org/vhbit/sherwood.svg?branch=master)](https://travis-ci.org/vhbit/sherwood)
  * [InfluxDB](https://www.influxdata.com/)
    * [panoptix-za/influxdb-rs](https://github.com/panoptix-za/influxdb-rs) — 异步接口
    * [driftluo/InfluxDBClient-rs](https://github.com/driftluo/InfluxDBClient-rs) — 同步接口 [![build badge](https://api.travis-ci.org/driftluo/InfluxDBClient-rs.svg?branch=master)](https://travis-ci.org/driftluo/InfluxDBClient-rs)
  * LevelDB
    * [skade/leveldb](https://github.com/skade/leveldb) — [LevelDB](https://github.com/google/leveldb) 绑定 [![build badge](https://api.travis-ci.org/skade/leveldb.svg?branch=master)](https://travis-ci.org/skade/leveldb)
  * LMDB [[lmdb](https://crates.io/keywords/lmdb)]
    * [vhbit/lmdb-rs](https://github.com/vhbit/lmdb-rs) [[lmdb-rs](https://crates.io/crates/lmdb-rs)] — [LMDB](https://symas.com/lmdb/) 绑定 [![build badge](https://api.travis-ci.org/vhbit/lmdb-rs.svg?branch=master)](https://travis-ci.org/vhbit/lmdb-rs)
  * MHdb
    * [MHmorgan/mhdb](https://github.com/MHmorgan/mhdb) [[mhdb](https://crates.io/crates/mhdb)] — 完全Rust写的可嵌入的KV存储数据库 [![build badge](https://api.travis-ci.com/MHmorgan/mhdb.svg?branch=master)](https://travis-ci.com/github/MHmorgan/mhdb)
  * MongoDB [[mongodb](https://crates.io/keywords/mongodb)]
    * [mongodb/mongo-rust-driver](https://github.com/mongodb/mongo-rust-driver) [[mongodb](https://crates.io/crates/mongodb)] — [MongoDB](https://www.mongodb.com/) 绑定
  * Neo4j [[cypher](https://crates.io/keywords/cypher), [neo4j](https://crates.io/keywords/neo4j)]
  * Redis [[redis](https://crates.io/keywords/redis)]
    * [mitsuhiko/redis-rs](https://github.com/mitsuhiko/redis-rs) — [Redis](https://redis.io/) 的Rust库 [![build badge](https://api.travis-ci.org/mitsuhiko/redis-rs.svg?branch=master)](https://travis-ci.org/mitsuhiko/redis-rs)
  * [RocksDB](https://rocksdb.org/)
    * [rust-rocksdb/rust-rocksdb](https://github.com/rust-rocksdb/rust-rocksdb) — RocksDB绑定 [![build badge](https://api.travis-ci.org/rust-rocksdb/rust-rocksdb.svg?branch=master)](https://travis-ci.org/rust-rocksdb/rust-rocksdb)
  * [UnQLite](https://unqlite.org/)
    * [zitsen/unqlite.rs](https://github.com/zitsen/unqlite.rs) — UnQLite绑定 [![build badge](https://api.travis-ci.org/zitsen/unqlite.rs.svg?branch=master)](https://travis-ci.org/zitsen/unqlite.rs)
  * [ZooKeeper](https://zookeeper.apache.org/)
    * [bonifaido/rust-zookeeper](https://github.com/bonifaido/rust-zookeeper) [[zookeeper](https://crates.io/crates/zookeeper)] — Apache ZooKeeper的客户端库 [![build badge](https://api.travis-ci.org/bonifaido/rust-zookeeper.svg?branch=master)](https://travis-ci.org/bonifaido/rust-zookeeper)
  * [PickleDB](https://pythonhosted.org/pickleDB/)
    * [seladb/pickledb-rs](https://github.com/seladb/pickledb-rs) — 一个轻量简单的KV存储，深受Python的PickleDB的启发。 [![build badge](https://api.travis-ci.org/seladb/pickledb-rs.svg?branch=master)](https://travis-ci.org/seladb/pickledb-rs)
* SQL [[sql](https://crates.io/keywords/sql)]
  * Generic
    * [launchbadge/sqlx](https://github.com/launchbadge/sqlx) - 强类型支持的异步PostgreSQL/MySQL/SQLite连接池 [![build badge](https://img.shields.io/github/workflow/status/launchbadge/sqlx/Rust/master?style=flat-square)](https://github.com/launchbadge/sqlx)
  * Microsoft SQL
    * [prisma/tiberius](https://github.com/prisma/tiberius) — ![Build status](https://badge.buildkite.com/172053d935f64a275beca911ab20bad34e7597775ce024469d.svg)
  * MySql [[mysql](https://crates.io/keywords/mysql)]
    * [AgilData/mysql-proxy-rs](https://github.com/AgilData/mysql-proxy-rs) — 一个MySQL代理 [![CircleCI](https://circleci.com/gh/AgilData/mysql-proxy-rs/tree/master.svg?style=svg)](https://app.circleci.com/pipelines/github/AgilData/mysql-proxy-rs?branch=master)
    * [blackbeam/mysql_async](https://github.com/blackbeam/mysql_async) [[mysql_async](https://crates.io/crates/mysql_async)] — 基于Tokio的异步Rust Mysql驱动程序 [![CircleCI](https://circleci.com/gh/blackbeam/mysql_async/tree/master.svg?style=shield)](https://app.circleci.com/pipelines/github/blackbeam/mysql_async?branch=master)
    * [blackbeam/rust-mysql-simple](https://github.com/blackbeam/rust-mysql-simple) [[mysql](https://crates.io/crates/mysql)] — 一个MySql原生客户端 [![build badge](https://api.travis-ci.org/blackbeam/rust-mysql-simple.svg?branch=master)](https://travis-ci.org/blackbeam/rust-mysql-simple)
  * PostgreSql [[postgres](https://crates.io/keywords/postgres), [postgresql](https://crates.io/keywords/postgresql)]
    * [sfackler/rust-postgres](https://github.com/sfackler/rust-postgres) [[postgres](https://crates.io/crates/postgres)] — 一个[PostgreSQL](https://www.postgresql.org/) 原生客户端 [![build badge](https://api.travis-ci.org/sfackler/rust-postgres.svg?branch=master)](https://travis-ci.org/sfackler/rust-postgres)
  * Sqlite [[sqlite](https://crates.io/keywords/sqlite)]
    * [rusqlite](https://github.com/rusqlite/rusqlite) — [Sqlite3](https://www.sqlite.org/index.html) 绑定 [![build badge](https://api.travis-ci.org/rusqlite/rusqlite.svg?branch=master)](https://travis-ci.org/rusqlite/rusqlite)
* ORM [[orm](https://crates.io/keywords/orm)]
  * [diesel-rs/diesel](https://github.com/diesel-rs/diesel) — Rust实现的ORM和查询生成器 [![Build Status](https://api.travis-ci.org/diesel-rs/diesel.svg?branch=master)](https://travis-ci.org/diesel-rs/diesel)
  * [ivanceras/rustorm](https://github.com/ivanceras/rustorm) — Rust的一个ORM实现 [![Build Status](https://api.travis-ci.org/ivanceras/rustorm.svg?branch=master)](https://travis-ci.org/ivanceras/rustorm)

### 数据处理

* [amv-dev/yata](https://github.com/amv-dev/yata) — 高性能技术分析库 [![Build Status](https://img.shields.io/github/workflow/status/amv-dev/yata/Rust?branch=master)](https://github.com/amv-dev/yata/actions?query=workflow%3ARust)
* [bluss/ndarray](https://github.com/rust-ndarray/ndarray) — 具有数组视图，多维切片和高效操作的N维数组
* [kernelmachine/utah](https://github.com/kernelmachine/utah) — Dataframe结构和操作的Rust实现
* [ritchie46/polars](https://github.com/ritchie46/polars) - 高速全功能的DataFrame库 [![Build Status](https://api.travis-ci.com/ritchie46/polars.svg?branch=master)](https://travis-ci.com/ritchie46/polars)
* [weld-project/weld](https://github.com/weld-project/weld) — 数据分析应用程序的高性能运行时

### 数据结构

* [billyevans/tst](https://github.com/billyevans/tst) [[tst](https://crates.io/crates/tst)] — 三分搜索树集合 [![build badge](https://api.travis-ci.org/billyevans/tst.svg?branch=master)](https://travis-ci.org/billyevans/tst)
* [rust-itertools/itertools](https://github.com/rust-itertools/itertools) — [![build badge](https://api.travis-ci.org/rust-itertools/itertools.svg?branch=master)](https://travis-ci.org/rust-itertools/itertools)
* [contain-rs](https://github.com/contain-rs) — Rust的std :: collections的扩展
* [danielpclark/array_tool](https://github.com/danielpclark/array_tool) — Rust的数组助手。在Vectors上可用的数组上将使用的一些最常见的方法。用于处理大多数用例的多态实现 [![build badge](https://api.travis-ci.org/danielpclark/array_tool.svg?branch=master)](https://travis-ci.org/danielpclark/array_tool)
* [fizyk20/generic-array](https://github.com/fizyk20/generic-array) – 允许使用typenums大小的数组 [![build badge](https://api.travis-ci.org/fizyk20/generic-array.svg?branch=master)](https://travis-ci.org/fizyk20/generic-array)
* [garro95/priority-queue](https://github.com/garro95/priority-queue)[[priority-queue](https://crates.io/crates/priority-queue)] —实现优先级更改的优先级队列 [![build badge](https://api.travis-ci.org/garro95/priority-queue.svg?branch=master)](https://travis-ci.org/garro95/priority-queue)
* [mrhooray/kdtree-rs](https://github.com/mrhooray/kdtree-rs) — Rust中的K维树，用于快速地理空间索引和最近邻居查找
* [RoaringBitmap/roaring-rs](https://github.com/RoaringBitmap/roaring-rs) – Roaring Bitmaps in Rust
* [orium/rpds](https://github.com/orium/rpds) [[rpds](https://crates.io/crates/rpds)] — Rust的持久化数据结构 [![build badge](https://api.travis-ci.org/orium/rpds.svg?branch=master)](https://travis-ci.org/orium/rpds)
* [pop-os/progress-streams](https://github.com/pop-os/progress-streams) — 实现`dyn io::Read` 或 `dyn io::Write`类型的进度回调
* [whitfin/usher](https://github.com/whitfin/usher) [[usher](https://crates.io/crates/usher)] — Rust的通用资源的参数化路由
* [xfix/enum-map](https://github.com/xfix/enum-map) [[enum-map](https://crates.io/crates/enum-map)] — 一种优化的map实现，用于使用数组存储枚举值 [![build badge](https://api.travis-ci.org/xfix/enum-map.svg?branch=master)](https://travis-ci.org/xfix/enum-map)

### 数据可视化

* [saresend/gust](https://github.com/saresend/Gust) — [![build badge](https://api.travis-ci.org/saresend/Gust.svg?branch=master)](https://travis-ci.org/saresend/Gust)
* [milliams/plotlib](https://github.com/milliams/plotlib) — [![build badge](https://api.travis-ci.org/milliams/plotlib.svg?branch=master)](https://travis-ci.org/milliams/plotlib)
* [igiagkiozis/plotly](https://github.com/igiagkiozis/plotly) — Rust的Plotly库
* [38/plotters](https://github.com/38/plotters) — [![build badge](https://api.travis-ci.org/38/plotters.svg?branch=master)](https://travis-ci.org/38/plotters)

### 日期和时间

[[date](https://crates.io/keywords/date), [time](https://crates.io/keywords/time)]

* [chronotope/chrono](https://github.com/chronotope/chrono) — [![build badge](https://api.travis-ci.org/chronotope/chrono.svg?branch=master)](https://travis-ci.org/chronotope/chrono)
* [yaa110/rust-persian-calendar](https://github.com/yaa110/rust-persian-calendar) — [![build badge](https://api.travis-ci.org/yaa110/rust-persian-calendar.svg?branch=master)](https://travis-ci.org/yaa110/rust-persian-calendar)
* [Mnwa/ms](https://github.com/Mnwa/ms) [[ms-converter](https://crates.io/crates/ms-converter)] — 一个用于可读的时间转换为毫秒的库 [![build badge](https://github.com/Mnwa/ms/workflows/build/badge.svg?branch=master)](https://github.com/Mnwa/ms/actions?query=workflow%3Abuild)

### 分布式系统

* Antimony
  * [antimonyproject/antimony](https://github.com/antimonyproject/antimony) [[antimony](https://crates.io/crates/antimony)] — 流处理/分布式计算平台 [![build badge](https://api.travis-ci.org/antimonyproject/antimony.svg?branch=master)](https://travis-ci.org/antimonyproject/antimony)
* Apache Hadoop
  * [whitfin/efflux](https://github.com/whitfin/efflux) — 易用的Rust Hadoop Streaming和MapReduce接口
* Apache Kafka
  * [fede1024/rust-rdkafka](https://github.com/fede1024/rust-rdkafka) [[rdkafka](https://crates.io/crates/rdkafka)] — [librdkafka](https://github.com/edenhill/librdkafka) 绑定 [![build badge](https://api.travis-ci.org/fede1024/rust-rdkafka.svg?branch=master)](https://travis-ci.org/fede1024/rust-rdkafka)
  * [gklijs/schema_registry_converter](https://github.com/gklijs/schema_registry_converter) — 与 [confluent schema registry](https://www.confluent.io/product/confluent-platform/data-compatibility/)的集成 [![build badge](https://api.travis-ci.org/gklijs/schema_registry_converter.svg?branch=master)](https://travis-ci.org/gklijs/schema_registry_converter)
  * [spicavigo/kafka-rust](https://github.com/spicavigo/kafka-rust) — [![build badge](https://api.travis-ci.org/spicavigo/kafka-rust.svg?branch=master)](https://travis-ci.org/spicavigo/kafka-rust)
* Beanstalkd
  * [schickling/rust-beanstalkd](https://github.com/schickling/rust-beanstalkd) — [Beanstalkd](https://github.com/beanstalkd/beanstalkd) 绑定 [![build badge](https://api.travis-ci.org/schickling/rust-beanstalkd.svg?branch=master)](https://travis-ci.org/schickling/rust-beanstalkd)
* HDFS
  * [hyunsik/hdfs-rs](https://github.com/hyunsik/hdfs-rs) — libhdfs绑定

### 电子邮件

[[email](https://crates.io/keywords/email), [imap](https://crates.io/keywords/imap), [smtp](https://crates.io/keywords/smtp)]

* [GildedHonour/atarashii_imap](https://github.com/GildedHonour/atarashii_imap) — Rust的新しい (atarashii/new) IMAP客户端。它支持简单而安全的连接。 [![build badge](https://api.travis-ci.org/GildedHonour/atarashii_imap.svg?branch=master)](https://travis-ci.org/GildedHonour/atarashii_imap)
* [gsquire/sendgrid-rs](https://github.com/gsquire/sendgrid-rs) — 用于SendGrid API的非官方Rust库 [![build badge](https://api.travis-ci.org/gsquire/sendgrid-rs.svg?branch=master)](https://travis-ci.org/gsquire/sendgrid-rs)
* [lettre/lettre](https://github.com/lettre/lettre) — 一个Rust的SMTP库 [![build badge](https://api.travis-ci.org/lettre/lettre.svg?branch=master)](https://travis-ci.org/lettre/lettre)
* [staktrace/mailparse](https://github.com/staktrace/mailparse) [[mailparse](https://crates.io/crates/mailparse)] — 用于解析实际电子邮件文件的库 [![build badge](https://api.travis-ci.org/staktrace/mailparse.svg?branch=master)](https://travis-ci.org/staktrace/mailparse)
* [meli](https://git.meli.delivery/meli/meli.git) [[meli](https://crates.io/crates/meli)] — 电子邮件客户端
* [jdrouet/mrml](https://github.com/jdrouet/mrml) [![build badge](https://api.travis-ci.org/jdrouet/mrml.svg?branch=main)](https://travis-ci.org/jdrouet/mrml) - 用于生成可在任何邮件客户端上使用的精美电子邮件模板的库
* [jdrouet/catapulte](https://github.com/jdrouet/catapulte) [![build badge](https://api.travis-ci.org/jdrouet/catapulte.svg?branch=main)](https://travis-ci.org/jdrouet/catapulte) - 一种使用[MRML](https://github.com/jdrouet/mrml)模板发送电子邮件的微服务
* [jdrouet/jolimail](https://github.com/jdrouet/jolimail) [![build badge](https://api.travis-ci.org/jdrouet/jolimail.svg?branch=main)](https://travis-ci.org/jdrouet/jolimail) - 构建[MRML](https://github.com/jdrouet/mrml)模板的Web应用程序

### 编码方式

[[编码](https://crates.io/keywords/encoding)]

* ASN.1
  * [alex/rust-asn1](https://github.com/alex/rust-asn1) — Rust的ASN.1（DER）序列化器 [![build badge](https://api.travis-ci.org/alex/rust-asn1.svg?branch=master)](https://travis-ci.org/alex/rust-asn1)
* Bencode
  * [arjantop/rust-bencode](https://github.com/arjantop/rust-bencode) — [Bencode](https://en.wikipedia.org/wiki/Bencode) Rust实现 [![build badge](https://api.travis-ci.org/arjantop/rust-bencode.svg?branch=master)](https://travis-ci.org/arjantop/rust-bencode)
* Binary
  * [arcnmx/nue](https://github.com/arcnmx/nue) — Rust的I/O和二进制数据编码 [![build badge](https://api.travis-ci.org/arcnmx/nue.svg?branch=master)](https://travis-ci.org/arcnmx/nue)
  * [servo/bincode](https://github.com/servo/bincode) — 一个Rust的二进制编解码器 [![build badge](https://api.travis-ci.com/servo/bincode.svg?branch=master)](https://travis-ci.org/servo/bincode)
  * [m4b/goblin](https://github.com/m4b/goblin) [[goblin](https://crates.io/crates/goblin)] — 跨平台，零复制和端感知的二进制解析器 [![build badge](https://api.travis-ci.org/m4b/goblin.svg?branch=master)](https://travis-ci.org/m4b/goblin)
* BSON
  * [mongodb/bson-rust](https://github.com/mongodb/bson-rust) — Rust中对BSON的编解码的支持
* Byte swapping
  * [BurntSushi/byteorder](https://github.com/BurntSushi/byteorder) — 支持大端，小端和本机字节顺序 [![build badge](https://api.travis-ci.org/BurntSushi/byteorder.svg?branch=master)](https://travis-ci.org/BurntSushi/byteorder)
* Cap'n Proto
  * [capnproto/capnproto-rust](https://github.com/capnproto/capnproto-rust) — [![build badge](https://api.travis-ci.org/capnproto/capnproto-rust.svg?branch=master)](https://travis-ci.org/capnproto/capnproto-rust)
* CBOR
  * [serde_cbor](https://crates.io/crates/serde_cbor) — CBOR对serde的支持 [![build badge](https://api.travis-ci.org/pyfisch/cbor.svg?branch=master)](https://travis-ci.org/pyfisch/cbor)
* Character Encoding
  * [hsivonen/encoding_rs](https://github.com/hsivonen/encoding_rs) [[encoding_rs](https://crates.io/crates/encoding_rs)] — 面向Gecko的编码标准的Rust实现 [![build badge](https://api.travis-ci.org/hsivonen/encoding_rs.svg?branch=master)](https://travis-ci.org/hsivonen/encoding_rs)
  * [lifthrasiir/rust-encoding](https://github.com/lifthrasiir/rust-encoding) — [![build badge](https://api.travis-ci.org/lifthrasiir/rust-encoding.svg?branch=master)](https://travis-ci.org/lifthrasiir/rust-encoding)
* CRC
  * [mrhooray/crc-rs](https://github.com/mrhooray/crc-rs) — [![build badge](https://api.travis-ci.org/mrhooray/crc-rs.svg?branch=master)](https://travis-ci.org/mrhooray/crc-rs)
* CSV
  * [BurntSushi/rust-csv](https://github.com/BurntSushi/rust-csv) — 快速，灵活的CSV读写器，支持Serde [![build badge](https://api.travis-ci.org/BurntSushi/rust-csv.svg?branch=master)](https://travis-ci.org/BurntSushi/rust-csv)
* [FlatBuffers](https://google.github.io/flatbuffers/)
  * [frol/flatc-rust](https://github.com/frol/flatc-rust) — 用于cargo构建脚本的FlatBuffers编译器（flatc）集成 [![build badge](https://api.travis-ci.org/frol/flatc-rust.svg?branch=master)](https://travis-ci.org/frol/flatc-rust)
* EDN
  * [naomijub/edn-rs](https://github.com/naomijub/edn-rs) — 解析EDN格式为Rust类型的crate [![Build Status]( https://api.travis-ci.org/naomijub/edn-rs.svg?branch=master)](https://travis-ci.org/naomijub/edn-rs)
* HAR
  * [mandrean/har-rs](https://github.com/mandrean/har-rs) — HTTP存档格式（HAR）序列化和反序列化库 [![Build Status](https://api.travis-ci.org/mandrean/har-rs.svg?branch=master)](https://travis-ci.org/mandrean/har-rs)
* HTML
  * [servo/html5ever](https://github.com/servo/html5ever) — 高性能的浏览器级HTML5解析器 [![build badge](https://api.travis-ci.com/servo/html5ever.svg?branch=master)](https://travis-ci.org/servo/html5ever)
  * [veddan/rust-htmlescape](https://github.com/veddan/rust-htmlescape) — 编解码HTML实体 [![build badge](https://api.travis-ci.org/veddan/rust-htmlescape.svg?branch=master)](https://travis-ci.org/veddan/rust-htmlescape)
* JSON
  * [pikkr/pikkr](https://github.com/pikkr/pikkr) [[pikkr](https://crates.io/crates/pikkr)] — JSON解析器，可直接获取值，而无需在Rust中执行标记化
  * [serde-rs/json](https://github.com/serde-rs/json) [[serde\_json](https://crates.io/crates/serde_json)] — 对[Serde](https://github.com/serde-rs/serde) 框架的JSON支持 [![build badge](https://api.travis-ci.org/serde-rs/json.svg?branch=master)](https://travis-ci.org/serde-rs/json)
  * [simd-lite/simd-json](https://github.com/simd-lite/simd-json) [[simd-json](https://crates.io/crates/simd-json)] — 基于simdjson端口的高性能JSON解析器
  * [maciejhirsz/json-rust](https://github.com/maciejhirsz/json-rust) [[json](https://crates.io/crates/json)] — Rust中的JSON实现 [![build badge](https://api.travis-ci.org/maciejhirsz/json-rust.svg?branch=master)](https://travis-ci.org/maciejhirsz/json-rust)
  * [importcjj/rust-ajson](https://github.com/importcjj/rust-ajson) [[ajson]](https://crates.io/crates/ajson) —  高速获取JSON值 [![build badge](https://api.travis-ci.com/importcjj/rust-ajson.svg?branch=master)](https://travis-ci.com/importcjj/rust-ajson)
* Jsonnet
  * [Qihoo360/rust-jsonnet](https://github.com/Qihoo360/rust-jsonnet)
* MsgPack
  * [3Hren/msgpack-rust](https://github.com/3Hren/msgpack-rust) — 完全Rust写的低层/高层MessagePack实现 [![build badge](https://api.travis-ci.org/3Hren/msgpack-rust.svg?branch=master)](https://travis-ci.org/3Hren/msgpack-rust)
* PEM
  * [jcreekmore/pem-rs](https://github.com/jcreekmore/pem-rs) [[pem](https://crates.io/crates/pem)] — 一种基于Rust的方法来解析和编码PEM数据 [![build badge](https://api.travis-ci.org/jcreekmore/pem-rs.svg?branch=master)](https://travis-ci.org/jcreekmore/pem-rs)
* Postman Collection
  * [mandrean/postman-collection-rs](https://github.com/mandrean/postman-collection-rs) — Postman Collection v1，v2和v2.1序列化和反序列化库 [![Build Status](https://api.travis-ci.org/mandrean/postman-collection-rs.svg?branch=master)](https://travis-ci.org/mandrean/postman-collection-rs)
* ProtocolBuffers
  * [danburkert/prost](https://github.com/danburkert/prost) — [![build badge](https://api.travis-ci.org/danburkert/prost.svg?branch=master)](https://travis-ci.org/danburkert/prost)
  * [stepancheg/rust-protobuf](https://github.com/stepancheg/rust-protobuf) — [![build badge](https://api.travis-ci.org/stepancheg/rust-protobuf.svg?branch=master)](https://travis-ci.org/stepancheg/rust-protobuf)
* RON (Rusty Object Notation)
  * [https://github.com/ron-rs/ron](https://github.com/ron-rs/ron) — [![build badge](https://api.travis-ci.org/ron-rs/ron.svg?branch=master)](https://travis-ci.org/https://github.com/ron-rs/ron)
* Tnetstring
  * [erickt/rust-tnetstring](https://github.com/erickt/rust-tnetstring) — [![build badge](https://api.travis-ci.org/erickt/rust-tnetstring.svg?branch=master)](https://travis-ci.org/erickt/rust-tnetstring)
* TOML
  * [alexcrichton/toml-rs](https://github.com/alexcrichton/toml-rs) — [![build badge](https://api.travis-ci.com/alexcrichton/toml-rs.svg?branch=master)](https://travis-ci.org/alexcrichton/toml-rs)
* XML
  * [tafia/quick-xml](https://github.com/tafia/quick-xml) — 高性能XML读写器 [![build badge](https://api.travis-ci.org/tafia/quick-xml.svg?branch=master)](https://travis-ci.org/tafia/quick-xml)
  * [Florob/RustyXML](https://github.com/Florob/RustyXML) — Rust写的XML读写器 [![build badge](https://api.travis-ci.org/Florob/RustyXML.svg?branch=master)](https://travis-ci.org/Florob/RustyXML)
  * [shepmaster/sxd-document](https://github.com/shepmaster/sxd-document) — Rust写的XML库 [![build badge](https://api.travis-ci.org/shepmaster/sxd-document.svg?branch=master)](https://travis-ci.org/shepmaster/sxd-document)
  * [shepmaster/sxd-xpath](https://github.com/shepmaster/sxd-xpath) — Rust写的XPath库 [![build badge](https://api.travis-ci.org/shepmaster/sxd-xpath.svg?branch=master)](https://travis-ci.org/shepmaster/sxd-xpath)
  * [netvl/xml-rs](https://github.com/netvl/xml-rs) — 流式XML库 [![build badge](https://api.travis-ci.org/netvl/xml-rs.svg?branch=master)](https://travis-ci.org/netvl/xml-rs)
  * [media-io/yaserde](https://github.com/media-io/yaserde) — 另一个专用于XML的序列化器/反序列化器 [![build badge](https://api.travis-ci.org/media-io/yaserde.svg?branch=master)](https://travis-ci.org/media-io/yaserde)
* YAML
  * [chyh1990/yaml-rust](https://github.com/chyh1990/yaml-rust) — Rust缺少的YAML 1.2实现 [![build badge](https://api.travis-ci.org/chyh1990/yaml-rust.svg?branch=master)](https://travis-ci.org/chyh1990/yaml-rust)
  * [dtolnay/serde-yaml](https://github.com/dtolnay/serde-yaml) [[serde\_yaml](https://crates.io/crates/serde_yaml)] — [Serde](https://github.com/serde-rs/serde) 框架的YAML支持 [![build badge](https://api.travis-ci.org/dtolnay/serde-yaml.svg?branch=master)](https://travis-ci.org/dtolnay/serde-yaml)
  * [kimhyunkang/libyaml-rust](https://github.com/kimhyunkang/libyaml-rust) — [libyaml](https://pyyaml.org/wiki/LibYAML) 绑定 [![build badge](https://api.travis-ci.org/kimhyunkang/libyaml-rust.svg?branch=master)](https://travis-ci.org/kimhyunkang/libyaml-rust)
  * [vitiral/stfu8](https://github.com/vitiral/stfu8) — UTF-8中的Sorta文本格式 [![build badge](https://api.travis-ci.org/vitiral/stfu8.svg?branch=master)](https://travis-ci.org/vitiral/stfu8)

### 文件系统

[[文件系统](https://crates.io/keywords/filesystem)]
* Libraries
  * [jonhkr/rust-file-seq](https://github.com/jonhkr/rust-file-seq) -> 使用文件系统作为存储的故障安全序列实现 [![Crates.io](https://img.shields.io/crates/v/file-seq)](https://crates.io/crates/file-seq) [![GitHub Workflow Status](https://img.shields.io/github/workflow/status/jonhkr/rust-file-seq/Rust)](https://github.com/jonhkr/rust-file-seq/actions)
* Operations
  * [pop-os/dbus-udisks2](https://github.com/pop-os/dbus-udisks2) -> UDisks2 DBus API
  * [pop-os/sys-mount](https://github.com/pop-os/sys-mount) — mount` / `umount2`系统调用的高层抽象
  * [vitiral/path_abs](https://github.com/vitiral/path_abs) — 绝对可序列化的路径类型和关联的方法 [![build badge](https://api.travis-ci.org/vitiral/path_abs.svg?branch=master)](https://travis-ci.org/webdesus/fs_extr://travis-ci.org/vitiral/path_abs)
  * [webdesus/fs_extra](https://github.com/webdesus/fs_extra) — std::io std::fs和std::io标准库的扩展 [![build badge](https://api.travis-ci.org/webdesus/fs_extra.svg?branch=master)](https://travis-ci.org/webdesus/fs_extra)
* Temporary Files
  * [rust-lang-deprecated/tempdir](https://github.com/rust-lang-deprecated/tempdir) — 临时目录库 [![build badge](https://api.travis-ci.org/rust-lang-deprecated/tempdir.svg?branch=master)](https://travis-ci.org/rust-lang-deprecated/tempdir)
  * [Stebalien/tempfile](https://github.com/Stebalien/tempfile) — 临时文件库 [![build badge](https://api.travis-ci.org/Stebalien/tempfile.svg?branch=master)](https://travis-ci.org/Stebalien/tempfile)
  * [Stebalien/xattr](https://github.com/Stebalien/xattr) [[xattr](https://crates.io/crates/xattr)] — 列出和操作unix扩展文件属性 [![build badge](https://api.travis-ci.org/Stebalien/xattr.svg?branch=master)](https://travis-ci.org/Stebalien/xattr)
  * [zboxfs/zbox](https://github.com/zboxfs/zbox) [[zbox](https://crates.io/crates/zbox)] — 零细节，注重隐私的可嵌入文件系统 [![build badge](https://api.travis-ci.org/zboxfs/zbox.svg?branch=master)](https://travis-ci.org/zboxfs/zbox)

### 函数式编程
[[函数式编程](https://crates.io/keywords/fp)]
* Prelude
  * [JasonShin/fp-core.rs](https://github.com/JasonShin/fp-core.rs) — 一个函数式编程的Rust库 [![Build Status](https://api.travis-ci.com/JasonShin/fp-core.rs.svg?branch=master)](https://travis-ci.com/JasonShin/fp-core.rs)

### 游戏开发

See also [Are we game yet?](https://arewegameyet.rs)
* Allegro
  * [SiegeLord/RustAllegro](https://github.com/SiegeLord/RustAllegro) — [Allegro 5](https://liballeg.org/) 绑定 [![build badge](https://api.travis-ci.org/SiegeLord/RustAllegro.svg?branch=master)](https://travis-ci.org/SiegeLord/RustAllegro)
* Challonge
  * [vityafx/challonge-rs](https://github.com/vityafx/challonge-rs) [[challonge](https://crates.io/crates/challonge)] — Challonge REST API的客户端库。帮助组织比赛 [![build badge](https://api.travis-ci.org/vityafx/challonge-rs.svg?branch=master)](https://travis-ci.org/vityafx/challonge-rs)
* Corange
  * [lucidscape/corange-rs](https://github.com/lucidscape/corange-rs) — [Corange](https://github.com/orangeduck/Corange) 绑定
* Entity-Component Systems (ECS)
  * [amethyst/specs](https://github.com/amethyst/specs) — 规格并行ECS [![build badge](https://api.travis-ci.org/amethyst/specs.svg?branch=master)](https://travis-ci.org/amethyst/specs)
  * [legion](https://github.com/amethyst/legion) — 具有最少样板的功能丰富的高性能ECS库游戏引擎 [![build badge](https://github.com/amethyst/legion/workflows/CI/badge.svg?branch=master)](https://github.com/amethyst/legion/actions)
* Game Engines
  * [Amethyst](https://amethyst.rs) — 面向数据的游戏引擎 - [![Crates.io](https://img.shields.io/crates/v/amethyst)](https://crates.io/crates/amethyst) [![license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/amethyst/amethyst/blob/main/COPYING)
  * [Bevy](https://github.com/bevyengine/bevy) 一款Rust构建的令人耳目一新的简单数据驱动游戏引擎 - [![Crates.io](https://img.shields.io/crates/v/bevy.svg)](https://crates.io/crates/bevy)
[![license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/bevyengine/bevy/blob/master/LICENSE)
[![Crates.io](https://img.shields.io/crates/d/bevy.svg)](https://crates.io/crates/bevy)
  * [ggez](https://github.com/ggez/ggez) — 用于制作2D游戏轻量级游戏框架 - [![Crates.io](https://img.shields.io/crates/v/ggez.svg)](https://crates.io/crates/ggez) [![license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/ggez/ggez/blob/master/LICENSE)
  * [harmony](https://github.com/StarArawn/harmony) — 一个先进的使用wgpu的3D/2D游戏引擎
  * [Kiss3d](http://kiss3d.org) — 一个Rust写的，简单，傻瓜式的3D图形引擎
  * [oxidator](https://github.com/Ruddle/oxidator) — 一个用Rust和WebGPU编写的即时战略游戏/引擎
  * [Piston](https://www.piston.rs/) — [![Crates.io](https://img.shields.io/crates/v/piston.svg?style=flat-square)](https://crates.io/crates/piston) [![Crates.io](https://img.shields.io/crates/l/piston.svg)](https://github.com/PistonDevelopers/piston/blob/master/LICENSE)
  * [Unrust](https://github.com/unrust/unrust) — unrust — 完全rust写的（webgl 2.0/原生）的游戏引擎
* [Godot](https://godotengine.org/)
  * [godot-rust/godot-rust](https://github.com/godot-rust/godot-rust) [[gdnative](https://crates.io/crates/gdnative)] - Godot游戏引擎的Rust绑定 [![build badge](https://api.travis-ci.com/godot-rust/godot-rust.svg?branch=master)](https://travis-ci.com/github/godot-rust/godot-rust)
* [SDL](http://www.libsdl.org/) [[sdl](https://crates.io/keywords/sdl)]
  * [brson/rust-sdl](https://github.com/brson/rust-sdl) — SDL1 绑定 [![build badge](https://api.travis-ci.org/brson/rust-sdl.svg?branch=master)](https://travis-ci.org/brson/rust-sdl)
  * [Rust-SDL2/rust-sdl2](https://github.com/Rust-SDL2/rust-sdl2) — SDL2 绑定 [![build badge](https://api.travis-ci.org/Rust-SDL2/rust-sdl2.svg?branch=master)](https://travis-ci.org/Rust-SDL2/rust-sdl2)
* SFML
  * [jeremyletang/rust-sfml](https://github.com/jeremyletang/rust-sfml) — [SFML](https://www.sfml-dev.org/) 绑定 [![build badge](https://api.travis-ci.org/jeremyletang/rust-sfml.svg?branch=master)](https://travis-ci.org/jeremyletang/rust-sfml)
* Tcod-rs
  * [tomassedovic/tcod-rs](https://github.com/tomassedovic/tcod-rs) — Libtcod 绑定
* Victorem
  * [VictoremWinbringer/Victorem](https://github.com/VictoremWinbringer/Victorem) [[Victorem](https://crates.io/crates/Victorem)] — 简单的UDP游戏服务器和UDP客户端框架，用于创建简单的2D和3D在线游戏原型 [![build badge](https://api.travis-ci.org/VictoremWinbringer/Victorem.svg?branch=master)](https://travis-ci.org/VictoremWinbringer/Victorem)
* Voxlap
  * [bbodi/rust-voxlap](https://github.com/bbodi/rust-voxlap) — [Voxlap](http://advsys.net/ken/voxlap.htm) 绑定
* [Awesome wgpu](https://github.com/rofrol/awesome-wgpu) — wgpu代码和资源的精选列表   

### 地理空间

* [DaveKram/coord_transforms](https://github.com/DaveKram/coord_transforms) [[coord_transforms](https://crates.io/crates/coord_transforms)] — 坐标变换（2-d，3- d和地理空间） [![build badge](https://api.travis-ci.org/DaveKram/coord_transforms.svg?branch=master)](https://travis-ci.org/DaveKram/coord_transforms)
* [Georust](https://github.com/georust) — Rust编写的地理空间工具和库
* [rust-reverse-geocoder](https://github.com/ggcode1/rrgeo) — 受https://github.com/thampiman/reverse-geocoder的启发，Rust中的一种高速离线地理编码器
* [vlopes11/geomorph](https://github.com/vlopes11/geomorph) [[geomorph](https://crates.io/crates/geomorph)] — UTM，LatLon和MGRS坐标之间的转换 [![build badge](https://api.travis-ci.org/vlopes11/geomorph.svg?branch=master)](https://travis-ci.org/vlopes11/geomorph)

### 图形学-1

* [gfx-rs/wgpu](https://github.com/gfx-rs/wgpu) - 基于gfx-hal的本地WebGPU实现 [![build badge](https://github.com/gfx-rs/wgpu/workflows/CI/badge.svg?branch=master)](https://github.com/gfx-rs/wgpu/actions)
* [gfx-rs/gfx](https://github.com/gfx-rs/gfx) — Rust的高性能，无绑定图形API [![build badge](https://api.travis-ci.org/gfx-rs/gfx.svg?branch=master)](https://travis-ci.org/gfx-rs/gfx)
* Font
  * [redox-os/rusttype](https://github.com/redox-os/rusttype) — FreeType之类的库的纯Rust替代实现 [![build badge](https://api.travis-ci.org/redox-os/rusttype.svg?branch=master)](https://travis-ci.org/redox-os/rusttype)
  * [RazrFalcon/rustybuzz](https://github.com/RazrFalcon/rustybuzz) - Rust的增量harfbuzz端口 [![build badge](https://api.travis-ci.org/RazrFalcon/rustybuzz.svg?branch=master)](https://travis-ci.org/RazrFalcon/rustybuzz)
* OpenGL [[opengl](https://crates.io/keywords/opengl)]
  * [brendanzab/gl-rs](https://github.com/brendanzab/gl-rs) — [![build badge](https://api.travis-ci.org/brendanzab/gl-rs.svg?branch=master)](https://travis-ci.org/brendanzab/gl-rs)
  * [glium/glium](https://github.com/glium/glium) — Rust语言的安全OpenGL包装器 [![build badge](https://api.travis-ci.org/glium/glium.svg?branch=master)](https://travis-ci.org/glium/glium)
  * [Kiss3d](http://kiss3d.org) — 绘制简单的几何图形 [![build badge](https://api.travis-ci.org/sebcrozet/kiss3d.svg?branch=master)](https://api.travis-ci.org/repositories/sebcrozet/kiss3d)
  * [PistonDevelopers/glfw-rs](https://github.com/PistonDevelopers/glfw-rs) — [![build badge](https://api.travis-ci.org/PistonDevelopers/glfw-rs.svg?branch=master)](https://travis-ci.org/PistonDevelopers/glfw-rs)
  * [glutin](https://crates.io/crates/glutin) — [GLFW](https://www.glfw.org/) 的Rust替代 [![build badge](https://api.travis-ci.org/rust-windowing/glutin.svg?branch=master)](https://travis-ci.org/rust-windowing/glutin)
* PDF
  * [kaj/rust-pdf](https://github.com/kaj/rust-pdf) — [![build badge](https://api.travis-ci.org/kaj/rust-pdf.svg?branch=master)](https://travis-ci.org/kaj/rust-pdf)
  * [fschutt/printpdf](https://github.com/fschutt/printpdf) — PDF生成库 [![build badge](https://api.travis-ci.org/fschutt/printpdf.svg?branch=master)](https://travis-ci.org/fschutt/printpdf)
  * [J-F-Liu/lopdf](https://github.com/J-F-Liu/lopdf) — PDF文档操作 [![build badge](https://api.travis-ci.org/J-F-Liu/lopdf.svg?branch=master)](https://travis-ci.org/J-F-Liu/lopdf)
  * [WASM-PDF](https://github.com/jussiniinikoski/wasm-pdf) – 使用JavaScript和WASM（WebAssembly）生成PDF文件 [![build badge](https://api.travis-ci.org/jussiniinikoski/wasm-pdf.svg?branch=master)](https://travis-ci.org/jussiniinikoski/wasm-pdf)
* [Vulkan](https://www.khronos.org/vulkan/) [[vulkan](https://crates.io/keywords/vulkan)]
  * [vulkano](https://github.com/vulkano-rs/vulkano) [[vulkano](https://crates.io/crates/vulkano)] — [![build badge](https://api.travis-ci.org/vulkano-rs/vulkano.svg?branch=master)](https://travis-ci.org/vulkano-rs/vulkano)

### 图形处理

* [kud1ing/tinkerpop-rs](https://github.com/kud1ing/tinkerpop-rs) — 如何在Rust使用Apache TinkerPop的示例

### GUI

[[gui](https://crates.io/keywords/gui)]

* [autopilot-rs/autopilot-rs](https://github.com/autopilot-rs/autopilot-rs) — 一个Rust的简单，跨平台的GUI自动化库
* [maps4print/azul](https://github.com/maps4print/azul) — 由Mozilla WebRender渲染引擎支持的免费，功能，面向IMGUI的GUI框架，用于快速开发用Rust编写的桌面应用程序 [![build badge](https://api.travis-ci.org/maps4print/azul.svg?branch=master)](https://travis-ci.org/maps4print/azul)
* [Druid](https://github.com/linebender/druid) [[druid](https://crates.io/crates/druid)] — [Druid](https://linebender.org/druid/), 一个使用Rust原生的UI设计工具包 [![build badge](https://github.com/linebender/druid/workflows/.github/workflows/ci.yml/badge.svg)](https://github.com/linebender/druid/actions)
* [OrbTk](https://github.com/redox-os/orbtk) — Orbital Widget Toolkit是使用SDL2的多平台（G）UI工具包构建和测试 [![Build and test](https://github.com/redox-os/orbtk/workflows/build/badge.svg?branch=develop)](https://github.com/redox-os/orbtk/actions)
* [PistonDevelopers/conrod](https://github.com/PistonDevelopers/conrod/) — 完全用Rust编写的易于使用的即时模式2D GUI库 [![build badge](https://api.travis-ci.org/PistonDevelopers/conrod.svg?branch=master)](https://travis-ci.org/PistonDevelopers/conrod)
* [rise-ui](https://github.com/rise-ui/rise) — 基于简单组件的跨平台GUI工具包，用于开发美观且用户友好的界面

* Cocoa
  * [kylewlacy/sorbet-cocoa](https://github.com/kylewlacy/sorbet-cocoa)
  * [servo/core-foundation-rs](https://github.com/servo/core-foundation-rs) — [![build badge](https://api.travis-ci.com/servo/core-foundation-rs.svg?branch=master)](https://travis-ci.org/servo/core-foundation-rs)
* [FLTK](https://www.fltk.org/)
  * [fltk-rs](https://github.com/MoAlyousef/fltk-rs) — FLTK Rust绑定 [![Build](https://github.com/MoAlyousef/fltk-rs/workflows/Build/badge.svg?branch=master)](https://github.com/MoAlyousef/fltk-rs/actions)
* [Flutter](https://flutter.dev/)
  * [flutter-rs](https://github.com/flutter-rs/flutter-rs) — 基于dart和rust的构建flutter桌面应用程序
* [GTK+](https://www.gtk.org/) [[gtk](https://crates.io/keywords/gtk)]
  * [gtk-rs/gtk](https://github.com/gtk-rs/gtk) — GTK+ 绑定 [![build badge](https://api.travis-ci.org/gtk-rs/gtk.svg?branch=master)](https://travis-ci.org/gtk-rs/gtk)
  * [relm](https://github.com/antoyo/relm) — 受Elm [![build badge](https://api.travis-ci.org/antoyo/relm.svg?branch=master)](https://travis-ci.org/antoyo/relm)启发的基于GTK +的异步GUI库
* [ImGui](https://github.com/ocornut/imgui)
  * [imgui-rs](https://github.com/imgui-rs/imgui-rs) — ImGui绑定 [![Build Status](https://github.com/imgui-rs/imgui-rs/workflows/ci/badge.svg?branch=master)](https://github.com/imgui-rs/imgui-rs/actions)
* [IUP](http://webserver2.tecgraf.puc-rio.br/iup/)
  * [clear-coat](https://github.com/jminer/clear-coat) — Clear Coat是IUP GUI库的Rust包装
  * [dcampbell24/iup-rust](https://github.com/dcampbell24/iup-rust) — IUP 绑定 [![build badge](https://api.travis-ci.org/dcampbell24/iup-rust.svg?branch=master)](https://travis-ci.org/dcampbell24/iup-rust)
  * [Kiss-ui](https://github.com/KISS-UI/kiss-ui) — 基于IUP构建的简单UI框架 [![Build Status](https://api.travis-ci.org/cybergeek94/kiss-ui.svg?branch=master)](https://travis-ci.org/cybergeek94/kiss-ui)
* [libui](https://github.com/andlabs/libui)
  * [rust-native-ui/libui-rs](https://github.com/rust-native-ui/libui-rs) — libui绑定 [![build badge](https://api.travis-ci.org/rust-native-ui/libui-rs.svg?branch=master)](https://travis-ci.org/rust-native-ui/libui-rs).
* [Nuklear](https://github.com/Immediate-Mode-UI/Nuklear)
  * [nuklear-rust](https://github.com/snuk182/nuklear-rust) — Nuklear Rust绑定
* [Qt](https://doc.qt.io)
  * [woboq/qmetaobject-rs](https://github.com/woboq/qmetaobject-rs) — 通过在编译时构建QMetaObject来集成Qml和Rust [![build badge](https://api.travis-ci.org/woboq/qmetaobject-rs.svg?branch=master)](https://travis-ci.org/woboq/qmetaobject-rs)
  * [cyndis/qmlrs](https://github.com/cyndis/qmlrs) — QtQuick绑定 [![build badge](https://api.travis-ci.org/cyndis/qmlrs.svg?branch=master)](https://travis-ci.org/cyndis/qmlrs)
  * [kitech/qt.rs](https://github.com/kitech/qt.rs) — Qt5绑定
  * [Rust Qt Binding Generator](https://phabricator.kde.org/source/rust-qt-binding-generator/) — 由KDE托管的绑定生成器
  * [rust-qt](https://github.com/rust-qt) —
  * [White-Oak/qml-rust](https://github.com/White-Oak/qml-rust) — QML绑定 [![build badge](https://api.travis-ci.org/White-Oak/qml-rust.svg?branch=master)](https://travis-ci.org/White-Oak/qml-rust)
* [saurvs/nfd-rs](https://github.com/saurvs/nfd-rs) — [nativefiledialog](https://github.com/mlabbe/nativefiledialog) 绑定
* [Sciter](https://sciter.com/)
  * [sciter-sdk/rust-sciter](https://github.com/sciter-sdk/rust-sciter) — Sciter绑定 [![build badge](https://ci.appveyor.com/api/projects/status/github/sciter-sdk/rust-sciter?svg=true)](https://ci.appveyor.com/project/sciter-sdk/rust-sciter)
* [hecrj/iced](https://github.com/hecrj/iced) — 受Elm的启发的Rust的跨平台GUI库，着重于简单性和类型安全性。
* [ivanceras/sauron-native](https://github.com/ivanceras/sauron-native) - 一个真正的本地和跨平台GUI库。一种统一的代码可以作为本机GUI，HTML Web和TUI运行。 [![Build Status](https://api.travis-ci.com/ivanceras/sauron-native.svg?branch=master)](https://travis-ci.com/github/ivanceras/sauron-native)
* [tauri-apps/tauri](https://github.com/tauri-apps/tauri) — 用于构建高度安全的本机应用程序的工具链，这些应用程序具有很小的二进制文件，并且在由[webview](https://github.com/webview/webview)支持的HTML，JS和CSS层中非常快速 [![test library](https://img.shields.io/github/workflow/status/tauri-apps/tauri/test%20library?label=test%20library)](https://github.com/tauri-apps/tauri/actions?query=workflow%3A%22test+library%22)

### 图像处理

* [abonander/img_hash](https://github.com/abonander/img_hash) — 感知图像的hash和图片相同相似性的比较 [![Build Status](https://api.travis-ci.org/abonander/img_hash.svg?branch=master)](https://travis-ci.org/abonander/img_hash)
* [image-rs/image](https://github.com/image-rs/image) — 基本的图像处理功能和用于与图像格式之间进行转换的方法 [![build badge](https://api.travis-ci.org/image-rs/image.svg?branch=master)](https://travis-ci.org/image-rs/image)
* [image-rs/imageproc](https://github.com/image-rs/imageproc) — 一个基于`image`库的图像处理库 [![Build Status](https://api.travis-ci.org/image-rs/imageproc.svg?branch=master)](https://travis-ci.org/image-rs/imageproc)
* [twistedfall/opencv-rust](https://github.com/twistedfall/opencv-rust) — OpenCV的Rust绑定 [![build badge](https://api.travis-ci.org/twistedfall/opencv-rust.svg?branch=cv2)](https://travis-ci.org/twistedfall/opencv-rust)
* [teovoinea/steganography](https://github.com/teovoinea/steganography) [[steganography](https://crates.io/crates/steganography)] — 一个简单的隐写术库 [![build badge](https://api.travis-ci.org/teovoinea/steganography.svg?branch=master)](https://travis-ci.org/teovoinea/steganography)

### 语言规范

* [shnewto/bnf](https://github.com/shnewto/bnf) — 用于解析Backus–Naur形式的上下文无关语法的库 [![build badge](https://api.travis-ci.org/shnewto/bnf.svg?branch=master)](https://travis-ci.org/shnewto/bnf)

### 日志

[[日志](https://crates.io/keywords/log)]

* [seanmonstar/pretty-env-logger](https://github.com/seanmonstar/pretty-env-logger) — Rust美观易用的日志模块 [![Build Status](https://api.travis-ci.org/seanmonstar/pretty-env-logger.svg?branch=master)](https://travis-ci.org/seanmonstar/pretty-env-logger)
* [rust-lang/log](https://github.com/rust-lang/log) — 一个Rust的日志模块实现 [![Build Status](https://api.travis-ci.org/rust-lang/log.svg?branch=master)](https://travis-ci.org/rust-lang/log)
* [slog-rs/slog](https://github.com/slog-rs/slog) — 一个Rust结构化的可组合的日志模块 [![Build Status](https://api.travis-ci.org/slog-rs/slog.svg?branch=master)](https://travis-ci.org/slog-rs/slog)
* [estk/log4rs](https://github.com/estk/log4rs) — 以Java的Logback和log4j库为原型灵活可配置的日志记录框架 [![CircleCI](https://circleci.com/gh/estk/log4rs.svg?style=shield)](https://app.circleci.com/pipelines/github/estk/log4rs)
* [tokio-rs/tracing](https://github.com/tokio-rs/tracing) — 用于异步感知的结构化日志，错误处理，指标等的应用程序级别跟踪框架 [![Build Status](https://github.com/tokio-rs/tracing/workflows/CI/badge.svg?branch=master)](https://github.com/tokio-rs/tracing/actions?query=workflow%3ACI)

### 宏

* cute
  * [mattgathu/cute](https://github.com/mattgathu/cute) — Rust的用于Python风格列表推导的宏 [![Build Status](https://api.travis-ci.org/mattgathu/cute.svg?branch=master)](https://travis-ci.org/tensorflow/rust)
* hado
  * [ludat/hado-rs](https://github.com/ludat/hado-rs) — 类似haskell的do表达式的宏
* [Linq-in-Rust](https://github.com/StardustDL/Linq-in-Rust) - 类似于C#-LINQ的表达式的宏和方法 [![CI](https://github.com/StardustDL/Linq-in-Rust/workflows/CI/badge.svg?branch=master)](https://github.com/StardustDL/Linq-in-Rust/actions?query=workflow%3ACI)

### 标记语言

* CommonMark
  * [raphlinus/pulldown-cmark](https://github.com/raphlinus/pulldown-cmark) — [CommonMark](https://commonmark.org/) Rust的一种解析器

### 移动开发

[移动开发](https://github.com/Geal/rust_on_mobile)

* Android
  * [rust-windowing/android-rs-glue](https://github.com/rust-windowing/android-rs-glue) — Rust和Android之间的粘合 [![build badge](https://api.travis-ci.org/rust-windowing/android-rs-glue.svg?branch=master)](https://travis-ci.org/rust-windowing/android-rs-glue)
* iOS
  * [TimNN/cargo-lipo](https://github.com/TimNN/cargo-lipo) — cargo lipo子命令，可自动创建用于iOS应用程序的通用库 [![build badge](https://api.travis-ci.org/TimNN/cargo-lipo.svg?branch=master)](https://travis-ci.org/TimNN/cargo-lipo)
  * [vhbit/ObjCrust](https://github.com/vhbit/ObjCrust) — 使用Rust创建iOS静态库
* Pebble
  * [andars/pebble.rs](https://github.com/andars/pebble.rs) — 一个允许使用Rust来开发Pebble应用程序的crate
* Android / iOS
  * [i-schuetz/rust_android_ios](https://github.com/i-schuetz/rust_android_ios) — 用Android使用共享Rust LIB和iOS使用rust-swig和cbindgen的一个例子

### 网络编程

* HTTP
  * [pop-os/parallel-getter](https://github.com/pop-os/parallel-getter) — 用并行GET请求来下载文件以最大程度地利用带宽
  * [pop-os/url-crawler](https://github.com/pop-os/url-crawler) — 一个可配置的并行Web爬虫，旨在搜寻网站内容
  * [pop-os/url-scraper](https://github.com/pop-os/url-scraper) — 从HTML页面抓取URL
* FTP
  * [mattnenterprise/rust-ftp](https://github.com/mattnenterprise/rust-ftp) — 一个Rust实现的 [FTP](https://en.wikipedia.org/wiki/File_Transfer_Protocol) 客户端 [![build badge](https://api.travis-ci.org/mattnenterprise/rust-ftp.svg?branch=master)](https://travis-ci.org/mattnenterprise/rust-ftp)
* gRPC
  * [tikv/grpc-rs](https://github.com/tikv/grpc-rs) — 基于C Core库和Future构建的Rust的gRPC库 [![Build Status](https://api.travis-ci.org/tikv/grpc-rs.svg?branch=master)](https://travis-ci.org/tikv/grpc-rs)
* IPNetwork
  * [achanda/ipnetwork](https://github.com/achanda/ipnetwork) — 一个完全Rust实现的使用IP网络的库 [![build badge](https://api.travis-ci.org/achanda/ipnetwork.svg?branch=master)](https://travis-ci.org/achanda/ipnetwork)
  * [candrew/netsim](https://github.com/canndrew/netsim) — 用于网络仿真和测试的Rust库 [![build badge](https://api.travis-ci.org/canndrew/netsim.svg?branch=master)](https://travis-ci.org/canndrew/netsim)
* JSON-RPC
  * [vlopes11/futures-jsonrpc](https://github.com/vlopes11/futures-jsonrpc) [[futures-jsonrpc](https://crates.io/crates/futures-jsonrpc)] — JSON-RPC的Future实现 [![build badge](https://api.travis-ci.org/vlopes11/futures-jsonrpc.svg?branch=master)](https://travis-ci.org/vlopes11/futures-jsonrpc)
* Low level
  * [libpnet/libpnet](https://github.com/libpnet/libpnet) — 跨平台的低层网络 [![build badge](https://api.travis-ci.org/libpnet/libpnet.svg?branch=master)](https://travis-ci.org/libpnet/libpnet)
  * [smoltcp-rs/smoltcp](https://github.com/smoltcp-rs/smoltcp) — 独立的，事件驱动的TCP/IP堆栈，设计用于裸机实时系统 [![build badge](https://api.travis-ci.org/smoltcp-rs/smoltcp.svg?branch=master)](https://travis-ci.org/smoltcp-rs/smoltcp)
  * [tokio-rs/tokio](https://github.com/tokio-rs/tokio) — 一种网络应用程序框架，用于客户端和服务器的快速开发和高度可扩展的生产部署
  * [dylanmckay/protocol](https://github.com/dylanmckay/protocol) — 定制的TCP/UDP协议定义
  * [actix/actix](https://github.com/actix/actix) — Actor库的Rust实现 [![build badge](https://api.travis-ci.org/actix/actix.svg?branch=master)](https://travis-ci.org/actix/actix)
* NanoMsg
  * [thehydroimpulse/nanomsg.rs](https://github.com/thehydroimpulse/nanomsg.rs) — [nanomsg](https://nanomsg.org/) 绑定 [![build badge](https://api.travis-ci.org/thehydroimpulse/nanomsg.rs.svg?branch=master)](https://travis-ci.org/thehydroimpulse/nanomsg.rs)
* Nng
  * [neachdainn/nng-rs](https://gitlab.com/neachdainn/nng-rs) [[Nng](https://crates.io/crates/nng)] — [Nng (nanomsg v2)](https://nng.nanomsg.org/index.html) 绑定 [![build badge](https://gitlab.com/neachdainn/nng-rs/badges/master/pipeline.svg)](https://gitlab.com/neachdainn/nng-rs/pipelines)
* NNTP
  * [mattnenterprise/rust-nntp](https://github.com/mattnenterprise/rust-nntp) — 一个Rust实现 [NNTP](https://en.wikipedia.org/wiki/Network_News_Transfer_Protocol) 客户端 [![build badge](https://api.travis-ci.org/mattnenterprise/rust-nntp.svg?branch=master)](https://travis-ci.org/mattnenterprise/rust-nntp)
* POP3
  * [mattnenterprise/rust-pop3](https://github.com/mattnenterprise/rust-pop3) — 一个Rust实现[POP3](https://en.wikipedia.org/wiki/Post_Office_Protocol) 客户端 [![build badge](https://api.travis-ci.org/mattnenterprise/rust-pop3.svg?branch=master)](https://travis-ci.org/mattnenterprise/rust-pop3)
* SSH
  * [alexcrichton/ssh2-rs](https://github.com/alexcrichton/ssh2-rs) — [libssh2](https://www.libssh2.org/) 绑定 [![build badge](https://api.travis-ci.com/alexcrichton/ssh2-rs.svg?branch=master)](https://travis-ci.org/alexcrichton/ssh2-rs)
  * [Thrussh](https://github.com/pijul-scm/thrussh/) — 用Rust从头开始编写的SSH库，由[libsodium](https://doc.libsodium.org/)支持
* Stomp
  * [zslayton/stomp-rs](https://github.com/zslayton/stomp-rs) — 一个 [STOMP 1.2](http://stomp.github.io/stomp-specification-1.2.html) 客户端的Rust实现 [![build badge](https://api.travis-ci.org/zslayton/stomp-rs.svg?branch=master)](https://travis-ci.org/zslayton/stomp-rs)
  * [adwhit/tokio-stomp](https://github.com/adwhit/tokio-stomp) — 使用Tokio堆栈的Rust异步[STOMP v1.1](https://stomp.github.io/stomp-specification-1.1.html)客户端。
* uTP
  * [meqif/rust-utp](https://github.com/meqif/rust-utp) — 一个 [uTP](http://www.bittorrent.org/beps/bep_0029.html) (微传输协议) 库的Rust实现 [![build badge](https://api.travis-ci.org/meqif/rust-utp.svg?branch=master)](https://travis-ci.org/meqif/rust-utp)
* ZeroMQ
  * [erickt/rust-zmq](https://github.com/erickt/rust-zmq) — [ZeroMQ](https://zeromq.org/) 绑定 [![build badge](https://api.travis-ci.org/erickt/rust-zmq.svg?branch=master)](https://travis-ci.org/erickt/rust-zmq)
* CoAP
  * [Covertness/coap-rs](https://github.com/Covertness/coap-rs) — 一个[受限应用协议(CoAP)](https://tools.ietf.org/html/rfc7252) 库的Rust实现 [![build badge](https://api.travis-ci.org/Covertness/coap-rs.svg?branch=master)](https://travis-ci.org/Covertness/coap-rs)
* Docker
  * [fussybeaver/bollard](https://github.com/fussybeaver/bollard) — Rust写的Docker守护程序API
* RPC
  * [smallnest/rpcx-rs](https://github.com/smallnest/rpcx-rs) — Rust的RPC库，简单易用的方式开发微服务 [![build badge](https://api.travis-ci.org/smallnest/rpcx-rs.svg?branch=master)](https://travis-ci.org/smallnest/rpcx-rs)
* QUIC
  * [cloudflare/quiche](https://github.com/cloudflare/quiche) — QUIC传输协议和HTTP/3的cloudflare实现 [![build badge](https://api.travis-ci.com/cloudflare/quiche.svg?branch=master)](https://travis-ci.com/cloudflare/quiche)
  * [quinn-rs/quinn](https://github.com/quinn-rs/quinn) — Rust中基于Future的QUIC实现 [![build badge](https://dev.azure.com/dochtman/Projects/_apis/build/status/Quinn?branchName=master)](https://dev.azure.com/dochtman/Projects/_build)
  * [mozilla/neqo](https://github.com/mozilla/neqo) — 用Rust编写的QUIC的实现
* P2P
  * [libp2p/rust-libp2p](https://github.com/libp2p/rust-libp2p) — libp2p网络堆栈的Rust实现 [![Circle CI](https://circleci.com/gh/libp2p/rust-libp2p.svg?style=svg)](https://app.circleci.com/pipelines/github/libp2p/rust-libp2p)
* NATS
  * [nats-io/nats.rs](https://github.com/nats-io/nats.rs) — 用于NATS（云原生消息传系统）的Rust客户端 [![Build Status](https://github.com/nats-io/nats.rs/workflows/Rust/badge.svg?branch=master)](https://github.com/nats-io/nats.rs/actions)

### 解析器

  * [aleshaleksey/libazdice](https://github.com/aleshaleksey/libazdice) — 用于解析TTRPG和TTRPG开发的骰子字符串的解析器 [![build badge](https://api.travis-ci.org/aleshaleksey/libazdice.svg?branch=master)](https://travis-ci.org/aleshaleksey/libazdice)
  * [Folyd/robotstxt](https://github.com/Folyd/robotstxt) - Google的robots.txt解析器和Matcher C ++库的本地Rust端口
  * [Geal/nom](https://github.com/Geal/nom) — 解析器组合器库 [![build badge](https://api.travis-ci.org/Geal/nom.svg?branch=master)](https://travis-ci.org/Geal/nom)
  * [ivanceras/inquerest](https://github.com/ivanceras/inquerest) — 用于Rest过滤器查询的URL参数解析器[![Build Status](https://api.travis-ci.org/ivanceras/inquerest.svg?branch=master)](https://travis-ci.org/ivanceras/inquerest)
  * [kevinmehall/rust-peg](https://github.com/kevinmehall/rust-peg) — 解析表达式语法（PEG）解析器生成器
  * [m4rw3r/chomp](https://github.com/m4rw3r/chomp) – 一种快速的单子式解析器组合器 [![build badge](https://api.travis-ci.org/m4rw3r/chomp.svg?branch=master)](https://travis-ci.org/m4rw3r/chomp)
  * [Marwes/combine](https://github.com/Marwes/combine) — 解析器组合器库 [![build badge](https://api.travis-ci.org/Marwes/combine.svg?branch=master)](https://travis-ci.org/Marwes/combine)
  * [lalrpop/lalrpop](https://github.com/lalrpop/lalrpop) — 用于Rust的LR（1）解析器生成器 [![Build status](https://api.travis-ci.org/lalrpop/lalrpop.svg?branch=master)](https://travis-ci.org/lalrpop/lalrpop)
  * [nrc/zero](https://github.com/nrc/zero) — 二进制数据的零分配解析
  * [pest-parser/pest](https://github.com/pest-parser/pest) — 优雅的解析器 [![Build Status](https://api.travis-ci.org/pest-parser/pest.svg?branch=master)](https://travis-ci.org/pest-parser/pest)
  * [ptal/oak](https://github.com/ptal/oak) — 类型化的PEG解析器生成器（编译器插件）
  * [replicadse/wavefront_rs](https://github.com/replicadse/wavefront_rs) — Wavefront OBJ格式的解析器 [![crates.io](https://img.shields.io/crates/v/wavefront_rs.svg)](https://crates.io/crates/wavefront_rs) [![crates.io](https://img.shields.io/crates/d/wavefront_rs?label=crates.io%20downloads)](https://crates.io/crates/wavefront_rs) [![build badge](https://github.com/replicadse/wavefront_rs/workflows/pipeline/badge.svg?branch=master)](https://github.com/replicadse/wavefront_rs/actions)
  * [s-panferov/queryst](https://github.com/s-panferov/queryst) — 受https://github.com/ljharb/qs启发的Rust查询字符串解析库
  * [freestrings/jsonpath](https://github.com/freestrings/jsonpath) — 用Rust编写的[JsonPath](https://goessner.net/articles/JsonPath/) 引擎。Webassembly和Javascript也支持。 [![Build Status](https://api.travis-ci.org/freestrings/jsonpath.svg?branch=master)](https://travis-ci.org/freestrings/jsonpath)

### 打包格式

- [pop-os/debarchive](https://github.com/pop-os/debarchive) 用于读取和提取debian档案

### 外围设备

* Serial Port
  * [Susurrus/serialport-rs](https://github.com/Susurrus/serialport-rs) [[serialport](https://docs.rs/serialport/3.0.0/serialport/)] — 一个提供串口访问的跨平台的库

### 平台相关

* Cross-platform
  * [svartalf/rust-battery](https://crates.io/crates/battery) — 跨平台的笔记本电池信息 [![build badge](https://api.travis-ci.org/svartalf/rust-battery.svg?branch=master)](https://travis-ci.org/svartalf/rust-battery)

* Linux
  * [frol/cgroups-fs](https://github.com/frol/cgroups-fs) — Linux控制组(cgroups)的Rust绑定 [![build badge](https://api.travis-ci.org/frol/cgroups-fs.svg?branch=master)](https://travis-ci.org/frol/cgroups-fs)
  * [pop-os/dbus-udisks2](https://github.com/pop-os/dbus-udisks2) — UDisks2 DBus API
  * [pop-os/distinst](https://github.com/pop-os/distinst/) — Linux发行安装程序库
  * [hannobraun/inotify](https://github.com/hannobraun/inotify) — [inotify](https://en.wikipedia.org/wiki/Inotify) 绑定 [![build badge](https://api.travis-ci.org/hannobraun/inotify.svg?branch=master)](https://travis-ci.org/hannobraun/inotify)
  * [arvancloud/nginx-rs](https://github.com/arvancloud/nginx-rs) — [Nginx](https://www.nginx.com) 绑定 [![build badge](https://api.travis-ci.org/arvancloud/nginx-rs.svg?branch=master)](https://travis-ci.org/arvancloud/nginx-rs)
  * [yaa110/rust-iptables](https://github.com/yaa110/rust-iptables) — [iptables](https://www.netfilter.org/projects/iptables/index.html) 绑定 [![build badge](https://api.travis-ci.org/yaa110/rust-iptables.svg?branch=master)](https://travis-ci.org/yaa110/rust-iptables)
* Unix-like
  * [nix-rust/nix](https://github.com/nix-rust/nix) — Unix风格的API绑定 [![build badge](https://api.travis-ci.org/nix-rust/nix.svg?branch=master)](https://travis-ci.org/nix-rust/nix)
  * [zargony/fuse-rs](https://github.com/zargony/fuse-rs) — [FUSE](https://github.com/libfuse/libfuse) 绑定
* Windows
  * [retep998/winapi-rs](https://github.com/retep998/winapi-rs) — Windows API 绑定 [![build badge](https://api.travis-ci.org/retep998/winapi-rs.svg?branch=master)](https://travis-ci.org/retep998/winapi-rs)
* FreeBSD
  * [fubarnetes/libjail-rs](https://github.com/fubarnetes/libjail-rs/) — FreeBSD jail库的Rust实现
  * [dlrobertson/capsicum-rs](https://github.com/dlrobertson/capsicum-rs) — FreeBSD capsicum框架的Rust绑定

### 脚本

[[脚本](https://crates.io/keywords/scripting)]

* [duckscript](https://crates.io/crates/duckscript) — [简单，可扩展和可嵌入的脚本语言](https://github.com/sagiegurari/duckscript) [![build badge](https://api.travis-ci.org/sagiegurari/duckscript.svg?branch=master)](https://travis-ci.org/sagiegurari/duckscript)
* [PistonDevelopers/dyon](https://github.com/PistonDevelopers/dyon) — 一种rust的动态类型脚本语言
* [gluon-lang/gluon](https://github.com/gluon-lang/gluon) —  一种小型的静态类型的函数式编程语言
* [murarth/ketos](https://github.com/murarth/ketos) — 一种Lisp方言功能性编程语言，用作Rust的脚本和扩展语言
* [moss](https://crates.io/crates/moss) — 一种动态类型脚本语言
* [mun](https://github.com/mun-lang/mun) — 一直优秀支持热加载的可编译的静态类型脚本语言 [![build badge](https://api.travis-ci.org/mun-lang/mun.svg?branch=master)](https://travis-ci.org/mun-lang/mun)
* [rhaiscript/rhai](https://github.com/rhaiscript/rhai) — 一种微型且快速的嵌入式脚本语言，类似于JS和Rust的组合

### 模拟

[[模拟](https://crates.io/keywords/simulation)]

* [bigbang](https://crates.io/crates/bigbang) - 具有可选GPU加速的引力和碰撞n体仿真 [![build badge](https://api.travis-ci.org/sezna/bigbang.svg?branch=master)](https://travis-ci.org/sezna/bigbang)
* [nyx-space](https://crates.io/crates/nyx-space) - 高保真，快速，可靠和经过验证的天体动力学工具包库，用于航天器任务设计和轨道确定 [![Build Status](https://gitlab.com/chrisrabotin/nyx/badges/master/pipeline.svg)](https://gitlab.com/chrisrabotin/nyx/pipelines)

### 任务调度

* [BinChengZhao/delay-timer](https://github.com/BinChengZhao/delay-timer) — delay-timer是基于时间轮算法的任务管理器，它使管理定时任务或定期执行诸如关闭之类的任意任务变得容易 [![Cargo](https://img.shields.io/crates/v/delay_timer.svg)](
https://crates.io/crates/delay_timer)

### 模版引擎

* Handlebars
  * [sunng87/handlebars-rust](https://github.com/sunng87/handlebars-rust) — 具有继承性，自定义帮助程序支持的模板引擎 [![build badge](https://api.travis-ci.org/sunng87/handlebars-rust.svg?branch=master)](https://travis-ci.org/sunng87/handlebars-rust)
  * [botika/yarte](https://github.com/botika/yarte) — Yarte代表另一个模块引擎, 最快的模板引擎 [![Build Status](https://api.travis-ci.org/botika/yarte.svg?branch=master)](https://travis-ci.org/botika/yarte)
* HTML
  * [lambda-fairy/maud](https://github.com/lambda-fairy/maud) — 编译时HTML模板 [![build badge](https://api.travis-ci.org/lambda-fairy/maud.svg?branch=master)](https://travis-ci.org/lambda-fairy/maud)
  * [Stebalien/horrorshow-rs](https://github.com/Stebalien/horrorshow-rs) — 编译时HTML模板 [![build badge](https://api.travis-ci.org/Stebalien/horrorshow-rs.svg?branch=master)](https://travis-ci.org/Stebalien/horrorshow-rs)
  * [kaj/ructe](https://github.com/kaj/ructe) — Rust的HTML模板系统 [![build badge](https://api.travis-ci.org/kaj/ructe.svg?branch=master)](https://travis-ci.org/kaj/ructe)
  * [Keats/tera](https://github.com/Keats/tera) — 基于Jinja2和Django模板语言的模板引擎 [![Actions Status](https://github.com/Keats/tera/workflows/ci/badge.svg?branch=master)](https://github.com/Keats/tera/actions)
  * [djc/askama](https://github.com/djc/askama) — 基于Jinja的模板呈现引擎 [![build badge](https://api.travis-ci.org/djc/askama.svg?branch=master)](https://travis-ci.org/djc/askama)
  * [naomijub/hiccup](https://github.com/naomijub/hiccup) — 灵感来自Clojure的Hiccup的模板引擎 [![Build Status](https://api.travis-ci.org/naomijub/hiccup.svg?branch=master)](https://travis-ci.org/naomijub/hiccup)
* Mustache
  * [rustache/rustache](https://github.com/rustache/rustache) — [![build badge](https://api.travis-ci.org/rustache/rustache.svg?branch=master)](https://travis-ci.org/rustache/rustache)
* [tailhook/marafet](https://github.com/tailhook/marafet) — 编译类似于Jade的模板语言到基于cito.js的虚拟dom的编译器

### 文本处理-1

* [BurntSushi/suffix](https://github.com/BurntSushi/suffix) — 线性时间后缀数组构造（支持Unicode）[![build badge](https://api.travis-ci.org/BurntSushi/suffix.svg?branch=master)](https://travis-ci.org/BurntSushi/suffix)
* [BurntSushi/tabwriter](https://github.com/BurntSushi/tabwriter) — 弹性制表位（如文本列对齐） [![build badge](https://api.travis-ci.org/BurntSushi/tabwriter.svg?branch=master)](https://travis-ci.org/BurntSushi/tabwriter)
* [mgeisler/textwrap](https://github.com/mgeisler/textwrap) [[textwrap](https://crates.io/crates/textwrap)] — 自动换行文本（支持断字） [![build badge](https://api.travis-ci.org/mgeisler/textwrap.svg?branch=master)](https://travis-ci.org/mgeisler/textwrap)
* [pwoolcoc/ngrams](https://github.com/pwoolcoc/ngrams) — 从任意迭代器构造[n-grams](https://en.wikipedia.org/wiki/N-gram) [![build badge](https://api.travis-ci.org/pwoolcoc/ngrams.svg?branch=master)](https://travis-ci.org/pwoolcoc/ngrams)
* [ps1dr3x/easy_reader](https://github.com/ps1dr3x/easy_reader) — 一种阅读器，它允许在不使用迭代器的情况下通过大型文件进行前进，后退和随机导航 [![build badge](https://api.travis-ci.org/ps1dr3x/easy_reader.svg?branch=master)](https://travis-ci.org/ps1dr3x/easy_reader)
* [rust-lang/regex](https://github.com/rust-lang/regex) — 正则表达式（RE2样式 [![build badge](https://api.travis-ci.com/rust-lang/regex.svg?branch=master)](https://travis-ci.org/rust-lang/regex)
* [strsim-rs](https://crates.io/crates/strsim) — 字符串相似性指标 [![build badge](https://api.travis-ci.org/dguo/strsim-rs.svg?branch=master)](https://travis-ci.org/dguo/strsim-rs)
* [greyblake/whatlang-rs](https://github.com/greyblake/whatlang-rs) — 基于trigrams的自然语言检测库 [![build badge](https://api.travis-ci.org/greyblake/whatlang-rs.svg?branch=master)](https://travis-ci.org/greyblake/whatlang-rs)
* [yaa110/rake-rs](https://github.com/yaa110/rake-rs) — Rust的RAKE算法的多语言实现 [![build badge](https://api.travis-ci.org/yaa110/rake-rs.svg?branch=master)](https://travis-ci.org/yaa110/rake-rs)
* [Lucretiel/joinery](https://github.com/Lucretiel/joinery) [[joinery](https://crates.io/crates/joinery)] – 可迭代的通用字符串 [![build badge](https://api.travis-ci.org/Lucretiel/joinery.svg?branch=master)](https://travis-ci.org/Lucretiel/joinery)
* [Daniel-Liu-c0deb0t/triple_accel](https://github.com/Daniel-Liu-c0deb0t/triple_accel) [[triple_accel](https://crates.io/crates/triple_accel)] - 使用SIMD加速的Rust编辑距离例程；支持高速Hamming，Levenshtein，严格Damerau-Levenshtein等。距离计算和字符串搜索。 [![build badge](https://github.com/Daniel-Liu-c0deb0t/triple_accel/workflows/Test/badge.svg?branch=master)](https://github.com/Daniel-Liu-c0deb0t/triple_accel/actions)

### 文本搜索

* [andylokandy/simsearch-rs](https://github.com/andylokandy/simsearch-rs) [[simsearch](https://crates.io/crates/simsearch)] — 一种简单轻量的模糊搜索引擎，可在内存中工作，搜索相似的字符串
* [BurntSushi/fst](https://github.com/BurntSushi/fst) [[fst](https://crates.io/crates/fst)] — [![build badge](https://api.travis-ci.org/BurntSushi/fst.svg?branch=master)](https://travis-ci.org/BurntSushi/fst)
* [meilisearch/MeiliSearch](https://github.com/meilisearch/MeiliSearch) — 即时且可输入错字的全文搜索API [![Build Status](https://github.com/meilisearch/MeiliSearch/workflows/Cargo%20test/badge.svg?branch=master)](https://github.com/meilisearch/MeiliSearch/actions)
* [minio/minsql](https://github.com/minio/minsql) — 高性能日志搜索引擎 [![build badge](https://api.travis-ci.org/minio/minsql.svg?branch=master)](https://travis-ci.org/minio/minsql)
* [CurrySoftware/perlin](https://github.com/CurrySoftware/perlin) [[perlin](https://crates.io/crates/perlin)]
* [tantivy-search/tantivy](https://github.com/tantivy-search/tantivy) [[tantivy](https://crates.io/crates/tantivy)] — [![build badge](https://api.travis-ci.org/tantivy-search/tantivy.svg?branch=master)](https://travis-ci.org/tantivy-search/tantivy)

### 非安全性

* [zerocopy](https://crates.io/crates/zerocopy) — 用于安全地将任意字节序列重新解释为本地Rust类型的实用程序

### 虚拟化

* [beneills/quantum](https://github.com/beneills/quantum) — 高级Rust量子计算机模拟器 [![build badge](https://api.travis-ci.org/beneills/quantum.svg?branch=master)](https://travis-ci.org/beneills/quantum)
* [chromium/chromiumos/platform/crosvm](https://chromium.googlesource.com/chromiumos/platform/crosvm/) CrOSVM — 使Chrome操作系统能够在快速，安全的虚拟环境中运行Linux应用
* [unicorn-rs/unicorn-rs](https://github.com/unicorn-rs/unicorn-rs) — unicorn CPU仿真器的Rust绑定 [![Build Status](https://api.travis-ci.org/ekse/unicorn-rs.svg?branch=master)](https://travis-ci.org/ekse/unicorn-rs)
* [saurvs/hypervisor-rs](https://github.com/saurvs/hypervisor-rs) — OS X上的硬件加速虚拟化

### Web编程

* Client-side / WASM
  * [cargo-web](https://crates.io/crates/cargo-web) — 用于客户端Web的Cargo子命令[![Build Status](https://api.travis-ci.org/koute/cargo-web.svg?branch=master)](https://travis-ci.org/koute/cargo-web)
  * [seed](https://seed-rs.org/) — 用于创建Web应用程序的Rust框架
  * [stdweb](https://crates.io/crates/stdweb) — 客户端Web的标准库 [![Build Status](https://api.travis-ci.org/koute/stdweb.svg?branch=master)](https://travis-ci.org/koute/stdweb)
  * [yew](https://crates.io/crates/yew) — 用于构建客户端Web应用程序的Rust框架
  * [sauron](https://github.com/ivanceras/sauron) - 与Elm架构紧密结合的客户端Web框架 [![Build Status](https://api.travis-ci.org/ivanceras/sauron.svg?branch=master)](https://travis-ci.org/ivanceras/sauron)
* HTTP Client
  * [alexcrichton/curl-rust](https://github.com/alexcrichton/curl-rust) — [libcurl](https://curl.se/libcurl/) 绑定 [![build badge](https://api.travis-ci.com/alexcrichton/curl-rust.svg?branch=master)](https://travis-ci.org/alexcrichton/curl-rust)
  * [async-graphql](https://github.com/async-graphql/async-graphql) - 用Rust实现的GraphQL服务器库 [![Build Status](https://dev.azure.com/graphql-rust/GraphQL%20Rust/_apis/build/status/graphql-rust.juniper)](https://dev.azure.com/graphql-rust/GraphQL%20Rust/_build/latest?definitionId=1)
  * [graphql-client](https://github.com/graphql-rust/graphql-client) — GraphQL客户端 [![Github actions Status](https://github.com/graphql-rust/graphql-client/workflows/CI/badge.svg?branch=master)](https://github.com/graphql-rust/graphql-client/actions)
  * [hyperium/hyper](https://github.com/hyperium/hyper) — 一种HTTP实现 [![build badge](https://api.travis-ci.org/hyperium/hyper.svg?branch=master)](https://travis-ci.org/hyperium/hyper)
  * [seanmonstar/reqwest](https://github.com/seanmonstar/reqwest) — 符合人体工程学的Rust HTTP客户端 [![build badge](https://api.travis-ci.org/seanmonstar/reqwest.svg?branch=master)](https://travis-ci.org/seanmonstar/reqwest)
  * [DoumanAsh/yukikaze](https://gitlab.com/Douman/yukikaze) — 优雅的Yukikaze是基于Hyper的小型HTTP客户端库 [![build badge](https://gitlab.com/Douman/yukikaze/badges/master/pipeline.svg)](https://gitlab.com/Douman/yukikaze)
* HTTP Server
  * [actix/actix-web](https://github.com/actix/actix-web) — 具有websocket支持的Rust轻量级异步Web框架 [![build badge](https://api.travis-ci.org/actix/actix-web.svg?branch=master)](https://travis-ci.org/actix/actix-web)
  * [branca](https://crates.io/crates/branca) — 完全Rust实现的Branca，用于经过身份验证和加密的API令牌 [![build badge](https://api.travis-ci.org/return/branca.svg?branch=master)](https://travis-ci.org/return/branca)
  * [Gotham](https://github.com/gotham-rs/gotham) — 一种灵活的Web框架，不牺牲安全性，安全性或速度 [![build badge](https://api.travis-ci.org/gotham-rs/gotham.svg?branch=master)](https://travis-ci.org/gotham-rs/gotham)
  * [hyperium/hyper](https://github.com/hyperium/hyper) — 一个HTTP实现 [![build badge](https://api.travis-ci.org/hyperium/hyper.svg?branch=master)](https://travis-ci.org/hyperium/hyper)
  * [GildedHonour/frank_jwt](https://github.com/GildedHonour/frank_jwt) — Rust的JSON Web令牌实现 [![build badge](https://api.travis-ci.org/GildedHonour/frank_jwt.svg?branch=master)](https://travis-ci.org/GildedHonour/frank_jwt)
  * [handlebars-rust](https://github.com/sunng87/handlebars-rust) — Iron Web框架中间件 [![build badge](https://api.travis-ci.org/sunng87/handlebars-iron.svg?branch=master)](https://travis-ci.org/sunng87/handlebars-iron)
  * [Iron](https://github.com/iron/iron) — 基于中间件的服务器框架 [![build badge](https://api.travis-ci.org/GildedHonour/frank_jwt.svg?branch=master)](https://travis-ci.org/GildedHonour/frank_jwt)
  * [Juniper](https://github.com/graphql-rust/juniper) — Rust的GraphQL服务器库 [![build badge](https://api.travis-ci.org/graphql-rust/juniper.svg?branch=master)](https://travis-ci.org/graphql-rust/juniper)
  * [Nickel](https://github.com/nickel-org/nickel.rs/) — 灵感来自[Express](http://expressjs.com/) [![build badge](https://api.travis-ci.org/nickel-org/nickel.rs.svg?branch=master)](https://travis-ci.org/nickel-org/nickel.rs)
  * [Ogeon/rustful](https://github.com/Ogeon/rustful) — Rust的RESTful Web框架  [![build badge](https://api.travis-ci.org/Ogeon/rustful.svg?branch=master)](https://travis-ci.org/Ogeon/rustful)
  * [Rocket](https://github.com/SergioBenitez/Rocket) — Rocket是Rust的专注于易用性，可表达性和速度的Web框架 [![build badge](https://api.travis-ci.org/SergioBenitez/Rocket.svg?branch=master)](https://travis-ci.org/SergioBenitez/Rocket)
  * [Rustless](https://github.com/rustless/rustless) — 受[Grape](https://github.com/ruby-grape/grape)和[Hyper](https://github.com/hyperium/hyper)启发的类似REST的API微框架 [![build badge](https://api.travis-ci.org/rustless/rustless.svg?branch=master)](https://travis-ci.org/rustless/rustless)
  * [Saphir](https://github.com/richerarc/saphir) — 具有底层控制权的渐进式Web框架
  * [daogangtang/sapper](https://github.com/daogangtang/sapper) — 一种轻量级的Web框架，基于Rust异步实现的异步超链接 [![build badge](https://api.travis-ci.org/daogangtang/sapper.svg?branch=master)](https://travis-ci.org/daogangtang/sapper)
  * [tiny-http](https://github.com/tiny-http/tiny-http) — 底层HTTP服务器库 [![build badge](https://api.travis-ci.org/tiny-http/tiny-http.svg?branch=master)](https://travis-ci.org/tiny-http/tiny-http)
  * [tomaka/rouille](https://github.com/tomaka/rouille) — Rust写的Web框架 [![build badge](https://api.travis-ci.org/tomaka/rouille.svg?branch=master)](https://travis-ci.org/tomaka/rouille)
  * [carllerche/tower-web](https://github.com/carllerche/tower-web) [[tower-web](https://crates.io/crates/tower-web)] — 一种快速，无样板的Rust Web框架 [![build badge](https://api.travis-ci.org/carllerche/tower-web.svg?branch=master)](https://travis-ci.org/carllerche/tower-web)
  * [danclive/sincere](https://github.com/danclive/sincere) — 基于超线程和多线程的Rust（稳定）微网络框架 [![build badge](https://api.travis-ci.org/danclive/sincere.svg?branch=master)](https://travis-ci.org/danclive/sincere)
  * [oltdaniel/zap](https://github.com/oltdaniel/zap) — Rust的高速http框架
* [WebSocket](https://datatracker.ietf.org/doc/rfc6455/)
  * [actix/sockjs](https://github.com/actix/sockjs) — 用于Rust的[SockJS](https://github.com/sockjs)服务器 [![build badge](https://api.travis-ci.org/actix/sockjs.svg?branch=master)](https://travis-ci.org/actix/sockjs)
  * [rust-websocket](https://github.com/websockets-rs/rust-websocket) — 用于处理WebSocket连接（客户端和服务器）的框架 [![build badge](https://api.travis-ci.org/websockets-rs/rust-websocket.svg?branch=master)](https://travis-ci.org/websockets-rs/rust-websocket)
  * [housleyjk/ws-rs](https://github.com/housleyjk/ws-rs) — 用于Rust的轻量级，事件驱动的WebSocket [![build badge](https://api.travis-ci.org/housleyjk/ws-rs.svg?branch=stable)](https://travis-ci.org/housleyjk/ws-rs)
  * [snapview/tungstenite-rs](https://github.com/snapview/tungstenite-rs) — 用于Rust的基于轻量流的WebSocket实现
  * [vi/websocat](https://github.com/vi/websocat) — 用于与WebSocket交互的CLI，具有Netcat，Curl和Socat的功能 [![build badge](https://api.travis-ci.org/vi/websocat.svg?branch=master)](https://travis-ci.org/vi/websocat)
  * [vityafx/urlshortener-rs](https://github.com/vityafx/urlshortener-rs) [[urlshortener](https://crates.io/crates/urlshortener)] — 一个非常简单的用于Rust的urlshortener库 [![build badge](https://api.travis-ci.org/vityafx/urlshortener-rs.svg?branch=master)](https://travis-ci.org/vityafx/urlshortener-rs)
  * [bitwyre/websocket_core](https://github.com/bitwyre/websocket_core) — Websocket通用服务器库，用于定期广播消息 [![build badge](https://github.com/bitwyre/websocket_core/workflows/Build/badge.svg?branch=master)](https://github.com/bitwyre/websocket_core/actions)
* Miscellaneous
  * [cargonauts](https://github.com/cargonauts-rs/cargonauts) — 用于构建可维护的，结构合理的Web应用程序的Web框架
  * [osohq/oso](https://github.com/osohq/oso) [[oso](https://crates.io/crates/oso)] - 嵌入在您的应用程序中的用于授权的策略引擎 [![Build Status](https://github.com/osohq/oso/workflows/Development/badge.svg?branch=main)](https://github.com/osohq/oso/actions?query=branch%3Amain+workflow%3ADevelopment)
  * [pyros2097/rust-embed](https://github.com/pyros2097/rust-embed) — 将静态资产嵌入rust二进制文件的宏
  * [utkarshkukreti/select.rs](https://github.com/utkarshkukreti/select.rs) [[select](https://crates.io/crates/select)] — 一个从HTML文档中提取有用数据的库，适用于Web抓取 [![Build Status](https://api.travis-ci.org/utkarshkukreti/select.rs.svg?branch=master)](https://travis-ci.org/utkarshkukreti/select.rs)
  * [pwoolcoc/soup](https://gitlab.com/pwoolcoc/soup) [[soup](https://crates.io/crates/soup)] — 一个类似于Python的BeautifulSoup的库，旨在实现对HTML文档的快速便捷的操作和查询 [![Build Status](https://gitlab.com/pwoolcoc/soup/badges/master/pipeline.svg)](https://gitlab.com/pwoolcoc/soup/badges/master/pipeline.svg)
  * [softprops/openapi](https://github.com/softprops/openapi) — 用于处理openapi规范文件的库
  * [tbot](https://gitlab.com/SnejUgal/tbot) - 使用Rust轻松制作酷炫的Telegram bot [![pipeline status](https://gitlab.com/SnejUgal/tbot/badges/master/pipeline.svg)](https://gitlab.com/SnejUgal/tbot/-/commits/master)
  * [teloxide/teloxide](https://github.com/teloxide/teloxide/) - Rust的优雅的Telegram bot框架 [![Build Status](https://github.com/teloxide/teloxide/workflows/Continuous%20integration/badge.svg?branch=master)](https://github.com/teloxide/teloxide/actions)
* Reverse Proxy
  * [sozu-proxy/sozu](https://github.com/sozu-proxy/sozu) [[sozu](https://crates.io/crates/sozu)] — 一个HTTP反向代理 [![Build Status](https://api.travis-ci.org/sozu-proxy/sozu.svg?branch=master)](https://travis-ci.org/sozu-proxy/sozu)
* Static Site Generators
  * [getzola/zola](https://github.com/getzola/zola) [[zola](https://www.getzola.org/)] — 内置一切的静态网站生成器 [![Build Status](https://dev.azure.com/getzola/zola/_apis/build/status/getzola.zola?branchName=master)](https://dev.azure.com/getzola/zola/_build)
  * [cobalt-org/cobalt.rs](https://github.com/cobalt-org/cobalt.rs) — 用Rust编写的静态站点生成器 [![Build Status](https://dev.azure.com/cobalt-org/cobalt-org/_apis/build/status/cobalt.rs?branchName=master)](https://dev.azure.com/cobalt-org/cobalt-org/_build?definitionId=2)
  * [FuGangqiang/mdblog.rs](https://github.com/FuGangqiang/mdblog.rs) — Markdown文件中的静态站点生成器
  * [leven-the-blog/leven](https://github.com/leven-the-blog/leven) [[leven](https://crates.io/crates/leven)] — 一个简单的并行化博客生成器 [![build badge](https://api.travis-ci.org/quadrupleslap/leven.svg?branch=master)](https://travis-ci.org/quadrupleslap/leven)

## Registries

* [Crates](https://crates.io) — Rust/Cargo的官方公共registry
* [Cloudsmith :heavy_dollar_sign:](https://cloudsmith.com/cargo-registry/) — 全面管理的包裹管理SaaS，具有对公共和私人Cargo/Rust registry（以及许多其他服务）的一流支持。对于开源完全免费。

## 资源

* Benchmarks
  * [TeXitoi/benchmarksgame-rs](https://github.com/TeXitoi/benchmarksgame-rs) — [计算机语言基准游戏的Rust实现](https://benchmarksgame-team.pages.debian.net/benchmarksgame/)的Rust实现 [![build badge](https://api.travis-ci.org/TeXitoi/benchmarksgame-rs.svg?branch=master)](https://travis-ci.org/TeXitoi/benchmarksgame-rs)
* Decks & Presentations
  * [Learning systems programming with Rust](https://speakerdeck.com/jvns/learning-systems-programming-with-rust) — [Julia Evans](https://twitter.com/@b0rk) @ Rustconf 2016的演示
  * [Shipping a Solid Rust Crate](https://www.youtube.com/watch?v=t4CyEKb-ywA) — [Michael Gattozzi](https://github.com/mgattozzi) @ RustConf 2017的演示
  * [Rust: Hack Without Fear!](https://www.youtube.com/watch?v=lO1z-7cuRYI) — [Nicholas Matsakis](https://github.com/nikomatsakis) @ C++Now 2018的演示
* Learning
  * [Easy Rust](https://github.com/Dhghomon/easy_rust) - Rust入门
  * [Rust Gym](https://github.com/warycat/rustgym) - 用Rust解决的一大堆编码面试问题
  * [Programming Community Curated Resources for Learning Rust](https://hackr.io/tutorials/learn-rust) — 编程社区投票推荐的资源列表
  * [awesome-rust-mentors](https://rustbeginners.github.io/awesome-rust-mentors/) — 愿意接受受训者并向他们传授Rust和编程知识的有用的Rust导师列表
  * [Awesome Rust Streaming](https://github.com/jamesmunns/awesome-rust-streaming) - 社区策划的有关Rust的实时流
  * [exercism.io](https://exercism.io/tracks/rust) — 编程练习，可帮助您学习Rust中的新概念
  * [Idiomatic Rust](https://github.com/mre/idiomatic-rust) —  教授Rust的文章/讲座/工程的集合
  * [宾夕法尼亚大学的Comp Sci Rust编程课程](https://rust-unofficial.github.io/too-many-lists/) — 通过实现几种不同类型的列表结构来深入探索Rust的内存管理规则
  * [Rust by Example](https://doc.rust-lang.org/rust-by-example/)
  * [Rust Cookbook](https://rust-lang-nursery.github.io/rust-cookbook/) — 一系列简单的示例，展示了使用Rust生态系统的crate完成常见编程任务的良好实践
  * [Rust Online Courses at Classpert](https://classpert.com/topics/rust) — Classpert在线策搜索出的Rust付费在线课程列表
  * [Rust for professionals](https://overexact.com/rust-for-professionals/) — 为经验丰富的软件开发人员快速介绍Rust
  * [Rust in Motion](https://www.manning.com/livevideo/rust-in-motion?a_aid=cnichols&a_bid=6a993c2e) — [Carol Nichols](https://github.com/carols10cents) 和 [Jake Goulding](https://github.com/shepmaster) 的付费视频系列
  * [rust-learning](https://github.com/ctjhoa/rust-learning) — 收集的学习Rust有用的资源
  * [Rustlings](https://github.com/rust-lang/rustlings) — 帮助你阅读和编写Rust代码的小练习
  * [stdx](https://github.com/brson/stdx) — 学习这些crate，作为对std的扩展
  * [University of Pennsylvania's Comp Sci Rust Programming Course](http://cis198-2016s.github.io/schedule/)
  * [Build a language VM](https://blog.subnetzero.io/post/building-language-vm-part-00/)
  * [Code Playground](https://codeplayground.app) - 在iPhone和iPad设备上交互式编辑和播放rust片段
  * [Refactoring to Rust](https://www.manning.com/books/refactoring-to-rust) - 介绍Rust语言的书  
* Podcasts
  * [New Rustacean](https://newrustacean.com) — 关于学习Rust的播客
  * [Rustacean Station](https://rustacean-station.org/) — 一个用于为Rust创建播客内容的社区项目
* [RustCamp 2015 Talks](https://www.youtube.com/playlist?list=PLE7tQUdRKcybdIw61JpCoo89i4pWU5f_t)
* [Rust Design Patterns](https://github.com/rust-unofficial/patterns)
* [Rust Guidelines](http://aturon.github.io/)
* [RustBooks](https://github.com/sger/RustBooks) — RustBooks列表
* [Rust Subreddit](https://www.reddit.com/r/rust/) — 一个子论坛（论坛），其中发布和讨论了与Rust有关的问题，文章和资源
* [Rust Servers, Services and Apps - MEAP](http://mng.bz/XdWl) - 用Rust构建后端服务器，服务和前端，以获取快速，可靠和可维护的应用程序

## 许可

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
