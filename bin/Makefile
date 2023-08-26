# Makefile reads top to bottom

# 'main.o' forces make to do main.o task first
main: main.o
	gfortran main.o -o main

main.o:
	gfortran -c main.f90 -o main.o
