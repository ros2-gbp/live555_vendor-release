LIVE555 - multimedia RTSP streaming library
===========================================

This code forms a set of C++ libraries for multimedia streaming, using open
standard protocols (RTP/RTCP, RTSP, SIP). These libraries - which can be
compiled for Unix (including Linux and Mac OS X), QNX (and other
POSIX-compliant systems) - can be used to build streaming applications.


How to use the library in your ROS package
------------------------------------------

Add `find_package(live555 REQUIRED)` to your `CMakeLists.txt`, and you
can link against `live555::liveMedia` with `target_link_libraries()`.
