> Daily learning log.  
> Focus on programming, languages, and long-term consistency.
## 2026-01-08

- 学习 Flutter 项目结构（android / ios / lib / assets）
- 配置 pubspec.yaml 中的 assets
- 解决 Image.asset 无法显示本地图片的问题
- 使用 VS Code + Flutter 进行调试
- docs: add trilingual daily learning log (2026-01-10)
## 2026-01-14

- 学习 Java 基础语法（变量、数据类型、if / for）
- 理解 JVM、JRE、JDK 的区别
- 编写第一个 Java 程序（HelloWorld）
- 使用命令行编译和运行 javac / java
- 记录常见编译错误及解决方法
## 2026-01-16｜Xcode & iOS 开发学习记录

✅ 今日学习内容（Xcode）

1. Xcode 真机运行与系统版本问题排查
	•	遇到 Xcode 提示需要下载高版本 iOS（如 iOS 26），但真机系统为 iOS 18.6.2
	•	学会排查以下关键点：
	•	Deployment Target（最低支持系统版本）
	•	当前 Scheme 选择的运行设备
	•	Xcode 是否识别到真实 iPhone 而非模拟器
	•	是否误选了未来系统 SDK 的 Device Support
	•	理解：
Xcode 的报错往往不是“系统真的不支持”，而是构建目标或运行目标不一致

⸻

2. Xcode 中的核心概念理解
	•	Deployment Target：App 最低支持的 iOS 版本
	•	SDK vs iOS 系统版本：
	•	SDK 是“开发用工具包”
	•	真机系统版本只要 ≥ Deployment Target 即可运行
	•	Clean Build Folder 的作用：
	•	清除旧缓存
	•	解决“改了设置但依然报错”的常见问题

⸻

3. iOS 真机调试的基本流程（巩固）
	•	使用 USB 连接 iPhone
	•	在 Xcode 中选择真实设备（非 Simulator）
	•	确认 Apple ID & Developer Team 已正确设置
	•	学会通过：
	•	重启 Xcode
	•	重新插拔手机
	•	Clean Build
进行基础排错

⸻

🧠 今日收获
	•	iOS / Xcode 报错90% 是配置问题，不是代码问题
	•	学会“看错误 → 反推设置”的思路，而不是盲目重装
	•	对 iOS 开发环境的整体结构更清晰了

⸻

📌 明日计划（预定）
	•	学习 Swift 基础语法（变量 / 常量 / struct）
	•	尝试写一个最简单的 iOS 界面（UILabel + Button）
	•	继续巩固 Xcode 常见报错的判断逻辑

⸻

⏱ 学习时长
	•	约 1–1.5 小时
## 2026-01-16
	•	Continued daily coding practice
	•	Reviewed previous notes and improved understanding
	•	Committed today’s learning progress
