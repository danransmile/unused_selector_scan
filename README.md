# unused_selector_scan

iOS 删除无用代码

一、操作步骤

一.点击左上角加号：New Run Script Phase

二.导出环境变量：添加脚本：“${PROJECT_DIR}/exportenv.sh”，并将exportenv.sh放到与工程同级目录下

三.将脚本：unused_selector_scan.py放到与工程目录同级

四.先运行下工程（真机或模拟器都可以），此时工程目录下会多出env.sh文件

五.打开terminal终端，cd到工程目录下

六.执行python unused_class_scan.py

七.查看工程目录下，会多出unused_selector.txt，即为无用类

二、原理 无用oc方法
