IOP_BIN = ds34usb.irx
IOP_BIN_DIR = ../../
IOP_OBJS = ds34usb.o smsutils.o imports.o

all: $(IOP_BIN)

clean:
	rm -r -f $(IOP_BIN) $(IOP_OBJS) $(IOP_OBJS_DIR) $(IOP_LIB_DIR)

include $(PS2SDK)/Defs.make
include $(IOP_BIN_DIR)Rules.make
