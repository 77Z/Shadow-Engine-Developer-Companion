.PHONY: all

all:
	g++ binary_to_compressed_c.cpp -o bin2c
	./bin2c Inter-Medium.ttf InterMedium > FONT-InterMedium.cpp
	./bin2c Inter-Black.ttf InterBlack > FONT-InterBlack.cpp
	./bin2c shadow.ttf ShadowIcons > FONT-ShadowIcons.cpp

# g++ -o ../FONT-InterMedium.o FONT-InterMedium.cpp
# g++ -o ../FONT-InterBlack.o FONT-InterBlack.cpp
# g++ -o ../FONT-ShadowIcons.o FONT-ShadowIcons.cpp

clean:
	rm bin2c
	rm FONT-*.cpp
	
# rm ../FONT-InterMedium.o
# rm ../FONT-InterBlack.o
# rm ../FONT-ShadowIcons.o