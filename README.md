adb devices	                	:列出adb设备
adb reboot		                :重启设备
adb reboot recovery	                :重启到recovery模式
adb reboot bootloader	                :重启到fastboot模式

fastboot devices			:列出fastboot设备
fastboot reboot				:重启设备
fastboot reboot recovery		:重启到recovery模式
fastboot reboot bootloader		:重启到fastboot模式
fastboot oem device-info 		:查看解锁状态（骁龙）true解锁，false未解锁
fastboot flash boot ^<分区名称^> ^<镜像文件名^>	:刷写对应分区
