# 9.introdcue the the visual formatting model(视觉格式化模型)
## 9.1introduction to the visual formatting model
vfm（我也不知道我为啥要讲一个vfm的缩写来指代），主要功能就是指导浏览器如何将‘文档树’排版；
渲染的过程就是 文档中的元素 根据 ‘盒模型’，生成 0 || 多个 盒子。然后 盒子 的 布局排版由 一下  
  
  * 盒子定义（尺寸什么的）和类型
  * position的类型（normal flow，float，absolute ）
  * 文档树中的元素的关系
  * 扩展信息（viewport 尺寸， 图片的 大小） 
### 9.1.1 the viewport 
### 9.1.2 Containing blocks
## 9.2 Controlling box generation 
###   9.2.1 Block－level elements and block boxes
#### 9.2.1.1 Anonymous block boxes
### 9.2.2 inline-level elements and inline boxes
### 9.2.3 Run-in boxes
### 9.2.4 this 'display' prototype 
## 9.3 Positioning schemes
### 9.3.1 Chooseing a positioning scheme:'position' property
### 9.3.2 box offsets :'top','right','bottom'，‘left’
## 9.4 Normal flow
### 9.4.1 Block formatting context
### 9.4.2 inline formatting context
### 9.4.3 Relative positioning
## 9.5 Floats
### 9.5.1 Positing the float:the 'float' property
### 9.5.2 Controlling flow next ti floats:the 'clear' property 
## 9.6 Absolute 
### 9.6.1 fixed positining
## 9.7 Relationship between 'display' ,'positin',and 'float'
## 9.8 Comparison of normal flow,floats,and absolute positioning
### 9.8.1 Normal flow
### 9.8.2 Relative positioning 
### 9.8.3 Floating a box
### 9.8.4 Absoute
## 9.9 layed presentation
### 9.9.1 spercifying the stack level : the 'z-index' property 
## 9.10 text direction:the 'direction' and 'unicode-bidi' properties





