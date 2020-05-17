
cc_library(
    name = "robot_controllers_interface",
    hdrs = glob(["**/*.h"]),
    srcs = glob(["**/*.cpp"]),
    deps = [
        "//robot_controllers_msgs:msgs_cc",
        "//robot_controllers:robot_controllers",
        "@roscpp",
        "@eigen//:eigen",
        "@boost//:system",
    ],
    strip_include_prefix="include",
    copts = ["-Wno-unused-value", "-Iexternal/boost/include/python2.7", "-Irobot_controllers_interface/include", "-Irobot_controllers/include"]
)
