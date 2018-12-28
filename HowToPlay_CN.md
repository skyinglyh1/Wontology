怎样玩 | [How to play](HowToPlay_EN.md)

## 基本规则

Ong Bet是运行在Ontology公链上的去中心化、可信的区块链游戏。Ong Bet的基本规则如下：

1. 这是一个“摇骰子”比大小的游戏，骰子点数根据下注当时Ontology主链当前区块hash生成；

2. 游戏由平台运营、游戏庄家、游戏玩家组成；

3. 庄家玩法

   1. 庄家投资坐庄。

   2. 投资逻辑

      | 运营成本 | 庄家激励  |游戏运营池|
      | -------- | -------- | ------ |
      | 2%       | 8%      | 90%    |

   3. 庄家投资的2%将作为运营成本。
   4. 庄家投资的8%将分给之前所有的庄家作为庄家激励，鼓励庄家尽早坐庄。
   5. 庄家投资的90%将用作游戏运营。游戏运营的利润立即分给所有庄家，直至当前游戏运营池小于所有庄家投资进入游戏运营池总额的10%，则本轮游戏结束，同时游戏运营池的剩余资金将按比例分给所有庄家。
   当有新庄进入游戏坐庄时，游戏进入下一轮。

4. 玩家玩法

   1. 玩家选择金额和数字下注，下注根据当轮区块hash所生成的“骰子”数 **小于** 玩家数字即根据下注金额获得对应赔率的回报；

   2. 游戏玩家随时下注，即时（当轮出块区块）获得当轮骰子结果，即时获得回报；

   3. 骰子点数范围1-100；

   4. 下注范围2-96；

   5. 中奖（获胜）概率1%-95%；

   <!-- 6. 赔率满足如下公式，赔率 x 中奖概率 = 0.98，回报金额从庄家游戏运营池获得。

      | 中奖补偿 | 运营成本 | 庄家激励 |
      | -------- | -------- | -------- |
      | 98%      | 1%       | 1%       | -->