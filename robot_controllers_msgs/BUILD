load("@bazel_rules_ros//:message_generation.bzl", "generate_messages")

generate_messages(
    srcs = glob([
        "msg/*.msg",
    ]),
    ros_package_name = "robot_controller_msgs",
    deps = [
        "@std_msgs//:msgs"
    ],
    visibility=["//visibility:public"] 
)
