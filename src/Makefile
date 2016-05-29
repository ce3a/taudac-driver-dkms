snd-soc-tau-dac-objs := tau-dac.o
obj-m += snd-soc-tau-dac.o

PWD := $(shell pwd)

all:
	make -C /lib/modules/${kernelver}/build M=$(PWD) modules

clean:
	make -C /lib/modules/${kernelver}/build M=$(PWD) clean
