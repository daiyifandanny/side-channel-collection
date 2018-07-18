CFLAGS = -std=c99 -march=native
PROGRAM = spectre.out
SOURCE  = Source.c
     
all: $(PROGRAM)
     
$(PROGRAM): $(SOURCE) ; $(CC) $(CFLAGS) -o $(PROGRAM) $(SOURCE)
     
clean: ; rm -f $(PROGRAM)
