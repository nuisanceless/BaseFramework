## 项目构建记录

- 主项目目录下面config.gradle文件用以统一配置第三方依赖库的版本信息；
以及项目版本号、最小支持系统版本号等全局信息。

   - config.gradle配置文件需要在项目级build.gradle文件中注册
   `apply from: "config.gradle"`
   
   
## 项目拾遗
- Espresso UI 自动化测试框架。