load("//tools:cpplint.bzl", "cpplint")

package(default_visibility = ["//visibility:public"])

cc_library(
    name = "velodyne_driver",
    srcs = [
        "driver.cc",
        "input.cc",
    ],
    hdrs = [
        "driver.h",
        "input.h",
        "ring_sequence.h",
    ],
    deps = [
        "//modules/common:log",
        "@ros//:ros_common",
    ],
)

cpplint()
