# layer
关于JQ-layer弹出层

默认居中出现，也可单独设置offset （官方文档只给了top和left的值）,但总是贴着边缘。若想距底部xxpx只能单独计算。
# 
    layer.msg("内容",{  
      time:1500,  //时间    
      offset:[800,0]  
      })
  
 #
 css在mobile/need，解决一直在左上角弹出问题
