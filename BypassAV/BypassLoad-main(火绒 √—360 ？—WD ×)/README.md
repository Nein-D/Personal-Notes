# BypassLoad
**通过远程加载AES + XOR异或加密shellcode的免杀加载器，无过多技术细节。**
## 使用指南

1. 编译BypassLoad和Encrypt
2. 将shellcode写入shellcode.txt然后运行Encrypt.exe进行加密编码（注意需要手动去除换行）
3. 将Encrypt.exe加密编码后的数据上传至服务器
4. 将远程访问链接写入webpath.txt
5. 运行BypassLoad.exe

注意：存在一段if判断内存是否小于4G，进行简单的反沙箱判断。
