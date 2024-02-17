# cudnn_v8验证安装
```bash
# 安装依赖
sudo apt install libfreeimage-dev build-essential -y

# 克隆测试代码
git clone https://github.com/fenghan0430/cudnn_samples_v8.git
cd cudnn_samples_v8/mnistCUDNN/

# 编译测试程序
make clean && make

# 运行测试
./mnistCUDNN

# 出现Test passed!就是安装成功
```
