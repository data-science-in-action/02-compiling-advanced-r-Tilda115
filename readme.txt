Git is a version control system.
Git is free software.
Rmd文件在转化为pdf的过程中需要用到pandoc，而低版本的pandoc可能不支持生成pdf文件，因此需要确保，服务器或本地环境已安装了pandoc并且是相对高的版本。可以通过命令行直接调用pandoc将.md文件或.html文件转换为pdf。基本使用命令如下：

md转pdf: pandoc somefile.md -o somefile.pdf, 指定编译器（包含中文）pandoc --latex-engine=xelatex somefile.md -o somefile.pdf。
html转pdf: 同上。
