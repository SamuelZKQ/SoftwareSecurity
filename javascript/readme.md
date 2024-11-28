# 软件安全课程实践

为了统一评估课程实践“静态分析检测去误报”效果， 该目录为利用不同静态分析工具，对一些javascript项目扫描结果的TP/FP粗略分类。  

## codeql目录

包含下面4个项目的codeql原始检测报告和标签文档  
https://github.com/jellyfin/jellyfin-web  
https://github.com/OWASP/NodeGoat.git  
https://github.com/Esri/MyStreet  
https://github.com/YiFeng-Developer/pc-admin  

每个子目录下包含一个项目的codeql原始检测报告和标签数据  
\*.csv 、\*.sarif：codeql原始检测报告，包含漏洞类型和在项目代码中的位置  
\*_label.txt：标签文档，在.csv报告基础上的漏洞TP/FP标注  
标注方式：在每一条检测结果后标注TP/FP  

## semgrep目录
包含下面4个项目的codeql原始检测报告和标签文档  
https://github.com/jellyfin/jellyfin-web  
https://github.com/OWASP/NodeGoat.git  
https://github.com/Esri/MyStreet  
https://github.com/YiFeng-Developer/pc-admin  

每个子目录下包含一个项目的semgrep原始检测报告和标签数据  
\*.json：semgrep原始检测报告，包含漏洞类型和在项目代码中的位置  
\*_label.json：标签文档，在semgrep .json报告基础上的漏洞TP/FP标注  
标注方式：为每一条检测结果增加TP、FP字段  
