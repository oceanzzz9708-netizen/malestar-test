# 男明星测试

部署到 Railway 的静态网站项目。

## 文件结构

```
male-star-quiz/
├── app.py          # Flask 后端（用于 serving 静态文件）
├── index.html      # 测试页面
├── requirements.txt # Python 依赖
├── Procfile        # Railway 启动命令
└── railway.json    # Railway 配置
```

## 部署步骤

1. 创建 GitHub 仓库
2. 推送代码到 GitHub
3. 在 Railway 创建新项目，连接 GitHub 仓库
4. 部署完成

## 本地测试

```bash
pip install -r requirements.txt
python app.py
```

访问 http://localhost:5000
