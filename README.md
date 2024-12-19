项目简介
本项目是一个简单的文件加密和解密工具，使用C语言编写。它支持通过命令行参数指定加密或解密模式，输入文件，输出文件以及加密密钥。加密和解密过程使用异或（XOR）算法实现。

使用说明
要使用这个工具，请确保系统已经安装了GCC编译器。然后按照以下步骤操作：
1.编译代码：
打开终端，导航到包含main.c和crypto.c文件的目录，执行以下命令来编译程序：gcc -o crypto-tool main.c crypto.c
2.运行程序：
使用以下命令格式来加密或解密文件：
./crypto-tool <mode> <input_file> <output_file> <key>
<mode>：模式选择，1代表加密，2代表解密。
<input_file>：要加密或解密的输入文件路径。
<output_file>：加密或解密后生成的输出文件路径。
<key>：用于加密或解密的密钥，是一个整数。

例如，要加密文件example.txt并使用密钥123，可以执行：
./crypto-tool 1 example.txt encrypted_example.txt 123
要解密文件，执行：
./crypto-tool 2 encrypted_example.txt decrypted_example.txt 123


作者信息
姓名:zhaomai
邮箱：2449096405@qq.com
GitHub:zhaomai-mai
