# 配色映射表

根据主题联想自动匹配配色方案。

## 主题关键词 → 配色方案

| 关键词 | 配色方案 | 配色预览 |
|--------|---------|---------|
| 蜂蜜 | 🍯 蜂蜜金棕 | `bg: #2C1810`, `accent: #D4A574`, `text: #FFFFFF` |
| 洋葱 | 🧅 紫色 | `bg: #4A1942`, `accent: #9B59B6`, `text: #FFFFFF` |
| 大象 | 🐘 灰色 | `bg: #2C3E50`, `accent: #95A5A6`, `text: #FFFFFF` |
| 猫 | 🐱 暖橘棕 | `bg: #8B4513`, `accent: #F4A460`, `text: #FFFFFF` |
| 天空/蓝色 | 🌌 深蓝星空 | `bg: #1A237E`, `accent: #3949AB`, `text: #FFFFFF` |
| 牙齿/古罗马 | 🦷 骨白 | `bg: #3E2723`, `accent: #D7CCC8`, `text: #FFFFFF` |
| 眼泪/打哈欠 | 😢 浅蓝 | `bg: #1565C0`, `accent: #64B5F6`, `text: #FFFFFF` |
| 打哈欠 | 😪 珊瑚粉 | `bg: #5D4037`, `accent: #FFAB91`, `text: #FFFFFF` |
| 跳跃/运动 | 🔥 活力橙红 | `bg: #BF360C`, `accent: #FF7043`, `text: #FFFFFF` |

## 默认配色（无匹配时随机）

```json
{
  "bg": "#2C3E50",
  "accent": "#3498DB",
  "text": "#FFFFFF"
}
```

## 添加新配色的方式

找到 `scripts/generate.py` 中的 `COLOR_MAP` 字典，按格式添加：

```python
"关键词": {
    "bg": "背景色",
    "accent": "强调色",
    "text": "文字色"
}
```

## 配色示例预览

### 蜂蜜金棕
![蜂蜜金](https://img.shields.io/badge/-bg:%232C1810-2C1810?style=flat-square)
![蜂蜜金](https://img.shields.io/badge/-accent:%23D4A574-D4A574?style=flat-square)

### 森林绿
![森林绿](https://img.shields.io/badge/-bg:%231B5E20-1B5E20?style=flat-square)
![森林绿](https://img.shields.io/badge/-accent:%2381C784-81C784?style=flat-square)

### 深蓝星空
![深蓝](https://img.shields.io/badge/-bg:%231A237E-1A237E?style=flat-square)
![深蓝](https://img.shields.io/badge/-accent:%233949AB-3949AB?style=flat-square)

### 紫色
![紫色](https://img.shields.io/badge/-bg:%234A1942-4A1942?style=flat-square)
![紫色](https://img.shields.io/badge/-accent:%239B59B6-9B59B6?style=flat-square)
