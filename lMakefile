all:lmain


lmain: LinkList.o lmain.o
	gcc LinkList.o lmain.o -o lmain

LinkList.o : LinkList.c
	gcc LinkList.c -c -o LinkList.o
lmain.o : lmain.c
	gcc lmain.c -c -o lmain.o
