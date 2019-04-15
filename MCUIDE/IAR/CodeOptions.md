![wpiLogo](../../imgs/wpiLogo.jpg)

# 3.3.2.修改 Options

---

###Step 1.右键工程结构树最上层目录(iarProject)，点击 Options

###Step 2.General Options->Target,Processor variant 选择 Device,NXP MKV30F64xxx10

![code12](../../imgs/IAR/code12.jpg)

###Step 3.C/C++ Complier->Preprocessor,添加文件路径

![code13](../../imgs/IAR/code13.jpg)

###Step 4.C/C++ Complier->Preprocessor,添加芯片定义

![code14](../../imgs/IAR/code14.jpg)

###Step 5.Assembler->Diagnostics，Warnings Disable

![code15](../../imgs/IAR/code15.jpg)

###Step 6.Linker->Config，勾选 Override default，选择 MKV30F64xxx10_flash.icf 文件，文件位于 ./MKV30F12810/iar

![code16](../../imgs/IAR/code16.jpg)

###Step 7.Debugger->Setup，Driver 选择 J-Link/J-Trace

![code17](../../imgs/IAR/code17.jpg)

###Step 8.Debugger.J-Link/J-Trace->Connection，Driver Interface 选择 SWD

![code18](../../imgs/IAR/code18.jpg)
