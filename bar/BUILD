load("@protobuf//:protobuf.bzl", "cc_proto_library", "py_proto_library")

cc_proto_library(
    name = "ping_cc_proto",
    srcs = [
        "ping.proto",
    ],
    deps = [
        "//foo:base_cc_proto",
    ],
    protoc = "@protobuf//:protoc",
    default_runtime = "@protobuf//:protobuf",
)

py_proto_library(
    name = "ping_py_proto",
    srcs = [
        "ping.proto",
    ],
    deps = [
        "//foo:base_py_proto",
    ],
    protoc = "@protobuf//:protoc",
    default_runtime = "@protobuf//:protobuf_python",
)

