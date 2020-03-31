# ZED-Camera-SDK-and-ZED-Python-API-Installation-on-Ubuntu-18.04-LTS
It's a repository to use ZED camera with with ZED SDK &amp; ZED Python API for Object detection with Tensorflow.
# ZED Camera SDK Installation:
Download the Latest SDK version from the site: https://www.stereolabs.com/developers/release/
The default download should be in your "Downloads" directory. To check, run in a terminal:
```
cd ~/Downloads
ls
```
You should see a file in the name of ZED_SDK_Ubuntu18_cuda10.2_v3.1.2.run or something similar. <br>
Now change the permission of the file so that you can execute it from the terminal.
```
chmod +x ZED_SDK_Ubuntu18_cuda10.2_v3.1.2.run
```
Now the file is executable. Run the following command:
```
./ZED_SDK_Ubuntu18_cuda10.2_v3.1.2.run
```
Follow the instruction & the necessary files and libraries will automatically be installed in to the system. To check installation, run the following command:
```
cd /usr/local/zed/tools
ls
```
You should see some executables. Try to run them one by one. After starting an executable, to stop it, hit ctrl+c. Now run the following command:
```
#start an example
./ZED_Explorer
#stop it
ctrl+c
#start another example
./ZED_Depth_Viewer
#stop it
ctrl+c
#start another example
./ZEDfu
#stop it
ctrl+c
```

