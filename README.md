## CVE-2020-8004
## 测试
`cd openocd-toolbox/scripts/linux/stm32f1x/`  
`./attach.sh`  
`cd stm32f1-firmware-extractor`  
`python3 main.py 0x08000000 512`

[test](https://github.com/wuxx/CVE-2020-8004/blob/master/doc/test.jpg)
[screenshot](https://github.com/wuxx/CVE-2020-8004/blob/master/doc/screenshot.png)
## 参考
- https://blog.zapb.de/stm32f1-exceptional-failure/
- https://gitlab.zapb.de/zapb/stm32f1-firmware-extractor/
- https://github.com/wuxx/CVE-2020-8004.git
- 《Cortex-M3权威指南》

