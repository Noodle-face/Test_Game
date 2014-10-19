Windows

Download and install CMake (32-bit):<br>
	http://www.cmake.org/download/

MinGW (32-bit):<br>
	http://www.mingw.org/

Add C:\MinGW\bin to your PATH.

Download and install cURL (32-bit 7.3.4) so that CURL/lib and CURL/include are in your Program Files directory:<br>
	http://curl.haxx.se/download.html

Compile and Run

Once you have the dependencies (see above), run the following commands in your terminal.<br>

git clone https://github.com/Noodle-face/Test_Game.git <br>
cd Craft <br>
cmake -G "MinGW Makefiles" <br>
mingw32-make
