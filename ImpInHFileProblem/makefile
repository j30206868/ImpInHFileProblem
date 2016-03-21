COMPILER = E:\Qt\Tools\mingw492_32\bin\g++
 
all: main.exe
main.exe: main.o man.o woman.o
	$(COMPILER) main.o man.o woman.o -o main.exe
main.o: main.cpp
	$(COMPILER) -c main.cpp
man.o: man.cpp
	$(COMPILER) -c man.cpp
woman.o: woman.cpp
	$(COMPILER) -c woman.cpp