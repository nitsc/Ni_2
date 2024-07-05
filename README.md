概述:
这个程序是一个集成了多种功能的代码管理和转换工具，旨在为开发者提供简便高效的工作流程。通过命令行界面，用户可以轻松创建项目文件夹、生成和编辑.n文件，并将自然语言描述的程序转换为Python代码。特别之处在于，它利用先进的AI技术，支持用户使用详细严谨的自然语言编写程序，并将其发送给AI转换为Python语言，极大地提升了编程效率和便捷性。

主要特点:
项目管理： 轻松创建项目文件夹和.n文件（Ni 语言的程序源文件），组织和管理代码文件更加简便。
代码转换： 支持用户使用详细的自然语言描述程序，通过智谱AI或OpenAI的API，将自然语言内容转换为Python代码，减少了编写代码的时间和难度。
文件操作： 使用记事本打开和编辑.n文件，方便进行内容修改和预览。
脚本运行： 快速运行转换后的Python脚本，验证代码功能和效果。
包管理： 生成并执行批处理文件，自动安装所需的Python包，确保开发环境的完整性。
配置管理： 保存和加载API密钥及用户同意状态，支持清空和撤销同意操作，提供灵活的配置管理功能。

使用方法:
1.启动程序:
运行程序后，程序会尝试加载API密钥和用户同意状态。
如果用户未同意条款，会提示用户同意条款并输入API选择和API密钥。

2.命令行操作:
check+：显示程序信息。
creat+ project+ [路径] [项目名称]：在指定路径创建项目文件夹。
creat+ n+ [路径] [文件名]：在指定路径创建.n文件。
open+ [文件路径]：使用记事本（Notepad）打开指定路径的文件。
trans+ [文件路径]：转换指定路径的代码文件。用户可以编写详细的自然语言内容，然后使用此命令将其转换为Python代码。
run+ [文件路径]：运行指定路径的Ni脚本。
install+ [包名]：安装指定的Python包。
uninstall+ [包名]：卸载指定的Python包。
up+：升级pip。
blist+：列出安装了的python包。
bshow+ [包名]：详细展示安装了的python包的信息
clean+ key：清空API KEY配置文件。
clean+ agree：撤销用户对条款的同意。
exit+：退出程序。

注意事项:
用户需先同意条款并提供有效的API密钥。
确保在执行文件操作和转换代码时提供正确的路径。
确保已经安装python，pip，sys，os，subprocess，json，zhipuai,openai。
编程时禁止使用含“python”和“`”的关键字，否则脚本可能无法正常运行。

声明:
本程序由中国初一学生开发，如有不足，请积极提交反馈，可以通过以下联系开发者：
邮箱：dministrator1st1234567890dddaz@outlook.com, a111111111199999@outlook.com, kreantolittle2@outlook.com, zhoukreanto@gmail.com, 3792561886@qq.com, 3874057698@qq.com
QQ: 3792561886, 3874057698
个人网站（静态页面，用于发布本人的公告）：https://nitsc.github.io


Copyright © NITSC，Dean of NITSC，周**
