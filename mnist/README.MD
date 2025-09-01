# MNIST 手写数字识别

```text
mnist-app/
├── app.py              # 您的 Streamlit 应用
├── train.py            # 训练脚本
├── requirements.txt    # Python 依赖
├── Dockerfile          # Docker 构建文件
├── .dockerignore       # Docker 忽略文件
└── mnist.h5            # 训练好的模型（运行 train.py 后生成）
```

## 构建 Docker 镜像

```bash
docker build -t mnist-app .
```

## 运行容器

```bash
docker run -p 8501:8501 mnist-app
```
