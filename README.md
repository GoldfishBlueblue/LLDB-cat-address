# LLDB-cat-address
LLDB 调试, 查看地址在哪个内存区: cat address 0xxxxxxxx

1. 下载 libfooplugin.dylib 文件到电脑
2. 进入根目录: ~
3. 新建文件: touch .lldbinit
4. 编辑文件: vim .lldbinit
5. 输入: plugin load <libfooplugin.dylib的绝对路径> // 绝对路径可以在终端通过 cd libfooplugin.dylib 来获取
6. 重新运行 xcode 就可以了
