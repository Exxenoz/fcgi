# Project name
project(fcgicc)

# Include headers
include_directories(include/)

add_library( fcgicc STATIC ./src/fcgicc.cpp ./include/fcgicc.h ./include/fastcgi.h )
# INSTALL( FILES fcgicc.h DESTINATION include )
# INSTALL( TARGETS fcgicc LIBRARY DESTINATION lib ARCHIVE DESTINATION lib )
