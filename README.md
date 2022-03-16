## Demo1：交互力引导布局，用户可增加删除节点/连边
## Demo2: 交互力引导布局，可进行分组节点（超点）的拓展和收缩
# 1. InteractiveForceLayout(简单的节点连边删除增加）

<img src="https://github.com/graytheone/InteractiveForceLayout/blob/main/demo1.gif" width="300px">
credit to :

https://gist.github.com/xswei/cdf09e3761bce41a21f87445fa2b3944
https://bl.ocks.org/xswei/cdf09e3761bce41a21f87445fa2b3944

参考资料:
1. http://bl.ocks.org/rkirsling/5001347 (与下同理)
2. http://bl.ocks.org/sebbacon/6138241 (Click-to-edit force directed graph in d3)
3. https://bl.ocks.org/mbostock/1062288 (树图的节点展开和收缩)
4. https://gist.github.com/GerHobbelt/3104394/585e0ba27af8abde56d5064e2eeb318d263b68e4 (多类型边的节点扩展和收缩)

# 2. Rewriting Bundle to Click(重写超点拓展/收缩功能）
http://bl.ocks.org/relunctance/b3958e757675874d438dd2eddc26decc ：d3.js: force layout; click to group/bundle nodes，原始项目的问题：扩展时节点从外围飞入，导致视觉不稳定。造成这个的原因是给新增节点设置x和y时，设置的与其他节点位置太近了，导致一开始斥力很大，设置xxx.x = dx+10*Math.Random();就可以了，所以可以直接上面这个demo，自己写的逻辑虽然清楚，但是代码不简洁。
### 重写后效果
<img src="https://github.com/graytheone/InteractiveForceLayout/blob/main/demo2.gif" width="300px">

