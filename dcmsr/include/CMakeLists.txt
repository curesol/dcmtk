# declare installation files
install(DIRECTORY dcmtk/dcmsr DESTINATION "${CMAKE_INSTALL_INCLUDEDIR}/dcmtk" COMPONENT include FILES_MATCHING PATTERN "*.h")
