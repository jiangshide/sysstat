add_definitions(
        -DHAVE_CONFIG_H
        -DWall
        -O2
)

add_executable(inotifywatch
        common.c
        inotifywatch.c
        inotifytools.c
        redblack.c)

add_executable(inotifywait
        common.c
        inotifywait.c
        inotifytools.c
        redblack.c)