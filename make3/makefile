OBJ=test.o max.o min.o

test:$(OBJ)
	gcc -o test $(OBJ)
test.o:test.c
	@echo "开始编译test.c"
	gcc -o test.o -c test.c
	@echo "test.c编译结束"
max.o:max.c
	@echo "开始编译max.c"
	gcc -o max.o -c max.c
	@echo "max.c编译结束"
min.o:min.c
	gcc -o min.o -c min.c
clean:
	@echo "开始clean"
	rm $(OBJ) test
	@echo "clean结束"

