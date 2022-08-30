Reference: 
* https://css-tricks.com/snippets/css/a-guide-to-flexbox/
* https://www.w3school.com.cn/css/css3_flexbox.asp
* https://www.cnblogs.com/fantianlong/p/13992697.html#:~:text=align-items%20%E4%BB%85%E5%AF%B9%E4%B8%BB%E8%BD%B4%E4%B8%BA%E4%B8%80%E8%A1%8C%E7%9A%84%E5%AE%B9%E5%99%A8%E9%A1%B9%E7%9B%AE%E6%9C%89%E6%95%88%2C%20align-content%20%E4%BB%85%E5%AF%B9%E4%BA%A4%E5%8F%89%E8%BD%B4%E4%B8%8A%E6%9C%89%E5%89%A9%E4%BD%99%E7%A9%BA%E9%97%B4%E4%B8%94%E6%9C%89%E5%A4%9A%E8%A1%8C%E9%A1%B9%E7%9B%AE%E6%97%B6%E6%9C%89%E6%95%88,align-items%20%E5%B1%9E%E6%80%A7%E6%98%AF%E6%8A%8A%E6%AF%8F%E4%B8%80%E4%B8%AA%E9%A1%B9%E7%9B%AE%E4%BD%9C%E4%B8%BA%E4%B8%80%E4%B8%AA%E6%95%B4%E4%BD%93%2C%20align-content%20%E5%B1%9E%E6%80%A7%E6%98%AF%E6%8A%8A%E6%95%B4%E4%BD%93%E9%A1%B9%E7%9B%AE%E4%BD%9C%E4%B8%BA%E4%B8%80%E4%B8%AA%E6%95%B4%E4%BD%93

Exercise:
* https://flexboxfroggy.com/

![](basic.svg)


* flex-direction controls the direction of flex, justify-content controls the x axis, align-items controls the y axis.
* when the flex direction is a column, justify-content changes to the vertical and align-items to the horizontal.
* use order to change the order of the flex items
* use align-self to change the way of align of one item
* use flex-wrap to constrain the items. nowrap: Every item is fit to a single line; wrap: Items wrap around to additional lines; wrap-reverse: Items wrap around to additional lines in reverse.
* flex-flow is a combination of flex-direction and flex-wrap

align-items vs align-content
align-items only works for one-row flex-box while align-content works for multi-row flex-box with space.
align-items views the every project as a whole while align-content views the whole project as a whole.

