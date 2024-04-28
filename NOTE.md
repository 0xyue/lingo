记录各个学习片段中使用到的命令和链接

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

# 5.Footer

## Flagpack
Flagpack: https://flagpack.xyz/


# 6.Main Layout

## 添加shadcn 的sheet
```
npx shadcn-ui@latest add sheet
```

# 7.Sidebar
sidebar 功能实现

# 8.Learn Page Wrappers
Learn Page Wrappers 布局

# 9.Drizzle & Neon
## Neon
https://console.neon.tech

## Drizzle
https://orm.drizzle.team/docs/get-started-postgresql

```
npm i drizzle-orm @neondatabase/serverless
npm i -D drizzle-kit
```

```
npm run db:push
npm run db:studio
```

```
npm i -D pg
```

### env
```
npm i dotenv
```

# 10.Courses Page
Courses Page布局

# 11.User Progress
```
npx shadcn-ui@latest add sonner
```

# 12.Seed Script
```
npm i -D tsx
```
tsx ./scripts/seed.ts

# 13.Schema
添加 units lessons challenges challengesOptions challengeProgress

# 14.Units
添加 units 数据，以及 getUnits 方法

# 15.Lesson Button
```
npm i react-circular-progressbar
```
# 16.Course Progress

# 17.Lesson Header
```
npx shadcn-ui@latest add progress
```

# 18.Exit Modal
```
npx shadcn-ui@latest add dialog
npm i zustand
```
# 19.Challenge Cards

## svg 资源网站
https://www.svgrepo.com/

# 20.Challenge Footer
语音文件生成
https://elevenlabs.io/

```
npm i react-use
```