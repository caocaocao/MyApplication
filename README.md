1、这是出现问题的最小工程；
2、需要注意的是：如果一开始不加渠道成功运行过，会生成临时文件。这时候工程添加渠道号后编译，运行是没问题的，因为使用了不加渠道号的临时文件。需要手动把之前的临时build文件删除，再运行问题就重现了。你那儿没重现估计是这个问题。