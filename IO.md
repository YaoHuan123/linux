##### 先上结论
- 优先使用带f开头的，fread，fwrite等
- fread，fwrite是带有缓冲区的
- 何时使用open等？打开设备文件的时候使用open这些低级IO
- 打开普通文件使用fopen这些高级IO
###### f开头的是ansi标准


##### read，write
- 低级IO

##### fread，fwrite
- 高级IO

##### recv,send
- 用于TCP，带有选项

##### recvfrom,sendto
- 用于UDP

##### recvmsg,sendmsg
- 既可以用于UDP也可以用于TCP


