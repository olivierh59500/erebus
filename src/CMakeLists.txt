add_subdirectory(plugin_framework)
add_subdirectory(plugins)
add_subdirectory(utils)
add_subdirectory(exceptions)

set(SOURCE
	${SOURCE}
	${CMAKE_CURRENT_SOURCE_DIR}/application.cc
	PARENT_SCOPE
)

set(HEADER
	${HEADER}
	${CMAKE_CURRENT_SOURCE_DIR}/application.h
	${CMAKE_CURRENT_SOURCE_DIR}/idisassembler.h
	${CMAKE_CURRENT_SOURCE_DIR}/byte_order.h
	PARENT_SCOPE
)	
