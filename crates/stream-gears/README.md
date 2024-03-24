# stream-gears

通过 PyO3 导出**上传** B 站与**下载** FLV、HLS 流的函数供Python调用,
支持时间或文件大小分段，同时解决拉取FLV流花屏的问题。

## Dev

1. Install the latest [Rust compiler](https://www.rust-lang.org/tools/install)
2. Install [maturin](https://maturin.rs/): `$ pip3 install maturin`

```shell
**1. 安装rust编译环境**

curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh


**直接回车开始安装**

**安装完毕之后请输入以下指令设置环境变量**


source "$HOME/.cargo/env"

**2.安装以下依赖**

pip3 install maturin
apt install libssl-dev pkg-config -y

**3.开始编译**

python3 -m venv .env
source .env/bin/activate
maturin develop
```

## Credits

感谢 [Genteure](https://github.com/Genteure) 提供帮助。
