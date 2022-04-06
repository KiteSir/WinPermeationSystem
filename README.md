## 																					**WinPermeationSystem** 

**说明**：做这个系统的原因是因为自己的笔记本电脑是一块4K屏幕，VMware Workstation Pro的缩放不友好，字体太小，所以被迫使用Oracle VM VirtualBox，这个系统是模仿大佬的penetration-suite-toolkit系统进行制作的，非常喜欢大佬的系统，这个是给大佬做的补充，因为大佬的系统是基于VMware Workstation Pro制作的，我无法导入Oracle VM VirtualBox里使用，如果大佬后期制作基于Oracle VM VirtualBox我会停止更新。我这个系统比较大，大家可以自行删除卸载不需要的东西，来减轻磁盘压力。因水平有限，未测试出系统是否已感染木马后门，请自行测试，见谅！如有发现也请及时告知，谢谢！如果你不是非常喜欢Oracle VM VirtualBox，建议使用大佬制作的系统非常好用，请多多支持他。

#### **大佬的项目地址：https://github.com/makoto56/penetration-suite-toolkit**



**引用大佬的话：**

**`Windows10 渗透测试套件`**

```
- 基于Windows server 2019 MSDN原版镜像制作
- 镜像容量68G
- 建议运行环境：
  * Oracle VM VirtualBox6.1.x，建议安装扩展包
  * 运行内存：建议8G及以上
  * 固态硬盘：100G
```

**`写在前面的话：`**

```
1. 所有的安装类软件均下载自软件对应的官方网站。
2. 所有的绿色类软件均下载自果核剥壳。（https://www.ghxi.com/）
3. 所有的脚本类工具均下载自github。（https://github.com/）
4. 部分授权类工具（破解版）及优秀的渗透工具来自微信公众号分享
   * 排名不分先后，有未列举到的请见谅。
     潇湘信安、学蚁致用、谢公子学安全、雾晓安全、无尾熊安全、
     T00ls、渗透攻击红队、零组攻防实验室、洛米唯熊、雷石安全实验室、
     酒仙桥六号部队、InBug实验室、鸿鹄实验室、黑白之道、HACK之道、
     GobySec、Gcow安全团队、Gamma实验室、CobaltStrike实战、冰河技术、
     K8实验室、开普勒安全团队...
5. 本项目制作的初衷是帮助渗透新手快速搭建工作环境，工欲善其事，必先利其器。
6. 本项目由于后期调试原因可能会遗留部分本人的信息，请直接忽视。
7. 本项目坚决不接受也从未曾接受任何形式的赞助。
```

**`免责声明：`**

```
本镜像仅面向合法授权的企业安全建设行为，如您需要测试本镜像的可用性，请自行搭建靶机环境。
在使用本镜像进行检测时，您应确保该行为符合当地的法律法规，并且已经取得了足够的授权。
如您在使用本镜像的过程中存在任何非法行为，您需自行承担相应后果，作者将不承担任何法律及连带责任。
```
#### 建议：工具系统那个顺手用那个，工具不能让你成为”高手“，他只是让你提高效率。

项目地址：https://github.com/KiteSir/WinPermeationSystem

**更新说明**： 

​				1、本次更新移除了kali子系统，因为我无法让无线工具 Aircrack-ng 在此系统上正常使用，所以大家做无线安全测试还是会用虚拟机单独安装kali系统，所以我就不想再集成里面了，如有需要可自己安装,部分常用工具已在系统中集成。

​				2、部分工具已经升级为最新（2022.04)。

​				3、本次更新桌面采用可爱风格，一分钟自动切换闭眼、睁眼（照顾一下女生吧，哈哈），其他壁纸可以自行切换。

**使用技巧**：

​			1、系统开机密码为**H202201!**，部分软件登录账户请在办公工具里面的“系统使用说明“中查看。

​			3、建议重装一下 Oracle VM VirtualBox 增强工具。

​			4、系统导入之后可能存在未激活，可利用系统工具的Window激活\CMWTAT_Digital_Release激活工具激活。
