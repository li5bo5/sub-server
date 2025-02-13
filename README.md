# sub-server
由huggingface.co上的DeepSeek-R1-Distill-Qwen-32B生成
# 项目结构
sub-manager/
├── server/               # 后端服务
│   ├── src/
│   │   ├── core/        # 核心功能模块
│   │   ├── routes/      # API路由
│   │   └── app.js       # 主程序
├── web/                  # 前端界面
│   ├── public/
│   └── src/
├── docker/
│   └── Dockerfile       # ARMv7 Dockerfile
├── .github/
│   └── workflows/
│       └── deploy.yml   # GitHub Actions
└── package.json
