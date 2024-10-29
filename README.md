# NotebookLlama

## 官方下载途径
您可以从Meta的官方GitHub仓库获取NotebookLlama：

```bash
git clone https://github.com/meta-llama/llama-recipes
cd llama-recipes/recipes/quickstart/NotebookLlama/
pip install -r requirements.txt
```

## 使用前提条件
1. 需要登录Hugging Face账号并获取访问令牌[4]：
- 从Hugging Face设置页面获取访问令牌
- 运行`huggingface-cli login`命令
- 输入访问令牌完成登录

2. 硬件要求：
- 如果要运行推荐配置（使用70B模型），需要具备约140GB显存的GPU[1][4]
- 也可以选择使用较小的模型（如8B或更小）来降低硬件要求[4]

## 注意事项
- 目前该工具仍处于开发阶段，需要具备一定的技术基础
- 运行过程中可能需要切换transformers库的版本[4]
- 建议按照官方文档中的notebook顺序逐步完成配置和使用

如果您不想自行部署，也可以考虑等待Meta后续发布更加用户友好的版本，或使用其他类似的在线服务。
