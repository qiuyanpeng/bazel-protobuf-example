load("@protobuf//:protobuf.bzl", "cc_proto_library", "py_proto_library")

cc_proto_library(
    name = "pong_cc_proto",
    srcs = [
        "pong.proto",
    ],
    deps = [
        "//foo:base_cc_proto",
    ],
    protoc = "@protobuf//:protoc",
    default_runtime = "@protobuf//:protobuf",
)

py_proto_library(
    name = "pong_py_proto",
    srcs = [
        "pong.proto",
    ],
    deps = [
        "//foo:base_py_proto",
    ],
    protoc = "@protobuf//:protoc",
    default_runtime = "@protobuf//:protobuf_python",
)

