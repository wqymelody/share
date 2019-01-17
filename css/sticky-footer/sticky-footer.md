### 我们在开发的过程中会碰到内容很少，然后底部没有固定到底部的问题，因此，sticky-footer很关键。在这里我推荐两种方法
#### 方法1：使用flex布局，具体的可以看该目录下的demo1，其主要原理就是利用改变flex主轴方向为纵轴，内容部分设为flex：1，就是占主轴方向的剩下部分，即100vh-footer的高度（100vh相当于视图高度，1vh=1%*视图的高度）,示例请看demo1.html

#### 方法2 ：就是把html，body高度设为100%，wrapper部分设置成min-height：100%；然后给wrapper下的内容设置padding-bottom：footer的高度； 最后给footer设置margin-top：-footer的高度，相当于把footer往上拉了和footer一样的高度，详细示例请看demo2.html