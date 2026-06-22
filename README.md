# https://mc.kurogames.com - 静态原型（HTML + Tailwind）

此仓库为云·鸣潮（mc.kurogames.com）整站静态原型的初始提交。内容基于用户授权直接抓取的素材与页面结构，采用桌面优先的响应式实现。

包含的页面：
- index.html
- cloud.html
- download.html
- login.html
- register.html
- notice.html
- shop.html
- server-list.html

快速预览：
1. 将仓库克隆到本地
2. 使用任意静态服务器预览（例如：
   - Python: `python -m http.server 8000`
   - npx serve: `npx serve .`
)

后续工作计划（开发流程）：
- 逐页复刻原站视觉与交互（替换占位图、同步实际文案与活动专题）
- 增加细粒度样式与组件（按钮样式、卡片、表单、对话框、轮播）
- 集成构建工具（Tailwind CLI / Vite）并加入自动部署脚本（GitHub Actions / gh-pages）

如果你确认结构与技术栈，我会在后续提交中逐步替换页面内容、补充资源并完成整站交付（预计 7–12 个工作日完成全部页面）。
