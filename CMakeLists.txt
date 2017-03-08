project(netcat C)

add_definitions(
    -D_CRT_SECURE_NO_WARNINGS=
)

add_executable(nc
    netcat.c
    doexec.c
    getopt.c
    strcasecmp.c

    generic.h
    getopt.h
)
