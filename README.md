![RobloxStudioBeta_YY5pypWTj6](https://github.com/user-attachments/assets/2295f92b-feea-4119-9820-48d61324bc9a)
# FluentPlus - Enhanced Roblox UI Library

A modified and enhanced version of [Fluent](https://github.com/dawid-scripts/Fluent) with additional features and improvements.

## ✨ Features Added

- **🎨 Extended Theme Collection** - Much more themes available
- **🔍 Element Search** - Search functionality across all modules and elements  
- **🖱️ Interface Toggle Button** - Fixed and improved for both PC and mobile
- **🎯 Icon Support** - Icons for sections, and tabs using Lucide icon system
- **🐛 Bug Fixes** - Various stability and performance improvements

## 📦 Installation

```lua
local Fluent = loadstring(Game:HttpGet("https://raw.githubusercontent.com/LongHip2012/FluentPlusPlus/refs/heads/main/main.lua"))()
```

## 🚀 Quick Start

```lua
-- Create window
local Window = Fluent:CreateWindow({
    Title = "My Script",
    SubTitle = "Enhanced UI",
    Size = UDim2.fromOffset(580, 460),
    Acrylic = true,
    Theme = "Dark"
})

-- Create tab with icon
local Tab = Window:AddTab({ Title = "Main", Icon = "settings" })

-- Create section with icon
local Section = Tab:AddSection("Configuration", "cog")
```

## 🎨 Available Themes

AMOLED, Amethyst, Arctic, Aqua, Balloon, Bloody, Cloud, Dark, Darker, Emerald, Forest, GitHub Dark, GitHub Dark Dimmed, GitHub Dark High Contrast, GitHub Light, GitHub Light Colorblind, GitHub Light Default, GitHub Light High Contrast, Grape, Light, Midnight, Monokai, Monokai Classic, Monokai Dimmed, Monokai Vibrant, Ocean, Quiet Light, Rose, Sapphire, SoftCream, Solarized Dark, Solarized Light, Sunset, Tomorrow Night Blue, Typewriter, United GNOME, United Ubuntu, Viow Arabian, Viow Arabian Mix, Viow Flat, Viow Light, Viow Mars, Viow Neon, VSC Dark High Contrast, VSC Dark Modern, VSC Dark+, VSC Light High Contrast, VSC Light Modern, VSC Light+, VSC Red, VS Dark, VS Light, Vynixu, Yaru, Yaru Dark

## 📄 License

Based on the original [Fluent](https://github.com/dawid-scripts/Fluent) library.
