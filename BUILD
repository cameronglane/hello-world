cc_library(
    name = "hello-lib",
    srcs = ["hello_world.cpp"],
    hdrs = ["hello_world.h"],
)

cc_binary(
    name = "hello_world",
    srcs = ["main.cpp"],
    deps = [":hello-lib"],
)