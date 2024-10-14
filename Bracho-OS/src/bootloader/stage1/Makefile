BUILD_DIR?=build/
ASM?=nasm


.PHONY all clean stage1

all: stage1

stage1: $(BUILD_DIR)/stage1.bin
	$(ASM) boot.asm -f bin -o ${BUILD_DIR}/stage1.bin

clean:
	rem -rf ${BUILD_DIR}/stage1.bin
