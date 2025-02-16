cmake_minimum_required(VERSION 3.10)
# target homework_8
file(GLOB_RECURSE SOURCE_FILES *.cpp)
add_executable(pa8 ${SOURCE_FILES})

# set(CGL_DIR E:/codelib/games101-cgl/build/install/share/CGL)
find_package(games101-cgl CONFIG REQUIRED)

if(WIN32)
  find_package(unofficial-getopt-win32 REQUIRED)
  target_link_libraries(pa8 unofficial::getopt-win32::getopt games101-cgl)
else()
  target_link_libraries(pa8 games101-cgl)
endif()