set(priv_requires "driver" "freertos")
idf_component_register(SRCS "leds.c"
                    INCLUDE_DIRS "include"
                    PRIV_REQUIRES ${priv_requires})
