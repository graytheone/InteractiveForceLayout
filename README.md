# InteractiveForceLayout(简单的节点连边删除增加）
Interactive Update for D3.js force directed layout, users can select nodes and links to manipulate(add/remove) the graph layout.
![demo](https://github.com/graytheone/InteractiveForceLayout/blob/main/demo.gif)

credit to :

https://gist.github.com/xswei/cdf09e3761bce41a21f87445fa2b3944
https://bl.ocks.org/xswei/cdf09e3761bce41a21f87445fa2b3944

dataset: miserables.json

d3.js: v5+

other material:
1. http://bl.ocks.org/rkirsling/5001347 (与下同理)
2. http://bl.ocks.org/sebbacon/6138241 (Click-to-edit force directed graph in d3)
3. https://bl.ocks.org/mbostock/1062288 (树图的节点展开和收缩)
4. https://gist.github.com/GerHobbelt/3104394/585e0ba27af8abde56d5064e2eeb318d263b68e4 (多类型边的节点扩展和收缩)

# Rewriting Bundle to Click(重写超点拓展/收缩功能）
[d3.js: force layout; click to group/bundle nodes]http://bl.ocks.org/relunctance/b3958e757675874d438dd2eddc26decc
![image](https://user-images.githubusercontent.com/25164823/156869457-3826d95f-a3f9-43c8-af0c-d0f23f79a119.png)
原始项目的问题：扩展时节点从外围飞入，导致视觉不稳定。
