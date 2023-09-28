# SEteamProject
软工结对项目

Myapp.exe运行说明
- 使用 -n 参数控制生成题目的个数，例如：Myapp.exe -n 10  将生成10个题目。
- 使用 -r 参数控制题目中数值（自然数、真分数和真分数分母）的范围，例如Myapp.exe -r 10   将生成10以内（不包括10）的四则运算题目。该参数可以设置为1或其他自然数。
- 程序支持对给定的题目文件和答案文件，判定答案中的对错并进行数量统计，输入参数如下：Myapp.exe -e <exercisefile>.txt -a <answerfile>.txt统计结果输出到文件Grade.txt
        
