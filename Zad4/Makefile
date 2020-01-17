myProgram: address.o employee.o main.o
	g++ -lm address.o employee.o main.o -o myProgram
main.o: main.cpp employee.h address.h
	g++ -c main.cpp
address.o: address.cpp
	g++ -c address.cpp
employee.o: employee.cpp address.h
	g++ -c employee.cpp
clean:
	rm -f *~ *.bak
	rm -f myProgram address.o employee.o main.o
