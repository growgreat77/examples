<!-- This README file is going to be the one displayed on the Grafana.com website for your plugin -->

# Data s7-1200 and s7-1500

trioop.hmi@gmail.com

You can only add one 1200 or one 1500 data source.

For local use only, no external distribution allowed.

This data source is compatible with Siemens 1200 and 1500 PLCs.

Variables can only be added up to 512.

 # Note

 1.The enable switch is used to start and stop communication.Before deleting the datasource page, please stop the communication first.

 2.Once a database name, variable name, and variable type are bound for the first time, the variable name belongs to the specified type and cannot be changed. 

 3.If you want to modify the variable type of the variable name, you would need to modify the database name.

# 注意

1. 使能按钮用于连接和断开PLC的连接。删除数据源之前，需要将使能按钮断开。

2. 第一次按了“Save & test”按钮，“Variable Name”就属于某个“Data Type”，在同一个“Database”，就无法修改成其他的数据类型了。

3. 如果想修改变量名的数据类型，需要一并修改Database的名字，或者重新初始化Database数据库。

