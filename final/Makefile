CXX = g++
CXXFLAGS = -Wall -I/Library/Frameworks/SDL2.framework/Headers
LDFLAGS = -F/Library/Frameworks -framework SDL2 -Wl,-rpath,/Library/Frameworks

main: visual.cpp
	$(CXX) $(CXXFLAGS) -o visual visual.cpp $(LDFLAGS)