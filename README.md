## WxJava-WeChat Development Java SDK (Development Kit) [![LICENSE](https://img.shields.io/badge/License-Anti%20996-blue.svg)](https://github.com /996icu/996.ICU/blob/master/LICENSE) [![Badge](https://img.shields.io/badge/Link-996.icu-red.svg)](https://996.icu /#/zh_CN)


[![码云Gitee](https://gitee.com/binary/weixin-java-tools/badge/star.svg?theme=blue)](https://gitee.com/binary/weixin-java- tools)
[![Github](https://img.shields.io/github/stars/Wechat-Group/WxJava?logo=github&style=flat)](https://github.com/Wechat-Group/WxJava)
[![GitHub release](https://img.shields.io/github/release/Wechat-Group/WxJava.svg)](https://github.com/Wechat-Group/WxJava/releases)
[![Maven Central](https://img.shields.io/maven-central/v/com.github.binarywang/wx-java.svg)](http://mvnrepository.com/artifact/com.github .binarywang/wx-java)
[![Build Status](https://travis-ci.org/Wechat-Group/WxJava.svg?branch=develop)](https://travis-ci.org/Wechat-Group/WxJava)
[![Develop and maintain using IntelliJ IDEA](https://img.shields.io/badge/IntelliJ%20IDEA-support-blue.svg)](https://www.jetbrains.com/?from=WxJava- weixin-java-tools)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

#### Support the back-end development of WeChat functions including WeChat payment, open platforms, official accounts, enterprise WeChat/enterprise accounts, and mini programs.

<p align="center">
  <b>Special sponsorship</b>
</p>
<br/>
<table align="center" cellspacing="0" cellpadding="0">
  <tbody>
    <tr>
<td align="left" valign="middle">
        <a href="http://mp.weixin.qq.com/mp/homepage?__biz=MzI3MzAwMzk4OA==&hid=1&sn=f31af3bf562b116b061c9ab4edf70b61&scene=18#wechat_redirect" target="_blank">
<img height="120" src="https://gitee.com/binary/weixin-java-tools/raw/develop/images/qrcodes/mp.png">
        </a>
<a href="https://promotion.aliyun.com/ntms/act/qwbk.html?userCode=7makzf5h" target="_blank">
<img height="120" src="https://gitee.com/binary/weixin-java-tools/raw/develop/images/banners/aliyun.jpg">
</a>
</td>
      <td align="center" valign="middle" width="450">
        <a href="http://ccflow.org/?from=WxJava" title=" Gallop BPM" target="_blank">
          <img height="60px" src="http://ccflow.org/ccflowAD_Title.png" title="gallop BPM official website">
          <p>1. Galloping rapid development platform, workflow engine, form engine adopt GPL agreement.</p>
<p>2. The gallop.net version is called ccflow, the java version is called jflow, and the code is 100% open source.</p>
<p>3. Support more than 10 domestic and foreign databases. Stand-alone version\group version\SAAS version.</p>
        </a>
      </td>
</tr>
</tbody>
</table>

### Important information
1. **Release on 2021-06-02 [【4.1.0 official version】](https://mp.weixin.qq.com/s/nIk_xOf6dxkhKfqq830Cuw)**!
1. Important reminder for novices: This project is only an SDK development kit and does not provide web implementation. It is recommended to use `maven` or `gradle` to reference this project to use the various functions provided by this SDK. For details, please refer to **[ [Demo project]](demo.md)** or part of the unit test code in this project; in addition, new WeChat developers must read [[Development Documentation Wiki Home Page]](https://github.com/Wechat-Group/ WxJava/wiki) FAQ section, you can avoid a lot of detours and save a lot of time.
1. Technical exchange group: For students who want to obtain information such as QQ group/WeChat group/Dingding enterprise group, please use WeChat to scan the QR code of the WeChat official account above to follow `WxJava` and click on the relevant menu to get the joining method. At the same time You can also search for `weixin-java-tools` or `WxJava` in WeChat and select the correct official account to follow. The official account will promptly notify the SDK of relevant update information, and share the technical knowledge of WeChat Java development from time to time;
1. Dingding technical exchange group: `30294972` (technical exchange group), `35724728` (notification group, real-time notification of Github project change records).
1. Please read [[The Wisdom of Questions]](https://github.com/ryanhanwu/How-To-Ask-Questions-The -Smart-Way/blob/master/README-zh_CN.md), and make sure you have checked [[Development Documentation Wiki]](https://github.com/wechat-group/WxJava/wiki) to avoid wasting everyone’s Precious time;
1. If you need to post code or a long list of abnormal information when seeking help, please use http://paste.ubuntu.com

--------------------------------
### other instructions
1. **Students who read the source code, please note that this SDK adds support for `lombok` when compiling the code to simplify the code. If you don’t understand `lombok`, please learn the relevant knowledge first, for example, you can read [this article](https: //mp.weixin.qq.com/s/cUc-bUcprycADfNepnSwZQ); **
1. If there is a need for a new function, a bug is found, or a code problem caused by the adjustment of the official WeChat interface, you can directly raise an issue on the [[Issues]](https://github.com/Wechat-Group/WxJava/issues) page , To facilitate discussion and tracking issues;
1. If you need to contribute code, please read [[Code Contribution Guide]](CONTRIBUTING.md) carefully before submitting PR, thank you for your understanding and cooperation;
1. At present, the minimum version of `JDK` required by the latest version of this `SDK` is `8`, students who use `7` can use `WxJava` `3.8.0` and previous versions, while still using `JDK`6 Users please refer to [[this project]](https://github.com/binarywang/weixin-java-tools-for-jdk6), while other earlier JDK versions need to be modified and implemented by themselves.
1. [The page of this project in Open Source China] (https://www.oschina.net/p/weixin-java-tools-new), welcome to leave a message and rate it 🙂
1. For SDK development documentation, please refer to [[Development Documentation Wiki]](https://github.com/wechat-group/WxJava/wiki). Some documents may not be updated in time. If you find out, you can report it in time or modify it yourself. .
1. **If this development kit is helpful to you, welcome to affirm our efforts, you can go directly to [[Project Homepage Hosted in Code Cloud]](http://gitee.com/binary/weixin- java-tools), find the "Donate" button at the end of the page to give a reward, the more the better 😄. Thank you very much for the rewards and donations! **
1. The Javadoc of each module can be viewed online: [weixin-java-miniapp](http://binary.ac.cn/weixin-java-miniapp-javadoc/), [weixin-java-pay](http:// binary.ac.cn/weixin-java-pay-javadoc/), [weixin-java-mp](http://binary.ac.cn/weixin-java-mp-javadoc/), [weixin-java-common ](http://binary.ac.cn/weixin-java-common-javadoc/), [weixin-java-cp](http://binary.ac.cn/weixin-java-cp-javadoc/), [weixin-java-open](http://binary.ac.cn/weixin-java-open-javadoc/)
1. This SDK project is updated synchronously on the following code hosting website:
* Code Cloud: https://gitee.com/binary/weixin-java-tools
* GitHub: https://github.com/wechat-group/WxJava

---------------------------------
### Maven citation method
Note: The latest version (including the beta version) is [![Maven Central](https://img.shields.io/maven-central/v/com.github.binarywang/wx-java.svg)](http:/ /mvnrepository.com/artifact/com.github.binarywang/wx-java), the following is the latest official version.

```xml
<dependency>
  <groupId>com.github.binarywang</groupId>
  <artifactId> (refer to the following for different modules)</artifactId>
  <version>4.1.0</version>
</dependency>
```

  -WeChat Mini Program: `weixin-java-miniapp`
  -WeChat Pay: `weixin-java-pay`
  -WeChat open platform: `weixin-jav