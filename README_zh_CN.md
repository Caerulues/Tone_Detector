# Tone Detector

基于 SwiftUI 与 AudioKit 的现代实时音调检测器与调音器。

## 功能

- 实时音高检测
- 科学音高标记
- 平滑动态调音指针
- 动态音名滚动 UI
- 基于 AudioKit 的 DSP
- 低延迟麦克风输入
- SwiftUI 界面
- 支持 iOS
- 支持 macOS

## 截图

<img width="301.5" height="594.5" alt="image" src="https://github.com/user-attachments/assets/d68ce454-e575-4672-acd6-67c7ca1c5886" />

## 技术栈

- SwiftUI
- AudioKit
- AVAudioEngine
- SoundpipeAudioKit

## 架构

```text
麦克风
↓
AVAudioEngine
↓
AudioKit PitchTap
↓
音高分析
↓
音名映射
↓
SwiftUI 渲染
````

### 环境要求

* iOS 18+
