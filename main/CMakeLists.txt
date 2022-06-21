set(srcs "pretty_effect.cpp"
    "spi_master_example_main.cpp"
    "decode_image.cpp"
    )

idf_component_register(SRCS ${srcs}
                    INCLUDE_DIRS "."
                    EMBED_FILES image.jpg)
