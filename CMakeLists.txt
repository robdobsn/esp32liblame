cmake_minimum_required(VERSION 3.16)

idf_component_register(
  SRCS
    src/liblame/lame.c
    src/liblame/util.c
    src/liblame/log.c
    src/liblame/set_get.c
    src/liblame/encoder.c
    src/liblame/bitstream.c
    src/liblame/gain_analysis.c
    src/liblame/id3tag.c
    src/liblame/VbrTag.c
    src/liblame/quantize_pvt.c
    src/liblame/tables.c
    src/liblame/presets.c
    src/liblame/psymodel.c
    src/liblame/newmdct.c
    src/liblame/quantize.c
    src/liblame/version.c
    src/liblame/takehiro.c
    src/liblame/fft.c
    src/liblame/reservoir.c
    src/liblame/vbrquantize.c
  INCLUDE_DIRS
    "src"
)

