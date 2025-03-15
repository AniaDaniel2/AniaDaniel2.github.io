# 2025苏州中考倒计时

🌈 一个动态渐变背景的苏州中考倒计时网页，实时显示访问者IP信息

## 功能特性

- 🌈 彩虹渐变动画背景
- 🕶️ 毛玻璃效果容器设计
- 📱 响应式移动端适配
- ⏳ 实时动态倒计时显示
- 🌍 IP定位信息展示
- 🔗 开源信息页脚链接

## 关键技术

技术栈
​前端框架: 原生HTML/CSS/JavaScript
​特效实现:
CSS渐变动画
毛玻璃效果（backdrop-filter）
​IP定位: ipapi.co API
​字体渲染: 系统默认无衬线字体
关键功能实现
倒计时计算
javascript
const examDate = new Date('2025-06-17T00:00:00').getTime();
setInterval(() => {
  // 计算天、时、分、秒...
}, 1000);
玻璃效果CSS
css
.glass-container {
  background: rgba(0, 0, 0, 0.25);
  backdrop-filter: blur(12px);
  border: 1px solid rgba(255, 255, 255, 0.15);
}
贡献指南
欢迎通过Issue或Pull Request参与改进：

Fork本仓库
创建特性分支 (git checkout -b feature/新功能)
提交更改 (git commit -am '添加新功能')
推送分支 (git push origin feature/新功能)
创建Pull Request
许可证
本项目基于 MIT License 授权

特别感谢
IP定位服务由 ipapi.co 提供
技术支持 DeepSeek
© 2024-2025 AniaDaniel2 | 保持热爱，奔赴星海 🚀


---
