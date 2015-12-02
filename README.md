### 说明  
  
#### `rem.html`：手机版响应式网页(采用相对单位rem)  
* 说明：rem是相对单位，相对于根元素html，root em。  
* 页面基于750px设计稿，但兼容多种尺寸移动设备。  
* html{font-size:100px;}为参照，方便计算rem值，如body的width为：7.5rem，设计稿的横向分辨率/`100`。  
* `除了html根节点的font-size使用px单位外，其他css尺寸尽量使用rem单位`思想(如果确实要用px单位，可以跟媒介查询挂钩)。  
* device-width的计算公式为：设备的物理分辨率/(devicePixelRatio * scale)，设备像素比devicePixelRatio高清屏一般都是2。  
  
#### `web.html`：电脑常用网页文件结构  
  
#### `mob.html`：手机常用网页文件结构  
  
本项目Sublime Text代码编辑器snippet已完成 https://github.com/wuyumin/mySublimeText/tree/master/snippet
  
如果出现什么问题或有什么建议，欢迎你在GitHub里Pull Requests或Issues一下，方便进行改进。  
