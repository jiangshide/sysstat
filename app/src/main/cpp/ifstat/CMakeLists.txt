add_definitions(
        -DHAVE_CONFIG_H
        -DWall
        -O2
)

add_executable(ifstat
        ifstat.c
        drivers.c
        data.c)