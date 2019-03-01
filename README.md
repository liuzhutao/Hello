# bug
The code has a bug£ºafter executing hello.exe, it returns a changed background & foreground color. 
Somthing like this [screen ](picture/screencut-hello.PNG)
# requirement
After executing hello.exe, making it return the original background & foreground color. 
# solution
All we need is a piece of code to reset the color to the defalt, and the code is here  
```C#
 Console.ResetColor();
```
# result
the result after my revision is like this [screen2 ](picture/screencut-hello-revision.png)