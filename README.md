# 1、收集访问短信接口不正常的ip；（通过es收集）
`1.1 收集后，放入redis暂存；`

# 2、利用nginx进行限制访问；
`2.1 去redis取ip，进行限制；`

# 3、运行原理
`参照‘Ip_black_list.xlsx’文件`