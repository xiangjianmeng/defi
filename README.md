# pool based dex对比

* n: token数量
* w: 资产价值比重, 不大于1

|  item \ project  |  uniswap                   | balancer                                     |  curve                   |
|  ---             |  ---                       |  ---                                          |  ---                     |
| 添加流动性 前后对比 |  n1/n2 值不变               |  p=n1/n2 * (w2/w1)不变 ，V=n1^w1 * n2^w2 变大   |                          |
| 减少流动性 前后对比 |  n1/n2 值不变               |  p=n1/n2 * (w2/w1)不变 ，V=n1^w1 * n2^w2 变小   |                          |
| swap 前后对比     |  n1 * n2 值不变             |  p变化，V不变                                   |                          |
|                 |                             |                              |                          |
|                 |                             |                              |                          |
|                 |                             |                              |                          |
|                 |                             |                              |                          |
|                 |                             |                              |                          |
|                 |                             |                              |                          |
|                 |                             |                              |                          |
|                 |                             |                              |                          |
|                 |                             |                              |                          |
|                 |                             |                              |                          |
|                 |                             |                              |                          |
|                 |                             |                              |                          |
