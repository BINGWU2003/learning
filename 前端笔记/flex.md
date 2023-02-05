# align-content和align-item的区别

## 结论

align-items属性是针对单独的每一个flex **子项**起作用，它的基本单位是每一个子项，在所有情况下都有效果（当然要看具体的属性值）。
align-content属性是将flex子项作为一个**整体**起作用，它的基本单位是**子项构成的行**，只在两种情况下有效果：①子项多行且flex容器高度固定 ②子项单行，flex容器高度固定且设置了flex-wrap:wrap;

flex-warp:wrap;属性必须有

![image-20221013000808970](C:\Users\1034291441\AppData\Roaming\Typora\typora-user-images\image-20221013000808970.png)

## 案例

