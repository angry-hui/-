#右键无Excel选项修复
##修复步骤
1. win + r 打开运行 ， 输入regedit 打开注册表
2. 找到 HKEY - CLASSES - ROOT > 选中[ xls or xlsx ] 
3. 右侧的默认的数据值由__Excel.Sheet.8__ 改为 __Excel.Sheet.12__