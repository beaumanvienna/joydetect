
# generate binary
add_executable (joydetect joydetect.c)

# set installation prefix; installation will be in 
set (CMAKE_INSTALL_PREFIX /usr)

# install target joydetect into subfolder $CMAKE_INSTALL_PREFIX/bin
install (TARGETS joydetect DESTINATION ${CMAKE_INSTALL_PREFIX}/bin)

