####  移动端1像素边框方案
---
基于CSS3媒体查询技术
利用Stylus编写

## 基本思路
使用伪元素::after,设置content,width,height,成为1px的盒子
利用CSS3属性device-pixel-ratio适配dpr进行缩放

## 使用方法示例
```Stylus
@import  'border.styl'
div
	border(1px 0 0 0)

```