已删除三码请自行添加三码

EFI文件加速下载地址： https://wwa.lanzoui.com/b00nzab4j 

正常工作：CPU变频、核显、亮度、声卡、键盘、触摸板、USB已定制、电池。

存在问题：

1.无hdpi，开启hdpi后遇到了第二阶段大苹果图标；

2.独立显卡MX150 无法驱动已禁用；

3.不明原因导致偶发电脑黑屏无法亮屏，合盖再打开可以解决；

4.WI-FI与蓝牙问题 无线网卡无法驱动 已更换AX200 换白果免驱网卡可以解决 或者可以使用USB网络共享。

已解决：

1.NVMeFix.kext可能存在不兼容会造成开机多次自动重启 无NVMe硬盘移除可恢复正常 有NVMe硬盘建议添加此驱动并自行测试兼容版本；

3.读卡器已成功驱动但未测试可用性；

4.已修复亮度调整（删除了“-igfxblr”和“enable-backlight-registers-fix”参数并定制SSDT-PNLF后成功修复）；

5.修复macOS12蓝牙关闭无法打开。

不出意外的话我会每月更新open core版本及驱动，我的笔记本电脑是Acer-A615-51G-51MQ，Corei5-8250U（Intel UHD Graphics 620）
有更好的efi配置或者可以帮助修复以上问题请联系我971247666@qq.com，谢谢。

![截屏2021-08-13 上午11 56 53](https://user-images.githubusercontent.com/67421836/129302893-6cb3954e-9356-4dc9-80e0-000f0ea93af2.png)

图片上的配置文件都是我改着玩的 可在config.plist文件内查看

![屏幕截图 2020-12-09 163158](https://user-images.githubusercontent.com/67421836/129293568-424256ba-1b45-428f-8a57-f515ef3cb905.png)
