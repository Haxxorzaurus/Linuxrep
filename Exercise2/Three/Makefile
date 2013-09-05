EXECUTABLE=main
CXX=g++

all: part1.o part2.o
	${CXX} -o ${EXECUTABLE} hello.o

hello.o: hello.cpp
	${CXX} -c hello.cpp
	
clean:
	rm hello.o ${EXECUTABLE}
	
help:
	@echo all hello.o clean help