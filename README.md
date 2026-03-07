# [Sanba's](https://github.com/sanba0519) Kernel  [![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/oppok7x) [![Build(rsuntk KSU legacy + Hooks) Oppo K7x MT6853](https://github.com/Eridian1628/kernel_mtk6853_RKSU/actions/workflows/buildOppoK7x.yml/badge.svg?event=success)](https://github.com/Eridian1628/kernel_mtk6853_RKSU/actions/workflows/buildOppoK7x.yml)

***
# 请移步至[此项目](https://github.com/sanba0519/android_kernel_4.14_MT6853)
OPPO/Realme通用内核

*适用:*

系统版本:安卓12

内核版本:4.14.186

处理器:天玑720/天玑800u 代号mtk6853

## 如何构建？
- fork本项目
- 点击Action 运行工作流程
- 等待构建完成 打开编译好的AK3 打开anykernel.sh 搜索BLOCK=字段 找到那一行并改成`BLOCK=/dev/block/by-name/boot;`
- enjoy it!

### 更改了什么？
 - 内置了RKSU
 - 没了(:

---

我的另一个仓库：https://github.com/sanba0519/android_kernel_4.14_MT6853 （也给这个仓库一个star吧 求求了）
