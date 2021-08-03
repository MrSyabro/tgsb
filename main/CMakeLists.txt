idf_component_register(SRCS "main.c"
                    INCLUDE_DIRS "."
                    REQUIRES tgbl nvs_flash audio_pipeline audio_stream esp_peripherals)
