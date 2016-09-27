INCLUDE(../../../../cmake/macros.cmake)

SD_ADD_SUBDIRECTORY(ls1-archer-r9)
SD_ADD_SUBDIRECTORY(ls1-cavallo-570s1)
SD_ADD_SUBDIRECTORY(ls1-newcastle-fury)
SD_ADD_SUBDIRECTORY(ls1-taipan-ltsr)
SD_ADD_SUBDIRECTORY(ls1-toro-rgt)
SD_ADD_SUBDIRECTORY(ls1-vulture-v6r)
SD_ADD_SUBDIRECTORY(ls1-zentek-z7r)

# Work-in-progress car sets.
IF(NOT OPTION_OFFICIAL_ONLY)

	SD_ADD_SUBDIRECTORY(ls1-marisatech-gt4r)

ENDIF()
