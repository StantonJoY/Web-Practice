# 互联网+方向实践

需求：

1. 展示外规列表。暂时不做分页，直接全部传。GET 请求

2. 选择某一个外规，向后端传在列表中的索引号。POST

3. 后端逐个计算相似度，将计算的结果给前端。（可能有较长等待时间，考虑做一点交互设计）同样暂时不做分页