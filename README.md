# LLM関連開発用 Docker環境構築テンプレート

## 手順
1. Docker Desktop起動
2. docker imageのbuild（初回のみ）
   - 例：`docker build -f docker/llm-dev/Dockerfile -t dev-llm:v141 .`
4. `cd docker`
5. `docker compose up -d`で、自動的にJupyterLabが起動。https://localhost:8888 でアクセス

## 使用方法
- 基本的に、srcディレクトリで作業を行います。このディレクトリはコンテナのボリュームにマウントされています。
