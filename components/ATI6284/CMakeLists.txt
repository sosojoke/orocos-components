OPTION( BUILD_ATI6284 "Build ATI6284 Component" ON )

if(BUILD_ATI6284)
GLOBAL_ADD_COMPONENT(ATI6284 ATI6284.cpp )
endif(BUILD_ATI6284)
