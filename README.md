# compiler
compiler for c-- language
compiler_lab1:lexical analysis and syntax analysis for c-- language
              It is more powerful,supporting hexical and octal numbers,and scientific way of floating numbers.
              lex.yy.c is the output file of compiler.lex using flex not lex.
              compiler.tab.c and compiler.tab.h are output files of compiler.y using bison not yacc.
              simplefuncs.c and debugfuncs.c show the syntax tree with rough information or detailed information.
              nodes.h is the header file needed,in which syntax tree node structure is defined.
compiler_lab2:semantic analysis for c-- language.
              It is more powerful,supporting nested structure and nested statement blocks.
              It calculates the offset and forms the symbol table through one traverse of the syntax tree.
              Drawback:recursive function call, making its space cost expensive.
              compiler.tab.c lex.yy.c simplefuncs.c nodes.c are the files from compiler_lab1, with some modifications in nodes.h and compiler.tab.c.
              The modification occurs because I put these files directly into a codeblocks project to make debugging process easiler which makes it possible for me to trace the entire semantic analysis process.
              CalcAttri.c and CalcAttri.h are files especially written for semantic analysis.
