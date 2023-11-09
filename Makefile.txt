TARGET = HelloW
CXX = g++
CXXFLAGS = -Wall

all: $(TARGET)

$(TARGET): HelloW.c
	$(CXX) $(CXXFLAGS) -o $(TARGET) HelloW.c

clean:
	rm -f $(TARGET)
