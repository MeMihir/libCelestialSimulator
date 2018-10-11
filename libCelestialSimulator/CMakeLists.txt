add_library(
    libCelestialSimulator
        "src/libCelestialSimulator.cpp" 
        "inc/libCelestialSimulator.h"
		"inc/Converter.h"
		"inc/Constants.h"
)

target_include_directories(
    libCelestialSimulator 
        PUBLIC "inc"
)
