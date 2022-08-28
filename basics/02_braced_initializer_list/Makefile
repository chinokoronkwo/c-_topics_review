
GCC := g++

OUTPUT := compiled_code
SOURCES := $(wildcard *.cpp)
CCFLAGS := -std=c++17

all: $(OUTPUT)
	
$(OUTPUT):
	$(GCC) $(CCFLAGS) -o $(OUTPUT) $(SOURCES)   
	
clean:
	rm $(OUTPUT)
	
.PHONY: all
