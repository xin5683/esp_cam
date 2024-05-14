idf_component_register(SRCS take_picture.c camera_http.c
                        PRIV_INCLUDE_DIRS .
                        PRIV_REQUIRES nvs_flash esp_http_server esp_timer 
                        REQUIRES esp_wifi)
component_compile_options(-Wno-error=format= -Wno-format)