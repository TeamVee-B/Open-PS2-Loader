IOP_BIN = httpclient.irx
IOP_OBJS = main.o httpclient.o imports.o exports.o

IOP_INCS += -I../common
IOP_CFLAGS += -Wall -fno-builtin -D_IOP -mno-gpopt -G0
IOP_LDFLAGS += -s

all: $(IOP_BIN)

clean:
	rm -f $(IOP_BIN) $(IOP_OBJS)

rebuild: clean all

include $(PS2SDK)/Defs.make
include ../../Rules.make
