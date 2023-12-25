1
==
**不能将虚拟机外部的文本复制到虚拟机内部**
**解决方法：**
**下载open-vm-tools-desktop**
2安装anaconda时报错
==
**依赖cpp (= 4:9.3.0-1ubuntu2)但是4:11.2.0-1ubuntu1正要被安装**

**错误原因：**
**考虑镜像源是否正确，22.04版本因该换jammy源，因误换focal源导致出错**
**解决办法：**
**更换最新的源**

3在使用git clone时出错
==
**fatal: 过早的文件结束符（EOF） fatal: index-pack 失败**

**错误原因：**
**下载的文件太大**
**解决办法：**
**减少克隆分支的高度默认克隆主分支，再进行其他的分支的下载**

4在配置环境变量时无法保存
==
**修改终端环境变量后，没有确认按钮**

**解决方法：按住Esc键，再按住shift+：，输入wq，即为保存，这是一个常用的快捷键**

5
==
**在配置anaconda时出现报错**
**解决方法：**
**虚拟机内存不够，重新开了一个内存更大的虚拟机**

6
==
**安装opencv时报错：**

**Package opencv was not found in the pkg-config search path.**
**Perhaps you should add the directory containing `opencv.pc'**
**to the PKG_CONFIG_PATH environment variable**

**o package 'opencv' found**

**解决方法：**
**缺失了opencv.pc这个配置信息文件，将其添加并保存到环境变量中**
