# Compiler
CC = gcc

# Compiler flags
CFLAGS = -I../Common -Wall -Wextra -O2

# Source files
SRCS = dma-proxy-test.c

# Output executable
TARGET = dma-proxy-test

# Build target
all: $(TARGET)

# Link the object files to create the executable
$(TARGET): $(SRCS)
	$(CC) $(CFLAGS) -o $(TARGET) $(SRCS)

# Clean up build files
clean:
	rm -f $(TARGET) *.o

# Phony targets
.PHONY: all clean