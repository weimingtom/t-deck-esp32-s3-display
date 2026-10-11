#set(ENV{IDF_COMPONENT_MANAGER} "1")

idf_component_register(SRC_DIRS "."
                       INCLUDE_DIRS "."
                       EMBED_FILES click.wav)
