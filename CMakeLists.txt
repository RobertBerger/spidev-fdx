project (spidev_fdx)
add_executable(spidev_fdx spidev_fdx.c)
target_link_libraries(spidev_fdx)
install(TARGETS spidev_fdx DESTINATION bin)

