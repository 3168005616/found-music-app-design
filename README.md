# found-music-app-design
找音乐app设计
# Music APP Design

## 项目简介
一款集音乐播放、推荐算法与社交功能于一体的移动应用。

## 功能列表
- 在线播放与下载
- 基于协同过滤的热点推荐
- 用户动态分享与评论

## 技术栈
- 前端：Flutter
- 后端：Spring Boot
- 数据库：MySQL + Redis

## 部署指南
一、 克隆仓库：git clone https://github.com/3168005616/found-music-app-design.git
二、 配置环境：
1.前端开发环境
 -Flutter SDK：安装最新版本，配置环境变量。
 -IDE：Android Studio
 -模拟器：Android Emulator（通过Android Studio安装）
2.后端开发环境
 -Spring Boot框架
 -JDK：安装JDK 21
 -IDE：IntelliJ IDEA
 -构建工具：Maven
 -数据库与缓存
   MySQL：安装MySQL Community Server，配置用户名/密码。
   Redis：安装Redis服务器，启动服务。
   管理工具：MySQL Workbench、Redis Desktop Manager。
 -API测试工具
   Postman：用于测试RESTful API接口。
3.算法开发环境
 -Python环境
   python解释器：使用Anaconda管理环境
   依赖库：pip install numpy pandas scikit-learn
   IDE：PyCharm
 -数据集与工具
   MovieLens数据集：用于测试协同过滤算法。
   Elasticsearch（可选）：安装并配置用于优化检索模块。
4.音频播放与性能优化
 -Android原生播放器
 -ExoPlayer：通过Gradle依赖集成到Android项目：
   gradle：implementation 'com.google.android.exoplayer:exoplayer:2.18.1'
 -Flutter音频插件
   audioplayers：在pubspec.yaml中添加依赖：
   dependencies:
    audioplayers: ^4.1.0
5.版本控制与协作工具
 -Git
  安装Git，配置全局用户名与邮箱：
 代码托管：注册GitHub/GitLab账号，创建项目仓库。
 -Docker（可选）
   安装Docker Desktop，用于容器化部署后端服务。
6.测试与部署工具
 -性能测试
  JMeter：安装并配置，用于模拟高并发场景测试。
 -安全测试
   OWASP ZAP：用于扫描API安全漏洞。
