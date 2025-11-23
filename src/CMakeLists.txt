# Define Source Files
set(SOURCE_FILES
	Cache.cpp
	CacheStatistics.cpp
	CacheTrace.cpp
	Logger.cpp
	MainMemory.cpp
	MemorySystem.cpp
	RandomNumberGenerator.cpp
	ReplacementAlgorithms.cpp
	CacheIQ.cpp
)

# Create Executable Target
add_executable(CacheIQ ${SOURCE_FILES})

# Add Header Files to the Project Structure
target_sources(CacheIQ PUBLIC
	Cache.h
	CacheDefinitions.h
	CacheStatistics.h
	CacheTrace.h
	Logger.h
	MainMemory.h
	MemorySystem.h
	RandomNumberGenerator.h
	ReplacementAlgorithms.h
	SystemDefinitions.h
)