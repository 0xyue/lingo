
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

