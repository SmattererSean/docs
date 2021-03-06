
词汇表
======

============================================  ======================
词汇                                          定义
============================================  ======================
交易                                          对区块链进行状态更改的最小操作单元。通常表现为普通转帐以及智能合约调用。
区块(创世区块、普通区块、配置区块、当前区块)  区块链中的最小确认单元，由零个或多个交易组成，一个区块中的交易要么全部生效，要么全部不生效。创世区块：区块链上第一个区块，确定分配规则、共识算法等系统级别的参数。配置区块：需要升级区块链系统级配置时，通过配置区块生效。
账本                                          存储区块数据、交易数据。
UTXO                                          一种余额记账方式。用于存储账号的余额数据。
区块链                                        由若干个区块组成的DAG。从数据结构上来说，区块链就是一个DAG。
系统链                                        区块链网络中的第一条区块链实例。
平行链                                        从系统链衍生出来的子链，解决扩展性问题。
跨链                                          不同的区块链之间的通信操作，目的是实现区块链世界的价值互连，解决扩展性问题。
账号(用户账号、合约账号)                       一种本地或自定义权限的链上标识符。本地标识符称为用户账号，通常分配一个公钥和一个私钥；自定义权限的链上标识符称为合约账号，通常分配一个或多个密钥或多个账号。
密钥对(公钥、私钥)                            私钥以及由私钥生成的对应的公钥。私钥通常用于签名，公钥通常用于验证。
地址                                          与用户数据挂钩的最小单元。地址可以是合约账号，也可以是由公钥生成的一个长度为33的字符串。
签名(普通签名、多重签名)                      利用密码学哈希函数单向不可逆、抗碰撞特性，进行身份确认的一种机制。
共识                                          一种确认区块中交易集正确性以及交易上链顺序的机制。
委托权益证明                                  一种共识算法，通过选举出区块链网络中有限节点作为代表并轮流出块记账。
智能合约(系统级、用户合约)                    一个由计算机处理、可执行合约条款的交易协议，其总体目标是满足协议既定的条件，例如支付、抵押、保密协议。
权限(许可)                                    一种安全机制，通过评估签名权限来验证一个或一组操作是否被正确授权。
虚拟机                                        智能合约的运行环境。通常包括合约上下文管理。
最长链                                        区块链中高度最大的分支。
DAG                                           有向无环图。
双重消费                                      同一份数据同时消费多次。
最终一致性                                    存在某个时刻，整个系统达成一致状态。区块链满足最终一致性。
发起人                                        发起交易的账号，通常为用户账号或合约账号。
见证人                                        当选为当前周期内出块节点。
节点                                          区块链网络中的一个节点。
周期(Epoch)                                   在委托权益证明共识算法中，一轮出块时间为一个周期。
提案                                          一种区块链系统级配置进行升级的机制。
查询                                          对区块链中的数据按照key进行查询。
对等网络                                      网络中的节点直接互联并交互信息，不需要借助第三方。
拜占庭(拜占庭问题、拜占庭容错)                拜占庭问题：在一个需要共识系统中，由于作恶节点导致的问题。拜占庭容错：在一个需要共识系统中，即使出现作恶节点也能保证系统正常运转的能力。
状态转移系统                                  一个维护状态变化的系统。区块链通常被认为是一种状态转移系统，其中的状态通常包括账本、余额、合约数据。
读写集                                        用于支持智能合约并发执行的一种技术。
============================================  ======================
