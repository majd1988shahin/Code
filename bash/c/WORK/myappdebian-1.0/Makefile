BIN = $(DESTDIR)/usr/bin
CFLAGS :=	-O $(CFLAGS)
TARGET=		myhello
SRCFILES=	myhello.c

all: $(TARGET)

$(TARGET):	$(SRCFILES) 
	$(CC) $(CFLAGS) -o $(TARGET) $(SRCFILES)

install: $(TARGET)
	install -d $(BIN)
	install $(TARGET) $(BIN)

clean:
	rm -f $(TARGET)

