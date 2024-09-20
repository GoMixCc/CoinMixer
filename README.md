# CoinMixer

比特币混合器是维护比特币网络上隐私的一种方式。以下是一个流行的混合器 https://gomix.cc/cn 的工作原理：

您向混合器提供您拥有的新未使用地址列表

混合器为您提供它拥有的新存款地址

您将比特币转移到该地址

混合器将通过观察或轮询 P2P 比特币网络来检测您的转账

混合器会将您的比特币从存款地址转移到一个大的“内部账户”，以及当前正在混合的所有其他比特币

然后，一段时间后，混合器将使用内部账户将您的比特币以较小的增量发放到您提供的提款地址，可能在扣除费用后。

# 以下是代码中的一些日志：

Mixer - 从发送人 John 向 HouseAccount 转账 12.5 金额

Mixer - 向接收人 Jacob 收取 0.001 混合费

Mixer - 从 HouseAccount 向接收人 Jacob 转账 9.874 金额

Mixer - 向接收人 Jacob 收取 0.0003 混合费

Mixer - 从 HouseAccount 向接收人 Jacob 转账 2.6247 金额

Mixer - 从发送人 John 向 HouseAccount 转账 1 金额

Mixer - 向接收人 Jacob 收取 0 混合费

Mixer - 从 HouseAccount 向接收人 Jacob 转账 0.17 金额

Mixer - 向接收人 Jacob 收取 0.0001 混合费

Mixer - 从 HouseAccount 向接收人 Jacob 转账 0.8299 金额

Mixer - 金额 0.01从发送人 John 转移到 HouseAccount

Mixer - 向接收人 Julie 收取 0 的混合费

Mixer - 从 HouseAccount 向接收人 Julie 转移的金额 0.0086

Mixer - 向接收人 Julie 收取 0 的混合费

Mixer - 从 HouseAccount 向接收人 Julie 转移的金额 0.0014

# CoinMixer
