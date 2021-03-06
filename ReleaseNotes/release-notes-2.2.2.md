# PLPlayerKit Release Notes for 2.2.2

## 内容

- [简介](#简介)
- [问题反馈](#问题反馈)
- [记录](#记录)

## 简介

PLPlayerKit 为 iOS 开发者提供直播播放 SDK。

## 问题反馈

当你遇到任何问题时，可以通过在 GitHub 的 repo 提交 ```issues``` 来反馈问题，请尽可能的描述清楚遇到的问题，如果有错误信息也一同附带，并且在 ```Labels``` 中指明类型为 bug 或者其他。

[通过这里查看已有的 issues 和提交 Bug](https://github.com/pili-engineering/PLPlayerKit/issues)

## 记录

### Player

- 功能
  - 新增 AAC HEV2 音频支持
  - 新增 SDK 自动重连功能，默认不开启
- 缺陷
  - 修复长时间播放偶发解码 crash
  - 修复 pause/resmue 快速调用导致 crash
  - 修复重连未更换服务器 IP
  - 修复 rtmp 硬解播放视频抖动
  - 修复 flv 开始播放偶发黑屏
  - 修复 flv 超时机制失效
