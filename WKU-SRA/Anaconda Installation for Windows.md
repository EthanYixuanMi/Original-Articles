- 在各位安装Anaconda时，我们通常建议勾选 "Add Anaconda to my PATH environment variable" 选项。这样可以正常在command prompt内使用conda命令。

**但是，如果忘记将Anaconda添加到系统环境变量，那么会导致conda命令在command prompt中无法使用，如：**
![[759cb77cf7ca92be93543fcd53bd436.png]]

### 解决方案
---
- 最简单的方法是【卸载重装】，再次安装时勾选“添加PATH”即可。
![[Pasted image 20240801141851.png]]

- 我们也可以手动将conda添加到环境变量中，步骤如下：
1. 打开控制面板（`win + r + control`），选择“系统与安全”，然后选择系统
![[Pasted image 20240801140039.png]]
![[Pasted image 20240801140205.png]]

2. 点击“高级系统设置”
![[Pasted image 20240801140424.png]]

3. 在“系统属性”窗口中，点击“环境变量”
![[Pasted image 20240801140533.png]]

4. 在“系统变量”部分，找到并选中名为`Path`的变量，编辑它
![[Pasted image 20240801140832.png]]

5. 确认Anaconda安装目录的路径在列表中。如果没有，请添加。


使用以上两种方法之一之后，不管是在command prompt，还是windows powershell，还是Anaconda自带的Anaconda powershell prompt等命令行中都可以运行conda命令了

![[Pasted image 20240801143256.png]]
![[Pasted image 20240801143225.png]]
![[Pasted image 20240801143400.png]]
