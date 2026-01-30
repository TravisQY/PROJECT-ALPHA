极简化代码：
没有复杂的框架（如 React/Vue）和构建流程（Webpack/Vite）。
所有的样式逻辑都写在 HTML 标签中（借助 Tailwind），CSS 和 JS 非常精简。

全 CDN 依赖：
Tailwind CSS：处理所有排版、间距和响应式。
Lucide Icons：提供清晰、轻量的科技感图标。
Google Fonts：加载现代字体，这是提升“高级感”的关键。

科技感视觉元素：
暗色背景 (Dark Mode)：采用 #030303 而非全黑，更显深邃。
背景网格 (Tech Grid)：使用简单的渐变背景模拟实验室/数据感。
毛玻璃效果 (Glassmorphism)：输入框使用半透明背景 + backdrop-filter。
呼吸灯效果 (Glow Effect)：主标题带有淡淡的蓝色光晕，增加视觉焦点。

响应式支持：
使用了 Tailwind 的 md: 前缀，自动适配手机和电脑屏幕。

粒子动态效果 (tsParticles)：
引入了轻量级粒子 CDN，配置了弱蓝色的点线连接效果。
具备鼠标交互感：当鼠标滑过时，线条会产生微弱的吸附（Grab）效果，增加互动性。

科技感倒计时：
字体选择：引入了 Google Fonts 的 Orbitron 字体，这是一种专门用于科幻/科技设计的等宽字体，数字变化时不会晃动。
视觉增强：数字带有 text-shadow 产生的蓝色霓虹发光感。
逻辑：使用 Vanilla JS 计算剩余时间，并使用 padStart(2, '0') 确保数字始终保持两位数（如 09 而非 9），维持排版整齐。
