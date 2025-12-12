# mnist-uv-typing-pytest
M1 後期授業人工知能応用特論Ⅰ 最終課題
## 元コード
- PyTorch Examples (MNIST): https://github.com/pytorch/examples/tree/main/mnist
- 参照元: `_original_mnist/main.py`

## このリポジトリで行った改善
- uv による依存関係管理（pyproject.toml / uv）
- `src/` 配下に分割して import 可能な構成に整理
- 主要箇所に型ヒントを付与（例: `mnist_uv/model.py`）
- pytest を追加し、モデルの入出力形状テストを実装（`tests/test_model.py`）
