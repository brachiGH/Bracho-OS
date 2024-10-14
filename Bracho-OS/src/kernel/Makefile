BUILD_DIR?=build/
ASM?=nasm


.PHONY all clean kernel

all: kernel

kernel: $(BUILD_DIR)/kernel.bin
	$(ASM) main.asm -f bin -o ${BUILD_DIR}/kernel.bin

clean:
	rem -rf ${BUILD_DIR}/kernel.bin
