# 手势贪吃蛇 (Gesture Snake Game)

一个使用 HTML5 + JavaScript + MediaPipe 实现的手势控制贪吃蛇游戏，可以通过浏览器直接运行。

## 功能特点

- 🎮 **手势控制**：使用 MediaPipe Hands 检测食指位置，控制蛇头移动
- 📱 **跨平台兼容**：支持 PC 和移动端摄像头
- 🎨 **流畅视觉效果**：蛇身具有平滑的拖尾效果
- 🍎 **经典游戏机制**：吃到苹果加分，蛇身变长
- 📊 **实时计分**：左上角显示当前分数
- 🔄 **镜像处理**：适配摄像头镜像显示

## 技术栈

- **HTML5**：页面结构和 Canvas 绘图
- **JavaScript**：游戏逻辑和交互
- **MediaPipe Hands**：手势检测和跟踪

## 快速开始

### 方法一：直接打开

1. 下载 `gesture_snake.html` 文件
2. 用现代浏览器（推荐 Chrome、Firefox、Safari）打开该文件
3. 允许浏览器访问摄像头
4. 使用食指控制蛇头移动，开始游戏

### 方法二：本地服务器

```bash
# 使用 Python 启动本地服务器
python -m http.server 8000

# 或使用 Node.js
npx serve
```

然后在浏览器中访问 `http://localhost:8000/gesture_snake.html`

## 游戏规则

1. 蛇头会跟随您的食指移动
2. 吃到红色苹果后，分数增加，蛇身变长
3. 苹果会随机生成在屏幕上
4. 游戏没有结束条件，可以一直玩下去

## 项目结构

```
gesture_snake/
├── gesture_snake.html  # 主游戏文件
└── README.md          # 项目说明文档
```

## 浏览器兼容性

- ✅ Chrome 88+
- ✅ Firefox 85+
- ✅ Safari 14+
- ✅ Edge 88+

## 注意事项

1. 确保您的设备有摄像头
2. 浏览器需要支持 WebRTC 和 Canvas API
3. 首次运行需要允许摄像头访问权限
4. 在光线充足的环境下游戏体验更佳

## 许可证

MIT License

## 贡献

欢迎提交 Issue 和 Pull Request！
