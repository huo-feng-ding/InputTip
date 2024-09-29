2024年9月29日15:22:10  
2.22.4 版本本地构建：  
    编译的时候注意选64位
    先编译InputTip.JAB.JetBrains.ahk文件成exe，将InputTip.JAB.JetBrains.exe拷贝到InputTipSymbol.zip压缩文件中去，替换原来的程序，因为原来的程序有异常。
    再编译InputTip.ahk这个文件成InputTip.exe。
    
对idea的支持：  
    如果JDK环境变量/bin目录下边里没有WindowsAccessBridge-64.dll，需要找这个文件并复制到/bin目录下边。
    这个文件一般存在于 jre/bin/WindowsAccessBridge-64.dll 下边，注意是jre目录下