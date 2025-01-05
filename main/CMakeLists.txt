idf_component_register(
  SRCS "esp32_ip_cam.c"
  INCLUDE_DIRS "."
)

set_source_files_properties(http_server.c
    PROPERTIES COMPILE_FLAGS
    -Wno-unused-function
)
