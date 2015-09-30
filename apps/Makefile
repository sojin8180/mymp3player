.PHONY: all clean

player: player.c
	gcc -g -c -I ~/ch3-make/RecursiveMakefile/include player.c -o player.o
	gcc -o player -L ~/ch3-make/RecursiveMakefile/lib player.o -lfuncs
clean:
	rm -f player.o player
