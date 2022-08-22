idf_component_register(REQUIRES driver)

target_include_directories(${COMPONENT_TARGET} INTERFACE
    "${COMPONENT_DIR}/include/"
)

target_sources(${COMPONENT_TARGET} INTERFACE
    "${COMPONENT_DIR}/src/"
)