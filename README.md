# CVE-2019-0708-poc
CVE-2019-0708 远程代码执行漏洞批量检测


3389_hosts为待检测IP地址清单，一行一个

pool = ThreadPool(10)  为自定义扫描线程


# 注意
Windows python3环境

# 使用
1. 编辑3389_hosts，将待检测的IP地址写入文件，一行一个
2. 命令行切换到代码所在的目录，运行python cve-2019-0708.py 
