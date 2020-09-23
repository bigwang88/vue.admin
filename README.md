# vue.admin

手摸手项目

## 准备

```bash
# 安装Node.js
https://nodejs.org

# 安装Vue CLI
npm install -g @vue/cli --registry=https://registry.npm.taobao.org

# 查看版本
vue --version
```

## 启动

```bash
# 克隆项目
git clone https://github.com/bigwang88/vue.admin.git

# 进入项目目录
cd vue.admin

# 安装依赖
npm install --registry=https://registry.npm.taobao.org

# 如果安装错误则执行下面命令单独安装node-sass模块
npm install -g cnpm --registry=https://registry.npm.taobao.org
cnpm install node-sass

# 启动服务
npm run dev
```

浏览器访问 [http://localhost:9528](http://localhost:9528)

## 发布

```bash
# 构建测试环境
npm run build:stage

# 构建生产环境
npm run build:prod
```

## 其它

```bash
# 预览发布环境效果
npm run preview

# 预览发布环境效果 + 静态资源分析
npm run preview -- --report

# 代码格式检查
npm run lint

# 代码格式检查并自动修复
npm run lint -- --fix
```

更多信息请参考 [使用文档](https://panjiachen.github.io/vue-element-admin-site/zh/)
