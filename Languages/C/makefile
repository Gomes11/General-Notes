# Typical directories to use
BDIR=../bin
IDIR =../inc
ODIR=../obj
LDIR =../lib

# Some useful flags
CC=gcc
CFLAGS=-I$(IDIR)

# Binutils libraries
LIBS=-lm

# Specify dependencies
_DEPS = <HEADER_FILE>.h
DEPS = $(patsubst %,$(IDIR)/%,$(_DEPS))

# Specify objects/shared objects
_OBJ = <OBJECT_FILE>.o
OBJ = $(patsubst %,$(ODIR)/%,$(_OBJ))

# Rules for objects
$(ODIR)/%.o: %.c $(DEPS)
	$(CC) -c -o $@ $< $(CFLAGS)

# Rules for binaries
<BINARY_FILE>: $(OBJ)
	$(CC) -o $(BDIR)/$@ $^ $(CFLAGS) $(LIBS)

# Don't interpret any file called "clean"!
.PHONY: clean

# General rule to clean
clean:
	rm -f $(ODIR)/*.o *~ core $(INCDIR)/*~ 
