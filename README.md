# weread-download

下载微信读书书架上的书到本地，目前仅支持下载 html 格式。

## 项目说明
所有接口均为直接调用微信读书网页版API，解决了数据加密的问题。但这部分代码目前不打算开源，但可以交流技术实现。

项目托管在 Deno Deploy 上面，由于流量有限，所以每个账号每月暂定只能下载10本书，月初会重置次数。

> 注意：同一本书重复下载会重复计次，因为消耗了流量。

## 后续计划

- 修复部分图片无法加载的问题
- 美化网站样式
- 添加更多微信读书API，比如导出笔记、书评等