# HW-Mind-Studio
This repos is for Huawei Mind Studio &amp; Atlas 200 DK related docs. Most of docs can be found at [Official Docs](https://www.huawei.com/minisite/ascend/cn/file.html). 

## Usage
Mind Studio is an online IDE for deep learning. It was built at 251 server with port 12345. So you can access it using <http://192.168.1.251:12345>. The default user is *MindStudioAdmin*, password is *Archlab125@*. If you forget the password you will need the token *Root125@*. If you reinstall the Mind Studio server, you will need the default password *Huawei123@*. After you login, a pre-built sample project named *mind* can be seen in the project view. Following the [Mind Studio Usage Docs](https://www.huawei.com/minisite/ascend/cn/filedetail_9.html) to learn how to use it.

Atlas 200 DK can be access as 253 server, using *ssh root@192.168.1.253* or *ssh hisilicon@192.168.1.253*, both using the same password *hisilicon*. If you rebuild the Atlas 200 DK server, the default ip will be *192.168.0.2* or *192.168.1.2*, which can be edited at */etc/network/interfaces*. You can refer to [Atlas 200 DK Install Docs](https://www.huawei.com/minisite/ascend/cn/filedetail_2.html) to learn details.

Mind Studio is built at 251 server, and the source code can be accessed by *ssh huawei@192.168.1.251* with password *huawei*. Original install pkg is */home/huawei/huawei/clean/mini_mind_studio_developerkit-1.1.0T.B650SP03.rar*. After unzip the pkg, simple run the *install.h* can install the Mind Studio server. Currently the server is installed at */home/huawei/huawei/clean/Mind-Studio*. You can refer to [Mind Studio Install Docs](https://www.huawei.com/minisite/ascend/cn/filedetail_1.html) to learn details.

When using Mind Studio to run some codes, you may met some errors like xxx libs not found. These libs may be found at */usr/aarch64-linux-gnu*, so you can modify the auto-generated makefile to add the library path.






