# MatLab 快速入门

**赋值语句**   
a = 1;  
a = 2  
(有分号，命令行窗口没有信息提示)  

**注释**

1）多行注释，选中语句，快捷键ctrl+r  
% a = 1;  
% a = 2  

2）取消注释，选中语句，快捷键ctrl+t

清除工作区的所有变量  
clear

清屏（命令行窗口）
clc

两条一起使用起到初始化的作用  
clear;clc  
分号也用于区分行

## 输出和输入函数

**disp函数**  
disp('Hello World')  
a = [1, 2, 3]  矩阵的同一行中间用逗号或空格分隔  
a = [1 2 3]  
disp(a)  

## 判断语句
a = input(‘请输入考试分数’)  
if a >= 85  
&emsp; disp('成绩优秀‘)  
elseif a >= 60  
&emsp; disp('成绩及格‘)  
else  
&emsp; disp('成绩挂科‘)  
end

