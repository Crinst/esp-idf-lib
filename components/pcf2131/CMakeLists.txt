idf_component_register(
    SRCS pcf2131.c
    INCLUDE_DIRS .
    REQUIRES i2cdev log esp_idf_lib_helpers
)
