CXX = g++
CXXFLAGS = -std=c++11 -Wall -Wextra -Wpedantic -g -fPIC

TARGET = psirver
SRC = test.cc

all: $(TARGET)

$(TARGET): $(SRC)
	$(CXX) $(CXXFLAGS) -o $(TARGET) $(SRC)

clean:
	rm -f $(TARGET)

