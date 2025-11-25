# Liquid Glass

**Liquid Glass** 是一款为 Home Assistant 设计的深度定制主题，专注于极致的**通透感**与**有机光影**交互。
![Liquid Glass Theme Preview](preview.jpg)

## ✨ 核心特性

- **💎 极致玻璃拟态 (Glassmorphism)**
    
    - 全局透明化处理，卡片如同悬浮在壁纸之上的水晶切片。
        
    - 精细的磨砂玻璃效果（Backdrop Blur），层次分明。
        
- **🌊 有机光感动画 (Organic Light)**
    
    - 弹出卡片背景不再是单调的颜色，而是拥有像水流一样的动态光斑。
        
    - 使用 `radial-gradient` 配合 `mix-blend-mode: soft-light` 模拟真实光线的混沌漫射。

        
- **🎬 iOS 风格交互**
    
    - 平滑的 `card-enter` 入场动画。
        
    - 弹窗采用 iOS 风格的缩放与回弹动画。
        
- **🌙 深色模式优化**
    
    - 专为 OLED 屏幕和夜间使用设计的霓虹配色（#29b6f6 / #ff4081）。
        

## 🛠️ 前置要求

本主题深度依赖 [**card-mod**](https://github.com/thomasloven/lovelace-card-mod "null") 来实现 Shadow DOM 注入和高级 CSS 动画。

1. 在 HACS 中搜索并安装 `card-mod`。
    
2. 或者手动安装，确保在 `configuration.yaml` 的 `frontend` 部分正确加载了资源。
    

## 📥 安装指南

### 方法一：直接复制（推荐）

1. 确保你的 Home Assistant 配置目录下有 `themes` 文件夹。
    
2. 将`liquid_glass.yaml`复制到 `themes` 文件夹中 。
    
3. 在 `configuration.yaml` 中添加以下内容（如果已有则跳过）：
    
    ```
    frontend:
      themes: !include_dir_merge_named themes
    ```
    
4. 重启 Home Assistant。
    

### 方法二：HACS (如果你打算发布到 HACS)

_(如果你将来将其发布到 HACS 自定义源，用户可以直接点击安装)_

## ⚙️ 启用主题

1. 点击 Home Assistant 左下角的 **用户资料 (Profile)** 图标。
    
2. 在 **主题 (Theme)** 下拉菜单中选择 **"liquid_glass"**。
    
3. **重要**：选择 **深色模式 (Dark Mode)** 以获得最佳体验。
    

## 📄 许可证

本项目采用 [MIT License](https://www.google.com/search?q=LICENSE "null") 开源。

_Enjoy the chaos of light._ ✨

POWERED BY DDG
