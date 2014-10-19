Windows

Download and install CMake (32-bit):
	http://www.cmake.org/download/

MinGW (32-bit):
	http://www.mingw.org/

Add C:\MinGW\bin to your PATH.

Download and install cURL (32-bit 7.3.4) so that CURL/lib and CURL/include are in your Program Files directory:
	http://curl.haxx.se/download.html

Compile and Run

Once you have the dependencies (see above), run the following commands in your terminal.

git clone https://github.com/Noodle-face/Test_Game.git
cd Craft
cmake -G "MinGW Makefiles"
mingw32-make
