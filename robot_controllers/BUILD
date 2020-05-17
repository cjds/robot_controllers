
cc_library(
    name = "robot_controllers",
    hdrs = glob(["**/*.h"]),
    srcs = glob(["**/*.cpp"], exclude=["src/robot_controllers_python.cpp"]),
    deps = [
        "//robot_controllers_msgs:msgs_cc",
        "@roscpp",
        "@eigen//:eigen",
        "@boost//:system",
    ],
    strip_include_prefix="include",
    include_prefix="robot_controllers",
    copts = ["-Wno-unused-value", "-Iexternal/boost/include/python2.7", "-Irobot_controllers/include"],
    visibility = ["//visibility:public"]
)
