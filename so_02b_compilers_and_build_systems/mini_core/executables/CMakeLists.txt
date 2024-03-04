# TODO compile executable that will be run  

# add_compile_options(-w) # to delete warning messages

add_executable(many_object_in_stack_example many_object_in_stack_example.cpp)

target_link_libraries(many_object_in_stack_example core_library)

