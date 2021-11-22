# luckylog
一个美化版的python日志库/A glorified version of the Python logging library

# 安装/install luckylog
pip install luckylog

# 基本使用/use luckylog
Import files before use: from luckylog import luckylog
luckylog have four global variables：  
1、path：Path for saving logs  
2、module：Type of logs to be saved(success,erro,warning,tip)  
3、debug_file:Save the error message to the file path(decorator)  
4、Debug:Set whether to enable debugging(decorator)  
Tip : When Debug is set to TRUE, the log displays additional parameters and error messages  

使用前请先导入文件：from luckylog import luckylog
lukylog有四个全局变量：  
1、path：保存日志的路径  
2、module：选择保存哪种类型的日志(success,erro,warning,tip)  
3、debug_file：错误文件保存的地址（装饰器使用）  
4、Debug：是否开启debug模式，开启后日志会增加输入参数和报错信息展示（装饰器使用）  

# 使用规范/usage specification
Import files before use: from luckylog.luckylog import Looger,logger  
Put it inside the function:Logger.success('message'),Logger.erro()  
When path is set, the module has this log type and logs are written to the file defined by path  
logger is decorator,On top of the function, you can set custom success and fail messages  
When debug_file is set, the error message will be written, and when Debug is set to TRUE, the log will display the input parameters and error message on the console  

使用前导入：from luckylog.luckylog import Looger,logger  
放在函数里面：Logger.success('message'),Logger.erro()  
当设置了path，并且module写入了此日志类型，此日志将写入path定义的日志中
logger是一个装饰器，放在函数上面，你可以自定义success和fail的消息
当debug_file设置后，函数报错后，报错信息会被写入此文件，当Debug设置为TRUE，控制台显示的日志将多出输入的参数和报错的详细信息

# luckylog的优势/advantage
1、Has well differentiated colors, success is green, erro is red, warning is yellow, and tip is blue  
2、Easy to use, only need to set global variables  
3、Use decorator can automatically catch errors, whether to report errors directly to see whether there is a file  
4、There are little expressions that can add spice to life  

1、有更容易区分的颜色，success是绿色，erro是红色，warning是黄色，tip是黄色  
2、更简单使用，只需要设置一下全局变量即可  
3、使用装饰器能自动捕获错误，是否报错可以直接看是不是有文件产出  
4、拥有小表情，给生活增添趣味性  

# 联系我/contact
If you have any questions or suggestions, please contact us at 1538379200@qq.com  

如果使用中有任何问题和建议，可以随时联系我的邮箱1538379200@qq.com


