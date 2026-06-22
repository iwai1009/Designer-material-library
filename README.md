# 设计师素材管理系统

一个简洁清新的设计师素材管理系统，帮助设计师高效管理和分类设计素材。

## 技术栈

### 前端
- Vue 3 + Vite
- Vue Router 4
- Pinia
- Vant UI 组件库
- Axios

### 后端
- FastAPI
- JWT 认证

## 项目结构

```
lingsu/
├── src/
│   ├── api/           # API 接口封装
│   │   ├── auth.js    # 认证接口
│   │   ├── group.js   # 分组接口
│   │   ├── material.js # 素材接口
│   │   └── request.js  # axios 封装
│   ├── router/        # 路由配置
│   │   └── index.js
│   ├── styles/        # 样式文件
│   │   └── variables.css # CSS 变量
│   ├── utils/         # 工具函数
│   │   └── storage.js  # 本地存储
│   ├── views/         # 页面组件
│   │   ├── Login.vue
│   │   ├── Register.vue
│   │   ├── Home.vue
│   │   ├── Upload.vue
│   │   ├── GroupDetail.vue
│   │   ├── Search.vue
│   │   └── Profile.vue
│   ├── App.vue
│   └── main.js
├── backend/           # 后端项目
│   ├── main.py       # FastAPI 主文件
│   └── requirements.txt
├── index.html
├── vite.config.js
└── package.json
```

## 运行方式

### 前端
```bash
# 安装依赖
npm install

# 开发模式
npm run dev

# 构建生产版本
npm run build
```

### 后端
```bash
cd backend

# 安装依赖
pip install -r requirements.txt

# 启动服务
python main.py
```

后端服务默认运行在 `http://localhost:8000`

## 功能特性

- 用户注册/登录（JWT 认证）
- 素材分组管理
- AI 智能分类建议
- 图片上传和预览
- 素材搜索和筛选
- 瀑布流展示

## 设计风格

- 清新绿色主色调
- 圆角卡片设计
- 微阴影效果
- 移动端响应式布局