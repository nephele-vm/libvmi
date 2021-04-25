if (ENABLE_FREEBSD)
    add_subdirectory(freebsd)
endif ()

if (ENABLE_LINUX)
    add_subdirectory(linux)
endif ()

if (ENABLE_WINDOWS)
    add_subdirectory(windows)
endif ()

if (ENABLE_UNIKRAFT)
    add_subdirectory(unikraft)
endif ()
