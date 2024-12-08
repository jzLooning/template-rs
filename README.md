# Rust Project Template
此template参考于[tyr-rust-bootcamp/template](https://github.com/tyr-rust-bootcamp/template)

## 环境设置

### 安装 Rust

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```
### 安装 cargo generate

cargo generate 是一个用于生成项目模板的工具。它可以使用已有的 github repo 作为模版生成新的项目。

安装：
```bash
cargo install cargo-generate
```

构建模板
```bash
cargo generate jzLooning/template-rs
```
或
```bash
cargo generate --git https://github.com/jzLooning/template-rs.git
```

### 安装 pre-commit

pre-commit 是一个代码检查工具，可以在提交代码前进行代码检查。

```bash
pipx install pre-commit
```

安装成功后在需要的仓库中运行一次 `pre-commit install` 即可，后续每次commit都会根据配置文件进行检查。

### 安装 Cargo deny

Cargo deny 是一个 Cargo 插件，可以用于检查依赖的安全性。

```bash
cargo install --locked cargo-deny
```

### 安装 typos

typos 是一个拼写检查工具。

```bash
cargo install typos-cli
```

### 安装 git cliff

git cliff 是一个生成 changelog 的工具。

```bash
cargo install git-cliff
```

### 安装 cargo nextest

cargo nextest 是一个 Rust 增强测试工具。

```bash
cargo install cargo-nextest --locked
```
## 安装后操作
请将`LICENSE`文件替换为您需要的对应的许可证文件。
请将`cliff.toml`文件第49行的链接替换为您的仓库地址。
