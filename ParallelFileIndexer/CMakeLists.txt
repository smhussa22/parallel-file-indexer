# CMakeList.txt : CMake project for ParallelFileIndexer, include source and define
# project specific logic here.
#

# Add source to this project's executable.
add_executable (ParallelFileIndexer "ParallelFileIndexer.cc" "ParallelFileIndexer.hh")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET ParallelFileIndexer PROPERTY CXX_STANDARD 23)
endif()

# TODO: Add tests and install targets if needed.
