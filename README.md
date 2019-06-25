# awesome-macaca [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](//github.com/sindresorhus/awesome)

---

A curated list of awesome things regarding [Macaca](//macacajs.github.io) ecosystem.

Click the <a href="https://github.com/macacajs/awesome-macaca/watchers"><img src="https://user-images.githubusercontent.com/1011681/53282856-ba237580-3778-11e9-8765-89e0c729568a.png" height="20"/></a> button on this repo (star us too!) to get notified of upcoming news.

<!-- GITCONTRIBUTOR_START -->

## Contributors

|[<img src="https://avatars1.githubusercontent.com/u/1011681?v=4" width="100px;"/><br/><sub><b>xudafeng</b></sub>](https://github.com/xudafeng)<br/>|[<img src="https://avatars3.githubusercontent.com/u/1209810?v=4" width="100px;"/><br/><sub><b>paradite</b></sub>](https://github.com/paradite)<br/>|[<img src="https://avatars2.githubusercontent.com/u/1380777?v=4" width="100px;"/><br/><sub><b>wusphinx</b></sub>](https://github.com/wusphinx)<br/>|
| :---: | :---: | :---: |


This project follows the git-contributor [spec](https://github.com/xudafeng/git-contributor), auto updated at `Tue Jun 25 2019 11:13:18 GMT+0800`.

<!-- GITCONTRIBUTOR_END -->

## Table of Contents

- [Resources](#resources)
- [Tutorials](#tutorials)
- [Examples](#examples)
- [Clients](#clients)
- [Tools](#tools)
  - [Inspector](#inspector)
  - [Recorder](#recorder)
  - [DataHub](#datahub)
  - [Reliable](#reliable)
  - [Coverage](#coverage)
  - [NoSmoke](#nosmoke)
  - [Monkey Testing](#monkey-testing)
  - [Computer Vision](#computer-vision)
  - [Page UITest](#page-uitest)
  - [Browser Testing](#browser-testing)
  - [Reporter](#reporter)
  - [Bot](#bot)
  - [Other Tools](#other-tools)
- [Drivers](#drivers)
- [Video](#video)
- [Articles](#articles)
  - [English](#english)
  - [Chinese](#chinese)
- [Presentations](#presentations)
  - [Slides](#slides)
- [Community](#community)
- [Contributing](#contributing)
- [Licence](#license)

## Resources

- [Macaca Official Site](//macacajs.com)
- [Macaca GitHub](//github.com/alibaba/macaca)
- [Macaca Community GitHub](//github.com/macacajs)
- [Macaca FAQ](//macacajs.com/faq)

## Tutorials

- [Quick Start](//macacajs.github.io/quick-start)
- [Environment Setup](//macacajs.github.io/environment-setup)
- [CLI Documentation](//macacajs.github.io/cli-usage)

## Examples

- [sample-nodejs](//github.com/macaca-sample/sample-nodejs) - Macaca test sample for Node.js
- [sample-java](//github.com/macaca-sample/sample-java) - Macaca test sample for Java
- [sample-python](//github.com/macaca-sample/sample-python) - Macaca test sample for Python
- [react-sample](//github.com/macaca-sample/react-sample) - Macaca test sample for browser React
- [vue-sample](//github.com/macaca-sample/vue-sample) - Macaca test sample for browser framework Vue.js
- [web-app-bootstrap](//github.com/app-bootstrap/web-app-bootstrap) - All in one sample for popular web framework
- [antd-sample](//github.com/macaca-sample/antd-sample) - Ant Design sample for DataHub
- [angular-datahub-sample](//github.com/macaca-sample/angular-datahub-sample) - Angular's ng toolchain sample for DataHub
- [android-datahub-sample](//github.com/app-bootstrap/android-app-bootstrap) - Android sample for DataHub
- [ios-datahub-sample](//github.com/app-bootstrap/ios-app-bootstrap) - iOS sample for DataHub
- [macaca-java-biz-framework](//github.com/macaca-sample/macaca-java-biz-framework) - A framework for uiautomation business development based on wd.java
- [macaca-java-biz-sample](//github.com/macaca-sample/macaca-java-biz-sample) - Sample for Macaca business development based on wd.java
- [macaca-reporter-standalone-sample](//github.com/macaca-sample/macaca-reporter-standalone-sample) - Sample for Macaca reporter
- [android-docker-ci-sample](//github.com/macaca-sample/android-docker-ci-sample) - Sample for Macaca docker ci
- [cv-sample-python](//github.com/macaca-sample/cv-sample-python) - Sample for Macaca CV Python
- [macaca_ci_android_ios](//github.com/macaca-sample/macaca_ci_android_ios) - Macaca iOS 和 Android 并行测试
- [po-sample-python](//github.com/macaca-sample/po-sample-python) - 基于 PageObject 跨平台的设计模式

## Clients

- [macaca-wd](//github.com/macacajs/macaca-wd) - Node.js WebDriver Client for Macaca
- [wd.java](//github.com/macacajs/wd.java) - Java client binding for Macaca
- [wd.py](//github.com/macacajs/wd.py) - Python client binding for Macaca

## Tools

### Inspector

- [App-inspector](//github.com/macacajs/app-inspector) - App-inspector is a mobile UI viewer in browser

### Recorder

- [UI Recorder](//github.com/alibaba/uirecorder) - UI Recorder is a UI test case recorder like Selenium IDE

### DataHub

- [DataHub](//github.com/macacajs/macaca-datahub) - Continuous data provider for development, testing, staging and production.
- [datahub-proxy-middleware](//github.com/macacajs/datahub-proxy-middleware) - DataHub proxy middleware for Express.js
- [datahub-nodejs-sdk](//github.com/macacajs/datahub-nodejs-sdk) - DataHub Node.js SDK
- [datahub-java-sdk](//github.com/macacajs/datahub-java-sdk) - DataHub SDK for Android and Java applications
- [datahub-ios-sdk](//github.com/macacajs/datahub-ios-sdk) - DataHub SDK for iOS
- [egg-datahub](//github.com/macacajs/egg-datahub) - [Egg.js](//github.com/eggjs/egg) plugin for Macaca DataHub
- [umi-plugin-datahub](//github.com/umijs/umi/tree/master/packages/umi-plugin-datahub) - [UmiJS](//github.com/umijs/umi/) plugin for Macaca DataHub

### Reliable

- [Reliable](//github.com/macacajs/reliable) - Release management suite with continuous delivery support for deployments

### Coverage

- [web-coverage-sample](//github.com/macaca-sample/coverage-sample) - Coverage sample for Web
- [android-coverage-sample](//github.com/app-bootstrap/android-app-bootstrap) Coverage sample for Android
- [ios-coverage-sample](//github.com/app-bootstrap/ios-app-bootstrap) Coverage sample for iOS

### NoSmoke

- [NoSmoke](//github.com/macacajs/nosmoke) - A cross platform UI crawler which scans view trees then generate and execute UI test cases.

### Monkey Testing

- [zhangzhao4444/Fastmonkey](//github.com/zhangzhao4444/Fastmonkey) - 非插桩 iOS Monkey, 支持控件，每秒4-5 action事件
- [baozhida/iosMonkey](//github.com/baozhida/iosMonkey) - 基于 Macaca 和 webdriveragent 模拟 monkey 的执行
- [mengdegong/iosMonkey](//github.com/mengdegong/iosMonkey) - iOS Monkey
- [zalando/SwiftMonkey](//github.com/zalando/SwiftMonkey) - A framework for doing randomised UI testing of iOS apps

### Computer Vision

- [nodecv](//github.com/macacajs/nodecv) - Node.js binding to OpenCV
- [nodecv-server](//github.com/macacajs/nodecv-server) - NodeCV server side

### Page UITest

- [Torchjs](//github.com/macacajs/torchjs) - Test framework to light up the world
- [uitest](//github.com/macacajs/uitest) - UI Test framework for Node.js based on Macaca

### Browser Testing

- [f2etest](//github.com/alibaba/f2etest) - F2etest是一个多浏览器兼容性测试整体解决方案

### Reporter

- [macaca-reporter](//github.com/macacajs/macaca-reporter) - Macaca reporter is a reporter used for mocha and other frameworks

### Bot

- [macaca-bot](//github.com/macacajs/macaca-bot) - :octocat: bot to resolve the issues and PR of Macaca

### Other Tools

- [macaca-adb](//github.com/macacajs/macaca-adb) - Node.js wrapper for ADB
- [XCTestWD](//github.com/macacajs/xctestwd) - A Swift implementation of WebDriver server for iOS that runs on Simulator/iOS devices
- [ios-simulator](//github.com/macacajs/ios-simulator) - Node.js wrapper for iOS simulator
- [UIAutomatorWD](//github.com/macacajs/uiautomatorwd) - Node.js wrapper for Android UIAutomator
- [iosHookViewId](//github.com/macacajs/ioshookviewid) - A solution for ios hook view id
- [android-unicode](//github.com/macacajs/android-unicode) - Android unicode UTF-7 input apk
- [command-line-test](//github.com/macacajs/command-line-test) - command-line test tool for Node.js
- [android-performance](//github.com/macacajs/android-performance) - Node.js wrapper to android performance with adb

## Drivers

- [macaca-android](//github.com/macacajs/macaca-android) - Macaca Android driver
- [macaca-ios](//github.com/macacajs/macaca-ios) - Macaca iOS driver
- [macaca-chrome](//github.com/macacajs/macaca-chrome) - Macaca Chrome driver
- [macaca-electron](//github.com/macacajs/macaca-electron) - Macaca Electron driver
- [macaca-puppeteer](//github.com/macacajs/macaca-puppeteer) - Macaca Puppeteer driver

## Video

- [Macaca Test Framework - Youtube Channels](https://www.youtube.com/playlist?list=PLpmrn9zBXhkiyfWhaZZV1ZaRj-LFtu6bj)

## Articles

### English

- [Can you find XPath for mobile apps?](https://www.linkedin.com/pulse/can-you-find-xpath-mobile-apps-now-we-dharmalingam-k-csm/)
- [Extract Xpath from App using Macaca Inspector](http://toolsqa.com/mobile-automation/appium/extract-xpath-from-app-using-macaca-inspector/)
- [Macaca inspector for Apple Mac - Automation Testing World!!](https://gopekannan.wordpress.com/2017/02/03/macaca-inspector-for-apple-mac/)
- [Mobile and Web UI Testing with Macaca and OpenCV](https://medium.com/@liangjunjiang/mobile-and-web-ui-testing-with-macaca-and-opencv-part-i-f7f4a5ae0b1c)

### Chinese

- [UI 自动化框架调研总结](https://testerhome.com/topics/6602)
- [基于 Node.js 的自动化持续集成](https://cnodejs.org/topic/56e8d829cf7763a6045c4af8)
- [获取 Android 应用的性能](https://testerhome.com/topics/5312)
- [小马 Macaca 入门指引合集](https://testerhome.com/wiki/macaca)
- [Macaca-Java 版入门指南](https://testerhome.com/topics/6431)
- [Mac OSX 布署 Reliable](https://testerhome.com/topics/4746)
- [Macaca 基础原理浅析](https://testerhome.com/topics/6608)
- [应用自动添加控件 ID 探索](https://testerhome.com/topics/6642)
- [Strikingly 团队2017技术展望](https://zhuanlan.zhihu.com/p/25229260)
- [Macaca 测试用例单步调试](https://testerhome.com/topics/4563)
- [混合 H5 应用 UI 自动化入门](https://testerhome.com/topics/9651)
- [Android 输入中文的实现](https://testerhome.com/topics/5327)
- [MacOS 安装 Inspector 超详细教程](https://www.jianshu.com/p/28d87ef66477)

## Presentations

### Slides

- [Automation Facing The Future](//xudafeng.github.io/slide/archives/ningjs)

## Community

- [Testerhome](https://testerhome.com/topics/node68)
- [Cnodejs](https://www.google.com.hk/search?hl=zh-CN&q=site:cnodejs.org+macaca&cad=h)
- [StackOverflow](https://stackoverflow.com/search?q=macaca)

## Contributing

Your contributions and suggestions are always welcome! :smiley:

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0/)
