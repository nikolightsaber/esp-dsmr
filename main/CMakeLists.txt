idf_component_register(SRCS "main.c"
                    INCLUDE_DIRS "."
                    EMBED_FILES index.html
                    )

# target_add_binary_data(${COMPONENT_LIB} "index.html" BINARY)
