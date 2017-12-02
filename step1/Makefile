#INCLUDES = $(shell pkg-config --cflags opencv)
INCLUDES = -I /opt/local/include/
# LIBS = $(shell pkg-config --libs opencv)
LIBS = -L /opt/local/lib/
LIBS += -lopencv_core
LIBS += -lopencv_highgui

CXX = clang++
CXXFLAGS = -Wall -Werror $(INCLUDES)
LDFLAGS = $(LIBS)

.PHONY: run

run: ar
	./ar

bender: ar.cpp

clean:
	rm ar
