

all:
	bison -v -d --file-prefix=y mini_l.y
	flex mini_l.lex
	gcc y.tab.c lex.yy.c -o mini_l -lfl