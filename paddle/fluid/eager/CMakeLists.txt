add_subdirectory(tests)
cc_library(grad_node_info SRCS grad_node_info.cc DEPS pten pten_api)
cc_library(autograd_meta SRCS autograd_meta.cc DEPS pten pten_api)