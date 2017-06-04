A Python Cookbook 3rd learning note

### Ubuntu 安装字体的步骤
1. 将要安装的字体放在一个文件夹下，如```/usr/share/fonts/chinese-fonts```
2. 执行以下命令
   ```shell
    sudo mkfontscale
    sudo mkfontdir
    sudo fc-cache -fv
   ```

3. 安装完成，打开软件，选择新安装的字体