# hybird_app

### felx
1. 2009提出
2. 为盒装模型提供了灵活性
3. 横向为主轴、纵向为交叉轴

### flex-direction
1. row
2. row-reverse // 里面的内容（项目）是从右至左排列，顶点在容器的最右面
3. column
4. column-reverse

### flex-wrap
1. 项目沿着主轴方法展开
2. 当项目的长度超过了主轴的长度时，该如何显示
3. wrap：换行
4. no-wrap：不换行，项目长度变小
5. wrap-reverse：沿着交叉轴相反的方法排列

### webpack
1. 多一个文件，浏览器就会多发一个请求，增加了出错的可能性
2. 开发时的多个模块打包成几个模块
3. 对图片进行压缩或者把图片转为base64

### @vue/cli
1. 基于webpack
2. 快速生成vue项目的基础结构
3. npm i @vue/cli -g
4. vue create your project name

### rem的兼容性设置
1. 1个px占据了一个绝对的像素点
2. 定义相同的文字大小，但是这些文字在不同的设备上应该展示不同的像素数
3. 相对于<html>标签元素FontSize大小的单位
4. 根据屏幕的宽度定义根元素fontSize的大小
