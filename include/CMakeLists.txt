file(GLOB old_hdrs "opencv/*.h*")
install(FILES ${old_hdrs}
    DESTINATION ${OPENCV_INCLUDE_INSTALL_PATH}/${INSTALL_LIB_PREFIX}
    COMPONENT dev)
install(FILES "opencv2/opencv.hpp"
    DESTINATION ${OPENCV_INCLUDE_INSTALL_PATH}/opencv2
    COMPONENT dev)
