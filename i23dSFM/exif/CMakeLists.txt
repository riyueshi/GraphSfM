ADD_DEFINITIONS(-DTHIS_SOURCE_DIR="${CMAKE_CURRENT_SOURCE_DIR}")
UNIT_TEST(i23dSFM exif_IO "stlplus;easyexif")

ADD_SUBDIRECTORY(sensor_width_database)
