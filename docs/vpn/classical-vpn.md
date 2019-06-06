## tunsafe

!> 2019 新款vpn

全局模式（翻墙环境）下，进入 [tunsafe](https://tunsafe.com) ，下载并按软件默认选项安装

![](https://i.postimg.cc/RhBH1YpM/Snipaste-2019-06-06-20-47-22.png)

![](https://i.postimg.cc/GpRnCJf4/Snipaste-2019-06-06-20-44-54.png)

在 `user guide` 选择 `using tunsafe windows`接着再选择`free vpn servers`

![](https://i.postimg.cc/7LKsW3r8/20190606205200.png)

点击 `create new account`，选择服务器，然后生成下载该配置文件

![](https://i.postimg.cc/63NrzTyJ/20190606205536.png)

打开软件在`File`项中选择`browse in explorer` 就会打开软件配置目录源

![](https://i.postimg.cc/hv8Qj0rf/Snipaste-2019-06-06-21-11-36.png)

将下载好的conf导入到该目录，选择服务器

![](https://i.postimg.cc/B6pkTrM3/Snipaste-2019-06-06-21-25-53.png)

连接测试

![](https://i.postimg.cc/9X6XrTRB/Snipaste-2019-06-06-21-35-24.png)


## GateVPN

!>重点且易被封杀的对象，需要选择合适的协议与连接方式并时常更新列表与软件，否则连接成功率极低，对协议间的了解与如何选择，[相关细节，请点击这里](4vpn.md)

> 原列表出处：[泡泡](https://pao-pao.net/article/82)，以及如何设置相关服务器连接方式，[GateVPN官网列表](http://www.vpngate.net/cn/)已有说明

| gateVPN服务器连接方式 | 软件设置 | 平台适用 | 服务器支持 | 翻墙体验 |
| :-: | :-: | :-: | :-: | :-: |
| SSL-VPN | 一般 | 只windows平台 | 全部支持 | 最好 |
| L2TP/Ipsec-VPN | 简单 | win,mac,ios,android | 很少 | 较差 |
| openvpn | 复杂 | win,mac,ios,android | 极好 | 一般 |
| MS-SSTP | 最易 | 只windows平台 | 较好 | 最差 |

<!-- ![](https://ipfs.io/ipfs/QmQc1YoVQvszg1rNZscxwWJ7ZmBMmDZyvALyw3T5iYsRa4?4.gif) -->

![](https://i.postimg.cc/RZFb7zhp/Snipaste-2019-06-06-04-03-52.png)

## OpenVPN

!> 目前，已被GFW特征识别成为重点封杀的对象，连接成功率低，一些SSH站点也提供OpenVPN配置文件下载，因为极大多数国家并没有像中国封锁网络那么严格

进入[freeopenvpn.org](https://www.freeopenvpn.org/)，点击home查看服务器列表，`get access`、`download`皆可进入下载页面

<!-- ![](https://ipfs.io/ipfs/QmbkkgwTLEQGRWNEqWAvhnLkaNB5dVWNmZiLV1HYonVkwQ?1.png) -->

![](https://i.postimg.cc/fRkYHqMb/2018-04-29-012851.png)

导入文件后，运行 openVPN 连接互联网

