idf_component_register(SRCS "oneshot_read_main.c"
                    INCLUDE_DIRS ".")
spiffs_create_partition_image(storage flash-memory FLASH_IN_PROJECT)
