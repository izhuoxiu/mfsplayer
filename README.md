# MFSPlayer - 多模态反馈播放器 SDK

基于 [MFS v0.2.3 白皮书](https://github.com/izhuoxiu/mfs) 实现的跨平台（H5/Android/iOS）多模态反馈引擎。

## 特性
- 一套 C++ 内核，编译为 WebAssembly，各平台共用
- 支持震动、屏幕彩带、闪光灯三种模态自由组合
- 严格遵循五维优先级（情绪 > 运动 > 力量 > 空间 > 节奏）
- 零人工标注，全自动时序调度

## 快速开始
各平台接入文档请查看对应子目录：
- [H5 接入](./h5/README.md)
- [Android 接入](./android/README.md)  
- [iOS 接入](./ios/README.md)

## 维护指南
仅需修改 `core/mfs_core.cpp`，提交后 GitHub Actions 自动编译并打包所有平台 SDK。

## License
MIT
