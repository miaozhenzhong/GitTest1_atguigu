解析json数据要分几部分

1.分析数据-结合ui，要做成什么样子

2.写JavaBean对象-两种写法

2.1 使用GsonFormat这个工具自动生成JavaBean对象
2.2,手动写JavaBean对象

3.解析json
3.1，使用第三方框架解析json 比例Gson解析 fastjson
3.2, 手动解析

注意，当GsonFormat根据数据生成JavaBean都无法生成，这个时候用gson无法解析
要想解析数据怎么办？
手动解析
