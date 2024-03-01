cmake_minimum_required(VERSION 3.5)

# Set the project name
project(helloyocto)

# Add the executable
add_executable(${PROJECT_NAME} main.cpp)

# Install the executable to /usr/bin
install(TARGETS ${PROJECT_NAME}
    RUNTIME DESTINATION /usr/bin
)

