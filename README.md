# EthernautWP
Writeups of Ethernaut, a Web3/Solidity based wargame.

## Intros
The Ethernaut is a Web3/Solidity based wargame inspired on overthewire.org, played in the Ethereum Virtual Machine. Each level is a smart contract that needs to be 'hacked'.
The game is 100% open source and all levels are contributions made by other players. Do you have an interesting idea? PRs are welcome at github.com/OpenZeppelin/ethernaut.
Are you interested in smart contract development or security? Does securing the world’s blockchain infrastructure sound exciting to you? We are hiring!

## Urls
* playground:https://ethernaut.openzeppelin.com/
* metamask:https://metamask.io/
* etherscan:https://rinkeby.etherscan.io/
* faucet:https://faucet.rinkeby.io/

## Prerequisites
* ⽐特币原理
  * 出处：[Satoshi, N., 2008. Bitcoin: A Peer-to-Peer Electronic Cash System.](https://bitcoin.org/bitcoin.pdf)
  * [论⽂的其他译⽂版](https://bitcoin.org/zh_CN/bitcoin-paper)
  * 区块结构科普解读：[Bitcoin 区块和交易数据结构](https://segmentfault.com/a/1190000017055507)
* 以太坊原理
  * 出处：[以太坊⻩⽪书](https://ethereum.github.io/yellowpaper/paper.pdf)
  * 科普解读：[How does Ethereum work, anyway?](https://preethikasireddy.medium.com/how-does-ethereum-work-anyway-22d1df506369)
  * 科普解读中⽂翻译版：[以太坊的⼯作原理](https://lilymoana.github.io/ethereum_theory.html)
* 共识机制
  * POW
    * 科普解读：[Proof-of-Work, Explained](https://cointelegraph.com/explained/proof-of-work-explained#:~:text=Proof%2Dof%2DWork%2C%20or,the%20network%20and%20get%20rewarded.)
  * PBFT
    * 出处：[Castro, M. and Liskov, B., 1999. Practical Byzantine Fault Tolerance. OSDI](http://pmg.csail.mit.edu/papers/osdi99.pdf)
    * 细节解读（有助于深⼊理解）：[Subtle Details in PBFT - Anh Dinh](http://ug93tad.github.io/pbft/)
  * 拜占庭将军问题
    * 出处：Lamport, L., Shostak, R. and Pease, M., 1982. [The Byzantine Generals Problem](https://people.eecs.berkeley.edu/~luca/cs174/byzantine.pdf). ACM Trans. Program. Lang. Syst.
    * 科普解读：[Understanding the Byzantine Generalsʼ Problem](https://medium.com/coinmonks/a-note-from-anthony-if-you-havent-already-please-read-the-article-gaining-clarity-on-key-787989107969) (and how it affects you)
* Solidity合约
  * 基本语法：[最新版v0.8.2](https://docs.soliditylang.org/en/v0.8.2/) & [旧版常⽤v0.4.24](https://docs.soliditylang.org/en/v0.4.24/)
  * IDE：[remix](https://remix.ethereum.org/),[remix中文版](http://remix.app.hubwiz.com/)
  * 钱包（链上交互⽤）：metamask（Chrome插件即可）
* 区块链安全
  * Solidity 合约安全：[Ethereum Smart Contract Best Practices - Consensys](https://consensys.github.io/smart-contract-best-practices/) & [Known Attacks](https://consensys.github.io/smart-contract-best-practices/known_attacks/)
  * 区块链漏洞定级标准（感受漏洞范围）：国家区块链漏洞库[《区块链漏洞定级细则》](https://bc.cnvd.org.cn/focus_info?num=e66b7041a4aa3a54e362b4accb076111)发布
  * 合约逆向（有助于理解逆向细节）：[Deconstructing a Solidity Contract](https://blog.openzeppelin.com/deconstructing-a-solidity-contract-part-i-introduction-832efd2d7737/)
* CTF题⽬环境
  * [ethernaut系列练习题](https://ethernaut.openzeppelin.com/)
  * RealworldCTF历年区块链题⽬
  * rw3rd - billboard [公链]：https://github.com/iczc/billboard
  * rw18q - MultiSigWallet [合约]：https://github.com/xhyumiracle/rwctf2018quals-MultiSigWallet
  * rw18f - Acoraida Monica [合约逆向]：https://github.com/xhyumiracle/rwctf2018finals-AcoraidaMonica
  * rw3rd - Re:Montagy [合约逆向+crypto]：https://github.com/xhyumiracle/rwctf3rd-Re-Montagy
  * rw3rd - Easy Defi [合约DeFi]：https://github.com/PandaTea/Realworld2021-EasyDefi
* 补充性趣味读物
  * [⽐特币设计起源与论⽂解读知乎文章](https://zhuanlan.zhihu.com/p/348414818)
