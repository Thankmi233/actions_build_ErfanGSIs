## actions_build_ErfanGSIs

修改了什么？

只跑ab

修改上传源为WeTransfer

取消精简

## 支持的Roms

### 9 Pie： ### 
> ColorOS	
Flyme
Generic
MIUI	
Moto	
Nubia	
OneUI	
OxygenOS	
Pixel	
Xperia	
ZUI	
ZenUI
### 10 Q： ###
> Generic
MIUI	
OxygenOS
Pixel
Flyme
### 11 R： ##
> Generic	
Pixel

## 一些简单的修改教程

如何跑精简包？

 在项目.github文件夹内的yml中找到这一段

 - name: Clone ErfanGSI Source Code

   run: git clone --recurse-submodules https://github.com/erfanoabdi/ErfanGSIs
       
fork该仓库https://github.com/erfanoabdi/ErfanGSIs

并将链接替换成你自己frok后的链接

修改Erfan项目中roms/安卓版本/rom文件夹中debloat.sh

例如：roms/10/MIUI/debloat.sh

并commit提交即可
