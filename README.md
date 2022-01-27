# Mac_Tools

![](https://img.shields.io/github/stars/NineRiverSec/Mac_Tools) ![](https://img.shields.io/github/forks/NineRiverSec/Mac_Tools)  ![](https://img.shields.io/github/issues/ghealer/GUI_Tools)
> 让你在Mac下免去在命令行执行 java -jar xxx.jar 改为原生应用启动。

### ✨ 演示
![](https://raw.githubusercontent.com/NineRiverSec/Mac_Tools/main/img/Demo.png)



### 🚀 快速使用
- 下载程序安装包 xxx.dmg 格式

  `双击打开后 将应用拖动到Applications文件夹就可 `
  
- 下载安装包地址

  `5Lyg6L6T6ZO+5o6l77yaaHR0cHM6Ly9hbmR1LmNvd3RyYW5zZmVyLmNvbS9zLzg0NTA1ZWIxMGU4YjQ1IOaIliDmiZPlvIDjgJDlpbbniZvlv6vkvKDjgJFjb3d0cmFuc2Zlci5jb20g5L2/55So5Lyg6L6T5Y+j5Luk77yacmJwdnZsIOaPkOWPlu+8mw==`
  
  ( 通用打开密码:123456 )
  
- 为了压缩体积 大部分应用没有内置JDK，这样的选择能够将应用保持和xxx.jar 原文件大小相同。
  
- 现有应用
```markdown
.
├── Behinder.dmg
├── Burp Suite Pro.dmg
├── Burp Suite Professional.dmg
├── CTFCrackTools-4.0.4.dmg
├── Cknife.dmg
├── Cobalt Strike 4.4.dmg
├── EXP-Verify.dmg
├── FastJsonAttack_V1.1.dmg
├── FastJson_JackSon.dmg
├── Fiora.dmg
├── Fofa_Viewer.dmg
├── Godzilla.dmg
├── Java反序列化漏洞利用工具V1.7.dmg
├── LandrayExploit.dmg
├── LiqunKit.dmg
├── LiqunShield.dmg
├── MDUT.dmg
├── MySQLMonitor.dmg
├── NMAP伴侣.dmg
├── Shiro-Decrypt.dmg
├── ShiroAttack2.dmg
├── ShiroExploit.dmg
├── SpringBootExploit.dmg
├── Struts 2 全版本漏洞检测工具.dmg
├── TODA.dmg
├── ThinkPHP GUI.dmg
├── ThinkPHP_Log_Scan.dmg
├── ThinkPHP命令执行检测工具.dmg
├── Tomcat弱口令爆破.dmg
├── WebLogicPasswordDecryptor.dmg
├── Weblogic-Framework.dmg
├── Weblogic漏洞利用工具.dmg
├── oracleShell.dmg
├── webfinder.dmg
├── 神机.dmg
└── 致远OA漏洞全版本扫描工具v1.0.1.dmg

0 directories, 36 files
```

### 🐾  更新日志

- 2021年12月31日 V1.0
	- 只有少量安装包
	- ~~采用直接内置jdk的方法避免配置jdk环境。~~ （在V1.1更新的时候大部分应用已经不携带jdk环境。）
	- 发现部分M1用户使用打包后的冰蝎打不开。
	
- 2022年1月27日 V1.1
	
	- 安装包大量增加突破30+常用 jar 原生应用。
	- 修复部分M1用户使用打包后的冰蝎打不开问题。
	- 采用去除 JDK 压缩体积的方式，来压缩体积。
	

### 📝 免责声明

	本工具仅面向合法授权的企业安全建设行为，在使用本工具进行检测时，您应确保该行为符合当地的法律法规，并且已经取得了足够的授权。  
	
	如您在使用本工具的过程中存在任何非法行为，您需自行承担相应后果，我们将不承担任何法律及连带责任。 
	
	在使用本工具前，请您务必审慎阅读、充分理解各条款内容，限制、免责条款或者其他涉及您重大权益的条款可能会以加粗、加下划线等形式提示您重点注意。 除非您已充分阅读、完全理解并接受本协议所有条款，否则，请您不要使用本工具。
	
	您的使用行为或者您以其他任何明示或者默示方式表示接受本协议的，即视为您已阅读并同意本协议的约束。 

### 🙋 问题反馈

- 反馈渠道
	- 如有问题请提交 Issues，我看到会及时解决。

- 关于工具
	- 后面会定期更新添加工具，各位在使用的时候如果有什么比较好用的想要添加到工具里的也可以提交 Issues。
	- **所有工具的收集均来自互联网，请自行甄别是否存在后门等程序，建议在虚拟机里运行本程序下的工具。**
	- **几乎90%工具都能在GitHub找到原版，不妨去给写工具的大佬们点个Star吧。**
	- 其实更新真的随缘。
	
- **关于可能 存在后门的工具**(发现可能存在后门的工具可以随时在issues提出。)
	
	- **CobaltStrike：采用原jar包配合CSAgent的方式破解，有效避免了可能存在后门的可能性，可以去官网对比Hash值。**
	- **MDUT：已经是根据原GitHub项目进行重新打包的，已经避免了当时可能存在后门的hta文件。**
	
	
	
	

