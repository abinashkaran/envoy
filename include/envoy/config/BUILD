licenses(["notice"])  # Apache 2

load(
    "//bazel:envoy_build_system.bzl",
    "envoy_cc_library",
    "envoy_package",
)

envoy_package()

envoy_cc_library(
    name = "subscription_interface",
    hdrs = ["subscription.h"],
    deps = [
        "//include/envoy/stats:stats_macros",
        "//source/common/protobuf",
    ],
)
