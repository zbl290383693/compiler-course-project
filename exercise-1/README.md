## Links
- [用LLVM开发一门新语言](https://llvm-tutorial-cn.readthedocs.io/en/latest/index.html)
- [自己动手写编译器](https://pandolia.net/tinyc/ch1_overview.html)
   : [***项目地址***](https://github.com/pandolia/tinyc)
- [Tiny-C毕业设计](https://wenku.baidu.com/view/3fa538efe2bd960591c6770e.html?rec_flag=default&sxts=1574903584337)
- [基于解析器组合子的简单解释器 python](https://github.com/DesertsP/P-cube-Interpreter)


## How to make it work
<pre>
## 编译流程
flex lexer.l//生成lexer.yy.c
bison -d -v parser.y//生成parser.tab.h, parser.tab.c 
gcc display.c parser.tab.c lex.yy.c -lfl -o test1
./test1 test.c
</pre>
