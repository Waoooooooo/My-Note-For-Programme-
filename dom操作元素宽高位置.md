
el.offsetWidth/Height 元素的border-box的宽高
el.clientWidth/Height 元素的padding-box的宽高

el.getBoundingClientRect()
 {
  top,left,right,bottom,width,height,x,y
 }
 表示元素的border box距离视口左上角的位置,x/y对于left和top,width/height对应于offsetWidth/Height
  获取包裹元素生成的所有矩形框的最小矩形框
  此处Bounding就是包裹,围住的意思
el.getClientRects() 获取行内元素生成的多个矩形框的数据

el.scrollLeft/Top 元素有滚动条时,元素内容水平及垂直滚动距离,可赋值以修改其滚动距离
el.scrollTo/By(x,y) 滚动到x,y位置/基于当前位置滚动x,y距离

window.scrollX/Y, window.pageX/YOffset 页面在窗口中的滚动位置,不可写
window.scrollTo/By(x,y) 滚动到x,y位置/基于当前位置滚动x,y距离

window.innerWidth/Height 视口宽度和高度
