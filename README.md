# HUST-C-Lab

华中科技大学18级C++实验

共有五个实验，第五个实验属于可做项，做了平时分满分，这里我没有做

四个实验的main函数中都自己编写了测试代码，这个测试代码其实并不严谨，不能代表所有的情况，但是实验代码是满分通过的，可以直接利用老师所给的测试文件测试（实验课上都是这样检查）。使用测试文件的代码参考如下：

     extern const char* TestSTACK(int& s);
  
  main函数中写：
  
     int a;
     int& q = a;
     printf("U201814788 CS1806 刘美 实验三");
     printf("\n%s\n", TestSTACK(q));
     printf("%d\n", a);
     
 即可直接输出成绩
 
测试前需要将老师所给的相关实验的lib和pdb文件添加到项目文件夹中。然后在VS中右键点击项目选择属性->链接器->输入->附加依赖项，输入相关.lib文件的名称。
