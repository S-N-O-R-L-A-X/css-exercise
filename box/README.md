![box](box.drawio.svg)

计算元素的width和height属性时，设置的仅是content的宽度和高度，要计算完整大小，还需要把padding,border,margin加上。
元素总宽度 = 宽度 + 左内边距 + 右内边距 + 左边框 + 右边框 + 左外边距 + 右外边距
元素总高度 = 高度 + 上内边距 + 下内边距 + 上边框 + 下边框 + 上外边距 + 下外边距