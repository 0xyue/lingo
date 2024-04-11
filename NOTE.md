
# 1.project setup

## 创建项目

```
npx create-next-app@latest
```

## ui组件库
https://ui.shadcn.com

安装组件库
```
npx shadcn-ui@latest init
```

## 运行项目
```
npm run dev
```

## 更改字体为Nunito
在  [layout.tsx](app/layout.tsx) 改为 Nunito
```
import { Nunito } from "next/font/google";
```

## 安装Tailwind CSS IntelliSense 插件
vscode 扩展 Tailwind CSS IntelliSense, 悬停显示 css以及自动补全功能

## 导入 shadcn 的 button
```
npx shadcn-ui@latest add button
```
在 components/ui 下 button.tsx


# 2.Buttons Library
自定义 button 组件库 [button.tsx](components/ui/button.tsx)

# 3.Marketing Skeleton
在文件夹名称中加上括号，就不会反应到 url 中

# 4.Authentication
## 使用 [clerk](https://dashboard.clerk.com) 做认证

在 clerk创建好项目后，添加.env 文件，将密钥保存在文件中
并在.gitignore 中加入.env

在本地安装 clerk
```
npm install @clerk/nextjs
```

## 作者图标github链接
https://github.com/AntonioErdeljac/lingo-early-access/tree/master/public

## 免费游戏资产
Kenney Assets:https://kenney.nl/

## Flagpack
Flagpack: https://flagpack.xyz/