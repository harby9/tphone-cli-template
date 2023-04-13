# tphone-cli-template#dev-branch

## 正常项目使用
```
pnpm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

## 调试开发期（pnpm link @tphone/core）

### 删除package.json中的@tphone/core依赖（防止走npm仓库下载）

### 删除node_modules和lock.json
```
pnpm run clean
```

### 安装依赖
```
pnpm install
```

### 建立pnpm link
```
pnpm link @tphone/core -g
```

### 启动服务
```
npm run serve-link
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
