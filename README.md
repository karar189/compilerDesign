# CompilerDesign

Lab Files GDRIVE LINK : https://drive.google.com/drive/folders/1rEOpV7qNs-oldl9XgGUF8sTktecINf8-

Rest of the materials are in Respective folders 

# Lex file Run 
``` 
gedit text.l
lex text.l
cc lex.yy.c -ll
./a.out 
``` 

# Yacc file Run 
``` 
gedit text.y
yacc -d text.y
cc lex.yy.c y.tab.c -ll
./a.out
``` 
