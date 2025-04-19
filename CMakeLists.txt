cmake_minimum_required(VERSION 3.16)
project(LearnCppProject)

set(CMAKE_CXX_STANDARD 17)

include_directories(include)

add_executable(welcome main.cpp
        lessons/buffered_reader.cpp
        lessons/comment.cpp
        lessons/context_actions.cpp
        lessons/duplicate.cpp
        lessons/file_structure.cpp
        lessons/find_in_files.cpp
        lessons/multiple_selection.cpp
        lessons/quadratic_equations_solver.cpp
        lessons/selection.cpp
        lessons/unwrap.cpp
        BasicEditing.cpp
        CodeAssistance.cpp
        Refactorings.cpp
        Navigation.cpp
)