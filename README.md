# AutoBuild-CSCLEDE

[![LICENSE](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square&label=LICENSE)](https://github.com/wubin2/AutoBuild-CSCLEDE/blob/master/LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/wubin2/AutoBuild-CSCLEDE.svg?style=flat-square&label=Stars)](https://github.com/wubin2/AutoBuild-CSCLEDE/stargazers)
[![GitHub Forks](https://img.shields.io/github/forks/wubin2/AutoBuild-CSCLEDE.svg?style=flat-square&label=Forks)](https://github.com/wubin2/AutoBuild-CSCLEDE/fork)

![MENU](docs/menu.png)  

## Usage 

Build OpenWRT firware using Github actions for X86\Newifi\K3\GL-iNet elses.  

- Fork [this GitHub repository](https://github.com/wubin2/AutoBuild-CSCLEDE/fork). 
- Click [`.github/workflows`] folder on the top of repo and you could see few workflow files, Each for one particular architecture(device). 
- Edit `CSCLEDE-device.yml` file that your choice，uncomment push section 3 lines together and submit the commit. 
- The build starts automatically. Progress can be viewed on the `Actions` page. 
- When the build is complete, click the `Artifacts` button in the upper right corner of the Actions page to download the zip file. 

## Default Setting  

- IP: `192.168.1.1`  
- Username&Password: Please change your password for the first time login!  
- WiFiSSID: `CSCLEDE`  
- WiFiPassword: `coolsong`  
- Schedule: AutoBuild runs at 04:15 on the 15th of every month.

## Acknowledgments

- Source form [Lean's OpenWrt](https://github.com/coolsnowwolf/lede) & [Lienol's LEDE](https://github.com/Lienol/lean-lede)  
- Build Tools [P3TERX](https://github.com/P3TERX/Actions-OpenWrt) & [eSirplayground](https://github.com/esirplayground/AutoBuild-OpenWrt) & [YAMLCheckout](http://www.yamllint.com/)   
- Packages Related  
[luci-app-ssr-plus-Jo](https://github.com/Leo-Jo-My/luci-app-ssr-plus-Jo)  
[luci-app-openclash](https://github.com/vernesong/OpenClash)  
[luci-app-koolproxyR](https://github.com/tzxiaozhen88/luci-app-koolproxyR)  
[luci-app-adguardhome](https://github.com/rufengsuixing/luci-app-adguardhome)  
[openwrt-adguardhome](https://github.com/happyzhang1995/openwrt-adguardhome)  
[luci-app-serverchan](https://github.com/tty228/luci-app-serverchan)  
- Themes Related  
[luci-theme-argon](https://github.com/jerrykuku/luci-theme-argon)   

## License

[MIT](https://github.com/wubin2/AutoBuild-CSCLEDE/edit/master/LICENSE) © Tristan
