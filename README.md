# CloudTix Landing Page

CloudTix 云票据 - 您的智能票据管理助手

一个基于 Vue 3 + Vite + TailwindCSS 的单页应用，包含以下页面：
- 主页（Landing Page）- 云票据应用介绍
- 联系我们 - 反馈与支持
- 用户协议 - 适用于票据收集应用
- 隐私政策 - 票据数据隐私保护说明

## 技术栈

- **Vue 3** - 渐进式 JavaScript 框架
- **Vite** - 下一代前端构建工具
- **Vue Router** - Vue.js 官方路由管理器
- **TailwindCSS** - 实用优先的 CSS 框架

## 本地开发

### 安装依赖

```bash
npm install
```

### 启动开发服务器

```bash
npm run dev
```

开发服务器将在 `http://localhost:5173` 启动

### 构建生产版本

```bash
npm run build
```

构建产物将生成在 `dist` 目录

### 预览生产构建

```bash
npm run preview
```

## 部署到 Cloudflare Pages

### 方法一：通过 Git 集成（推荐）

1. **初始化 Git 仓库并推送到 GitHub**

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin <你的GitHub仓库URL>
git push -u origin main
```

2. **在 Cloudflare Pages 创建项目**
   - 登录 [Cloudflare Dashboard](https://dash.cloudflare.com/)
   - 进入 **Workers & Pages** > **Pages**
   - 点击 **Create a project** > **Connect to Git**
   - 选择你的 GitHub 仓库
   - 配置构建设置：
     - **构建命令**: `npm run build`
     - **构建输出目录**: `dist`
     - **Node.js 版本**: 18 或更高
   - 点击 **Save and Deploy**

3. **自动部署**
   - 每次推送到主分支时，Cloudflare Pages 会自动构建和部署
   - 预览部署会为每个 Pull Request 自动创建

### 方法二：使用 Wrangler CLI

1. **安装 Wrangler**

```bash
npm install -g wrangler
```

2. **登录 Cloudflare**

```bash
wrangler login
```

3. **构建项目**

```bash
npm run build
```

4. **部署**

```bash
wrangler pages deploy dist --project-name=cloudtix-landing
```

## 项目结构

```
singlepage/
├── public/              # 静态资源
│   └── _redirects      # Cloudflare Pages 路由配置
├── src/
│   ├── assets/         # 资源文件
│   ├── router/         # 路由配置
│   │   └── index.js
│   ├── views/          # 页面组件
│   │   ├── Home.vue    # 主页
│   │   ├── Contact.vue # 联系我们
│   │   ├── Terms.vue   # 用户协议
│   │   └── Privacy.vue # 隐私政策
│   ├── App.vue         # 根组件
│   ├── main.js         # 入口文件
│   └── style.css       # 全局样式
├── index.html          # HTML 模板
├── package.json        # 项目依赖
├── vite.config.js      # Vite 配置
├── tailwind.config.js  # TailwindCSS 配置
└── postcss.config.js   # PostCSS 配置
```

## 路由

- `/` - 主页（Landing Page）
- `/contact` - 联系我们
- `/terms` - 用户服务协议
- `/privacy` - 隐私政策

## 自定义域名

在 Cloudflare Pages 部署完成后，你可以：

1. 进入项目设置
2. 点击 **Custom domains**
3. 添加你的自定义域名
4. 按照指引配置 DNS 记录

## 环境变量

如果需要配置环境变量，可以在 Cloudflare Pages 项目设置中添加：

1. 进入项目设置
2. 点击 **Environment variables**
3. 添加所需的环境变量

## 许可证

MIT
