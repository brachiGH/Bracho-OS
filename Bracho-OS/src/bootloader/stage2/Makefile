BUILD_DIR?=build/
ASM?=nasm


.PHONY all clean stage2

all: stage2

stageZ: $(BUILD_DIR)/stageZ.bin
	$(ASM) main.asm -f bin -o ${BUILD_DIR}/stage2.bin

clean:
	rem -rf ${BUILD_DIR}/stage2.bin
