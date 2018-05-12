#一个有趣的LoadingView

https://juejin.im/post/5aec99ab6fb9a07ab83de81f?utm_source=gold_browser_extension


这个图，大家看着眼熟吗？对就是github最近一年的提交表单。

不好意思贴错了，这才是我的。。。
最近在着手写一个GitHub客户端，然后看到这个表的时候突然来了灵感，想把它模拟成一个加载动画展现出来，于是就有了下边的这个菊花。

gif制作工具把mov格式改成gif格式后深绿色变了颜色，不过这个不影响分辨颜色深度。
而且，方块的出现频率 是和当前App 上传与下载的流量有关系的。也就是说网速越快，出现深色的概率也高。网速越差 可能都不会出现方块。
使用起来也很简单。

所有的参数有：
nodeCount  方块总数
nodeAutomation  是否自动动画
nodeSize 方块的大小
nodeInterval 方块的间距
nodeCycle 每列方块的数量控件是com/freedom/wecore/widget/node/NodeView
//TODO 后期还需要添加上动画的速度，以及算概率的时候把动画速度的因素也考虑进去。
