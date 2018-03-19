all: spy spy_new
spy: spy.c ../../cacheutils.h
	gcc -std=gnu11 -O2 -o $@ $< -lrt -pthread -lxdo -lX11
spy_new: spy_new.c ../../cacheutils.h
	gcc -std=gnu11 -O2 -o $@ $< -lrt -pthread -lxdo -lX11

