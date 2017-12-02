#INCLUDES = $(shell pkg-config --cflags opencv)
INCLUDES = -I /opt/local/include/
# LIBS = $(shell pkg-config --libs opencv)
LIBS = -L /opt/local/lib/
LIBS += -lopencv_core
LIBS += -lopencv_imgproc
LIBS += -lopencv_highgui
LIBS += -lopencv_ml
LIBS += -lopencv_video
LIBS += -lopencv_videostab
LIBS += -lopencv_features2d
LIBS += -lopencv_calib3d
LIBS += -lopencv_objdetect
LIBS += -lopencv_flann
LIBS += -lopencv_video
LIBS += -lopencv_videoio
CXX = clang++
CXXFLAGS = -Wall -Werror $(INCLUDES)
LDFLAGS = $(LIBS)

.PHONY: run

run: ar
	./ar

bender: ar.cpp

clean:
	rm ar
